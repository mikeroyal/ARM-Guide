<h1 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/109712161-8bed8300-7b54-11eb-8ab1-0c91b7ff5159.png">
  <br />
  ARM Guide
</h1>

#### A guide covering ARM architecture including the applications and tools that will make you a better and more efficient ARM developer.

**Note: You can easily convert this markdown file to a PDF in [VSCode](https://code.visualstudio.com/) using this handy extension [Markdown PDF](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf).**

# Table of Contents

1. [ARM Learning Resources](https://github.com/mikeroyal/ARM-Guide#arm-learning-resources)

2. [ARM Tools & Projects](https://github.com/mikeroyal/ARM-Guide#arm-tools--projects)

3. [Apple Silicon & Learning Resources](https://github.com/mikeroyal/ARM-Guide#apple-silicon--learning-resources)

4. [Linux on ARM](https://github.com/mikeroyal/ARM-Guide#linux-on-arm)

5. [Windows on ARM](https://github.com/mikeroyal/ARM-Guide#windows-on-arm) 

6. [FPGA(Field Programmable Gate Arrays) Development](https://github.com/mikeroyal/ARM-Guide#fpga-development)

7. [Verilog/SystemVerilog Development](https://github.com/mikeroyal/ARM-Guide#verilogsystemverilog-development)

8. [C/C++ Development](https://github.com/mikeroyal/ARM-Guide#cc-development)

9. [Java Development](https://github.com/mikeroyal/ARM-Guide#java-development)

10. [Python Development](https://github.com/mikeroyal/ARM-Guide#python-development)

11. [Rust Development](https://github.com/mikeroyal/ARM-Guide#rust-development)

12. [Kubernetes](https://github.com/mikeroyal/ARM-Guide#kubernetes)

13. [Machine Learning](https://github.com/mikeroyal/ARM-Guide#machine-learning)

14. [Robotics](https://github.com/mikeroyal/ARM-Guide#robotics)

15. [Telco 5G](https://github.com/mikeroyal/ARM-Guide#telco-5g)

16. [Networking](https://github.com/mikeroyal/ARM-Guide#networking)


<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/156943308-e32a0d8c-0df8-4cc4-8dbc-e19de33953ea.png">
</p>

# ARM Learning Resources

[Back to the Top](https://github.com/mikeroyal/ARM-Guide/blob/main/README.md#table-of-contents)

[ARM](https://www.arm.com/) stands for Advanced RISC Machine, which is a collection of reduced instruction set computing architectures for CPUs configured for various development environments such servers, IoT, and other mobile devices. 

[Digital signal processing (DSP)](https://developer.arm.com/architectures/instruction-sets/dsp-extensions) is the use of digital processing, with computers or specialized digital signal processors, to perform a wide variety of signal processing operations.

[Floating-point](https://developer.arm.com/architectures/instruction-sets/floating-point) is a variable type that is used to store floating-point number values.  A Floating-point is particularly suitable when computational accuracy is a critical requirement and is essential for a wide range of digital signal processing (DSP) applications. Many applications that involve large data sets or data sets with unpredictable ranges also benefit from the precision and dynamic range of floating-point data types.

[A64 instruction set](https://developer.arm.com/architectures/instruction-sets/base-isas/a64) is an instruction set, introduced in Armv8-A to support the 64-bit architecture.

[Arm Processor IPs for Devices](https://www.arm.com/products/silicon-ip-cpu)

[Arm’s Total Compute design](https://www.arm.com/why-arm/total-compute)

[SVE and SVE2 Programmer's Guide](https://developer.arm.com/architectures/instruction-sets/simd-isas/sve/sve-programmers-guide)

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

[ARM64 Blog Series - Part 1: ARM Instruction Set + Simple Heap Overflow](https://8ksec.io/arm64-reversing-and-exploitation-part-1-arm-instruction-set-simple-heap-overflow/)

[ARM64 Blog Series - Part 2: Use After Free](https://8ksec.io/arm64-reversing-and-exploitation-part-2-use-after-free/)

[ARM64 Blog Series - Part 3: A Simple ROP Chain](https://8ksec.io/arm64-reversing-and-exploitation-part-3-a-simple-rop-chain/)

[ARM64 Blog Series - Part 4: Using Mprotect() To Bypass NX Protection](https://8ksec.io/arm64-reversing-and-exploitation-part-4-using-mprotect-to-bypass-nx-protection-8ksec-blogs/)

[ARM64 Blog Series - Part 5: Writing Shellcode](https://8ksec.io/arm64-reversing-and-exploitation-part-5-writing-shellcode-8ksec-blogs/)

[ARM64 Blog Series - Part 6: Exploiting An Uninitialized Stack Variable Vulnerability](https://8ksec.io/arm64-reversing-and-exploitation-part-6-exploiting-an-uninitialized-stack-variable-vulnerability/)

[ARM64 Blog Series - Part 7: Bypassing ASLR And NX](https://8ksec.io/arm64-reversing-and-exploitation-part-7-bypassing-aslr-and-nx/)

[ARM64 Blog Series - Part 8: Exploiting An Integer Overflow Vulnerability](https://8ksec.io/arm64-reversing-and-exploitation-part-8-exploiting-an-integer-overflow-vulnerability/)

[ARM64 Blog Series - Part 9 :Exploiting An Off By One Overflow Vulnerability](https://8ksec.io/arm64-reversing-and-exploitation-part-9-exploiting-an-off-by-one-overflow-vulnerability/)

[ARM64 Blog Series - Part 10: Intro To Arm Memory Tagging Extension (MTE)](https://8ksec.io/arm64-reversing-and-exploitation-part-10-intro-to-arm-memory-tagging-extension-mte/)

# ARM Tools & Projects

[Back to the Top](https://github.com/mikeroyal/ARM-Guide#table-of-contents)

[Armv9](https://www.arm.com/blogs/blueprint/armv9?_ga=2.37680224.1534693862.1616989380-1578602299.1612458803&_gac=1.48967698.1616092796.EAIaIQobChMIv8K527667wIVBfHACh3nBwKhEAAYASAAEgIdYfD_BwE) is a new Arm architecture built on the success of [Armv8](https://en.wikichip.org/wiki/arm/armv8) that offers a CPU performance increase of more than 30% over the next two generations of mobile and infrastructure CPUs. Armv9 will accelerate the move from general-purpose to more specialized compute across every application as AI, the Internet of Things (IoT) and 5G gain momentum world-wide.

[SVE2](https://developer.arm.com/tools-and-software/server-and-hpc/compile/arm-instruction-emulator/resources/tutorials/sve/sve-vs-sve2/introduction-to-sve2) is the Scalable Vector Extension version two of the Arm AArch64 architecture. It closley follows the development process of the [Neon architecture extension](https://www.arm.com/why-arm/technologies/neon), which has a fixed 128-bit vector length for the instruction set, Arm designed the Scalable Vector Extension (SVE). Arm developed SVE2 for [Armv9]((https://www.arm.com/blogs/blueprint/armv9_ga=2.37680224.1534693862.1616989380-1578602299.1612458803&_gac=1.48967698.1616092796.EAIaIQobChMIv8K527667wIVBfHACh3nBwKhEAAYASAAEgIdYfD_BwE)) to enable enhanced machine learning (ML) and digital signal processing (DSP) capabilities across a wider range of applications. SVE2 will enhance the processing ability of 5G systems, virtual and augmented reality, and ML workloads running locally on CPUs, such as image processing and smart home applications. 

[Arm Neon](https://www.arm.com/why-arm/technologies/neon) is an advanced single instruction [multiple data (SIMD) architecture extension](https://developer.arm.com/architectures/instruction-sets/simd-isas/neon) for the Arm Cortex-A and Arm Cortex-R series of processors with capabilities that vastly improve use cases on mobile devices, such as multimedia encoding/decoding, user interface, 2D/3D graphics and gaming.

[Arm Helium](https://developer.arm.com/architectures/instruction-sets/simd-isas/helium) is an extension of the Armv8.1-M architecture and delivers a significant performance uplift for machine learning and digital signal processing applications.

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
 <img src="https://user-images.githubusercontent.com/45159366/110054438-f3036700-7d0f-11eb-88bc-dab9b262c097.png">
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
 <img src="https://user-images.githubusercontent.com/45159366/110253144-9f766080-7f3d-11eb-9a01-2ac6738637e9.png">
  <br />
</h1>

[openSUSE for ARM](https://en.opensuse.org/Portal:ARM)

[openSUSE Wiki](https://en.opensuse.org/Main_Page)

<h1 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/110253145-a00ef700-7f3d-11eb-9b5c-d3cee3cbce84.png">
  <br />
</h1>

[Asahi Linux](https://asahilinux.org/) is a project and community with the goal of porting Linux to Apple Silicon Macs, starting with the 2020 M1 Mac Mini, MacBook Air, and MacBook Pro. Our goal is not just to make Linux run on these machines but to polish it to the point where it can be used as a daily OS.

[Asahi Linux Wiki](https://github.com/AsahiLinux/docs/wiki)

<h1 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/110054441-f4349400-7d0f-11eb-8889-743009b33994.png">
  <br />
</h1>

# Windows on ARM

[Back to the Top](https://github.com/mikeroyal/ARM-Guide/blob/main/README.md#table-of-contents)

[ARM64EC (“Emulation Compatible”)](https://docs.microsoft.com/en-us/windows/uwp/porting/arm64ec) is a new application binary interface (ABI) for Windows 11 on ARM that runs with native speed and is interoperable with x64 architecture. An app, process, or even a module can freely mix and match with ARM64EC and x64 as needed. The ARM64EC code in the app will run natively while any x64 code will run using Windows 11 on ARM’s built-in emulation. The ARM64EC ABI differs slightly from the current [ARM64 ABI](https://docs.microsoft.com/en-us/cpp/build/arm64-windows-abi-conventions?view=msvc-160) in ways that make it binary compatible with x64 code. Specifically, the ARM64EC ABI follows x64 software conventions including calling convention, stack usage, and data alignment, making ARM64EC and x64 interoperable. Apps built as ARM64EC may contain x64 code but do not have to, since ARM64EC is its own complete, first-class ABI for Windows.

[Windows 10 on ARM](https://docs.microsoft.com/en-us/windows/arm/)

[Qualcomm Snapdragon Mobile Platforms, Processors and Chipsets](https://www.qualcomm.com/snapdragon)

[Introducing x64 emulation in preview for Windows 10 on ARM PCs to the Windows Insider Program](https://blogs.windows.com/windows-insider/2020/12/10/introducing-x64-emulation-in-preview-for-windows-10-on-arm-pcs-to-the-windows-insider-program/)

[Porting UWP applications for Windows 10 on ARM](https://docs.microsoft.com/en-us/windows/uwp/porting/apps-on-arm)

[Configuring C++ projects for ARM processors using the Microsoft Visual C++ (MSVC) compiler toolset](https://docs.microsoft.com/en-us/cpp/build/configuring-programs-for-arm-processors-visual-cpp)

<h3 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124997795-20cf2400-e000-11eb-8954-4944286b8ea8.png">
  Windows 11 Desktop
</h3>

<h3 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/120387363-a9aabf80-c2de-11eb-84a5-8e4b422e7546.png">
  Windows 10 Desktop
</h3>

# FPGA Development

[Back to the Top](https://github.com/mikeroyal/ARM-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/104069966-ab060f00-51ba-11eb-8295-d3479b485c86.png">
  <br />
</p>

## Models of FPGA Boards

[Checkout the PolarFire® FPGA Development Kits](https://www.microsemi.com/product-directory/dev-kits-solutions/3864-polarfire-kits)

<img src="https://user-images.githubusercontent.com/45159366/104068349-97a67400-51b9-11eb-82b5-d06f804400ee.png">


[Checkout the Artix 7 FPGA Development board](https://store.digilentinc.com/basys-3-artix-7-fpga-trainer-board-recommended-for-introductory-users/)

<img src="https://user-images.githubusercontent.com/45159366/104068359-9d03be80-51b9-11eb-9bd2-0045e8f45eb9.png">


[Checkout the Spartan 6 FPGA Development board](https://store.digilentinc.com/anvyl-spartan-6-fpga-trainer-board/)

<img src="https://user-images.githubusercontent.com/45159366/104068361-9e34eb80-51b9-11eb-9c68-0b59c5a107e1.png">



[Checkout the Zynq-7000 for ARM/FPGA SoC Development board](https://store.digilentinc.com/cora-z7-zynq-7000-single-core-and-dual-core-options-for-arm-fpga-soc-development/)

<img src="https://user-images.githubusercontent.com/45159366/104068367-a12fdc00-51b9-11eb-966a-08a0868fcfb7.png">


## FPGA Learning Resources
 
[FPGA(Field Programmable Gate Arrays)](https://www.xilinx.com/products/silicon-devices/fpga/what-is-an-fpga.html) are semiconductor devices that are based around a matrix of configurable logic blocks (CLBs) connected via programmable interconnects. FPGAs can be reprogrammed to desired application or functionality requirements after manufacturing.

[TinyFPGA](https://tinyfpga.com) is a new series of boards that are low-cost, [open source FPGA boards](https://github.com/tinyfpga) in a tiny form factor.

[SiFive FPGA shells](https://github.com/sifive/fpga-shells)

[FPGA & SoC Design Tools from Microsemi](https://www.microsemi.com/product-directory/fpga-soc/1637-design-resources)

[QuickLogic Embedded FPGA (eFPGA) Intellectual Property (IP) and Software](https://www.quicklogic.com/products/efpga/efpga-ip-software/)

[FPGA for Beginners with Development Boards from Digilent®](https://store.digilentinc.com/fpga-for-beginners/)

[Hundreds of FPGA Projects on Instructables](https://www.instructables.com/circuits/howto/FPGA/)
 
[FPGA Fundamentals from NI(National Instruments)](https://www.ni.com/en-us/innovations/white-papers/08/fpga-fundamentals.html)

[Getting Started With LabVIEW FPGA from NI(National Instruments)](https://www.ni.com/tutorial/14532/en/)
 
[Programming and FPGA Basics - INTEL® FPGAS](https://www.intel.com/content/www/us/en/products/programmable/fpga/new-to-fpgas/resource-center/overview.html)
 
[Intel FPGA Training Program](https://www.intel.com/content/www/us/en/programmable/support/training/overview.html)
 
[FPGA Courses on Coursera](https://www.coursera.org/courses?query=fpga)
 
[FPGA Courses on Udemy](https://www.udemy.com/topic/fpga/)
 
[FPGA Online Training Courses on LinkedIn Learning](https://www.linkedin.com/learning/topics/fpga)

[UMass Lowell's Graduate Certificate in Field Programmable Gate Arrays(FPGA)](https://gps.uml.edu/certificates/grad/online-field-programmable-gate-arrays-bae-graduate-certificate.cfm)

[FPGA Design Fundamentals Course (UC San Diego Extension)](https://extension.ucsd.edu/courses-and-programs/fpga-design-fundamentals)

[FPGA II Course (UC San Diego Extension)](https://extension.ucsd.edu/courses-and-programs/fpga-embedded-design)

[FPGAs & SoCs Training from Microsemi](https://www.microsemi.com/product-directory/training/4244-fpgas-socs-training)
 
[DSP fundamentals for FPGAs course from MATLAB and Simulink Training](https://www.mathworks.com/training-schedule/dsp-for-fpgas.html)
 
[Verilog Courses on Coursera](https://www.coursera.org/courses?query=verilog)


## FPGA Tools

[LabVIEW FPGA](https://www.ni.com/en-us/shop/software/products/labview-fpga-module.html) is a software add-on for LabVIEW that you can use to more efficiently and effectively design FPGA-based systems through a highly integrated development environment, IP libraries, a high-fidelity simulator, and debugging features.

[Apio](https://github.com/FPGAwars/apio) is a multiplatform toolbox, with static pre-built packages, project configuration tools and easy command interface to verify, synthesize, simulate and upload your verilog designs.

[IceStorm](https://github.com/YosysHQ/icestorm) is a project that aims at documenting the bitstream format of Lattice iCE40 FPGAs and providing simple tools for analyzing and creating bitstream files.

[Icestudio](https://icestudio.io/) is a visual editor for open FPGA boards. Built on top of the Icestorm project using Apio.

[FuseSoC](https://github.com/olofk/fusesoc) is an award-winning package manager and a set of build tools for HDL (Hardware Description Language) code and FPGA/ASIC development.
 
[OpenWiFi](https://github.com/open-sdr/openwifi) is an open-source IEEE802.11/Wi-Fi baseband chip/FPGA design.
 
[PipeCNN](https://github.com/doonny/PipeCNN) is an OpenCL-based FPGA Accelerator for Large-Scale Convolutional Neural Networks (CNNs). Currently, there is a growing trend among developers in the FPGA community to utilize High Level Synthesis (HLS) tools to design and implement customized circuits on FPGAs.

[Verilator](https://verilator.org/) is an open-source SystemVerilog simulator and lint system.

[Verilog to Routing(VTR)](https://verilogtorouting.org/) is a collaborative project to provide a open-source framework for conducting FPGA architecture and CAD Research & Development. The VTR design flow takes as input a Verilog description of a digital circuit, and a description of the target FPGA architecture.

[PlatformIO](https://platformio.org/) is a professional collaborative platform for embedded development with no vendor lock-in. It provides support for multiplatforms and frameworks such as IoT, Arduino, CMSIS, ESP-IDF, FreeRTOS, libOpenCM3, mbed OS, Pulp OS, SPL, STM32Cube, Zephyr RTOS, ARM, AVR, Espressif (ESP8266/ESP32), FPGA, MCS-51 (8051), MSP430, Nordic (nRF51/nRF52), NXP i.MX RT, PIC32, RISC-V.

[PlatformIO for VSCode](https://marketplace.visualstudio.com/items?itemName=platformio.platformio-ide) is a plugin that provides support for the PlatformIO IDE on VSCode.
 
[Tock](https://www.tockos.org/) is an embedded operating system designed for running multiple concurrent, mutually distrustful applications on Cortex-M and RISC-V based embedded platforms. Tock's design centers around protection, both from potentially malicious applications and from device drivers. 

[OpenTimer](https://github.com/OpenTimer/OpenTimer) is a High-Performance Timing Analysis Tool for VLSI Systems.

[LLVM](https://github.com/llvm/) is a library that has collection of modular/reusable compiler and toolchain  components (assemblers, compilers, debuggers, etc.). With these components LLVM can be used as a compiler framework, providing a front-end(parser and lexer) and a back-end (code that converts LLVM's representation to actual machine code).

[TinyGo](https://tinygo.org/) is a Go compiler(based on LLVM) intended for use in small places such as microcontrollers, WebAssembly (Wasm), and command-line tools.

[Chipyard](https://chipyard.readthedocs.io/en/latest/) is an open source framework for agile development of Chisel-based systems-on-chip. It will allow you to leverage the Chisel HDL, Rocket Chip SoC generator, and other [Berkeley](https://berkeley.edu/) projects to produce a RISC-V SoC with everything from MMIO-mapped peripherals to custom accelerators.

[The Eclipse Embedded CDT](https://github.com/eclipse-embed-cdt/eclipse-plugins) is a collection of plug-ins for Arm & RISC-V C/C++ developers.
[Unicorn](https://github.com/unicorn-engine/unicorn) is a lightweight, multi-platform, multi-architecture CPU emulator framework(ARM, AArch64, M68K, Mips, Sparc, X86) based on [QEMU](https://www.qemu.org/).

[Keystone](https://github.com/keystone-engine/keystone) is a lightweight multi-platform, multi-architecture(Arm, Arm64, Hexagon, Mips, PowerPC, Sparc, SystemZ & X86) assembler framework.

[Reko](https://github.com/uxmal/reko) is a decompiler for machine code binaries.

[Renode](https://renode.io/) is [Antmicro's](https://antmicro.com) virtual development framework for multinode embedded networks (both wired and wireless) and is intended to enable a scalable workflow for creating effective, tested and secure IoT systems.

[Diosix](https://diosix.org/) is a lightweight, secure, multiprocessor bare-metal hypervisor written in Rust for RISC-V.

# Verilog/SystemVerilog Development

[Back to the Top](https://github.com/mikeroyal/ARM-Guide/blob/main/README.md#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/102273517-4b785480-3ed7-11eb-910a-113821428f17.png">
  <br />

</p>

## Verilog/SystemVerilog Learning Resources

[Verilog](https://verilog.com/) is a Hardware Description Language(HDL) used to design and document electronic systems. Verilog HDL allows designers to design at various levels of abstraction.

[SystemVerilog](https://www.systemverilog.io/) is an extension of Verilog with many of the verification features that allow engineers to verifythe design using complex testbench structures and random stimuli in simulation. 

[Verilog Book Shelf](https://verilog.com/v-books.html)

[Verilog HDL Basics training from Intel](https://www.intel.com/content/www/us/en/programmable/support/training/course/ohdl1120.html)

[SystemVerilog for Design and Verification](https://www.cadence.com/en_US/home/training/all-courses/82143.html)

[Verilog HDL Programming Courses on Udemy](https://www.udemy.com/topic/verilog-hdl-programming/)

[Top Verilog Programming Courses on Coursera](https://www.coursera.org/courses?query=verilog)

[Verilog course for Engineers on Technobyte](https://technobyte.org/verilog-course-tutorials/)

[Verilog Tutorials and Courses on hackr.io](https://hackr.io/tutorials/learn-verilog)

[Designing With Verilog Certification from the Xilinx Learning Center](https://xilinxprod-catalog.netexam.com/Certification/35916/designing-with-verilog)

[Learning Verilog for FPGA Development on LinkedIn Learning](https://www.linkedin.com/learning/learning-verilog-for-fpga-development)

[SystemVerilog tutorial on ChipVerify](https://www.chipverify.com/systemverilog/systemverilog-tutorial)

## Verilog/SystemVerilog Tools

[Apio](https://github.com/FPGAwars/apio) is a multiplatform toolbox, with static pre-built packages, project configuration tools and easy command interface to verify, synthesize, simulate and upload your verilog designs.

[IceStorm](https://github.com/YosysHQ/icestorm) is a project that aims at documenting the bitstream format of Lattice iCE40 FPGAs and providing simple tools for analyzing and creating bitstream files.

[Icestudio](https://icestudio.io/) is a visual editor for open FPGA boards. Built on top of the Icestorm project using Apio.

[EDA Playground](https://www.edaplayground.com) is a online code for programming your Verilog projects.

[PlatformIO](https://platformio.org/) is a professional collaborative platform for embedded development with no vendor lock-in. It provides support for multiplatforms and frameworks such as IoT, Arduino, CMSIS, ESP-IDF, FreeRTOS, libOpenCM3, mbed OS, Pulp OS, SPL, STM32Cube, Zephyr RTOS, ARM, AVR, Espressif (ESP8266/ESP32), FPGA, MCS-51 (8051), MSP430, Nordic (nRF51/nRF52), NXP i.MX RT, PIC32, RISC-V.

[PlatformIO for VSCode](https://marketplace.visualstudio.com/items?itemName=platformio.platformio-ide) is a plugin that provides support for the PlatformIO IDE on VSCode.

[Chisel](https://www.chisel-lang.org/) is a hardware design language that facilitates advanced circuit generation and design reuse for both ASIC and FPGA digital logic designs. Chisel adds hardware construction primitives to the [Scala](https://www.scala-lang.org/) programming language, providing designers with the power of a modern programming language to write complex, parameterizable circuit generators that produce synthesizable Verilog.

[Clash compiler](https://www.clash-lang.org/) is a functional hardware description language that borrows both its syntax and semantics from the functional programming language Haskell. The Clash compiler transforms these high-level descriptions to low-level synthesizable VHDL, Verilog, or SystemVerilog.

[Verilator](https://verilator.org/) is an open-source SystemVerilog simulator and lint system.

[Verilog to Routing(VTR)](https://verilogtorouting.org/) is a collaborative project to provide a open-source framework for conducting FPGA architecture and CAD Research & Development. The VTR design flow takes as input a Verilog description of a digital circuit, and a description of the target FPGA architecture.

[Cascade](https://github.com/vmware/cascade) is a Just-In-Time Compiler for Verilog from VMware Research. Cascade executes code immediately in a software simulator, and performs compilation in the background. When compilation is finished, the code is moved into hardware, and from the user’s perspective it simply gets faster over time.

[OpenTimer](https://github.com/OpenTimer/OpenTimer) is a High-Performance Timing Analysis Tool for VLSI Systems.


# C/C++ Development

[Back to the Top](https://github.com/mikeroyal/ARM-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/115297894-961e0d80-a111-11eb-81c3-e2bd2ac9a7cd.png">
  <br />
 
</p>


## C/C++ Learning Resources

[C++](https://www.cplusplus.com/doc/tutorial/) is a cross-platform language that can be used to build high-performance applications developed by Bjarne Stroustrup, as an extension to the C language.

[C](https://www.iso.org/standard/74528.html) is a general-purpose, high-level language that was originally developed by Dennis M. Ritchie to develop the UNIX operating system at Bell Labs. It supports structured programming, lexical variable scope, and recursion, with a static type system. C also provides constructs that map efficiently to typical machine instructions, which makes it one was of the most widely used programming languages today.

[Embedded C](https://en.wikipedia.org/wiki/Embedded_C) is a set of language extensions for the C programming language by the [C Standards Committee](https://isocpp.org/std/the-committee) to address issues that exist between C extensions for different [embedded systems](https://en.wikipedia.org/wiki/Embedded_system). The extensions hep enhance microprocessor features such as fixed-point arithmetic, multiple distinct memory banks, and basic I/O operations. This makes Embedded C the most popular embedded software language in the world.

[C & C++ Developer Tools from JetBrains](https://www.jetbrains.com/cpp/)

[Open source C++ libraries on cppreference.com](https://en.cppreference.com/w/cpp/links/libs)

[C++ Graphics libraries](https://cpp.libhunt.com/libs/graphics)

[C++ Libraries in MATLAB](https://www.mathworks.com/help/matlab/call-cpp-library-functions.html)

[C++ Tools and Libraries Articles](https://www.cplusplus.com/articles/tools/)

[Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html)

[Introduction C++ Education course on Google Developers](https://developers.google.com/edu/c++/)

[C++ style guide for Fuchsia](https://fuchsia.dev/fuchsia-src/development/languages/c-cpp/cpp-style)

[C and C++ Coding Style Guide by OpenTitan](https://docs.opentitan.org/doc/rm/c_cpp_coding_style/)

[Chromium C++ Style Guide](https://chromium.googlesource.com/chromium/src/+/master/styleguide/c++/c++.md)

[C++ Core Guidelines](https://github.com/isocpp/CppCoreGuidelines/blob/master/CppCoreGuidelines.md)

[C++ Style Guide for ROS](http://wiki.ros.org/CppStyleGuide)

[Learn C++](https://www.learncpp.com/)

[Learn C : An Interactive C Tutorial](https://www.learn-c.org/)

[C++ Institute](https://cppinstitute.org/free-c-and-c-courses)

[C++ Online Training Courses on LinkedIn Learning](https://www.linkedin.com/learning/topics/c-plus-plus)

[C++ Tutorials on W3Schools](https://www.w3schools.com/cpp/default.asp)

[Learn C Programming Online Courses on edX](https://www.edx.org/learn/c-programming)

[Learn C++ with Online Courses on edX](https://www.edx.org/learn/c-plus-plus)

[Learn C++ on Codecademy](https://www.codecademy.com/learn/learn-c-plus-plus)

[Coding for Everyone: C and C++ course on Coursera](https://www.coursera.org/specializations/coding-for-everyone)

[C++ For C Programmers on Coursera](https://www.coursera.org/learn/c-plus-plus-a)

[Top C Courses on Coursera](https://www.coursera.org/courses?query=c%20programming)

[C++ Online Courses on Udemy](https://www.udemy.com/topic/c-plus-plus/)

[Top C Courses on Udemy](https://www.udemy.com/topic/c-programming/)

[Basics of Embedded C Programming for Beginners on Udemy](https://www.udemy.com/course/embedded-c-programming-for-embedded-systems/)

[C++ For Programmers Course on Udacity](https://www.udacity.com/course/c-for-programmers--ud210)

[C++ Fundamentals Course on Pluralsight](https://www.pluralsight.com/courses/learn-program-cplusplus)

[Introduction to C++ on MIT Free Online Course Materials](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-096-introduction-to-c-january-iap-2011/)

[Introduction to C++ for Programmers | Harvard ](https://online-learning.harvard.edu/course/introduction-c-programmers)

[Online C Courses | Harvard University](https://online-learning.harvard.edu/subject/c)


## C/C++ Tools

[Visual Studio](https://visualstudio.microsoft.com/) is an integrated development environment (IDE) from Microsoft; which is a feature-rich application that can be used for many aspects of software development. Visual Studio makes it easy to edit, debug, build, and publish your app. By using Microsoft software development platforms such as Windows API, Windows Forms, Windows Presentation Foundation, and Windows Store.

[Visual Studio Code](https://code.visualstudio.com/) is a code editor redefined and optimized for building and debugging modern web and cloud applications.

[Vcpkg](https://github.com/microsoft/vcpkg) is a C++ Library Manager for Windows, Linux, and MacOS.

[ReSharper C++](https://www.jetbrains.com/resharper-cpp/features/) is a Visual Studio Extension for C++ developers developed by JetBrains.

[AppCode](https://www.jetbrains.com/objc/) is constantly monitoring the quality of your code. It warns you of errors and smells and suggests quick-fixes to resolve them automatically. AppCode provides lots of code inspections for Objective-C, Swift, C/C++, and a number of code inspections for other supported languages. All code inspections are run on the fly.

[CLion](https://www.jetbrains.com/clion/features/) is a cross-platform IDE for C and C++ developers developed by JetBrains.

[Code::Blocks](https://www.codeblocks.org/) is a free C/C++ and Fortran IDE built to meet the most demanding needs of its users. It is designed to be very extensible and fully configurable. Built around a plugin framework, Code::Blocks can be extended with plugins.

[CppSharp](https://github.com/mono/CppSharp) is a tool and set of libraries which facilitates the usage of native C/C++ code with the .NET ecosystem. It consumes C/C++ header and library files and generates the necessary glue code to surface the native API as a managed API. Such an API can be used to consume an existing native library in your managed code or add managed scripting support to a native codebase.

[Conan](https://conan.io/) is an Open Source Package Manager for C++ development and dependency management into the 21st century and on par with the other development ecosystems. 

[High Performance Computing (HPC) SDK](https://developer.nvidia.com/hpc) is a comprehensive toolbox for GPU accelerating HPC modeling and simulation applications. It includes the C, C++, and Fortran compilers, libraries, and analysis tools necessary for developing HPC applications on the NVIDIA platform.

[Thrust](https://github.com/NVIDIA/thrust) is a C++ parallel programming library which resembles the C++ Standard Library. Thrust's high-level interface greatly enhances programmer productivity while enabling performance portability between GPUs and multicore CPUs. Interoperability with established technologies such as CUDA, TBB, and OpenMP integrates with existing software.

[Boost](https://www.boost.org/) is an educational opportunity focused on cutting-edge C++. Boost has been a participant in the annual Google Summer of Code since 2007, in which students develop their skills by working on Boost Library development.

[Automake](https://www.gnu.org/software/automake/) is a tool for automatically generating Makefile.in files compliant with the GNU Coding Standards. Automake requires the use of GNU Autoconf.

[Cmake](https://cmake.org/) is an open-source, cross-platform family of tools designed to build, test and package software. CMake is used to control the software compilation process using simple platform and compiler independent configuration files, and generate native makefiles and workspaces that can be used in the compiler environment of your choice.

[GDB](http://www.gnu.org/software/gdb/) is a debugger, that allows you to see what is going on `inside' another program while it executes or what another program was doing at the moment it crashed. 

[GCC](https://gcc.gnu.org/) is a compiler Collection that includes front ends for C, C++, Objective-C, Fortran, Ada, Go, and D, as well as libraries for these languages.

[GSL](https://www.gnu.org/software/gsl/) is a numerical library for C and C++ programmers. It is free software under the GNU General Public License. The library provides a wide range of mathematical routines such as random number generators, special functions and least-squares fitting. There are over 1000 functions in total with an extensive test suite.

[OpenGL Extension Wrangler Library (GLEW)](https://www.opengl.org/sdk/libs/GLEW/) is a cross-platform open-source C/C++ extension loading library. GLEW provides efficient run-time mechanisms for determining which OpenGL extensions are supported on the target platform.

[Libtool](https://www.gnu.org/software/libtool/) is a generic library support script that hides the complexity of using shared libraries behind a consistent, portable interface. To use Libtool, add the new generic library building commands to your Makefile, Makefile.in, or Makefile.am.

[Maven](https://maven.apache.org/) is a software project management and comprehension tool. Based on the concept of a project object model (POM), Maven can manage a project's build, reporting and documentation from a central piece of information.

[TAU (Tuning And Analysis Utilities)](http://www.cs.uoregon.edu/research/tau/home.php) is capable of gathering performance information through instrumentation of functions, methods, basic blocks, and statements as well as event-based sampling. All C++ language features are supported including templates and namespaces.

[Clang](https://clang.llvm.org/) is a production quality C, Objective-C, C++ and Objective-C++ compiler when targeting X86-32, X86-64, and ARM (other targets may have caveats, but are usually easy to fix). Clang is used in production to build performance-critical software like Google Chrome or Firefox.

[OpenCV](https://opencv.org/) is a highly optimized library with focus on real-time applications. Cross-Platform C++, Python and Java interfaces support Linux, MacOS, Windows, iOS, and Android.

[Libcu++](https://nvidia.github.io/libcudacxx) is the NVIDIA C++ Standard Library for your entire system. It provides a heterogeneous implementation of the C++ Standard Library that can be used in and between CPU and GPU code.

[ANTLR (ANother Tool for Language Recognition)](https://www.antlr.org/) is a powerful parser generator for reading, processing, executing, or translating structured text or binary files. It's widely used to build languages, tools, and frameworks. From a grammar, ANTLR generates a parser that can build parse trees and also generates a listener interface that makes it easy to respond to the recognition of phrases of interest.

[Oat++](https://oatpp.io/) is a light and powerful C++ web framework for highly scalable and resource-efficient web application. It's zero-dependency and easy-portable.

[JavaCPP](https://github.com/bytedeco/javacpp) is a program that provides efficient access to native C++ inside Java, not unlike the way some C/C++ compilers interact with assembly language. 

[Cython](https://cython.org/) is a language that makes writing C extensions for Python as easy as Python itself. Cython is based on Pyrex, but supports more cutting edge functionality and optimizations such as calling C functions and declaring C types on variables and class attributes.

[Spdlog](https://github.com/gabime/spdlog) is a very fast, header-only/compiled, C++ logging library. 

[Infer](https://fbinfer.com/) is a static analysis tool for Java, C++, Objective-C, and C. Infer is written in [OCaml](https://ocaml.org/).


# Java Development

[Back to the Top](https://github.com/mikeroyal/ARM-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/93925952-c0b6fd80-fccb-11ea-9f90-21c4148e3c86.png">
  <br />
</p>


## Java Learning Resources

[Java](https://www.oracle.com/java/) is a popular programming language and development platform(JDK). It reduces costs, shortens development timeframes, drives innovation, and improves application services. With millions of developers running more than 51 billion Java Virtual Machines worldwide.

[The Eclipse Foundation](https://www.eclipse.org/downloads/) is home to a worldwide community of developers, the Eclipse IDE, Jakarta EE and over 375 open source projects, including runtimes, tools and frameworks for Java and other languages.

[Getting Started with Java](https://docs.oracle.com/javase/tutorial/)

[Oracle Java certifications from Oracle University](https://education.oracle.com/java-certification-benefits)

[Google Developers Training](https://developers.google.com/training/)

[Google Developers Certification](https://developers.google.com/certification/)

[Java Tutorial by W3Schools](https://www.w3schools.com/java/)

[Building Your First Android App in Java](codelabs.developers.google.com/codelabs/build-your-first-android-app/)

[Getting Started with Java in Visual Studio Code](https://code.visualstudio.com/docs/java/java-tutorial)

[Google Java Style Guide](https://google.github.io/styleguide/javaguide.html)

[AOSP Java Code Style for Contributors](https://source.android.com/setup/contribute/code-style)

[Chromium Java style guide](https://chromium.googlesource.com/chromium/src/+/master/styleguide/java/java.md)

[Get Started with OR-Tools for Java](https://developers.google.com/optimization/introduction/java)

[Getting started with Java Tool Installer task for Azure Pipelines](https://docs.microsoft.com/en-us/azure/devops/pipelines/tasks/tool/java-tool-installer)

[Gradle User Manual](https://docs.gradle.org/current/userguide/userguide.html)

## Tools

[Java SE](https://www.oracle.com/java/technologies/javase/tools-jsp.html) contains several tools to assist in program development and debugging, and in the monitoring and troubleshooting of production applications. 

[JDK Development Tools](https://docs.oracle.com/javase/7/docs/technotes/tools/) includes the Java Web Start Tools (javaws) Java Troubleshooting, Profiling, Monitoring and Management Tools (jcmd, jconsole, jmc, jvisualvm); and Java Web Services Tools (schemagen, wsgen, wsimport, xjc).

[Android Studio](https://developer.android.com/studio/) is the official integrated development environment for Google's Android operating system, built on JetBrains' IntelliJ IDEA software and designed specifically for Android development. Availble on Windows, macOS, Linux, Chrome OS.

[IntelliJ IDEA](https://www.jetbrains.com/idea/) is an IDE for Java, but it also understands and provides intelligent coding assistance for a large variety of other languages such as Kotlin, SQL, JPQL, HTML, JavaScript, etc., even if the language expression is injected into a String literal in your Java code.

[NetBeans](https://netbeans.org/features/java/index.html) is an IDE provides Java developers with all the tools needed to create professional desktop, mobile and enterprise applications. Creating, Editing, and Refactoring. The IDE provides wizards and templates to let you create Java EE, Java SE, and Java ME applications.

[Java Design Patterns ](https://github.com/iluwatar/java-design-patterns) is a collection of the best formalized practices a programmer can use to solve common problems when designing an application or system.

[Elasticsearch](https://www.elastic.co/products/elasticsearch) is a distributed RESTful search engine built for the cloud written in Java.

[RxJava](https://github.com/ReactiveX/RxJava) is a Java VM implementation of [Reactive Extensions](http://reactivex.io/): a library for composing asynchronous and event-based programs by using observable sequences. It extends the [observer pattern](http://en.wikipedia.org/wiki/Observer_pattern) to support sequences of data/events and adds operators that allow you to compose sequences together declaratively while abstracting away concerns about things like low-level threading, synchronization, thread-safety and concurrent data structures.

[Guava](https://github.com/google/guava) is a set of core Java libraries from Google that includes new collection types (such as multimap and multiset), immutable collections, a graph library, and utilities for concurrency, I/O, hashing, caching, primitives, strings, and more! It is widely used on most Java projects within Google, and widely used by many other companies as well.

[okhttp](https://square.github.io/okhttp/) is a HTTP client for Java and Kotlin developed by Square. 

[Retrofit](https://square.github.io/retrofit/) is a type-safe HTTP client for Android and Java develped by Square.

[LeakCanary](https://square.github.io/leakcanary/) is a memory leak detection library for Android develped by Square.

[Apache Spark](https://spark.apache.org/) is a unified analytics engine for large-scale data processing. It provides high-level APIs in Scala, Java, Python, and R, and an optimized engine that supports general computation graphs for data analysis. It also supports a rich set of higher-level tools including Spark SQL for SQL and DataFrames, MLlib for machine learning, GraphX for graph processing, and Structured Streaming for stream processing.

[Apache Flink](https://flink.apache.org/) is an open source stream processing framework with powerful stream- and batch-processing capabilities with elegant and fluent APIs in Java and Scala.

[Fastjson](https://github.com/alibaba/fastjson/wiki) is a Java library that can be used to convert Java Objects into their JSON representation. It can also be used to convert a JSON string to an equivalent Java object.

[libGDX](https://libgdx.com/) is a cross-platform Java game development framework based on OpenGL (ES) that works on Windows, Linux, Mac OS X, Android, your WebGL enabled browser and iOS.

[Jenkins](https://www.jenkins.io/) is the leading open-source automation server. Built with Java, it provides over 1700 [plugins](https://plugins.jenkins.io/) to support automating virtually anything, so that humans can actually spend their time doing things machines cannot.

[DBeaver](https://dbeaver.io/) is a free multi-platform database tool for developers, SQL programmers, database administrators and analysts. Supports any database which has JDBC driver (which basically means - ANY database). EE version also supports non-JDBC datasources (MongoDB, Cassandra, Redis, DynamoDB, etc).

[Redisson](https://redisson.pro/) is a Redis Java client with features of In-Memory Data Grid. Over 50 Redis based Java objects and services: Set, Multimap, SortedSet, Map, List, Queue, Deque, Semaphore, Lock, AtomicLong, Map Reduce, Publish / Subscribe, Bloom filter, Spring Cache, Tomcat, Scheduler, JCache API, Hibernate, MyBatis, RPC, and local cache.

[GraalVM](https://www.graalvm.org/) is a universal virtual machine for running applications written in JavaScript, Python, Ruby, R, JVM-based languages like Java, Scala, Clojure, Kotlin, and LLVM-based languages such as C and C++.

[Gradle](https://gradle.org/) is a build automation tool for multi-language software development. From mobile apps to microservices, from small startups to big enterprises, Gradle helps teams build, automate and deliver better software, faster. Write in Java, C++, Python or your language of choice. 

[Apache Groovy](http://www.groovy-lang.org/) is a powerful, optionally typed and dynamic language, with static-typing and static compilation capabilities, for the Java platform aimed at improving developer productivity thanks to a concise, familiar and easy to learn syntax. It integrates smoothly with any Java program, and immediately delivers to your application powerful features, including scripting capabilities, Domain-Specific Language authoring, runtime and compile-time meta-programming and functional programming. 

[JaCoCo](https://www.jacoco.org/jacoco/) is a free code coverage library for Java, which has been created by the EclEmma team based on the lessons learned from using and integration existing libraries for many years.

[Apache JMeter](http://jmeter.apache.org/) is  used to test performance both on static and dynamic resources, Web dynamic applications. It also used to simulate a heavy load on a server, group of servers, network or object to test its strength or to analyze overall performance under different load types.

[Junit](https://junit.org/) is a simple framework to write repeatable tests. It is an instance of the xUnit architecture for unit testing frameworks.

[Mockito](https://site.mockito.org/) is the most popular Mocking framework for unit tests written in Java.

[SpotBugs](https://spotbugs.github.io/) is a program which uses static analysis to look for bugs in Java code.

[SpringBoot](https://spring.io/projects/spring-boot) is a great tool that helps you to create Spring-powered, production-grade applications and services with absolute minimum fuss. It takes an opinionated view of the Spring platform so that new and existing users can quickly get to the bits they need.

[YourKit](https://www.yourkit.com/) is a technology leader, creator of the most innovative and intelligent tools for profiling Java & .NET applications.

# Python Development

[Back to the Top](https://github.com/mikeroyal/ARM-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/93133273-ce490380-f68b-11ea-81d0-7f6a3debe6c0.png">
  <br />
  
</p>

## Python Learning Resources

[Python](https://www.python.org) is an interpreted, high-level programming language. Python is used heavily in the fields of Data Science and Machine Learning. 

[Python Developer’s Guide](https://devguide.python.org) is a comprehensive resource for contributing to Python – for both new and experienced contributors. It is maintained by the same community that maintains Python. 

[Azure Functions Python developer guide](https://docs.microsoft.com/en-us/azure/azure-functions/functions-reference-python) is an introduction to developing Azure Functions using Python. The content below assumes that you've already read the [Azure Functions developers guide](https://docs.microsoft.com/en-us/azure/azure-functions/functions-reference).

[CheckiO](https://checkio.org/) is a programming learning platform and a gamified website that teaches Python through solving code challenges and competing for the most elegant and creative solutions.

[Python Institute](https://pythoninstitute.org)

[PCEP – Certified Entry-Level Python Programmer certification](https://pythoninstitute.org/pcep-certification-entry-level/)

[PCAP – Certified Associate in Python Programming certification](https://pythoninstitute.org/pcap-certification-associate/)

[PCPP – Certified Professional in Python Programming 1 certification](https://pythoninstitute.org/pcpp-certification-professional/)

[PCPP – Certified Professional in Python Programming 2](https://pythoninstitute.org/pcpp-certification-professional/)

[MTA: Introduction to Programming Using Python Certification](https://docs.microsoft.com/en-us/learn/certifications/mta-introduction-to-programming-using-python)

[Getting Started with Python in Visual Studio Code](https://code.visualstudio.com/docs/python/python-tutorial)

[Google's Python Style Guide](https://google.github.io/styleguide/pyguide.html)

[Google's Python Education Class](https://developers.google.com/edu/python/)

[Real Python](https://realpython.com)

[The Python Open Source Computer Science Degree by Forrest Knight](https://github.com/ForrestKnight/open-source-cs-python)

[Intro to Python for Data Science](https://www.datacamp.com/courses/intro-to-python-for-data-science)

[Intro to Python by W3schools](https://www.w3schools.com/python/python_intro.asp)

[Codecademy's Python 3 course](https://www.codecademy.com/learn/learn-python-3)

[Learn Python with Online Courses and Classes from edX](https://www.edx.org/learn/python)

[Python Courses Online from Coursera](https://www.coursera.org/courses?query=python)

## Python Frameworks and Tools

[Python Package Index (PyPI)](https://pypi.org/) is a repository of software for the Python programming language. PyPI helps you find and install software developed and shared by the Python community. 

[PyCharm](https://www.jetbrains.com/pycharm/) is the best IDE I've ever used. With PyCharm, you can access the command line, connect to a database, create a virtual environment, and manage your version control system all in one place, saving time by avoiding constantly switching between windows.

[Python Tools for Visual Studio(PTVS)](https://microsoft.github.io/PTVS/) is a free, open source plugin that turns Visual Studio into a Python IDE. It supports editing, browsing, IntelliSense, mixed Python/C++ debugging, remote Linux/MacOS debugging, profiling, IPython, and web development with Django and other frameworks.

[Pylance](https://github.com/microsoft/pylance-release) is an extension that works alongside Python in Visual Studio Code to provide performant language support. Under the hood, Pylance is powered by Pyright, Microsoft's static type checking tool.

[Pyright](https://github.com/Microsoft/pyright) is a fast type checker meant for large Python source bases. It can run in a “watch” mode and performs fast incremental updates when files are modified.

[Django](https://www.djangoproject.com/) is a high-level Python Web framework that encourages rapid development and clean, pragmatic design.

[Flask](https://flask.palletsprojects.com/) is a micro web framework written in Python. It is classified as a microframework because it does not require particular tools or libraries. 
 
[Web2py](http://web2py.com/) is an open-source web application framework written in Python allowing allows web developers to program dynamic web content. One web2py instance can run multiple web sites using different databases.

[AWS Chalice](https://github.com/aws/chalice) is a framework for writing serverless apps in python. It allows you to quickly create and deploy applications that use AWS Lambda. 

[Tornado](https://www.tornadoweb.org/) is a Python web framework and asynchronous networking library. Tornado uses a non-blocking network I/O, which can scale to tens of thousands of open connections.

[HTTPie](https://github.com/httpie/httpie) is a command line HTTP client that makes CLI interaction with web services as easy as possible. HTTPie is designed for testing, debugging, and generally interacting with APIs & HTTP servers. 

[Scrapy](https://scrapy.org/) is a fast high-level web crawling and web scraping framework, used to crawl websites and extract structured data from their pages. It can be used for a wide range of purposes, from data mining to monitoring and automated testing.

[Sentry](https://sentry.io/) is a service that helps you monitor and fix crashes in realtime. The server is in Python, but it contains a full API for sending events from any language, in any application.

[Pipenv](https://github.com/pypa/pipenv) is a tool that aims to bring the best of all packaging worlds (bundler, composer, npm, cargo, yarn, etc.) to the Python world.

[Python Fire](https://github.com/google/python-fire) is a library for automatically generating command line interfaces (CLIs) from absolutely any Python object.

[Bottle](https://github.com/bottlepy/bottle) is a fast, simple and lightweight [WSGI](https://www.wsgi.org/) micro web-framework for Python. It is distributed as a single file module and has no dependencies other than the [Python Standard Library](https://docs.python.org/library/).

[CherryPy](https://cherrypy.org) is a minimalist Python object-oriented HTTP web framework.

[Sanic](https://github.com/huge-success/sanic) is a Python 3.6+ web server and web framework that's written to go fast. 

[Pyramid](https://trypyramid.com) is a small and fast open source Python web framework. It makes real-world web application development and deployment more fun and more productive.

[TurboGears](https://turbogears.org) is a hybrid web framework able to act both as a Full Stack framework or as a Microframework. 

[Falcon](https://falconframework.org/) is a reliable, high-performance Python web framework for building large-scale app backends and microservices with support for MongoDB, Pluggable Applications and autogenerated Admin.

[Neural Network Intelligence(NNI)](https://github.com/microsoft/nni) is an open source AutoML toolkit for automate machine learning lifecycle, including [Feature Engineering](https://github.com/microsoft/nni/blob/master/docs/en_US/FeatureEngineering/Overview.md), [Neural Architecture Search](https://github.com/microsoft/nni/blob/master/docs/en_US/NAS/Overview.md), [Model Compression](https://github.com/microsoft/nni/blob/master/docs/en_US/Compressor/Overview.md) and [Hyperparameter Tuning](https://github.com/microsoft/nni/blob/master/docs/en_US/Tuner/BuiltinTuner.md).

[Dash](https://plotly.com/dash) is a popular Python framework for building ML & data science web apps for Python, R, Julia, and Jupyter.

[Luigi](https://github.com/spotify/luigi) is a Python module that helps you build complex pipelines of batch jobs. It handles dependency resolution, workflow management, visualization etc. It also comes with Hadoop support built-in.

[Locust](https://github.com/locustio/locust) is an easy to use, scriptable and scalable performance testing tool. 

[spaCy](https://github.com/explosion/spaCy) is a library for advanced Natural Language Processing in Python and Cython. 

[NumPy](https://www.numpy.org/) is the fundamental package needed for scientific computing with Python.

[Pillow](https://python-pillow.org/) is a friendly PIL(Python Imaging Library) fork.

[IPython](https://ipython.org/) is a command shell for interactive computing in multiple programming languages, originally developed for the Python programming language, that offers enhanced introspection, rich media, additional shell syntax, tab completion, and rich history.

[GraphLab Create](https://turi.com/) is a Python library, backed by a C++ engine, for quickly building large-scale, high-performance machine learning models.

[Pandas](https://pandas.pydata.org/) is a fast, powerful, and easy to use open source data structrures, data analysis and manipulation tool, built on top of the Python programming language.

[PuLP](https://coin-or.github.io/pulp/) is an Linear Programming modeler written in python. PuLP can generate LP files and call on use highly optimized solvers, GLPK, COIN CLP/CBC, CPLEX, and GUROBI, to solve these linear problems.

[Matplotlib](https://matplotlib.org/) is a 2D plotting library for creating static, animated, and interactive visualizations in Python. Matplotlib produces publication-quality figures in a variety of hardcopy formats and interactive environments across platforms.

[Scikit-Learn](https://scikit-learn.org/stable/index.html) is a simple and efficient tool for data mining and data analysis. It is built on NumPy,SciPy, and mathplotlib.

# Rust Development

[Back to the Top](https://github.com/mikeroyal/ARM-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/93025405-8dc98700-f5b2-11ea-93f9-12b4a0ef3001.png">
  <br />
</p>

## Rust Learning Resources

[Rust](https://www.rust-lang.org) is a multi-paradigm programming language focused on performance and safety. Rust has a comparable amount of runtime to C and C++, and has set up its standard library to be amenable towards OS development. Specifically, the standard library is split into two parts: core and std. Core is the lowest-level aspects only, and doesn't include things like allocation, threading, and other higher-level features.

[The Rust Language Reference](https://doc.rust-lang.org/nightly/reference/)

[The Rust Programming Language Book](https://doc.rust-lang.org/book/)

[Learning Rust](https://www.rust-lang.org/learn)

[Why AWS loves Rust](https://aws.amazon.com/blogs/opensource/why-aws-loves-rust-and-how-wed-like-to-help/)

[Rust Programming courses on Udemy](https://www.udemy.com/courses/search/?src=ukw&q=Rust)

[Safety in Systems Programming with Rust at Standford by Ryan Eberhardt](https://reberhardt.com/blog/2020/10/05/designing-a-new-class-at-stanford-safety-in-systems-programming.html)

[WebAssembly meets Kubernetes with Krustlet using Rust](https://cloudblogs.microsoft.com/opensource/2020/04/07/announcing-krustlet-kubernetes-rust-kubelet-webassembly-wasm/)

[Microsoft's Project Verona](https://github.com/microsoft/verona/blob/master/docs/explore.md)

## Rust Tools

[Cargo](https://github.com/rust-lang/cargo) is a package manager that downloads your Rust project’s dependencies and compiles your project.

[Crater](https://crater.rust-lang.org/) is a tool to run experiments across parts of the Rust ecosystem. Its primary purpose is to detect regressions in the Rust compiler, and it does this by building a large number of crates, running their test suites and comparing the results between two versions of the Rust compiler. It can operate locally (with Docker as the only dependency) or distributed on the cloud. It can operate locally (with Docker as the only dependency) or distributed on the cloud.

[VSCode-Rust](https://github.com/rust-lang/vscode-rust) is plugin that adds language support for Rust to Visual Studio Code. Rust support is powered by a separate language server - either by the official Rust Language Server (RLS) or rust-analyzer, depending on the user's preference. If you don't have it installed, the extension will install it for you (with permission). This extension is built and maintained by the Rust IDEs and editors team with the focus on providing a stable, high quality extension that makes the best use of the respective language server. 

[Apache Arrow](https://github.com/apache/arrow) is a development platform for in-memory analytics. It contains a set of technologies that enable big data systems to process and move data fast. Arrow's libraries are available for C, C++, C#, Go, Java, JavaScript, MATLAB, Python, R, Ruby, and Rust.

[Wasmer](https://wasmer.io/) enables super lightweight containers based on [WebAssembly](https://webassembly.org/) that can run anywhere such as the Desktop to the Cloud and IoT devices, and also embedded in [any programming language](https://github.com/wasmerio/wasmer#language-integrations).

[Firecracker](https://firecracker-microvm.github.io) is an open source virtualization technology that is purpose-built for creating and managing secure, multi-tenant container and function-based services that provide serverless operational models. Firecracker runs workloads in lightweight virtual machines, called microVMs, which combine the security and isolation properties provided by hardware virtualization technology with the speed and flexibility of containers. Firecracker has also been integrated in container runtimes, for example [Kata Containers](https://github.com/kata-containers/documentation/wiki/Initial-release-of-Kata-Containers-with-Firecracker-support) and [Weaveworks Ignite](https://github.com/weaveworks/ignite).

[Tokio](https://github.com/tokio-rs/tokio) is an event-driven, non-blocking I/O platform for writing asynchronous applications with the Rust programming language.

[TiKV](https://github.com/tikv/tikv) is an open-source distributed transactional key-value database that also provides classical key-vlue APIs, but also transactional APIs with ACID compliance.

[Sonic](https://crates.io/crates/sonic-server) is a fast, lightweight and schema-less search backend similar to Elasticsearch in some use-cases.

[Hyper](https://github.com/hyperium/hyper) is a fast and correct HTTP library for Rust.

[Rocket](https://github.com/SergioBenitez/Rocket) is an async web framework for Rust with a focus on usability, security, extensibility, and speed.

[Clippy](https://rust-lang.github.io/rust-clippy/) is a collection of lints to catch common mistakes and improve your Rust code.

[Servo](https://github.com/servo/servo) is a prototype web browser engine written in the Rust language.

[Vector](https://vector.dev/) is a high-performance, end-to-end (agent & aggregator) observability data platform that puts the user in control of their observability data.

[RustPython](https://github.com/RustPython/RustPython) is a Python Interpreter written in Rust.

[Miri](https://github.com/rust-lang/miri) is an interpreter for Rust's mid-level intermediate representation. It can run binaries and test suites of cargo projects and detect certain classes of undefined behavior. Miri will alsowill also tell you about memory leaks: when there is memory still allocated at the end of the execution, and that memory is not reachable from a global static, Miri will raise an error.

[Chalk](https://rust-lang.github.io/chalk/book/) is an implementation and definition of the Rust trait system using a PROLOG-like logic solver.

[stdarch](https://doc.rust-lang.org/stable/core/arch/) is Rust's standard library vendor-specific APIs and run-time feature detection.

[Simpleinfra](https://github.com/rust-lang/simpleinfra) is rep that contains the tools and automation written by the Rust infrastructure team to manage our services. Using some of the tools in this repo require privileges only infra team members have.

[Rustlings](https://github.com/rust-lang/rustlings) is a small set of exercises to get you used to reading and writing Rust code.

[Krustlet](https://krustlet.dev/) acts as a Kubernetes Kubelet(written in Rust) by listening on the event stream for new pods that the scheduler assigns to it based on specific Kubernetes [tolerations](https://kubernetes.io/docs/concepts/configuration/taint-and-toleration/). The project is currently experimental.

## Operating System

[Redox](https://www.redox-os.org) is a Unix-like Operating System written in Rust, aiming to bring the innovations of Rust to a modern microkernel and full set of applications. Acitvely being developed by [Jeremy Soeller](https://gitlab.redox-os.org/jackpot51).

[Bottlerocket OS](https://github.com/bottlerocket-os/bottlerocket) is an open-source Linux-based operating system meant for hosting containers. Bottlerocket focuses on security and maintainability, providing a reliable, consistent, and safe platform for container-based workloads.

[Tock](https://www.tockos.org) is an embedded operating system designed for running multiple concurrent, mutually distrustful applications on Cortex-M and RISC-V based embedded platforms. Tock's design centers around protection, both from potentially malicious applications and from device drivers. Tock uses two mechanisms to protect different components of the operating system. First, the kernel and device drivers are written in Rust, a systems programming language that provides compile-time memory safety, type safety and strict aliasing. Tock uses Rust to protect the kernel (the scheduler and hardware abstraction layer) from platform specific device drivers as well as isolate device drivers from each other. Second, Tock uses memory protection units to isolate applications from each other and the kernel.

[Rust on Chrome OS](https://chromium.googlesource.com/chromiumos/docs/+/master/rust_on_cros.md) is a document that provides information on creating Rust projects for installation within Chrome OS and Chrome OS SDK. 

[Writing an OS in Rust ](https://os.phil-opp.com) is a blog series creates a small operating system in the Rust programming language by [Philipp Oppermann](https://github.com/phil-opp). 

# Kubernetes

[Back to the Top](https://github.com/mikeroyal/ARM-Guide#table-of-contents)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/95383873-a884d800-08a0-11eb-8eaf-57af5b119f56.png">
</p>

[Kubernetes (K8s)](https://kubernetes.io/) is an open-source system for automating deployment, scaling, and management of containerized applications. 

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/105645195-db9ea780-5e4e-11eb-8357-fb38b2f06d74.png">

**Building Highly-Availability(HA) Clusters with kubeadm. Source: [Kubernetes.io](https://kubernetes.io/docs/setup/production-environment/tools/kubeadm/high-availability/), 2020**
</p>

[Google Kubernetes Engine (GKE)](https://cloud.google.com/kubernetes-engine/) is a managed, production-ready environment for running containerized applications.

[Azure Kubernetes Service (AKS)](https://azure.microsoft.com/en-us/services/kubernetes-service/) is serverless Kubernetes, with a integrated continuous integration and continuous delivery (CI/CD) experience, and enterprise-grade security and governance. Unite your development and operations teams on a single platform to rapidly build, deliver, and scale applications with confidence.

[Amazon EKS](https://docs.aws.amazon.com/eks/latest/userguide/what-is-eks.html) is a tool that runs Kubernetes control plane instances across multiple Availability Zones to ensure high availability.

[AWS Controllers for Kubernetes (ACK)](https://aws.amazon.com/blogs/containers/aws-controllers-for-kubernetes-ack/) is a new tool that lets you directly manage AWS services from Kubernetes. ACK makes it simple to build scalable and highly-available Kubernetes applications that utilize AWS services.

[Container Engine for Kubernetes (OKE)](https://www.oracle.com/cloud-native/container-engine-kubernetes/) is an Oracle-managed container orchestration service that can reduce the time and cost to build modern cloud native applications. Unlike most other vendors, Oracle Cloud Infrastructure provides Container Engine for Kubernetes as a free service that runs on higher-performance, lower-cost compute.

[Anthos](https://cloud.google.com/anthos/docs/concepts/overview) is a modern application management platform that provides a consistent development and operations experience for cloud and on-premises environments.

[Red Hat Openshift](https://www.openshift.com/) is a fully managed Kubernetes platform that provides a foundation for on-premises, hybrid, and multicloud deployments. 

[OKD](https://okd.io/) is a community distribution of Kubernetes optimized for continuous application development and multi-tenant deployment. OKD adds developer and operations-centric tools on top of Kubernetes to enable rapid application development, easy deployment and scaling, and long-term lifecycle maintenance for small and large teams.

[Odo](https://odo.dev/) is a fast, iterative, and straightforward CLI tool for developers who write, build, and deploy applications on Kubernetes and OpenShift.

[Kata Operator](https://github.com/openshift/kata-operator) is an operator to perform lifecycle management (install/upgrade/uninstall) of [Kata Runtime](https://katacontainers.io/) on Openshift as well as Kubernetes cluster.

[Thanos](https://thanos.io/) is a set of components that can be composed into a highly available metric system with unlimited storage capacity, which can be added seamlessly on top of existing Prometheus deployments.

[OpenShift Hive](https://github.com/openshift/hive) is an operator which runs as a service on top of Kubernetes/OpenShift. The Hive service can be used to provision and perform initial configuration of OpenShift 4 clusters.

[Rook](https://rook.io/) is a tool that turns distributed storage systems into self-managing, self-scaling, self-healing storage services. It automates the tasks of a storage administrator: deployment, bootstrapping, configuration, provisioning, scaling, upgrading, migration, disaster recovery, monitoring, and resource management.

[VMware Tanzu](https://tanzu.vmware.com/tanzu) is a centralized management platform for consistently operating and securing your Kubernetes infrastructure and modern applications across multiple teams and private/public clouds.

[Kubespray](https://kubespray.io/) is a tool that combines Kubernetes and Ansible to easily install Kubernetes clusters that can be deployed on [AWS](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/aws.md), GCE, [Azure](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/azure.md), [OpenStack](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/openstack.md), [vSphere](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/vsphere.md), [Packet](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/packet.md) (bare metal), Oracle Cloud Infrastructure (Experimental), or Baremetal.

[KubeInit](https://github.com/kubeinit/kubeinit) provides Ansible playbooks and roles for the deployment and configuration of multiple Kubernetes distributions.

[Rancher](https://rancher.com/) is a complete software stack for teams adopting containers. It addresses the operational and security challenges of managing multiple Kubernetes clusters, while providing DevOps teams with integrated tools for running containerized workloads.

[K3s](https://github.com/rancher/k3s) is a highly available, certified Kubernetes distribution designed for production workloads in unattended, resource-constrained, remote locations or inside IoT appliances. 

[Helm](https://helm.sh/) is a Kubernetes Package Manager tool that makes it easier to install and manage Kubernetes applications.

[Knative](https://knative.dev/) is a Kubernetes-based platform to build, deploy, and manage modern serverless workloads. Knative takes care of the operational overhead details of networking, autoscaling (even to zero), and revision tracking. 

[KubeFlow](https://www.kubeflow.org/) is a tool dedicated to making deployments of machine learning (ML) workflows on Kubernetes simple, portable and scalable.

[Etcd](https://etcd.io/) is a distributed key-value store that provides a reliable way to store data that needs to be accessed by a distributed system or cluster of machines. Etcd is used as the backend for service discovery and stores cluster state and configuration for Kubernetes.

[OpenEBS](https://openebs.io/) is a Kubernetes-based tool to create stateful applications using Container Attached Storage.

[Container Storage Interface (CSI)](https://www.architecting.it/blog/container-storage-interface/) is an API that lets container orchestration platforms like Kubernetes seamlessly communicate with stored data via a plug-in.

[MicroK8s](https://microk8s.io/) is a tool that delivers the full Kubernetes experience. In a Fully containerized deployment with compressed over-the-air updates for ultra-reliable operations. It is supported on Linux, Windows, and MacOS.

[Charmed Kubernetes](https://ubuntu.com/kubernetes/features) is a well integrated, turn-key, conformant Kubernetes platform, optimized for your multi-cloud environments developed by Canonical.

[Grafana Kubernetes App](https://grafana.com/grafana/plugins/grafana-kubernetes-app) is a toll that allows you to monitor your Kubernetes cluster's performance. It includes 4 dashboards, Cluster, Node, Pod/Container and Deployment. It allows for the automatic deployment of the required Prometheus exporters and a default scrape config to use with your in cluster Prometheus deployment.

[KubeEdge](https://kubeedge.io/en/) is an open source system for extending native containerized application orchestration capabilities to hosts at Edge.It is built upon kubernetes and provides fundamental infrastructure support for network, app. deployment and metadata synchronization between cloud and edge.

[Lens](https://k8slens.dev/)  is the most powerful IDE for people who need to deal with Kubernetes clusters on a daily basis. It has support for MacOS, Windows and Linux operating systems.

[kind](https://kind.sigs.k8s.io/) is a tool for running local Kubernetes clusters using Docker container “nodes”. It was primarily designed for testing Kubernetes itself, but may be used for local development or CI.

[Flux CD](https://fluxcd.io/) is a tool that automatically ensures that the state of your Kubernetes cluster matches the configuration you've supplied in Git. It uses an operator in the cluster to trigger deployments inside Kubernetes, which means that you don't need a separate continuous delivery tool.

## Kubernetes Learning Resources

[Getting Kubernetes Certifications](https://training.linuxfoundation.org/certification/catalog/?_sft_technology=kubernetes)

[Getting started with Kubernetes on AWS](https://aws.amazon.com/kubernetes/)

[Kubernetes on Microsoft Azure](https://azure.microsoft.com/en-us/topic/what-is-kubernetes/)

[Intro to Azure Kubernetes Service](https://docs.microsoft.com/en-us/azure/aks/kubernetes-dashboard)

[Getting started with Google Cloud](https://cloud.google.com/learn/what-is-kubernetes)

[Getting started with Kubernetes on Red Hat](https://www.redhat.com/en/topics/containers/what-is-kubernetes)

[Getting started with Kubernetes on IBM](https://www.ibm.com/cloud/learn/kubernetes)

[YAML basics in Kubernetes](https://developer.ibm.com/technologies/containers/tutorials/yaml-basics-and-usage-in-kubernetes/)

[Elastic Cloud on Kubernetes](https://www.elastic.co/elastic-cloud-kubernetes)

[Docker and Kubernetes](https://www.docker.com/products/kubernetes)

[Deploy a model to an Azure Kubernetes Service cluster](https://docs.microsoft.com/en-us/azure/machine-learning/how-to-deploy-azure-kubernetes-service?tabs=python)

[Simplify Machine Learning Inference on Kubernetes with Amazon SageMaker Operators](https://aws.amazon.com/blogs/machine-learning/simplify-machine-learning-inference-on-kubernetes-with-amazon-sagemaker-operators/)

[Running Apache Spark on Kubernetes](http://spark.apache.org/docs/latest/running-on-kubernetes.html)

[Kubernetes Across VMware vRealize Automation](https://blogs.vmware.com/management/2019/06/kubernetes-across-vmware-cloud-automation-services.html)

[VMware Tanzu Kubernetes Grid](https://tanzu.vmware.com/kubernetes-grid)

[All the Ways VMware Tanzu Works with AWS](https://tanzu.vmware.com/content/blog/all-the-ways-vmware-tanzutm-works-with-aws)

[VMware Tanzu Education](https://tanzu.vmware.com/education)

[Using Ansible in a Cloud-Native Kubernetes Environment](https://www.ansible.com/blog/how-useful-is-ansible-in-a-cloud-native-kubernetes-environment)

[Managing Kubernetes (K8s) objects with Ansible](https://docs.ansible.com/ansible/latest/collections/community/kubernetes/k8s_module.html)

[Setting up a Kubernetes cluster using Vagrant and Ansible](https://kubernetes.io/blog/2019/03/15/kubernetes-setup-using-ansible-and-vagrant/)

[Running MongoDB with Kubernetes](https://www.mongodb.com/kubernetes)

[Kubernetes Fluentd](https://docs.fluentd.org/v/0.12/articles/kubernetes-fluentd)

[Understanding the new GitLab Kubernetes Agent](https://about.gitlab.com/blog/2020/09/22/introducing-the-gitlab-kubernetes-agent/)

[Kubernetes Contributors](https://www.kubernetes.dev/)

[KubeAcademy from VMware](https://kube.academy/)

# Machine Learning

[Back to the Top](https://github.com/mikeroyal/ARM-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/108111395-756e0480-7049-11eb-85ca-b87315e9d3ef.jpeg">
 </p>

 
 ## ML frameworks & applications

[TensorFlow Lite](https://www.tensorflow.org/lite/guide) is a set of tools to help developers run TensorFlow models on mobile, embedded, and IoT devices. It enables on-device machine learning inference with low latency and a small binary size.

[PyTorch](https://pytorch.org) is a library for deep learning on irregular input data such as graphs, point clouds, and manifolds. Primarily developed by Facebook's AI Research lab.

[Amazon SageMaker](https://aws.amazon.com/sagemaker/) is a fully managed service that provides every developer and data scientist with the ability to build, train, and deploy machine learning (ML) models quickly. SageMaker removes the heavy lifting from each step of the machine learning process to make it easier to develop high quality models.

[Azure Databricks](https://azure.microsoft.com/en-us/services/databricks/) is a fast and collaborative Apache Spark-based big data analytics service designed for data science and data engineering. Azure Databricks, sets up your Apache Spark environment in minutes, autoscale, and collaborate on shared projects in an interactive workspace. Azure Databricks supports Python, Scala, R, Java, and SQL, as well as data science frameworks and libraries including TensorFlow, PyTorch, and scikit-learn.

[Microsoft Cognitive Toolkit (CNTK)](https://docs.microsoft.com/en-us/cognitive-toolkit/) is an open-source toolkit for commercial-grade distributed deep learning. It describes neural networks as a series of computational steps via a directed graph. CNTK allows the user to easily realize and combine popular model types such as feed-forward DNNs, convolutional neural networks (CNNs) and recurrent neural networks (RNNs/LSTMs). CNTK implements stochastic gradient descent (SGD, error backpropagation) learning with automatic differentiation and parallelization across multiple GPUs and servers.

[Apache Airflow](https://airflow.apache.org) is an open-source workflow management platform created by the community to programmatically author, schedule and monitor workflows. Install. Principles. Scalable. Airflow has a modular architecture and uses a message queue to orchestrate an arbitrary number of workers. Airflow is ready to scale to infinity.

[Open Neural Network Exchange(ONNX)](https://github.com/onnx) is an open ecosystem that empowers AI developers to choose the right tools as their project evolves. ONNX provides an open source format for AI models, both deep learning and traditional ML. It defines an extensible computation graph model, as well as definitions of built-in operators and standard data types.

[Apache MXNet](https://mxnet.apache.org/) is a deep learning framework designed for both efficiency and flexibility. It allows you to mix symbolic and imperative programming to maximize efficiency and productivity. At its core, MXNet contains a dynamic dependency scheduler that automatically parallelizes both symbolic and imperative operations on the fly. A graph optimization layer on top of that makes symbolic execution fast and memory efficient. MXNet is portable and lightweight, scaling effectively to multiple GPUs and multiple machines. Support for Python, R, Julia, Scala, Go, Javascript and more.

[AutoGluon](https://autogluon.mxnet.io/index.html) is toolkit for Deep learning that automates machine learning tasks enabling you to easily achieve strong predictive performance in your applications. With just a few lines of code, you can train and deploy high-accuracy deep learning models on tabular, image, and text data.

[Anaconda](https://www.anaconda.com/) is a very popular Data Science platform for machine learning and deep learning that enables users to develop models, train them, and deploy them.

[PlaidML](https://github.com/plaidml/plaidml) is an advanced and portable tensor compiler for enabling deep learning on laptops, embedded devices, or other devices where the available computing hardware is not well supported or the available software stack contains unpalatable license restrictions.

[OpenCV](https://opencv.org) is a highly optimized library with focus on real-time computer vision applications. The C++, Python, and Java interfaces support Linux, MacOS, Windows, iOS, and Android.

[Scikit-Learn](https://scikit-learn.org/stable/index.html) is a Python module for machine learning built on top of SciPy, NumPy, and matplotlib, making it easier to apply robust and simple implementations of many popular machine learning algorithms.

[Weka](https://www.cs.waikato.ac.nz/ml/weka/) is an open source machine learning software that can be accessed through a graphical user interface, standard terminal applications, or a Java API. It is widely used for teaching, research, and industrial applications, contains a plethora of built-in tools for standard machine learning tasks, and additionally gives transparent access to well-known toolboxes such as scikit-learn, R, and Deeplearning4j. 

[Theano](https://github.com/Theano/Theano) is a Python library that allows you to define, optimize, and evaluate mathematical expressions involving multi-dimensional arrays efficiently including tight integration with NumPy.

[nGraph](https://github.com/NervanaSystems/ngraph) is an open source C++ library, compiler and runtime for Deep Learning. The nGraph Compiler aims to accelerate developing AI workloads using any deep learning framework and deploying to a variety of hardware targets.It provides the freedom, performance, and ease-of-use to AI developers.

[Jupyter Notebook](https://jupyter.org/) is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text. Jupyter is used widely in industries that do data cleaning and transformation, numerical simulation, statistical modeling, data visualization, data science, and machine learning.

## Online ML Learning Resources

[Machine Learning by Stanford University from Coursera](https://www.coursera.org/learn/machine-learning)

[Machine Learning Courses Online from Coursera](https://www.coursera.org/courses?query=machine%20learning&)

[Machine Learning Courses Online from Udemy](https://www.udemy.com/topic/machine-learning/)

[Learn Machine Learning with Online Courses and Classes from edX](https://www.edx.org/learn/machine-learning)

# Robotics

[Back to the Top](https://github.com/mikeroyal/ARM-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/96352533-b55fb380-1078-11eb-874c-f165cbcce899.png">
</p>

## Tools for Robotics

[ROS](https://www.ros.org/) is robotics middleware. Although ROS is not an operating system, it provides services designed for a heterogeneous computer cluster such as hardware abstraction, low-level device control, implementation of commonly used functionality, message-passing between processes, and package management.

[ROS2](https://index.ros.org/doc/ros2/) is a set of [software libraries and tools](https://github.com/ros2) that help you build robot applications. From drivers to state-of-the-art algorithms, and with powerful developer tools, ROS has what you need for your next robotics project. And it’s all open source.

[Robot Framework](https://robotframework.org/) is a generic open source automation framework. It can be used for test automation and robotic process automation. It has easy syntax, utilizing human-readable keywords. Its capabilities can be extended by libraries implemented with Python or Java. 

[The Robotics Library (RL)](https://github.com/roboticslibrary/rl) is a self-contained C++ library for robot kinematics, motion planning and control. It covers mathematics, kinematics and dynamics, hardware abstraction, motion planning, collision detection, and visualization.RL runs on many different systems, including Linux, macOS, and Windows. It uses CMake as a build system and can be compiled with Clang, GCC, and Visual Studio.

[MoveIt](https://moveit.ros.org/) is the most widely used software for manipulation and has been used on over 100 robots. It provides an easy-to-use robotics platform for developing advanced applications, evaluating new designs and building integrated products for industrial, commercial, R&D, and other domains.

[AutoGluon](https://autogluon.mxnet.io/index.html) is toolkit for [Deep learning](https://gitlab.com/maos20008/intro-to-machine-learning) that automates machine learning tasks enabling you to easily achieve strong predictive performance in your applications. With just a few lines of code, you can train and deploy high-accuracy deep learning models on tabular, image, and text data.

[Gazebo](http://gazebosim.org/) accurately and efficiently simulates indoor and outdoor robots. You get a robust physics engine, high-quality graphics, and programmatic and graphical interfaces.

[Robotics System Toolbox](https://www.mathworks.com/products/robotics.html) provides tools and algorithms for designing, simulating, and testing manipulators, mobile robots, and humanoid robots. For manipulators and humanoid robots, the toolbox includes algorithms for collision checking, trajectory generation, forward and inverse kinematics, and dynamics using a rigid body tree representation. 
For mobile robots, it includes algorithms for mapping, localization, path planning, path following, and motion control. The toolbox provides reference examples of common industrial robot applications. It also includes a library of 
commercially available industrial robot models that you can import, visualize, and simulate.

[Intel Robot DevKit](https://github.com/intel/robot_devkit) is the tool to generate Robotics Software Development Kit (RDK) designed for autonomous devices, including the ROS2 core and capacibilities packages like perception, planning, control driver etc. It provides flexible build/runtime configurations to meet different autonomous requirement on top of diversity hardware choices, for example use different hareware engine CPU/GPU/VPU to accelerate AI related features.

[Arduino](https://www.arduino.cc/) is an open-source platform used for building electronics projects. Arduino consists of both a physical programmable circuit board (often referred to as a microcontroller) and a piece of software, or IDE (Integrated Development Environment) that runs on your computer, used to write and upload computer code to the physical board.

[ArduPilot](https://ardupilot.org/ardupilot/index.html) enables the creation and use of trusted, autonomous, unmanned vehicle systems for the peaceful benefit of all. ArduPilot provides a comprehensive suite of tools suitable for almost any vehicle and application.

[AirSim](https://github.com/Microsoft/AirSim) is a simulator for drones, cars and more, built on Unreal Engine (we now also have an experimental Unity release). It is open-source, cross platform, and supports hardware-in-loop with popular flight controllers such as PX4 for physically and visually realistic simulations.

[F´ (F Prime)](https://github.com/nasa/fprime) is a component-driven framework that enables rapid development and deployment of spaceflight and other embedded software applications. Originally developed at the Jet Propulsion Laboratory, F´ has been successfully deployed on several space applications.

[The JPL Open Source Rover](https://github.com/nasa-jpl/open-source-rover) is an open source, build it yourself, scaled down version of the 6 wheel rover design that JPL uses to explore the surface of Mars. The Open Source Rover is designed almost entirely out of consumer off the shelf (COTS) parts. This project is intended to be a teaching and learning experience for those who want to get involved in mechanical engineering, software, electronics, or robotics.

[Light Detection and Ranging(LiDAR)](https://en.wikipedia.org/wiki/Lidar) is a remote sensing method that uses light in the form of a pulsed laser at an object, and uses the time and wavelength of the reflected beam of light to estimate the distance and in some applications ([Laser Imaging](https://en.wikipedia.org/wiki/Laser_scanning)), to create a 3D representation of the object and its surface characteristics. This technology is commonly used in aircraft and self-driving vehicles.

[AliceVision](https://github.com/alicevision/AliceVision) is a Photogrammetric Computer Vision Framework which provides a 3D Reconstruction and Camera Tracking algorithms. AliceVision aims to provide strong software basis with state-of-the-art computer vision algorithms that can be tested, analyzed and reused. The project is a result of collaboration between academia and industry to provide cutting-edge algorithms with the robustness and the quality required for production usage.

[CARLA](https://github.com/carla-simulator/carla) is an open-source simulator for autonomous driving research. CARLA has been developed from the ground up to support development, training, and validation of autonomous driving systems. In addition to open-source code and protocols, CARLA provides open digital assets (urban layouts, buildings, vehicles) that were created for this purpose and can be used freely. The simulation platform supports flexible specification of sensor suites and environmental conditions.

[ROS bridge](https://github.com/carla-simulator/ros-bridge) is a package to bridge ROS for CARLA Simulator.

[ROS-Industrial](https://rosindustrial.org/) is an open source project that extends the advanced capabilities of ROS software to manufacturing.

[AWS RoboMaker](https://aws.amazon.com/robomaker/) is the most complete cloud solution for robotic developers to simulate, test and securely deploy robotic applications at scale. RoboMaker provides a fully-managed, scalable infrastructure for simulation that customers use for multi-robot simulation and CI/CD integration with regression testing in simulation.

[Microsoft Robotics Developer Studio](https://www.microsoft.com/en-us/download/details.aspx?id=29081)  is a free .NET-based programming environment for building robotics applications. 

[Visual Studio Code Extension for ROS](https://github.com/ms-iot/vscode-ros) is an extension provides support for Robot Operating System (ROS) development.

[Azure Kinect ROS Driver](https://github.com/microsoft/azure_kinect_ros_driver) is a node which publishes sensor data from the [Azure Kinect Developer Kit](https://azure.microsoft.com/en-us/services/kinect-dk/) to the [Robot Operating System (ROS)](http://www.ros.org/). Developers working with ROS can use this node to connect an Azure Kinect Developer Kit to an existing ROS installation.

[Azure IoT Hub for ROS](https://github.com/microsoft/ros_azure_iothub) is a ROS package works with the Microsoft Azure IoT Hub service to relay telemetry messages from the Robot to Azure IoT Hub or reflect properties from the Digital Twin to the robot using dynamic reconfigure.

[ROS 2 with ONNX Runtime](https://github.com/ms-iot/ros_msft_onnx) is a program that uses ROS 2 to run on different hardware platforms using their respective AI acceleration libraries for optimized execution of the ONNX model.

[Azure Cognitive Services LUIS ROS Node](https://github.com/ms-iot/ros_msft_luis) is a ROS node that bridges between ROS and the Azure Language Understanding Service. it can be configured to process audio directly from a microphone, or can subscribe to a ROS audio topic, then processes speech and generates "intent" ROS messages which can be processed by another ROS node to generate ROS commands. 

## Robotics Learning Resources

[Robotics courses from Coursera](https://www.edx.org/learn/robotics)

[Learn Robotics with Online Courses and Classes from edX](https://www.edx.org/learn/robotics)

[Top Robotics Courses Online from Udemy](https://www.udemy.com/topic/robotics/)

[Free Online AI & Robotics Courses](https://www.futurelearn.com/subjects/it-and-computer-science-courses/ai-and-robotics)

[REC Foundation Robotics Industry Certification](https://www.roboticseducation.org/industry-certifications/)

[Carnegie Mellon Robotics Academy](https://www.cmu.edu/roboticsacademy/Training/Certifications.html)

[RIA Robotic Integrator Certification Program](https://www.robotics.org/robotics/integrator-certification)

[AWS RoboMaker – Develop, Test, Deploy, and Manage Intelligent Robotics Apps](https://aws.amazon.com/blogs/aws/aws-robomaker-develop-test-deploy-and-manage-intelligent-robotics-apps/)

[Microsoft AI School](https://aischool.microsoft.com/en-us/home)

[Language Understanding (LUIS) for Azure Cognitive Services](https://docs.microsoft.com/en-us/azure/cognitive-services/luis/what-is-luis)

[Azure VM templates to bootstrap ROS and ROS 2 environments](https://ms-iot.github.io/ROSOnWindows/ROSAtMS/AzureVM.html)

[Google Robotics Research](https://research.google/teams/brain/robotics/)

# Telco 5G

[Back to the Top](https://github.com/mikeroyal/ARM-Guide#table-of-contents)


<img src="https://user-images.githubusercontent.com/45159366/105409952-14881380-5be6-11eb-84fc-b07db69698ed.png">
 
 **VMware Cloud First Approach. Source: [VMware](https://www.vmware.com/products/telco-cloud-automation.html).**
 
 
 <img src="https://user-images.githubusercontent.com/45159366/105409956-1520aa00-5be6-11eb-8215-735c92a5470c.png">
 
 **VMware Telco Cloud Automation Components. Source: [VMware](https://www.vmware.com/products/telco-cloud-automation.html).**
 
 
## Telco Learning Resources

[HPE(Hewlett Packard Enterprise) Telco Blueprints overview](https://techhub.hpe.com/eginfolib/servers/docs/Telco/Blueprints/infocenter/index.html#GUID-9906A227-C1FB-4FD5-A3C3-F3B72EC81CAB.html)

[Network Functions Virtualization Infrastructure (NFVI) by Cisco](https://www.cisco.com/c/en/us/solutions/service-provider/network-functions-virtualization-nfv-infrastructure/index.html)

[Introduction to vCloud NFV Telco Edge from VMware](https://docs.vmware.com/en/VMware-vCloud-NFV-OpenStack-Edition/3.1/vloud-nfv-edge-reference-arch-31/GUID-744C45F1-A8D5-4523-9E5E-EAF6336EE3A0.html)

[VMware Telco Cloud Automation(TCA) Architecture Overview](https://docs.vmware.com/en/VMware-Telco-Cloud-Platform-5G-Edition/1.0/telco-cloud-platform-5G-edition-reference-architecture/GUID-C19566B3-F42D-4351-BA55-DE70D55FB0DD.html)

[5G Telco Cloud from VMware](https://telco.vmware.com/)

[Maturing OpenStack Together To Solve Telco Needs from Red Hat](https://www.redhat.com/cms/managed-files/4.Nokia%20CloudBand%20&%20Red%20Hat%20-%20Maturing%20Openstack%20together%20to%20solve%20Telco%20needs%20Ehud%20Malik,%20Senior%20PLM,%20Nokia%20CloudBand.pdf)

[Red Hat telco ecosystem program](https://connect.redhat.com/en/programs/telco-ecosystem)

[OpenStack for Telcos by Canonical](https://ubuntu.com/blog/openstack-for-telcos-by-canonical)

[Open source NFV platform for 5G from Ubuntu](https://ubuntu.com/telco)

[Understanding 5G Technology from Verizon](https://www.verizon.com/5g/)

[Verizon and Unity partner to enable 5G & MEC gaming and enterprise applications](https://www.verizon.com/about/news/verizon-unity-partner-5g-mec-gaming-enterprise)

[Understanding 5G Technology from Intel](https://www.intel.com/content/www/us/en/wireless-network/what-is-5g.html)

[Understanding 5G Technology from Qualcomm](https://www.qualcomm.com/invention/5g/what-is-5g)

[Telco Acceleration with Xilinx](https://www.xilinx.com/applications/wired-wireless/telco.html)

[VIMs on OSM Public Wiki](https://osm.etsi.org/wikipub/index.php/VIMs)

[Amazon EC2 Overview and Networking Introduction for Telecom Companies](https://docs.aws.amazon.com/whitepapers/latest/ec2-networking-for-telecom/ec2-networking-for-telecom.pdf)

[Citrix Certified Associate – Networking(CCA-N)](http://training.citrix.com/cms/index.php/certification/networking/)

[Citrix Certified Professional – Virtualization(CCP-V)](https://www.globalknowledge.com/us-en/training/certification-prep/brands/citrix/section/virtualization/citrix-certified-professional-virtualization-ccp-v/)

[CCNP Routing and Switching](https://learningnetwork.cisco.com/s/ccnp-enterprise)

[Certified Information Security Manager(CISM)](https://www.isaca.org/credentialing/cism)

[Wireshark Certified Network Analyst (WCNA)](https://www.wiresharktraining.com/certification.html)

[Juniper Networks Certification Program Enterprise (JNCP)](https://www.juniper.net/us/en/training/certification/)

[Cloud Native Computing Foundation Training and Certification Program](https://www.cncf.io/certification/training/)


## Tools

[Open Stack](https://www.openstack.org/) is an open source cloud platform, deployed as infrastructure-as-a-service (IaaS) to orchestrate data center operations on bare metal, private cloud hardware, public cloud resources, or both (hybrid/multi-cloud architecture). OpenStack includes advance use of virtualization & SDN for network traffic optimization to handle the core cloud-computing services of compute, networking, storage, identity, and image services.

[StarlingX](https://www.starlingx.io/) is a complete cloud infrastructure software stack for the edge used by the most demanding applications in industrial IOT, telecom, video delivery and other ultra-low latency use cases.

[Airship](https://www.airshipit.org/) is a collection of open source tools for automating cloud provisioning and management. Airship provides a declarative framework for defining and managing the life cycle of open infrastructure tools and the underlying hardware.

[Network functions virtualization (NFV)](https://www.vmware.com/topics/glossary/content/network-functions-virtualization-nfv) is the replacement of network appliance hardware with virtual machines. The virtual machines use a hypervisor to run networking software and processes such as routing and load balancing. NFV allows for the separation of communication services from dedicated hardware, such as routers and firewalls. This separation means network operations can provide new services dynamically and without installing new hardware. Deploying network components with network functions virtualization only takes hours compared to months like with traditional networking solutions. 

[Software Defined Networking (SDN)](https://www.vmware.com/topics/glossary/content/software-defined-networking) is an approach to networking that uses software-based controllers or application programming interfaces (APIs) to communicate with underlying hardware infrastructure and direct traffic on a network. This model differs from that of traditional networks, which use dedicated hardware devices (routers and switches) to control network traffic. 

[Virtualized Infrastructure Manager (VIM)](https://www.cisco.com/c/en/us/td/docs/net_mgmt/network_function_virtualization_Infrastructure/3_2_2/install_guide/Cisco_VIM_Install_Guide_3_2_2/Cisco_VIM_Install_Guide_3_2_2_chapter_00.html) is a service delivery and reduce costs with high performance lifecycle management Manage the full lifecycle of the software and hardware comprising your NFV infrastructure (NFVI), and maintaining a live inventory and allocation plan of both physical and virtual resources.

[Management and Orchestration(MANO)](https://www.etsi.org/technologies/open-source-mano) is an ETSI-hosted initiative to develop an Open Source NFV Management and Orchestration (MANO) software stack aligned with ETSI NFV. Two of the key components of the ETSI NFV architectural framework are the NFV Orchestrator and VNF Manager, known as NFV MANO.

[Magma](https://www.magmacore.org/) is an open source software platform that gives network operators an open, flexible and extendable mobile core network solution. Their mission is to connect the world to a faster network by enabling service providers to build cost-effective and extensible carrier-grade networks. Magma is 3GPP generation (2G, 3G, 4G or upcoming 5G networks) and access network agnostic (cellular or WiFi). It can flexibly support a radio access network with minimal development and deployment effort.

[OpenRAN](https://open-ran.org/) is an intelligent Radio Access Network(RAN) integrated on general purpose platforms with open interface between software defined functions. Open RANecosystem enables enormous flexibility and interoperability with a complete openess to multi-vendor deployments.

[Open vSwitch(OVS)](https://www.openvswitch.org/)is an open source production quality, multilayer virtual switch licensed under the open source Apache 2.0 license. It is designed to enable massive network automation through programmatic extension, while still supporting standard management interfaces and protocols (NetFlow, sFlow, IPFIX, RSPAN, CLI, LACP, 802.1ag).

[Edge](https://www.ibm.com/cloud/what-is-edge-computing) is a distributed computing framework that brings enterprise applications closer to data sources such as IoT devices or local edge servers. This proximity to data at its source can deliver strong business benefits, including faster insights, improved response times and better bandwidth availability.

[Multi-access edge computing (MEC)](https://www.etsi.org/technologies/multi-access-edge-computing) is an Industry Specification Group (ISG) within ETSI to create a standardized, open environment which will allow the efficient and seamless integration of applications from vendors, service providers, and third-parties across multi-vendor Multi-access Edge Computing platforms.

[Virtualized network functions(VNFs)](https://www.juniper.net/documentation/en_US/cso4.1/topics/concept/nsd-vnf-overview.html) is a software application used in a Network Functions Virtualization (NFV) implementation that has well defined interfaces, and provides one or more component networking functions in a defined way. For example, a security VNF provides Network Address Translation (NAT) and firewall component functions.
 
[Cloud-Native Network Functions(CNF)](https://www.cncf.io/announcements/2020/11/18/cloud-native-network-functions-conformance-launched-by-cncf/) is a network function designed and implemented to run inside containers. CNFs inherit all the cloud native architectural and operational principles including Kubernetes(K8s) lifecycle management, agility, resilience, and observability.
 
[Physical Network Function(PNF)](https://www.mpirical.com/glossary/pnf-physical-network-function) is a physical network node which has not undergone virtualization. Both PNFs and VNFs (Virtualized Network Functions) can be used to form an overall Network Service.

[Network functions virtualization infrastructure(NFVI)](https://docs.vmware.com/en/VMware-vCloud-NFV/2.0/vmware-vcloud-nfv-reference-architecture-20/GUID-FBEA6C6B-54D8-4A37-87B1-D825F9E0DBC7.html) is the foundation of the overall NFV architecture. It provides the physical compute, storage, and networking hardware that hosts the VNFs. Each NFVI block can be thought of as an NFVI node and many nodes can be deployed and controlled geographically.


## Containers

[Open Container Initiative](https://opencontainers.org/about/overview/) is an open governance structure for the express purpose of creating open industry standards around container formats and runtimes.

[Kubernetes](https://kubernetes.io/) is an open-source container-orchestration system for automating application deployment, scaling, and management. It was originally designed by Google, and is now maintained by the Cloud Native Computing Foundation.

[Google Kubernetes Engine (GKE)](https://cloud.google.com/kubernetes-engine/) is a managed, production-ready environment for deploying containerized applications.

[OpenShift](https://www.openshift.com/) is focused on security at every level of the container stack and throughout the application lifecycle. It includes long-term, enterprise support from one of the leading Kubernetes contributors and open source software companies.

[Rancher](https://rancher.com/) is a complete software stack for teams adopting containers. It addresses the operational and security challenges of managing multiple Kubernetes clusters, while providing DevOps teams with integrated tools for running containerized workloads.

[Docker](https://www.docker.com/) is a set of platform as a service products that use OS-level virtualization to deliver software in packages called containers. Containers are isolated from one another and bundle their own software, libraries and configuration files; they can communicate with each other through well-defined channels. All containers are run by a single operating-system kernel and are thus more lightweight than virtual machines.

[Rook](https://rook.io/) is an open source cloud-native storage orchestrator for Kubernetes that turns distributed storage systems into self-managing, self-scaling, self-healing storage services. It automates the tasks of a storage administrator: deployment, bootstrapping, configuration, provisioning, scaling, upgrading, migration, disaster recovery, monitoring, and resource management.

[Rkt](https://coreos.com/rkt/) is a pod-native container engine for Linux. It is composable, secure, and built on standards. 

[Open Container Initiative](https://opencontainers.org/about/overview/) is an open governance structure for the express purpose of creating open industry standards around container formats and runtimes.

[Buildah](https://buildah.io/) is a command line tool to build Open Container Initiative (OCI) images. It can be used with Docker, Podman, Kubernetes.

[Podman](https://podman.io/) is a daemonless, open source, Linux native tool designed to make it easy to find, run, build, share and deploy applications using Open Containers Initiative (OCI) Containers and Container Images. Podman provides a command line interface (CLI) familiar to anyone who has used the Docker Container Engine.

[Containerd](https://containerd.io) is a daemon that manages the complete container lifecycle of its host system, from image transfer and storage to container execution and supervision to low-level storage to network attachments and beyond. It is available for Linux and Windows. 

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/113521413-2ffc8c80-954e-11eb-9d19-b9c996bc524b.png">
  <br />
</p>

**Container Architecture. Source: [Containerd.io](https://containerd.io)**

# Networking

[Back to the Top](https://github.com/mikeroyal/ARM-Guide#table-of-contents)

## Networking Learning Resources
  
[AWS Certified Security - Specialty Certification](https://aws.amazon.com/certification/certified-security-specialty/)

[Microsoft Certified: Azure Security Engineer Associate](https://docs.microsoft.com/en-us/learn/certifications/azure-security-engineer)

[Google Cloud Certified Professional Cloud Security Engineer](https://cloud.google.com/certification/cloud-security-engineer)

[Cisco Security Certifications](https://www.cisco.com/c/en/us/training-events/training-certifications/certifications/security.html)

[The Red Hat Certified Specialist in Security: Linux](https://www.redhat.com/en/services/training/ex415-red-hat-certified-specialist-security-linux-exam)

[Linux Professional Institute LPIC-3 Enterprise Security Certification](https://www.lpi.org/our-certifications/lpic-3-303-overview)

[Cybersecurity Training and Courses from IBM Skills](https://www.ibm.com/skills/topics/cybersecurity/)

[Cybersecurity Courses and Certifications by Offensive Security](https://www.offensive-security.com/courses-and-certifications/)  
  
[Citrix Certified Associate – Networking(CCA-N)](http://training.citrix.com/cms/index.php/certification/networking/)

[Citrix Certified Professional – Virtualization(CCP-V)](https://www.globalknowledge.com/us-en/training/certification-prep/brands/citrix/section/virtualization/citrix-certified-professional-virtualization-ccp-v/)

[CCNP Routing and Switching](https://learningnetwork.cisco.com/s/ccnp-enterprise)

[Certified Information Security Manager(CISM)](https://www.isaca.org/credentialing/cism)

[Wireshark Certified Network Analyst (WCNA)](https://www.wiresharktraining.com/certification.html)

[Juniper Networks Certification Program Enterprise (JNCP)](https://www.juniper.net/us/en/training/certification/)

[Networking courses and specializations from Coursera](https://www.coursera.org/browse/information-technology/networking)

[Network & Security Courses from Udemy](https://www.udemy.com/courses/it-and-software/network-and-security/)

[Network & Security Courses from edX](https://www.edx.org/learn/cybersecurity)
  
## Tools & Networking Concepts
  
    • Connection: In networking, a connection refers to pieces of related information that are transferred through a network. This generally infers that a connection is built before the data transfer (by following the procedures laid out in a protocol) and then is deconstructed at the at the end of the data transfer.
    
    • Packet: A packet is, generally speaking, the most basic unit that is transferred over a network. When communicating over a network, packets are the envelopes that carry your data (in pieces) from one end point to the other.
    
Packets have a header portion that contains information about the packet including the source and destination, timestamps, network hops. The main portion of a packet contains the actual data being transferred. It is sometimes called the body or the payload.

    • Network Interface: A network interface can refer to any kind of software interface to networking hardware. For instance, if you have two network cards in your computer, you can control and configure each network interface associated with them individually.
    
A network interface may be associated with a physical device, or it may be a representation of a virtual interface. The "loop-back" device, which is a virtual interface to the local machine, is an example of this.

    • LAN: LAN stands for "local area network". It refers to a network or a portion of a network that is not publicly accessible to the greater internet. A home or office network is an example of a LAN.
    
    • WAN: WAN stands for "wide area network". It means a network that is much more extensive than a LAN. While WAN is the relevant term to use to describe large, dispersed networks in general, it is usually meant to mean the internet, as a whole.
If an interface is connected to the WAN, it is generally assumed that it is reachable through the internet.

    • Protocol: A protocol is a set of rules and standards that basically define a language that devices can use to communicate. There are a great number of protocols in use extensively in networking, and they are often implemented in different layers. 
    
Some low level protocols are TCP, UDP, IP, and ICMP. Some familiar examples of application layer protocols, built on these lower protocols, are HTTP (for accessing web content), SSH, TLS/SSL, and FTP.

    • Port: A port is an address on a single machine that can be tied to a specific piece of software. It is not a physical interface or location, but it allows your server to be able to communicate using more than one application.
    
    • Firewall: A firewall is a program that decides whether traffic coming into a server or going out should be allowed. A firewall usually works by creating rules for which type of traffic is acceptable on which ports. Generally, firewalls block ports that are not used by a specific application on a server.
    
    • NAT: Network address translation is a way to translate requests that are incoming into a routing server to the relevant devices or servers that it knows about in the LAN. This is usually implemented in physical LANs as a way to route requests through one IP address to the necessary backend servers.
    
    • VPN: Virtual private network is a means of connecting separate LANs through the internet, while maintaining privacy. This is used as a means of connecting remote systems as if they were on a local network, often for security reasons.
    
## Network Layers

	While networking is often discussed in terms of topology in a horizontal way, between hosts, its implementation is layered in a vertical fashion throughout a computer or network. This means is that there are multiple technologies and protocols that are built on top of each other in order for communication to function more easily. Each successive, higher layer abstracts the raw data a little bit more, and makes it simpler to use for applications and users. It also allows you to leverage lower layers in new ways without having to invest the time and energy to develop the protocols and applications that handle those types of traffic.
 
	As data is sent out of one machine, it begins at the top of the stack and filters downwards. At the lowest level, actual transmission to another machine takes place. At this point, the data travels back up through the layers of the other computer. Each layer has the ability to add its own "wrapper" around the data that it receives from the adjacent layer, which will help the layers that come after decide what to do with the data when it is passed off.
 
	One method of talking about the different layers of network communication is the OSI model. OSI stands for Open Systems Interconnect.This model defines seven separate layers. The layers in this model are:

    • Application: The application layer is the layer that the users and user-applications most often interact with. Network communication is discussed in terms of availability of resources, partners to communicate with, and data synchronization.
    
    • Presentation: The presentation layer is responsible for mapping resources and creating context. It is used to translate lower level networking data into data that applications expect to see.
    
    • Session: The session layer is a connection handler. It creates, maintains, and destroys connections between nodes in a persistent way.
    
    • Transport: The transport layer is responsible for handing the layers above it a reliable connection. In this context, reliable refers to the ability to verify that a piece of data was received intact at the other end of the connection. This layer can resend information that has been dropped or corrupted and can acknowledge the receipt of data to remote computers.

    • Network: The network layer is used to route data between different nodes on the network. It uses addresses to be able to tell which computer to send information to. This layer can also break apart larger messages into smaller chunks to be reassembled on the opposite end.
    
    • Data Link: This layer is implemented as a method of establishing and maintaining reliable links between different nodes or devices on a network using existing physical connections.
    
    • Physical: The physical layer is responsible for handling the actual physical devices that are used to make a connection. This layer involves the bare software that manages physical connections as well as the hardware itself (like Ethernet).
    
The TCP/IP model, more commonly known as the Internet protocol suite, is another layering model that is simpler and has been widely adopted.It defines the four separate layers, some of which overlap with the OSI model:

    • Application: In this model, the application layer is responsible for creating and transmitting user data between applications. The applications can be on remote systems, and should appear to operate as if locally to the end user. 
The communication takes place between peers network.

    • Transport: The transport layer is responsible for communication between processes. This level of networking utilizes ports to address different services. It can build up unreliable or reliable connections depending on the type of protocol used.
    
    • Internet: The internet layer is used to transport data from node to node in a network. This layer is aware of the endpoints of the connections, but does not worry about the actual connection needed to get from one place to another. IP addresses are defined in this layer as a way of reaching remote systems in an addressable manner.
    
    • Link: The link layer implements the actual topology of the local network that allows the internet layer to present an addressable interface. It establishes connections between neighboring nodes to send data.
    
## Interfaces
Interfaces are networking communication points for your computer. Each interface is associated with a physical or virtual networking device. Typically, your server will have one configurable network interface for each Ethernet or wireless internet card you have. In addition, it will define a virtual network interface called the "loopback" or localhost interface. This is used as an interface to connect applications and processes on a single computer to other applications and processes. You can see this referenced as the "lo" interface in many tools.

## Protocols
Networking works by piggybacks on a number of different protocols on top of each other. In this way, one piece of data can be transmitted using multiple protocols encapsulated within one another.

Media access control is a communications protocol that is used to distinguish specific devices. Each device is supposed to get a unique MAC address during the manufacturing process that differentiates it from every other device on the internet. Addressing hardware by the MAC address allows you to reference a device by a unique value even when the software on top may change the name for that specific device during operation. Media access control is one of the only protocols from the link layer that you are likely to interact with on a regular basis.

The IP protocol is one of the fundamental protocols that allow the internet to work. IP addresses are unique on each network and they allow machines to address each other across a network. It is implemented on the internet layer in the IP/TCP model. Networks can be linked together, but traffic must be routed when crossing network boundaries. This protocol assumes an unreliable network and multiple paths to the same destination that it can dynamically change between. There are a number of different implementations of the protocol. The most common implementation today is IPv4, although IPv6 is growing in popularity as an alternative due to the scarcity of IPv4 addresses available and improvements in the protocols capabilities.

ICMP: internet control message protocol is used to send messages between devices to indicate the availability or error conditions. These packets are used in a variety of network diagnostic tools, such as ping and traceroute. Usually ICMP packets are transmitted when a packet of a different kind meets some kind of a problem. Basically, they are used as a feedback mechanism for network communications.

TCP: Transmission control protocol is implemented in the transport layer of the IP/TCP model and is used to establish reliable connections. TCP is one of the protocols that encapsulates data into packets. It then transfers these to the remote end of the connection using the methods available on the lower layers. On the other end, it can check for errors, request certain pieces to be resent, and reassemble the information into one logical piece to send to the application layer. The protocol builds up a connection prior to data transfer using a system called a three-way handshake. This is a way for the two ends of the communication to acknowledge the request and agree upon a method of ensuring data reliability. After the data has been sent, the connection is torn down using a similar four-way handshake. TCP is the protocol of choice for many of the most popular uses for the internet, including WWW, FTP, SSH, and email. It is safe to say that the internet we know today would not be here without TCP.

UDP: User datagram protocol is a popular companion protocol to TCP and is also implemented in the transport layer. The fundamental difference between UDP and TCP is that UDP offers unreliable data transfer. It does not verify that data has been received on the other end of the connection. This might sound like a bad thing, and for many purposes, it is. However, it is also extremely important for some functions. It’s not required to wait for confirmation that the data was received and forced to resend data, UDP is much faster than TCP. It does not establish a connection with the remote host, it simply fires off the data to that host and doesn't care if it is accepted or not. Since UDP is a simple transaction, it is useful for simple communications like querying for network resources. It also doesn't maintain a state, which makes it great for transmitting data from one machine to many real-time clients. This makes it ideal for VOIP, games, and other applications that cannot afford delays.

HTTP: Hypertext transfer protocol is a protocol defined in the application layer that forms the basis for communication on the web. HTTP defines a number of functions that tell the remote system what you are requesting. For instance, GET, POST, and DELETE all interact with the requested data in a different way.

[JSON Web Token (JWT)](https://jwt.io) is a compact URL-safe means of representing claims to be transferred between two parties. The claims in a JWT are encoded as a JSON object that is digitally signed using JSON Web Signature (JWS).

[OAuth 2.0](https://oauth.net/2/) is an open source authorization framework that enables applications to obtain limited access to user accounts on an HTTP service, such as Amazon, Google, Facebook, Microsoft, Twitter GitHub, and DigitalOcean. It works by delegating user authentication to the service that hosts the user account, and authorizing third-party applications to access the user account.

FTP: File transfer protocol is in the application layer and provides a way of transferring complete files from one host to another. It is inherently insecure, so it is not recommended for any externally facing network unless it is implemented as a public, download-only resource.

DNS: Domain name system is an application layer protocol used to provide a human-friendly naming mechanism for internet resources. It is what ties a domain name to an IP address and allows you to access sites by name in your browser.

SSH: Secure shell is an encrypted protocol implemented in the application layer that can be used to communicate with a remote server in a secure way. Many additional technologies are built around this protocol because of its end-to-end encryption and ubiquity. There are many other protocols that we haven't covered that are equally important. However, this should give you a good overview of some of the fundamental technologies that make the internet and networking possible.

## Virtualization

[KVM (for Kernel-based Virtual Machine)](https://www.linux-kvm.org/page/Main_Page) is a full virtualization solution for Linux on x86 hardware containing virtualization extensions (Intel VT or AMD-V). It consists of a loadable kernel module, kvm.ko, that provides the core virtualization infrastructure and a processor specific module, kvm-intel.ko or kvm-amd.ko.

[QEMU](https://www.qemu.org) is a fast processor emulator using a portable dynamic translator. QEMU emulates a full system, including a processor and various peripherals. It can be used to launch a different Operating System without rebooting the PC or to debug system code.

[Hyper-V](https://docs.microsoft.com/en-us/virtualization/hyper-v-on-windows/) enables running virtualized computer systems on top of a physical host. These virtualized systems can be used and managed just as if they were physical computer systems, however they exist in virtualized and isolated environment. Special software called a hypervisor manages access between the virtual systems and the physical hardware resources. Virtualization enables quick deployment of computer systems, a way to quickly restore systems to a previously known good state, and the ability to migrate systems between physical hosts.

[VirtManager](https://github.com/virt-manager/virt-manager) is a graphical tool for managing virtual machines via libvirt. Most usage is with QEMU/KVM virtual machines, but Xen and libvirt LXC containers are well supported. Common operations for any libvirt driver should work.

[oVirt](https://www.ovirt.org) is an open-source distributed virtualization solution, designed to manage your entire enterprise infrastructure. oVirt uses the trusted KVM hypervisor and is built upon several other community projects, including libvirt, Gluster, PatternFly, and Ansible.Founded by Red Hat as a community project on which Red Hat Enterprise Virtualization is based allowing for centralized management of virtual machines, compute, storage and networking resources, from an easy-to-use web-based front-end with platform independent access.

[Xen](https://github.com/xen-project/xen) is focused on advancing virtualization in a number of different commercial and open source applications, including server virtualization, Infrastructure as a Services (IaaS), desktop virtualization, security applications, embedded and hardware appliances, and automotive/aviation.

[Ganeti](https://github.com/ganeti/ganeti) is a virtual machine cluster management tool built on top of existing virtualization technologies such as Xen or KVM and other open source software. Once installed, the tool assumes management of the virtual instances (Xen DomU).

[Packer](https://www.packer.io/) is an open source tool for creating identical machine images for multiple platforms from a single source configuration. Packer is lightweight, runs on every major operating system, and is highly performant, creating machine images for multiple platforms in parallel. Packer does not replace configuration management like Chef or Puppet. In fact, when building images, Packer is able to use tools like Chef or Puppet to install software onto the image.

[Vagrant](https://www.vagrantup.com/) is a tool for building and managing virtual machine environments in a single workflow. With an easy-to-use workflow and focus on automation, Vagrant lowers development environment setup time, increases production parity, and makes the "works on my machine" excuse a relic of the past. It provides easy to configure, reproducible, and portable work environments built on top of industry-standard technology and controlled by a single consistent workflow to help maximize the productivity and flexibility of you and your team.


## Contribute

- [x] If would you like to contribute to this guide simply make a [Pull Request](https://github.com/mikeroyal/ARM-Guide/pulls).


## License
[Back to the Top](https://github.com/mikeroyal/ARM-Guide/blob/main/README.md#table-of-contents)

Distributed under the [Creative Commons Attribution 4.0 International (CC BY 4.0) Public License](https://creativecommons.org/licenses/by/4.0/).
