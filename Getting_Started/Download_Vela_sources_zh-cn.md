# 下载 openvela 源码

\[ [English](Download_Vela_sources.md) | 简体中文 \]

openvela 源码位于由 [GitHub](https://github.com/open-Vela) 或 [Gitee](https://gitee.com/open-vela) 托管的 Git 仓库中。

## 初始化 Repo 客户端
  
1. 创建并导航到工作目录：

    ```
    mkdir vela-opensource
    cd vela-opensource
    ```

2. 初始化用于操作源码的工作目录:

    - Github：

        ``` bash
        # Install Git LFS (Large File Storage) for managing large files
        sudo apt install git-lfs
        git lfs install
        git lfs --version

        repo init --partial-clone -u git@github.com:open-vela/manifests.git -b dev -m openvela.xml --git-lfs
        ```

    - Gitee：

        ```
        repo init --partial-clone -b opensource -m vela.xml -u {GITEE_URL}
        ```

## 下载 openvela 源码

运行如下命令下载 openvela 源码树至工作目录：

```
repo sync -c -j8
```

## 后续步骤

请参阅 [编译 openvela 源码](./Build_Vela_from_sources_zh-cn.md)。