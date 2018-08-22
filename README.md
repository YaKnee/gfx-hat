# GFX HAT
https://shop.pimoroni.com/products/gfx-hat

Combining a 128x64 pixel monochrome LCD, 6 touch buttons, a 6 zone RGB backlight and 6 button LEDs the GFX HAT has everything you need to turn your Pi into a controller and status display.

## Installing

### Full install (recommended):

We've created an easy installation script that will install all pre-requisites and get your Pan-Tilt HAT
up and running with minimal efforts. To run it, fire up Terminal which you'll find in Menu -> Accessories -> Terminal
on your Raspberry Pi desktop, as illustrated below:

![Finding the terminal](http://get.pimoroni.com/resources/github-repo-terminal.png)

In the new terminal window type the command exactly as it appears below (check for typos) and follow the on-screen instructions:

```bash
curl https://get.pimoroni.com/gfxhat | bash
```

If you choose to download examples you'll find them in `/home/pi/Pimoroni/gfxhat/`.

### Manual install:

#### Library install for Python 3:

```bash
sudo pip3 install gfxhat
```

#### Library install for Python 2:

```bash
sudo pip2 install gfxhat
```

### Development:

If you want to contribute, or like living on the edge of your seat by having the latest code, you should clone this repository, `cd` to the library directory, and run:

```bash
sudo python3 setup.py install
```
(or `sudo python setup.py install` whichever your primary Python environment may be)

In all cases you will have to enable the i2c and spi buses.

## Documentation & Support

* Guides and tutorials - https://learn.pimoroni.com/gfx-hat
* Function reference - http://docs.pimoroni.com/gfxhat/
* GPIO Pinout - https://pinout.xyz/pinout/gfx_hat
* Get help - http://forums.pimoroni.com/c/support
