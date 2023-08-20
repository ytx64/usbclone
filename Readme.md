# USB Clone Tool

The USB Clone Tool is a command-line utility for cloning files from a connected USB device to a specified destination folder. This tool supports both Windows and Linux platforms.

## Prerequisites

- Go to the [Releases](https://github.com/yourusername/usbclone/releases) page to download the latest release for your operating system.

## Usage

Make sure you have the required source and destination paths ready before using the USB Clone Tool.

```sh
./usbclone -source='/path/to/source' -destination='/path/to/destination'
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

### License
This project is licensed under the MIT License.

### Support
For questions, issues, or feedback, please create an issue in this repository.
