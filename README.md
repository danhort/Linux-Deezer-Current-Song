# DeezerCurrent BETA
This simple bash script allows you to get the current deezer-song playing.

## Installation
### Requirements
For this to work, you have to have ```wmctrl``` installed. This is needed to find the window title of Deezer. 
You can install wmctrl by using the command ```sudo apt-get install wmctrl``` .

### Running the script
Download the script and give it the appropriate rights to run (you don't need sudo or anything like that).

```
git clone git@github.com:danhort/Linux-Deezer-Current-Song.git

chmod +x deezercurrent

./deezercurrent
```

### Installing the script
You also can install the application by using the install script located in the source folder.
```
chmod a+x install-deezercurrent
sudo ./install-deezercurrent
```
This will copy the deezercurrent file to the /usr/bin directory, so you can run it anytime.

## Usage
### Running the application
By running the ```deezercurrent``` command, you'll see this output: