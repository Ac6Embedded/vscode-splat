# Splat

![Step](https://raw.githubusercontent.com/Ac6Embedded/vscode-splat/refs/heads/main/images/Overview.png)

## What is Splat?

Splat, developed by AC6, is an innovative hardware simulation tool based on Renode. Integrated directly into Visual Studio Code.

With Splat, you can accelerate the development, testing, debugging, and simulation of your IoT software without having to modify existing code. This makes the process not only faster but also more economical and reliable, perfect for optimizing your IoT projects.

## Features

- **Integrated Development**: Seamlessly integrates with Visual Studio Code to provide a unified development environment for hardware simulation.
- **Hardware Simulation**: Allows for accurate simulation of various IoT hardware platforms without needing physical devices.
- **Debugging and Testing**: Provides robust tools for debugging and testing your software directly within the simulation environment.
- **Fast Setup**: Accelerates the setup process with minimal configuration, making it easier to start working on your IoT projects quickly.
- **Cost-Effective**: Reduces the need for physical hardware, saving costs and streamlining the development workflow.
- **Reliable Performance**: Ensures reliable performance and accurate simulation results to improve your software’s quality.

## Usage

1. Open the Splat extension view by clicking on the Splat icon.
2. Install Splat's dependencies by clicking on the "install button".
3. Open the Splat configuration menu.

    ![Step](https://raw.githubusercontent.com/Ac6Embedded/vscode-splat/refs/heads/main/images/UsageStep.png)

## Splat Configuration

To start using the tool, simply click on the Project field to view the list of available projects in the workspace. Once the project is selected, the tool will automatically find the executable file, without any further input required.

Port and simulator configurations are mainly useful for advanced cases, such as when you want to run multiple debug instances in parallel.

Before configuring Splat, ensure you have a compiled project for the board you intend to simulate. Additionally, if you plan to debug, make sure you have the appropriate toolchain installed, such as arm-none-eabi-gdb.

![Step](https://raw.githubusercontent.com/Ac6Embedded/vscode-splat/refs/heads/main/images/SplatConfiguration.png)

## Run and Debug

Once you have finished configuring Splat, you can run a debug or run command to automatically apply the changes and launch the simulation.

## Supported Board

- STM32F4-DISCOVERY  
- SiFive_HiFive1  
- STM32B-L475E-IOT01A  
- STM32F4_Discovery  
- STM32F746G_DISCO  
- STM32L562E-DK  
- STM32NUCLEO_WBA55CG
