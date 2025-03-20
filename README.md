# docker-robot-remote
Docker Container to visualize data and control robot remotely

Provides to Docker images to control your ROS 2 robot using 
 - Keyboard
 - UI (rqt-robot-steering)
 - (Gamepad) PlayStation 4 DualShock controller (just references https://github.com/brean/docker-ros2-ds4-controller)

# Running
## Teleop:
Run `docker compose run -it --rm teleop`

## Playstation 4 DualShock controller
Connect the controller via Bluetooth or USB and run 
`docker compose run -it --rm teleop`

(its just pulling/starting the [ROS2 DS4-Controller Docker image](https://github.com/brean/docker-ros2-ds4-controller))

## QT UI
You might need to add xhost control for example: `xhost +local:docker`
Run `docker compose run -it --rm ui`

## QT UI
You might need to add xhost control for example: `xhost +local:docker`
Run `docker compose run -it --rm rviz`