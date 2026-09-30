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
| 7 | SMA antenna | 2.4 / 5 / 6 GHz antenna for the MT7916 board | 3 | [Farnell](https://www.newark.com/siretta/delta47-smam-36/rf-antenna-600mhz-5-6ghz/dp/97AK2184) |
| 8 | SMA antenna (HaLow) | 868 MHz SMA antenna for the Lunpid MM8108 HaLow board | 1 | [Hexaspot 868MHz gooseneck antenna](https://hexaspot.com/products/hexaspot-tactical-gooseneck-antenna-868mhz?variant=57776200810827) |
| 9 | SMA cable, 2.4/5GHz | IPEX MHF 1 - SMA female cable assembly for MT7916 board | 3 | [TME](https://www.tme.eu/en/details/ipex-sma-150/coaxial-assemblies/onteck)
| 10 | SMA cable, sub 1GHz | Ccable for SMA male to SMA female adapter for the MM8108 HaLow board antenna | 1 | [AliExpress](https://www.aliexpress.com/item/1005003433705318.html) |

## Connectors and Cables

| # | Name | Description | Amount | Link |
|---|---|---|---|---|
| 11 | Waterproof USB-C connector | Panel-mount waterproof USB-C, wired to the carrier board | 1 | [AliExpress](https://www.aliexpress.com/item/1005006218980573.html) |
| 12 | USB-C cable & connector (Pololu → carrier) | Cable with USB-C plug carrying 5 V from the Pololu board to the carrier board | 1 | [AliExpress](https://www.aliexpress.com/item/1005011867528852.html?algo_exp_id=3512d09b-6d92-47c5-8030-31c9b93164dd-17&pdp_ext_f=%7B%22order%22%3A%22944%22%2C%22eval%22%3A%221%22%2C%22orig_sl_item_id%22%3A%221005011867528852%22%2C%22orig_item_id%22%3A%221005011531079663%22%2C%22fromPage%22%3A%22search%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005011867528852%7C_p_origin_prod%3A1005011531079663) |
| 13 | Pololu → pogo-pin cable | Cable from the Pololu input to a 3-pin magnetic pogo-pin connector | 1 | [AliExpress](N/A) |
| 14 | Magnetic Pogo 3 Pin connector | Panel-mount circular 12mm connector, wired to the #11 cable. Connects to the off-set connector on the battery enclosure. | 1 | [AliExpress](https://www.aliexpress.com/item/1005008792560196.html#nav-specification)
| 15 | USB-C snap connector UC1 | Snap USB-C connector, Lunpid MM8108 HaLow board | 1 | [AliExpress](https://www.aliexpress.com/item/1005008383845058.html) |
| 15 | Ribbon cable for USB-C snap connector | Short cable, carrier board to Lunpid MM8108 HaLow USB-C snap connector | 1 | [AliExpress](https://www.aliexpress.com/item/1005008383845058.html) |
| 16 | M12 connector | Panel-mount M12 connector for Ethernet. Pick Male Back M12-P-GCFM-16-NZG 8Pin variant. | 1 | [AliExpress](https://www.aliexpress.com/item/1005012293627764.html) |
| 17 | Flat Ethernet connector | Internal connector, M12 connector to carrier RJ45 port | 1 | [AliExpress](https://www.aliexpress.com/item/1005005257546532.html?algo_exp_id=6e2c1bfa-acc1-43cb-8c84-af66e6a55b85-0&pdp_ext_f=%7B%22order%22%3A%22153%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005005257546532%7C_p_origin_prod%3A) |

## Hardware

| # | Name | Description | Amount | Link |
|---|---|---|---|---|
| 18 | Heatsink for MT7916 | Wakefield 559-50AB-ND heatsink | 1 | [Wakefield 559-50AB](https://www.digikey.com/en/products/detail/wakefield-thermal-solutions/559-50ab/5068188) |
| 19 | M2.5 screws | Hex M2.5x7mm | 4 | N/A |
| 20 | M3 screws, back plate| Hex, M3x6mm | 6 | N/A |
| 21 | M3 screws, front plate | Hex, M3x8mm | 6 | N/A |
| 22 | M3 screws, top I/O plate | Hex, M3x12mm | 4 | N/A
| 23 | M3 nuts | Standard Hex, mounting the grounding bar | 2 | N/A |
| 24 | M2.5 heat-set inserts | M2.5\*4\*3.5mm Heat-set inserts for mounting the CM4 carrier board | 4 | N/A |
| 25 | M3 heat-set inserts | M3\*4\*4mm Heat-set inserts for mounting the front, back and top plates to the enclosure | 16 | N/A |

## Misc
| # | Name | Description | Amount | Link |
|---|---|---|---|---|
| 26 | Diamant Dichtol AM Hydro | Polimer sealant for additive manufacturing | 1 | [Diamant Dichtol AM Hydro](https://diamant-polymer.de/en/industry/3d-printing-additive-manufacturing/impregnating-and-sealing/make-3d-print-waterproof) |
| 27 | Grounding bar and wings assembly | Mesh node side of the twist-lock assembly | 1(each) | * - Check [Notes](#notes)

## Notes

- Quantities are for **one** unit.
- Confirm antenna connector gender (SMA vs RP-SMA) matches your bulkheads before ordering.
- If purchasing a different buck board model, check the input voltage range against your power source.
- SupplyNet provides both the wings and grounding bar for sale. If sourcing isn't available, models for both components can be found [here( 1x GND bar )](https://www.thesupplynet.com/Attachment/DownloadFile?downloadId=779) and [here( left and right wings, one of each )](https://www.thesupplynet.com/Attachment/DownloadFile?downloadId=83) for FDM printing or CNC machining.
