

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
https://learn.sparkfun.com/tutorials/lsm6ds3-breakout-hookup-guide

Breakout Board for TPA2005D1 - https://github.com/sparkfun/Mono_Audio_Amp_Breakout-TPA2005D1
http://cdn.sparkfun.com/datasheets/BreakoutBoards/Mono%20Audio%20Amp%20TPA2005D1%20v10.pdf
