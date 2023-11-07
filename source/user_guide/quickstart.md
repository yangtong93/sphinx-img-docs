# Getting Started

This page contains information that you need to get started with BI-Viewer, including how to install and use basic features.

## Operating system requirements

* BI-Viewer mainly runs on the Windows computer and will run on linux computer in the future. Older computers may work.
* Windows 7/10/11 (x64) or above, with all recommended updates installed.  Microsoft does not support Windows 8.1 and Windows 7 anymore and BI-Viewer is not tested on these legacy operating system versions, but may still work.

## Hardware requirements

* Memory: As a general rule, have 2x-5x more memory than the amount of data that you load.

* Display: a minimum resolution of 1024 by 768 (1920 by 1080 or better is recommended). Using a 4K or larger monitor at full resolution will reduce live interaction FPS.

* Graphics: Dedicated graphics hardware (discrete GPU) memory is recommended for fast volume rendering. GPU: Graphics must support minimum OpenGL 3.2. Integrated graphics card is sufficient for basic visualization. Discrete graphics card (such as NVidia GPU) is recommended for interactive 3D volume rendering and fast rendering of complex scenes. GPU texture memory (VRAM) should be larger than your largest dataset (e.g., working with 2GB data, get VRAM > 4GB) and check that your images fit in maximum texture dimensions of your GPU hardware. Except rendering, most calculations are performed on CPU, therefore having a faster GPU will generally not impact the overall speed of the application.

* Some computations are multi-threaded and will benefit from multi core, multi CPU configurations.

* Interface device: a three button mouse with scroll wheel is recommended. Pen, multi-touchscreen, touchpad, and graphic tablet are supported. All OpenVR-compatible virtual reality headsets are supported for virtual reality display.

### Minimum System Requirements (for evaluation with small datasets only)

* CPU: 3 GHz CPU (Intel or AMD) 4 Core with 64 bit support
* RAM: 8 GB
* Graphics: NVIDA Quadro P400

### Recommended System

* CPU: 4 GHz CPU 8-16 Cores or 2GHz CPU 16-32 Cores
* RAM: 32-64 GB
* Graphics: NVIDA Quadro RTX 4000

### High End System

* CPU: 2.4GHz CPU 56 cores
* RAM: 128-256GB
* Graphics: NVIDIA RTX A4000

## Installing BI-Viewer

To download BI-Viewer, click [here](http://www.chipcloudtech.com).

Click on the exe installation package to install

Optionally install the Python module. If no Python module is selected, the functions of the Python-related modules will not be available, and the normal operation of the system will not be affected.

It is recommended not to install it, it will take up much less space and the installation speed will be faster.
## Apply for a license

1. Fill in the **Email** information
2. Click **Generate** Registration Information
3. Click **Request** and contact the account manager to issue license information
4. After receiving the email, click **Request** again to complete license activation

## Using BI-Viewer

BI-Viewer offers lots of features and gives users great flexibility in how to use them. As a result, new users may be overwhelmed with the number of options and have difficulty figuring out how to perform even simple operations. This is normal and many users successfully crossed this difficult stage by investing some time into learning how to use this software.

### Load data

1. Click on **File** -> **Open Data** in the menu bar
2. Select the specified image file, and click OK

### View data

1. Right click on the data node in the **Project View** and select a **Display** module, such as **Volume**.
2. Click **Reset** in the toolbar to center the perspective on the data
3. Adjust the appropriate range of **Colormap**
### Save data

1. Click on **File** -> **Save Data** in the menu bar
2. Enter the name of the file to be saved, and the file saving format
