# USB Clone Tool

The USB Clone Tool employs an efficient file copying process that selectively transfers image and video files (JPG, JPEG, PNG, GIF, BMP, MP4, MOV, AVI, MKV) from the connected device. By targeting only relevant files, this process ensures a faster transfer compared to traditional methods, saving you time and resources.

## Features
- Looks for any device/folder in "-source" and then creates a programming-friendly (name without spaces or special characters) folder name in "-destination" and places all video/images there.
- Can be used in combination with crontab, as a service, or your preferred method.
- Excludes any folders that do NOT contain a video or image of any type.
- Keeps the folder structure.
- Selectively transfer.

## Prerequisites
- Go to the [Releases](https://github.com/ytx64/usbclone/releases) page to download the latest release for your operating system.

## Usage
Make sure you have the required source and destination paths ready before using the USB Clone Tool.

### Linux:
```
./usbclone -source='/path/to/source' -destination='/path/to/destination'
```
### Windows
```
.\usbclone -source='\path\to\source' -destination='\path\to\destination'
```
Replace /path/to/source with the full path of the directory where the device will show up, and /path/to/destination with the full path of the directory where you want to save the data.

You can also use the -h flag to display the usage information:
```
user@user:~/usbClone./usbclone -h
Usage of ./usbclone:
  -destination string
        Destination folder to clone stuff too. (default "NONE")
  -source string
        Source folder where the device will connect. (default "NONE")
```

## Additional Highlights
### 1. Efficiency
The USB Clone Tool optimizes file copying by excluding folders that don't contain video or image files, ensuring only relevant content is transferred.

### 2. Minimalist Configuration
Simply provide the source and destination paths—no complex settings required.

### 3. User Flexibility
Integrate the tool into your preferred workflow using crontab, services, or other methods.

### 4. Cross-Platform Compatibility
The tool works seamlessly on both Linux and Windows systems, accommodating a wide range of users.

### 5. Preserve Folder Structure
The USB Clone Tool maintains the original folder structure during transfers, keeping your data organized.

### 6. Fast and Selective Transfer
Selective transfer accelerates copying of video and image files, making it quicker than traditional methods.

### 7. Customizable Inclusions/Exclusions
Configure the tool to include or exclude specific file types during transfers.

### 8. Stress-Free Installation
Quickly download, install, and start using the USB Clone Tool.

### 9. Acknowledgments
If you've utilized third-party libraries or resources, find an acknowledgments section to give proper credit.

### License
Executable Download License

This license allows you to download and use the provided executable file ("usbclone") for your personal or business purposes. You are not granted any rights to access, modify, distribute, or sublicense the source code of the Software.

All rights to the Software, including the source code, are reserved by the author. No warranty or support is provided for the Software.

By downloading and using the Software, you agree to abide by the terms of this license.

© [TNV], [2023]

Support
For questions, issues, or feedback, please create an issue in this repository.
