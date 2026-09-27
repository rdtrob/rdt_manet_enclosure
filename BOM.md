# Bill of Materials

Parts required to build one radio node. Printed parts are listed in the [README](README.md#repository-structure).

Links are provided for reference only; equivalent parts from other suppliers should work unless noted.

## Electronics

| # | Name | Description | Amount | Link |
|---|---|---|---|---|
| 1 | Raspberry Pi Compute Module 4 | CM4004032: 4 GB RAM, 32 GB eMMC, no onboard Wi-Fi/BT | 1 | [PiShop](https://www.pishop.us/product/raspberry-pi-compute-module-4-4gb-32gb-cm4004032/) |
| 2 | CM4 carrier board | Waveshare Mini Base Board (A) (CM4-IO-BASE-A) | 1 | [Eckstein](https://eckstein-shop.de/WaveShareMiniBaseBoardADesignedforRaspberryPiComputeModule4) |
| 3 | MT7916 Wi-Fi 6E board | AsiaRF AW7916-AED, M.2 A/E-key, MediaTek MT7916AN | 1 | [AsiaRF](https://asiarf.com/product/wi-fi-6e-m-2-ae-key-module-mt7916-aw7916-aed/) |
| 4 | M.2 A/E-key adapter | M.2 M-key to M.2 A/E-key adapter for the Wi-Fi board | 1 | [AliExpress](https://www.aliexpress.com/item/4000175123887.html) |
| 5 | MM8108 HaLow board | Morse Micro MM8108 Wi-Fi HaLow (802.11ah) board | 1 | [Shopify Lunpid](https://lunpid.com/products/usb-mm8108-halow) |
| 6 | Pololu buck converter | Pololu D36V28F5, 5 V 3.2 A step-down regulator | 1 | [Pololu](https://www.pololu.com/product/3782) |

## Antennas and RF

| # | Name | Description | Amount | Link |
|---|---|---|---|---|
| 7 | SMA antenna | 2.4 / 5 / 6 GHz antenna for the MT7916 board | 3 | TODO |
| 8 | SMA adapter (HaLow) | SMA adapter for the MM8108 HaLow board antenna port | 1 | TODO |

## Connectors and Cables

| # | Name | Description | Amount | Link |
|---|---|---|---|---|
| 9 | Waterproof USB-C connector | Panel-mount waterproof USB-C, wired to the carrier board | 1 | [AliExpress](https://www.aliexpress.com/item/1005006218980573.html) |
| 10 | USB-C cable & connector (Pololu → carrier) | Cable with USB-C plug carrying 5 V from the Pololu board to the carrier | 1 | [AliExpress](https://) |
| 11 | Pololu → pogo-pin cable | Cable from the Pololu input to a 3-pin magnetic pogo-pin connector | 1 | [AliExpress](https://) |
| 12 | Magnetic Pogo 3 Pin connector | Panel-mount circular 12mm connector, wired to the #11 cable. Connects to the off-set connector on the battery enclosure. | 1 | [AliExpress](https://www.aliexpress.com/item/1005008792560196.html#nav-specification)
| 13 | USB-C to USB-C cable | Short cable, carrier board to MM8108 HaLow board | 1 | [AliExpress](https://) |
| 14 | M12 connector | Panel-mount M12 connector for Ethernet. Pick Male Back M12-P-GCFM-16-NZG 8Pin variant. | 1 | [AliExpress](https://www.aliexpress.com/item/1005012293627764.html) |
| 15 | M12 to Ethernet cable | Internal cable, M12 connector to carrier RJ45 port | 1 | [AliExpress](https://) |

## Hardware

| # | Name | Description | Amount | Link |
|---|---|---|---|---|
| 16 | M2.5 screws | TODO: length and head type | 4 | TODO |
| 17 | M3 screws | TODO: length and head type | 16 | TODO |
| 18 | M3 nuts | TODO: standard hex or nyloc | 2 | TODO |
| 19 | M2.5 heat-set inserts | TODO: | 4 | TODO |
| 20 | M3 heat-set inserts | TODO: | 16 | TODO |

## Notes

- Quantities are for **one** unit.
- Confirm antenna connector gender (SMA vs RP-SMA) matches your bulkheads before ordering.
- If purchasing different buck board, check the input voltage range against your power source.
