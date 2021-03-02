<h1 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/109712161-8bed8300-7b54-11eb-8ab1-0c91b7ff5159.png">
  <br />
  ARM Guide
</h1>

#### A guide covering ARM architecture including the applications and tools that will make you a better and more efficient ARM developer.

# Table of Contents

1. [ARM Learning Resources](https://github.com/mikeroyal/ARM-Guide/blob/main/README.md#arm-learning-resources)

2. [Apple Silicon & Learning Resources](https://github.com/mikeroyal/ARM-Guide/blob/main/README.md#apple-silicon--learning-resources)

3. [Linux on ARM](https://github.com/mikeroyal/ARM-Guide/blob/main/README.md#linux-on-arm)

4. [Windows 10 on ARM](https://github.com/mikeroyal/ARM-Guide/blob/main/README.md#windows-10-on-arm)

5. [ARM Tools & Projects](https://github.com/mikeroyal/ARM-Guide/blob/main/README.md#arm-tools--projects)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/109565966-0d331000-7a98-11eb-8236-7bc8419c3a98.png">
</p>

# ARM Learning Resources

[Back to the Top](https://github.com/mikeroyal/ARM-Guide/blob/main/README.md#table-of-contents)

[ARM](https://www.arm.com/) stands for Advanced RISC Machine, which is a collection of reduced instruction set computing architectures for CPUs configured for various development environments such servers, IoT, and other mobile devices. Arm was acquired by [NVIDIA](http://www.nvidia.com/page/home.html) in [September 2020](https://www.arm.com/company/news/2020/09/nvidia-to-acquire-arm).

[NVIDIA CUDA on Arm](https://developer.nvidia.com/cuda-toolkit/arm)

[Learning the Arm Architecture](https://developer.arm.com/architectures/learn-the-architecture)

[Arm Development Tools and Software](https://www.arm.com/products/development-tools)

[GNU Arm Embedded Toolchain](https://developer.arm.com/tools-and-software/open-source-software/developer-tools/gnu-toolchain/gnu-rm)

[Internet of Things on Arm](https://developer.arm.com/solutions/internet-of-things/tools)

[MATLAB Code Generation for Deep Learning on ARM Targets](https://www.mathworks.com/help/deeplearning/ug/code-generation-for-deep-learning-on-arm-targets.html)

[Getting started with AWS Graviton](https://aws.amazon.com/ec2/graviton/)

[Improving performance of PHP for Arm64 and impact on AWS Graviton2 based EC2 instances](https://aws.amazon.com/blogs/compute/improving-performance-of-php-for-arm64-and-impact-on-amazon-ec2-m6g-instances/)

[Google's "Whitechapel" 5nm SoC Chip for future Pixel devices & Chromebooks](https://www.axios.com/scoop-google-readies-its-own-chip-for-future-pixels-chromebooks-e5f8479e-4a38-485c-a264-9ef9cf68908c.html)

[Qualcomm Snapdragon Mobile Platforms, Processors and Chipsets](https://www.qualcomm.com/snapdragon)

[Run ARM applications on the Android Emulator](https://android-developers.googleblog.com/2020/03/run-arm-apps-on-android-emulator.html)

[Android Application Binary Interface (ABIs)](https://developer.android.com/ndk/guides/abis)

[Raspberry Pi board computers](https://www.raspberrypi.org/)

[NVIDIA Jetson Nano 2GB Developer Kit](https://developer.nvidia.com/embedded/jetson-nano-2gb-developer-kit)

[Arm Online Courses](https://www.arm.com/resources/education/online-courses)

[Deep Learning on ARM Processors - From Ground Up online course](https://www.udemy.com/course/deep-learning-from-ground-uptm-on-arm-processors/)

[Embedded Systems using the ARM Mbed Platform online course](https://www.udemy.com/course/arm-mbed/)

[Microcontroller Courses from Coursera](https://www.coursera.org/courses?query=microcontroller)

# Apple Silicon & Learning Resources

[Back to the Top](https://github.com/mikeroyal/ARM-Guide/blob/main/README.md#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/105645197-de010180-5e4e-11eb-823b-c2152b3223ef.jpeg">
</p>

[Does it ARM? Apps that are reported to support Apple Silicon](https://doesitarm.com)

[Apple Hypervisor](https://developer.apple.com/documentation/hypervisor) is a frameowrk that builds virtualization solutions on top of a lightweight hypervisor, without third-party kernel extensions. Hypervisor provides C APIs so you can interact with virtualization technologies in user space, without writing kernel extensions (KEXTs). As a result, the apps you create using this framework are suitable for distribution on the [Mac App Store](https://www.appstore.com/).

[Apple A-series](https://www.apple.com/) is Apple's 64-bit ARM-based system on a chip (SoC) used in their iPhones and iPads. Though, at WWDC 2020 it was announced that [Apple Silicon](https://developer.apple.com/documentation/apple_silicon) would [transition into Mac laptops](https://www.apple.com/newsroom/2020/06/apple-announces-mac-transition-to-apple-silicon/). 

[Apple M1 Chip](https://www.apple.com/mac/m1/) is Apple's first SoC chip designed specifically for their ARM Mac products, it delivers incredible performance(8-core CPU and 8-core GPU), custom technologies, and great power efficiency. The M1 Chip is now availble for [Macbook Pro 13 with M1](https://www.apple.com/macbook-pro-13/), [Macbook Air 13 with M1](https://www.apple.com/macbook-air/), and [Mac Mini with M1](https://www.apple.com/mac-mini/).

[Xcode 12](https://developer.apple.com/xcode/) is built as an Universal app that runs 100% natively on Intel-based CPUs and Apple Silicon. It includes a unified macOS SDK that features all the frameworks, compilers, debuggers, and other tools you need to build apps that run natively on Apple Silicon and the Intel x86_64 CPU. 

[Tensorflow_macOS](https://github.com/apple/tensorflow_macos) is a Mac-optimized version of TensorFlow and TensorFlow Addons for macOS 11.0+ accelerated using Apple's ML Compute framework.

[Universal App Quick Start Program](https://developer.apple.com/programs/universal/)

[Writing ARM64 Code for Apple Platforms](https://developer.apple.com/documentation/xcode/writing_arm64_code_for_apple_platforms)

[Porting Your macOS Apps to Apple Silicon](https://developer.apple.com/documentation/xcode/porting_your_macos_apps_to_apple_silicon)

[Building a Universal macOS Binary](https://developer.apple.com/documentation/xcode/building_a_universal_macos_binary)

[Addressing Architectural Differences in Your macOS Code](https://developer.apple.com/documentation/apple_silicon/addressing_architectural_differences_in_your_macos_code)

[Porting Just-In-Time(JIT) Compilers to Apple Silicon](https://developer.apple.com/documentation/apple_silicon/porting_just-in-time_compilers_to_apple_silicon)

[Porting Your Audio Code to Apple Silicon](https://developer.apple.com/documentation/audiounit/porting_your_audio_code_to_apple_silicon)

[Porting Your Metal Code to Apple Silicon](https://developer.apple.com/documentation/metal/porting_your_metal_code_to_apple_silicon)

[Tuning Your Code’s Performance for Apple Silicon](https://developer.apple.com/documentation/os/workgroups/tuning_your_code_s_performance_for_apple_silicon)

[Learn how Rosetta translates executables and what Rosetta can’t translate](https://developer.apple.com/documentation/apple_silicon/about_the_rosetta_translation_environment)

[Running Your iOS Apps on macOS](https://developer.apple.com/documentation/apple_silicon/running_your_ios_apps_on_macos)

[Adapting iOS Code to Run in the macOS Environment](https://developer.apple.com/documentation/apple_silicon/adapting_ios_code_to_run_in_the_macos_environment)

[Implementing Drivers, System Extensions, and Kexts](https://developer.apple.com/documentation/apple_silicon/implementing_drivers_system_extensions_and_kexts)

[Installing a Custom Kernel Extension](https://developer.apple.com/documentation/apple_silicon/installing_a_custom_kernel_extension)

[Debugging a Custom Kernel Extension](https://developer.apple.com/documentation/apple_silicon/debugging_a_custom_kernel_extension)

# Linux on ARM

[Back to the Top](https://github.com/mikeroyal/ARM-Guide/blob/main/README.md#table-of-contents)

[Ubuntu Desktop](https://ubuntu.com/raspberry-pi)

[Ubuntu Server for ARM](https://ubuntu.com/download/server/arm)

[Ubuntu Wiki for ARM](https://wiki.ubuntu.com/ARM)

<h1 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/106686328-f5db3280-657e-11eb-9109-88a1df99983a.png">
  <br />
</h1>

[Debian for ARM](https://www.debian.org/releases/stable/arm64/)

[Debian Wiki](https://wiki.debian.org/)

<h1 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/107439775-73ef8a00-6ae7-11eb-9037-6aa910fc3c74.png">
  <br />
</h1>

[Fedora ARM](https://arm.fedoraproject.org)

[Fedora Project Wiki](http://fedoraproject.org/wiki/Fedora_Project_Wiki)

<h1 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/107158827-70220300-6941-11eb-917b-dbdb7142a13b.png">
  <br />
</h1>

[Manjaro Linux ARM](https://manjaro.org/download/#ARM)

[Manjaro Wiki](https://wiki.manjaro.org/index.php?title=Main_Page)

 <h1 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/107439879-9da8b100-6ae7-11eb-81a5-219d713130dc.png">
  <br />
</h1>

[EndeavourOS for ARM](https://arm.endeavouros.com/) 

[EndeavourOS Wiki](https://endeavouros.com/wiki/)

<h1 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/107439882-9e414780-6ae7-11eb-819e-e87e7bcc7a97.png">
  <br />
</h1>
 
[SUSE Linux Enterprise Server for ARM](https://www.suse.com/products/arm/)

[SUSE Wiki](https://documentation.suse.com/)

 <h1 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/107439814-84a00000-6ae7-11eb-843c-7c1ecc4b60cf.png">
  <br />
</h1>

[openSUSE for ARM](https://en.opensuse.org/Portal:ARM)

[openSUSE Wiki](https://en.opensuse.org/Main_Page)

<h1 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/107439822-879af080-6ae7-11eb-9404-9f1113945c0e.png">
  <br />
</h1>


# Windows 10 on ARM

[Back to the Top](https://github.com/mikeroyal/ARM-Guide/blob/main/README.md#table-of-contents)

[Windows 10 on ARM](https://docs.microsoft.com/en-us/windows/arm/)

[Windows 10X](https://docs.microsoft.com/en-us/windows/apps/10x/faq)

[Qualcomm Snapdragon Mobile Platforms, Processors and Chipsets](https://www.qualcomm.com/snapdragon)

[Introducing x64 emulation in preview for Windows 10 on ARM PCs to the Windows Insider Program](https://blogs.windows.com/windows-insider/2020/12/10/introducing-x64-emulation-in-preview-for-windows-10-on-arm-pcs-to-the-windows-insider-program/)

[Porting UWP applications for Windows 10 on ARM](https://docs.microsoft.com/en-us/windows/uwp/porting/apps-on-arm)

[Configuring C++ projects for ARM processors using the Microsoft Visual C++ (MSVC) compiler toolset](https://docs.microsoft.com/en-us/cpp/build/configuring-programs-for-arm-processors-visual-cpp)

<h1 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/109593441-d4aa2b00-7ac5-11eb-87f6-d88772c2ac9f.png">
  Windows 10 Deskop
</h1>

<h1 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/109593447-d70c8500-7ac5-11eb-9a73-ab9690d5a8e8.png">
  Windows 10X Deskop
</h1>

# ARM Tools & Projects

[Back to the Top](https://github.com/mikeroyal/ARM-Guide/blob/main/README.md#table-of-contents)

[Arm Instruction Emulator (ArmIE)](https://developer.arm.com/tools-and-software/server-and-hpc/compile/arm-instruction-emulator/resources/tutorials) is a tool that emulates Scalable Vector Extension (SVE) and SVE2 instructions on AArch64/ARM64 platforms. 

[Arm Mobile Studio](https://developer.arm.com/tools-and-software/graphics-and-gaming/arm-mobile-studio) is a suite of free-to-use performance analysis tools that automatically analyzes the CPU activity, GPU activity and content metrics of your game as it runs on a non-rooted Android device. 

[Android Studio](https://developer.android.com/studio/) is the official integrated development environment for Google's Android operating system, built on JetBrains' IntelliJ IDEA software and designed specifically for Android development. Availble on Windows, macOS, Linux, Chrome OS.

[Visual Studio](https://visualstudio.microsoft.com/) is an integrated development environment (IDE) from Microsoft; which is a feature-rich application that can be used for many aspects of software development. Visual Studio makes it easy to edit, debug, build, and publish your app. By using Microsoft software development platforms such as Windows API, Windows Forms, Windows Presentation Foundation, and Windows Store.

[Arduino IDE](https://www.arduino.cc/en/software) is an open-source integrated development environment for the Arduino platform that provides easy-to-use hardware and software.

[Compute Library](https://github.com/ARM-software/ComputeLibrary) is a set of computer vision and machine learning functions optimised for both Arm CPUs and GPUs using SIMD technologies.

[LISA](https://github.com/ARM-software/lisa) is a project provides a toolkit that supports regression testing and interactive analysis of Linux kernel behavior. LISA stands for Linux Integrated/Interactive System Analysis. LISA's goal is to help Linux kernel developers to measure the impact of modifications in core parts of the kernel. The focus is on the scheduler (EAS), power management and thermal frameworks. 

[LLVM](https://github.com/llvm/) is a library that has a collection of modular/reusable compiler and toolchain components(assemblers, compilers, debuggers, etc.). With these components LLVM can be used as a compiler framework, providing a front-end(parser and lexer) and a back-end(where code converts LLVM's representation to actual machine code).

[The Eclipse Embedded CDT](https://github.com/eclipse-embed-cdt/eclipse-plugins) is a collection of plug-ins for Arm & RISC-V C/C++ developers.

[PlatformIO](https://platformio.org/) is a professional collaborative platform for embedded development with no vendor lock-in. It provides support for multiplatforms and frameworks such as IoT, Arduino, CMSIS, ESP-IDF, FreeRTOS, libOpenCM3, mbed OS, Pulp OS, SPL, STM32Cube, Zephyr RTOS, ARM, AVR, Espressif (ESP8266/ESP32), FPGA, MCS-51 (8051), MSP430, Nordic (nRF51/nRF52), NXP i.MX RT, PIC32, RISC-V.

[PlatformIO for VSCode](https://marketplace.visualstudio.com/items?itemName=platformio.platformio-ide) is a plugin that provides support for the PlatformIO IDE on VSCode.

[simdjson](https://simdjson.org/) library uses commonly available SIMD instructions and microparallel algorithms to parse gigabytes of JSON per second.

[TinyGo](https://tinygo.org/) is a Go compiler(based on LLVM) intended for use in small places such as microcontrollers, WebAssembly (Wasm), and command-line tools.

[Unicorn](https://github.com/unicorn-engine/unicorn) is a lightweight, multi-platform, multi-architecture CPU emulator framework(ARM, AArch64, M68K, Mips, Sparc, X86) based on [QEMU](https://www.qemu.org/).

[Tock](https://www.tockos.org/) is an embedded operating system designed for running multiple concurrent, mutually distrustful applications on Cortex-M and RISC-V based embedded platforms. Tock's design centers around protection, both from potentially malicious applications and from device drivers. 

[Keystone](https://github.com/keystone-engine/keystone) is a lightweight multi-platform, multi-architecture(Arm, Arm64, Hexagon, Mips, PowerPC, Sparc, SystemZ & X86) assembler framework.

[faasd](https://openfaas.com/blog/introducing-faasd/) is a project similar to [OpenFaaS](https://github.com/openfaas/), but without the cost and complexity of Kubernetes. It runs on a single host with very modest requirements, making it fast and easy to manage. Under the hood it uses [containerd](https://containerd.io/) and [Container Networking Interface (CNI)](https://github.com/containernetworking/cni) along with the same core OpenFaaS components from the main project.

## Contribute

- [x] If would you like to contribute to this guide simply make a [Pull Request](https://github.com/mikeroyal/ARM-Guide/pulls).


## License
[Back to the Top](https://github.com/mikeroyal/ARM-Guide/blob/main/README.md#table-of-contents)

Distributed under the [Creative Commons Attribution 4.0 International (CC BY 4.0) Public License](https://creativecommons.org/licenses/by/4.0/).
