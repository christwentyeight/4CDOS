# 4CDOS

## Description

4CDOS is a command-based program simulating a simple operating system with basic file operations and utilities.
The program includes a boot sequence, user authentication, and various commands to navigate and manipulate the file system.

This github page is the only official place to download this program.

## Features

- Boot sequence with loading bar
- User authentication
- File and folder operations
- Image and video viewing
- Command history and help
- Disk usage information
- Date and time display
- Basic system configuration

## Requirements

- Python 3.x
- Pip
- Pillow Library

## Installation

- Install Python and pip:
```
sudo apt update
sudo apt install python3 python3-pip
```

- Install Pillow Library:
```
pip install pillow
```

- Extract the 4CDOS archive by placing the 4CDOS.tar.gz file where you want to extract it then run:
```
tar -xf 4CDOS.tar.gz
```

- Or Extract the zip file with your GUI

## How To Run

- cd into the directory that contains the 4CDOS.py folder then run:
```
python3 4CDOS.py
```

## Usage

- On first run, the program will prompt you to create a username and password, which will be stored in userdata.txt.
- For subsequent logins, you will be prompted to enter your username and password to access the system.

- Run the command 'help' to see all available commands and their usages.
- Run the command config4cdos to configure the settings.


## License

- This project is open source and available under the MIT License.
