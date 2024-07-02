

1. Enable command and data ports on Linux:
```
sudo chmod 666 /dev/ttyACM0
sudo chmod 666 /dev/ttyACM1
```
Note: If multiple sensors are used, enable additional ports `/dev/ttyACM2` and `/dev/ttyACM3`, etc. the same as this step.

2. Launch AWR1843 short range config:
```
roslaunch ti_mmwave_rospkg multi_1843es0_short_range.launch
```
