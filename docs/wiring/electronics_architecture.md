# Electronics Architecture

## Raspberry Pi
Responsibilities:
- SLAM
- Navigation
- Mapping
- ROS2

## ESP32
Responsibilities:
- Motor PWM
- Encoder reading
- Sensor polling
- Safety systems

## Communication
- UART serial between Pi and ESP32

## Sensors
- LiDAR -> Raspberry Pi
- Ultrasonic -> ESP32
- IMU -> ESP32

## Power
- Separate rails for:
  - motors
  - logic
  - vacuum motor