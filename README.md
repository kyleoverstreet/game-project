# Dodge 3D
![Main Menu](images/menu.png "Main Menu")

Dodge 3D is a game in which the main objective is to collect as many coins as possible while avoiding death by dodging harmful items (spikes and bombs). Other items include hearts which replenish 25% of the player's health and stars which give the player invincibility for three seconds.

## Getting Started
The game can be downloaded using the following command:

```
git clone https://github.com/kyleoverstreet/dodge-3d
```

## Prerequisites
OpenGL, OpenAL, and Xlib must be installed to run Dodge 3D.

Users on Linux machines can try install the necessary libraries using the following commands:

```
sudo apt install libalut-dev
sudo apt-get install libx11-dev
sudo apt-get install libglu1-mesa-dev
```

## Deployment
The game can be compiled using the ```make``` command which will create an executable file.


## Built With
* C++
* [OpenGL](https://www.opengl.org/) (graphics)
* [OpenAL](https://www.openal.org/) (sounds)
