# ProMini LoRaWAN Node
A LoRaWAN node based on the Arduino ProMini and the RFM95 LoRa module. Based on the original design by [Doug Larue](https://github.com/dlarue/KiCAD/tree/master/ProMini-LoRaWAN-node), but with some additional options:

* u.FL antenna connector
* Grove connector for I2C (can also be used for analog or digital signals)
* Circuitry to measure battery voltage

![3D rendered PCB](./images/pcb01.jpg)

## Parts
* Arduino Pro Mini 3.3V, 8 Mhz
* RFM95 module (frequency band based on your location)
* Pin headers
* Edge-mounted SMA connector (e.g. [this part](https://www.digikey.com/product-detail/en/rf-solutions/CON-SMA-EDGE-S/CON-SMA-EDGE-S-ND/5845767)) or wire-antenna of correct length

## Additional information
* Board can be powered directly from 2 AA batteries to the 3.3V input
* [Full tutorial using this board by Frank Beks](https://www.thethingsnetwork.org/labs/story/creating-a-ttn-node)

## License
* Licensed under Creative Commons Attribution-ShareAlike 4.0 Unported License (CC BY-SA 4.0)
* Original work by [Doug Larue](https://github.com/dlarue)
* Modifications by [Severin Schols](https://github.com/tiefpunkt)
