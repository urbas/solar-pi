# Solar Pi

An off-grid, modular, solar-powered, battery-buffered, computing, data storage, and communications kit.


## Total cost of ownership


### Fixed costs

_Base Kit_ material costs:

- Solar panels: £20 ([KINGSOLAR 14W Foldable Solar Panel](https://www.amazon.co.uk/KINGSOLAR-Foldable-Certification-Intelligent-Stabilization/dp/B01A6X4MJA/ref=sr_1_1?ie=UTF8&qid=1489841488&sr=8-1&keywords=kingsolar+14w))
- Battery: £15 ([Poweradd Pilot X7 20000mAh](https://www.amazon.co.uk/Poweradd-Pilot-X7-Universal-Red-Black/dp/B00XVTJKCQ/ref=sr_1_2?ie=UTF8&qid=1489841563&sr=8-2&keywords=poweradd+portable+charger))
- Compute module: £5 ([Raspberry Pi Zero W](https://thepihut.com/products/raspberry-pi-zero?variant=14062715972))
- USB cables: £4.2 (3/5 of [Micro USB Cable, RAVPower 5-Pack](https://www.amazon.co.uk/gp/product/B00YAF14QK/ref=oh_aui_detailpage_o01_s00?ie=UTF8&psc=1))
- GSM Module: £7.9 ([SIM800L GPRS GSM Module Micro SIM Card Core Board Quad-Band TTL Serial Port](http://www.ebay.co.uk/itm/162017759834?_trksid=p2060353.m2749.l2649&ssPageName=STRK%3AMEBIDX%3AIT))
- SD Card: £7 ([SanDisk Ultra 16 GB microSDHC Class 10 Memory Card](https://www.amazon.co.uk/d/Memory-Cards/SanDisk-Ultra-16-GB-microSDHC-Class-Mbps/B010NE3U2M/ref=sr_1_4?s=electronics-accessories&rps=1&ie=UTF8&qid=1489843042&sr=1-4&keywords=micro+sd+card))
- Buck converter: £2 ([LM2596 on eBay](http://www.ebay.co.uk/itm/162289623433))
- Boxing: £? (TODO)

_Base Kit_ total fixed cost: £61.1 + £?


### Variable costs

TODO


## Assembly instructions

1. Buy the _Base Kit_.


## GSM Module Notes

### Assembly

Pin connectors: [./images/sim800l-pinout.jpg](./images/sim800l-pinout.jpg)

### Commands

Connect to the GSM module via this command:

```
sudo minicom -b 9600 -D /dev/ttyS0
```


# Links

[Solar Power for the ESP8266, Arduino, etc.](https://www.youtube.com/watch?v=WdP4nVQX-j0) by Andreas Spiess _[YouTube video]_: Andreas calculates the required solar panel size and battery size given that he wanted to power his device throughout the year assuming some circumstances.
