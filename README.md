This directory is symlinked in to /etc/init.d (via /opt/lcd), and called in various runlevels.

Run `/etc/init.d/lcd-screen {start|stop}` to interact with it.

## Troubleshooting

* If the LCD screen is "dead", try checking that [I2C is enabled](https://learn.adafruit.com/adafruits-raspberry-pi-lesson-4-gpio-setup/configuring-i2c)

