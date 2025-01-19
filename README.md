# LSM303DLH-compass-RaspberryPi

DF Robot LSM303DLH compass software for Raspberry Pi (Tested on Pi 5)

## Background

Adafruit LSM303DLH software has been re-purposed to drive the DF Robot LSM303DLH.

## Change

```python
return vector_2_degrees(magnet_x, magnet_y)
```

was changed to:

```python
return vector_2_degrees(magnet_x, magnet_z)
```
