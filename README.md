# Team cyborg++ [rc2017]
Our robocup 2017 code from team cyborg++

The sensors are connected like this:
```
NXT Brick
├── S1 (Outer Left HT Color Sensor)
├── S2 (Touch Splitter)
│   ├── 1 (Left Bumper)
│   ├── 2 (Center Bumper)
│   └── 3 (Right Bumper)
├── S3 (i2c Splitter)
│   ├── EV3 Splitter
│   │   ├── C1 (Outer Right EV3 Color Sensor)
│   │   ├── C2 (Left EV3 Color Sensor)
│   │   └── C3 (Right EV3 Color Sensor)
│   └── IR Dist Sensor
└── S4 (US Sensor)
```
