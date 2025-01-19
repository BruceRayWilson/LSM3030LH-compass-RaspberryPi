# LSM3030LH-compass-RaspberryPi

DF Robot LSM3030LH compass software for Raspberry Pi (Tested on Pi 5)

## Background

Adafruit LSM3030DLH software has been re-purposed to drive the DF Robot LSM3030LH.

## Change

```python
return vector_2_degrees(magnet_x, magnet_y)
```

was changed to:

```python
return vector_2_degrees(magnet_x, magnet_z)
```
