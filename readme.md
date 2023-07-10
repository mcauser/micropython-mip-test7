# MicroPython MIP test 7

One in a series of example repos to test various mpremote mip installation patterns.

#### Install I2C version

```
$ mpremote mip install github:mcauser/micropython-mip-test7/i2c

Install github:mcauser/micropython-mip-test7/i2c
Installing github:mcauser/micropython-mip-test7/i2c/package.json to /lib
Installing: /lib/test7_i2c/__init__.py
Done
```

GitHub               | Device
:--------------------|:------------------------------
/i2c/\_\_init\_\_.py | /lib/test7_i2c/\_\_init\_\_.py

```
$ mpremote repl

>>> import test7_i2c
test7 i2c
```

#### Install SPI version

```
$ mpremote mip install github:mcauser/micropython-mip-test7/spi

Install github:mcauser/micropython-mip-test7/spi
Installing github:mcauser/micropython-mip-test7/spi/package.json to /lib
Installing: /lib/test7_spi/__init__.py
Done
```

GitHub      | Device
:-----------|:------------------------------
/spi/spi.py | /lib/test7_spi/\_\_init\_\_.py

```
$ mpremote repl

>>> import test7_spi
test7 spi
```
