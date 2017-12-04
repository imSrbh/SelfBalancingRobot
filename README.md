# SelfBalancingRobot
About  self-balancing, inverted pendulum robot,The build is straightforward and the software is free and open source, based on the Arduino.
The heart of a self-balancing bot is the IMU, consisting of 3-axis rate gyros, accelerometers. These 6 sensors are sampled up to 1,000 times per second and integrated with a piece of code called the DCM (direction-cosine-matrix algorithm), a mathematical filter that combines the best attributes of each sensor. The robot’s higher-level code can simply ask the DCM the angle and the rate of rotation of the bot as needed for balancing.
