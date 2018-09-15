# DeezerCurrent BETA
This simple linux bash script allows you to get the current playing song on deezer.

[Deezer](https://www.deezer.com) is an Internet-based music streaming service.

## Installation
### Requirements
For this to work, you have to have ```wmctrl``` installed. This is needed to find the window title of Deezer.
You can install wmctrl by using the command ```sudo apt-get install wmctrl``` .

### Running the script
```
git clone git@github.com:danhort/Linux-Deezer-Current-Song.git
./deezercurrent
```

### Installing the script
You also can install the application by using the install script located in the source folder.
```
sudo ./install-deezercurrent
```
This will copy the deezercurrent file to the /usr/bin directory, so you can run it anytime.

### Uninstall the script
```
sudo ./uninstall-deezercurrent
```

## Usage
### Running the application
```deezercurrent```
