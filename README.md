# Ride_Experience App
Ride Experience is the ultimate coaster enthusiast app that features data logging from the iPhone's on-board sensors to preview force and position data during a roller coaster ride. Access to live wait times at popular theme parks and collect user stats such as the number of different roller coasters ridden.

## Data Logging
The app is able to access a variety of sensors using CoreMotion and CoreLocation APIs incuding: 
- Acceleratometer (Calibrated & Raw)
- Gyroscope (Rotation Rate & Attitude)
- Barometer (Relative and Absolute Altitude)
- GPS Location (Coordinates & Speed)
- Magnetometer (Heading)

![Data Logging](rideXP_previews1/Slide1.jpeg?raw=true "Data Logging")

### Data Analysis 
Features interactive 2D and 3D graphs to preview data. 3D Graphs implement Shant Tokatyan's [3D graph view]( https://github.com/stokatyan/Plot3D) to view relative position and gps data. Further data smoothing will be achieved used SLAM related algorithms such as the Extended Kalman Filter to improve accuracy. 

![Analysis](rideXP_previews1/Slide3.jpeg?raw=true "Data Analysis")

#### Data Import
All sensor data can be imported via CSV files using various header templates from existing Sensor loggers.

##### Live Queue Times
Using [QueueTimes.com](https://queue-times.com/pages/api) the app can fetch live wait times from 124 different parks globally.

![Alt text](rideXP_previews1/Slide2.jpeg?raw=true "Live Theme Park Queue Times")

###### Track "Coaster Credits" Stats
Uses will be able to track and share the number of different roller coasters they have ridden.


