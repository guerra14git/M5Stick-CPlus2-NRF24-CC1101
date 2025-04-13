# M5Stick-CPlus2-NRF24-CC1101
This project integrates the M5Stick-C Plus2(esp32) with NRF24L01 or CC1101 transceivers:

    NRF24L01: 2.4GHz short-range, low-power RF module (SPI)

    CC1101: Sub-GHz (433/868/915 MHz) long-range transceiver (SPI)

Useful for prototyping IoT nodes, gateways, or multi-protocol communication systems.

    Dual SPI radio support on ESP32

    Wi-Fi + BLE + 2x RF links

    Ideal for sensor networks, RF bridging, remote control systems

# Modules needed:
'''
M5Stick CPlus 2 - [m5stack](https://shop.m5stack.com/products/m5stickc-plus2-esp32-mini-iot-development-kit)
BreadBoard/ProtoBoard - [aliexpress](https://de.aliexpress.com/item/1005003126962531.html?spm=a2g0o.productlist.main.69.7d67TIBVTIBVOY&algo_pvid=6ba7db82-8941-4d51-87b3-1abd87f3268a&algo_exp_id=6ba7db82-8941-4d51-87b3-1abd87f3268a-34&pdp_ext_f=%7B%22order%22%3A%22320%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21EUR%211.69%210.99%21%21%211.87%211.09%21%40210388c917445863711634120eee2e%2112000024243771430%21sea%21DE%210%21ABX&curPageLogUid=r1JT4UtQlv0x&utparam-url=scene%3Asearch%7Cquery_from%3A)
Curved Breadway Pins 2,54mm - [amazon](https://www.amazon.com/maierke-Connector-Assortment-Stackable-Breakaway/dp/B0B9MYBH6C/ref=sr_1_16?dib=eyJ2IjoiMSJ9.ta8Z8Op10qrZHbS0nd10UI14z-PfbSERroI9RKnw6hnmAXWzcmID2JkaBszDJfpN72rdVxdsEguhKF6ZGzUHTdUTeHQd1lG5l4BEt574oAq6kKuE3SHrNpOzbS65h6pkxXybaPwHFjb5kCn2bMKfEkcVd-kS-rHmKkfjKq6gOmuDtjGkif-FFZXR0iynxe-Vc5jey95xcM5wOMtuckdNdYeeSWXXVo0iLqSFPEA3-s0.zzsnZhF0YtSEiFIiDuT_O5o05OvTQJkafqfdy9U7AKA&dib_tag=se&keywords=breadboard+pins&qid=1744586855&sr=8-16)
Breadway Wires - [amazon](https://www.amazon.com/360-Pc-Multicolor-Breadboard-Jumper-Wires/dp/B089FZ79CS/ref=sr_1_2_sspa?dib=eyJ2IjoiMSJ9.ta8Z8Op10qrZHbS0nd10UI14z-PfbSERroI9RKnw6hnmAXWzcmID2JkaBszDJfpN72rdVxdsEguhKF6ZGzUHTdUTeHQd1lG5l4BEt574oAq6kKuE3SHrNpOzbS65h6pkxXybaPwHFjb5kCn2bMKfEkcVd-kS-rHmKkfjKq6gOmuDtjGkif-FFZXR0iynxe-Vc5jey95xcM5wOMtuckdNdYeeSWXXVo0iLqSFPEA3-s0.zzsnZhF0YtSEiFIiDuT_O5o05OvTQJkafqfdy9U7AKA&dib_tag=se&keywords=breadboard%2Bpins&qid=1744586855&sr=8-2-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&th=1)
NRF24 - [amazon](https://www.amazon.com/Aideepen-NRF24L01-Transceiver-Breakout-Compatible/dp/B07ZGQ2X7Q/ref=sr_1_1_sspa?crid=1OU5RLO6KKO57&dib=eyJ2IjoiMSJ9.dZuwdL7h26Xl_FGsDUee2-UEXahZuGed0eOismHOjlZBV5KeaOK0inaQhnAGV_IMiAXiaA3oQLomcP5jnEqChwfU7DvWvqjrv-tbyrIc1yc9UMz3QccPoNRDMW9c5vsUu8UcDLH6pFe3b5JzeUC2Rtuo6SXsgciaK1SedTeAeCsd_aAgFwz2UtoDPHUHGzXIJjzTYtjjQOFOj0JsUimD0bRSo1FdoEHA0lDMYxLhNEw.x2eJzsokaUM1KdYPwvTRsQxT-lKo43OFqrDerpT-JlM&dib_tag=se&keywords=nrf24&qid=1744587172&sprefix=nr%2Caps%2C542&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&th=1) / CC1101 - [amazon](https://www.amazon.com/CC1101-Wireless-Module-Antenna-Transceiver/dp/B0D2TMTV5Z/ref=sr_1_1?crid=3NM8O5J2T7PRO&dib=eyJ2IjoiMSJ9.TdBjM4Yj0nrdKXgEVvK6pJtOL-9MQZ3ZdT9YLke5WDmeCrOM7ZCFqVshzxspYKtfR6YYN1K-X_x9uWcSfIHg7hMN_sCC1nFFzlAA-H7vlpcEL2lKW94wxnnbQpQePicuhcihiePpUZASFxlMgqLj9TolxyTkE9cjSljcR3w9asUFrRQoPMTKdzLDFGjwHairQ2-JichzamD00Jzj6mOK8MzH-5Sw6wxnGHm9gHyazNQ.1-RbZ2XzSJdAEHvvCHVihpwwftU5IIKPQpb6SQ5VgxA&dib_tag=se&keywords=cc1101&qid=1744587251&sprefix=cc1101+%2Caps%2C421&sr=8-1)
Proficiency in soldering
'''

