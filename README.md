# UWP Image Detection sample

This is a Windows UWP application that uses a pre-trained machine learning model, generated using the [Custom Vision](https://www.customvision.ai/) service on Azure, to detect if the given image contains a specific object: a plane.

It leverages the UWP APIs included in the **Windows.AI.MachineLearning** namespace.

## Prerequisites

- [Visual Studio 2017 Version 15.7.4 or Newer](https://developer.microsoft.com/en-us/windows/downloads)
- [Windows 10 - Build 17763 or higher](https://www.microsoft.com/en-us/software-download/windowsinsiderpreviewiso)
- [Windows SDK - Build 17763 or higher](https://www.microsoft.com/en-us/software-download/windowsinsiderpreviewSDK)

## Build the sample

1. If you download the samples ZIP, be sure to unzip the entire archive, not just the folder with the sample you want to build.
2. Start Microsoft Visual Studio 2017 and select **File > Open > Project/Solution**.
3. Starting in the folder where you unzipped the samples, go to the **UWPImageDetection** subfolder. Double-click the Visual Studio solution file (.sln).
4. Confirm that the project is pointed to the correct SDK that you installed (e.g. 17763). You can do this by right-clicking the project in the **Solution Explorer**, selecting **Properties**, and modifying the **Windows SDK Version**.
5. Confirm that you are set for the right configuration and platform (for example: Debug, x64).
6. Build the solution (**Ctrl+Shift+B**).

## Run the sample

Right click on **UWPImageDetection** project in Visual Studio and choose **Set as StartUp Project**. Then press F5 to deploy the application on your machine and launch the debugging experience.







Ref: https://github.com/Microsoft/Windows-AppConsult-Samples-UWP

