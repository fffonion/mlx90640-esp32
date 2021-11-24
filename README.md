```
git clone https://github.com/stickbreaker/arduino-esp32
cp -r arduino-esp32/libraries/Wire/ $HOME/.platformio/packages/framework-arduinoespressif32/libraries/
cp -r arduino-esp32/cores/esp32/esp32-hal-i2c.* $HOME/.platformio/packages/framework-arduinoespressif32/cores/esp32/
```

edit `User_Setup_Select.h` inside `.pio/libdep/<env>/TFT_eSPI`
