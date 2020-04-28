# Four Letter pHAT
https://shop.pimoroni.com/products/four-letter-phat

Four Letter pHAT has one simple purpose: to let you display four letter words! It will also let you display numbers, characters, etc.

Modified to work on the [Pi-puck robot platform](https://github.com/yorkrobotlab/pi-puck), using the [YRL Expansion Board](https://github.com/yorkrobotlab/pi-puck-expansion-board).

Hardware modification is also required to make the pHAT work on the Pi-puck, to change the I2C address of the controller to 0x71.

This can be achieved by soldering a diode and 39kΩ resistor between AD (2) and A0 (23) pins of the controller chip. See the HT16K33 datasheet for more information.

## Installing

Clone this repository, `cd` to the library directory, and run:

```bash
sudo python3 setup.py install
```
(or `sudo python setup.py install` whichever your primary Python environment may be)

In all cases you will have to enable the i2c bus.

## Documentation & Support

* Guides and tutorials - https://learn.pimoroni.com/four-letter-phat
* Function reference - http://docs.pimoroni.com/fourletterphat/
* GPIO Pinout - https://pinout.xyz/pinout/four_letter_phat
* Get help - http://forums.pimoroni.com/c/support
