# docker-robot-remote
Docker Container to visualize data and control robot remotely

Provides to Docker images to control your ROS 2 robot using 
 - Keyboard
 - UI (rqt-robot-steering)
 - (Gamepad) PlayStation 4 DualShock controller (just references https://github.com/brean/docker-ros2-ds4-controller)

# Running
## Teleop:
Run `docker compose run -it --rm teleop`

## QT UI
Run `docker compose run -it --rm ui`

## Playstation 4 DualShock controller
Connect the controller via Bluetooth or USB and run 
`docker compose run -it --rm teleop`