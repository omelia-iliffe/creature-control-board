

I am developing a circuit board for non-organic creatures.


#### Useful links:
Auto-Program circuit - https://arduino.stackexchange.com/questions/38012/major-difference-between-dtr-signal-and-rts-signal


| GPIO Determining the Boot Mode |           |          |               |
|--------------------------------|-----------|----------|---------------|
| Pin                            | Default   | Run Mode | Download Mode |
| IO0                            | Pull-up   | 1        | 0             |
| TXD0                           | Pull-up   | 1        | x             |
| IO2                            | Pull-down | x        | 0             |
| IO5                            | Pull-up   | 1        | x             |
(Table from https://www.sparkfun.com/news/2017)

Breakout Board for LSM6DS3 - https://github.com/sparkfun/LSM6DS3_Breakout
