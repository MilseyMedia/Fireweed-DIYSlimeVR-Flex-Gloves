# Fireweed-DIYSlimeVR-Flex-Gloves
A PCB with a removable 14500 lithium ion battery for flex sensor finger and thumb tracking with SlimeVR. A variant of GizmoQC's flex sensor Finger tracker project. A collaboration between Milsey, GizmoQC and LocaCola. 

It is recommended that you use  a SlimeVR tracker for your wrist and hand to improve tracking data. This can be done with a [Trillium DIYSlimeVR tracker](https://github.com/MilseyMedia/Trillium-DIYSlimeVR-Trackers) & extension or two smol SlimeVR trackers

![Fireweed Flex Glove](https://github.com/user-attachments/assets/e64f0504-fbcd-4158-8023-d769b5144841)

<img width="733" height="624" alt="Fireweed PCB traces" src="https://github.com/user-attachments/assets/a1f4b2d4-1bf8-4160-99a8-d78c5fa7c905" />


## Parts list
- [2.2 inch flex sensors](https://shop.app/p/6077250502849?variantId=42337369194724&utm_source=shop_app&utm_medium=shop_app_share&utm_campaign=share_product&link_alias=jsltZ9lIef5v) x5 
- [Male to male jumper wires](https://a.co/d/0dMju9wd)
- [10kΩ 1/4 watt resistor](https://www.amazon.ca/Projects-100EP11410K0-10k-Resistors-Pack/dp/B07C93JL54/ref=sr_1_3_sspa?sr=8-3-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1) x5
- [180k ohm resistor](https://www.aliexpress.com/item/1005002994755806.html?spm=a2g0o.order_list.order_list_main.135.13be1802HgETiE&gatewayAdapt=4itemAdapt) x1 
- [MSS22D18 6 pin switch](https://www.aliexpress.com/item/4000699849055.html?spm=a2g0o.productlist.main.1.41aa6d8aSzOAC4&algo_pvid=0c0f082c-a444-4a1e-ba30-c9aa43c2c727&algo_exp_id=0c0f082c-a444-4a1e-ba30-c9aa43c2c727-0&pdp_ext_f=%7B%22order%22%3A%2238%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21CAD%215.00%214.05%21%21%213.57%212.89%21%40210328df17726608201306737eea9a%2110000006192024429%21sea%21CA%211616760453%21X%211%210%21n_tag%3A-29919%3Bd%3A16d45553%3Bm03_new_user%3A-29895&curPageLogUid=wtDTKdXzcQws&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A4000699849055%7C_p_origin_prod%3A) x1 
- [Feather V2 micro controller](https://www.pishop.ca/product/adafruit-esp32-feather-v2-with-headers-8mb-flash-2-mb-psram-stemma-qt/) x1 
- [14500 lithium ion battery ](https://www.aliexpress.com/item/1005011650960730.html?spm=a2g0o.productlist.main.2.345511e21mZYlX&algo_pvid=5993e997-54b4-4adf-bcd5-d847ba858e5f&algo_exp_id=5993e997-54b4-4adf-bcd5-d847ba858e5f-1&pdp_ext_f=%7B%22order%22%3A%221%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21CAD%2116.56%2111.09%21%21%2181.87%2154.85%21%402101e62517726664367935713e1b1b%2112000056151489269%21sea%21CA%211616760453%21X%211%210%21n_tag%3A-29919%3Bd%3A16d45553%3Bm03_new_user%3A-29895&curPageLogUid=QWVlhoRbiu7R&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005011650960730%7C_p_origin_prod%3A)
- [Female header pins](https://a.co/d/07kqznTs)
- [30 x 400mm stretchy velcro straps](https://www.aliexpress.com/item/1005006869319882.html?spm=a2g0o.order_list.order_list_main.100.13be1802HgETiE)

## Soldering Livestream
> Streaming Friday, March 6th 2026

## Firmware Flashing guide

- For connection with the slimeVR server, please select **ConnectToSlime/**
- Be sure to use the **GizmoSlimeFirmware.ino** file for Arudino IDE
- Otherwise, please follow all instructions within the GizmoQC GitHub starting with Step 0

## GizmoQC's GitHub for firmware files:
https://github.com/Guizmo12/gizmoglovesmocap

