<div align="center">
  <img src="./images/openvela.svg" width="180" />
</div>

<h1 align="center">openvela</h1>

\[ English | [简体中文](README_zh-cn.md) \]

## openvela Introduction

openvela is an operating system specifically crafted for the AIoT industry, with a focus on being lightweight, standards-compliant, secure, and highly scalable. It has become the technology of choice for millions of IoT devices and AI gadgets, including smart watches, fitness bands, smart speakers, earbuds, smart appliances, and robotics.

The name "Vela" is originated from the Latin term for "sail," which is also the name of the constellation resembling a sail in the southern sky. We aspire to partner with developers and set sail on a voyage through the AIoT landscape.

## Technical Advantages

- **Highly Scalable**: openvela has been designed to be modular and scalable, allowing it to easily adapt to a wide range of IoT applications. It can fit in a small BLE module with 32K RAM, and scale up to a powerful smart display device with 256M RAM, highly scalable! 

- **One-Stop Solution**: Over the years, openvela has evolved into a powerful platform with comprehensive feature sets, making it a one-stop solution for various IoT applications. We consistently incorporate new functionalities to meet emerging needs. By leveraging openvela, manufacturers can significantly reduce their R&D costs and accelerate their product development cycles. 

- **Mature Heterogeneous Computing Support**: openvela offers top-of-the-line support for heterogeneous multi-core systems, featuring a seamless IPC mechanism between various processing units such as MCU, MPU, DSP, GPU, and NPU. Additionally, openvela provides an advanced RPC framework between openvela, Linux, and Android systems to enable hybrid OS leveraging strength from three systems.

- **Standard Compliant and High Portability**: openvela Kernel is built upon Apache NuttX,  which is often referred to as "tiny Linux". With this foundation, openvela achieves a high degree of conformity with the POSIX standard. Our team has been continually enhancing its POSIX compatibility, which has now reached an impressive 88%. Because of this standards conformance, software developed under other standard OSs (such as Linux) can be easily ported to openvela with minimum effort.

- **Comprehensive Connectivity Suite**: openvela offers broad protocol support, including Bluetooth BR/EDR/LE, LE Mesh, WiFi, Matter, IEEE802.15.4, and LTE Cat1, Ethernet, CAN/LIN, etc. Additionally, it seamlessly integrates with Xiaomi HyperConnect protocols.

- **Rich Developer Tools**: openvela offers a comprehensive suite of developer tools, including system monitoring, and performance analysis, debugger, trace, crash dumb, and log analysis tools. 

## Supported Platforms

openvela supports a wide variety of architectures and platforms. See the full list on the [Supported Architectures and Platforms](https://nuttx.apache.org/docs/latest/platforms/index.html) page.


## Quick Start

If you want to experience openvela, we provide a fully functional simulator that can be used without a hardware platform. For more information, please refer to the following guide.

1. [Prepare the development environment](./Getting_Started/Set_up_the_development_environment.md)
2. [Download openvela source code](./Getting_Started/Download_Vela_sources.md)
3. [Compile openvela source code](./Getting_Started/Build_Vela_from_sources.md)
4. [Run openvela with openvela Emulator](./Getting_Started/Run_Vela_on_Vela_Emulator.md)

## Examples

* [Music Player Example](./Examples/Music_Player_Example.md)
* [Smart Band Example](./Examples/Smart_Band_Example.md)
* [Bicycle Track Example](./Examples/X_Track.md)

## Code Contributions

Contribute: [Contribution Guideline](./CONTRIBUTING.md).

## License Agreement

The code in this repository is licensed under the Apache 2.0 license. You can find more information about Apache 2.0 license [here](https://www.apache.org/licenses/LICENSE-2.0.txt).

Third-party license: [Third-Party Open-Source Software and License Notice](Third_Party_and_Open_Source_Components.md)


## Contact

In order to better manage and respond to feedback and support requests, we recommend contacting us through the following methods:

- **GitHub Issues**: If you have any questions, suggestions, or find any bugs, please submit a new issue on the Issues page. Please try to provide detailed information so that we can understand and solve the problem faster.
- **Pull Requests**: If you find an issue and have fixed it, you are welcome to submit a Pull Request. Please make sure to follow our [Contribution Guide](./CONTRIBUTING.md).
- **Discussions**: If you have a broader topic or discussion, you can start a new discussion on the Discussions page.

We are very grateful for the feedback and support of every user. Communicating through the GitHub platform can help us better maintain and improve the project.