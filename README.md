# SenseBox-Shield
The senseBox-Shield is a plug-on module for Arduino to connect different sensor modules.

Infos about the senseBox: http://www.sensebox.de and https://github.com/sensebox


## Shop
* [senseBox Kits](http://www.watterott.com/en/Sensors/senseBox)


## Hardware and Software
* [Schematics + Layout](https://github.com/watterott/SenseBox-Shield/tree/master/hardware)
* [Arduino Examples](https://github.com/sensebox)

### Connector Pinout

#### I2C/Wire
Pin | Function
----|---------
1   | GND (Ground)
2   | VCC (Power)
3   | SDA (Data)
4   | SCL (Clock)

#### UART/Serial
Pin | Function
----|---------
1   | GND (Ground)
2   | VCC (Power)
3   | Rx  (Receive from host)
4   | Tx  (Transmit from host)

#### SPI
Pin | Function
----|---------
1   | GND  (Ground)
2   | VCC  (Power)
3   | MISO (Master In)
4   | MOSI (Master Out)
5   | SCK  (Clock)
6   | CS   (Chip Select)
