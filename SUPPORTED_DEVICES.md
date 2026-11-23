# Supported devices

Orion Vision OS needs ARCore, which is Google Play Services for AR. ARCore is what tracks the phone in the room, so the
windows you open stay where you put them when you turn your head or walk. This page lists every phone that Google
certifies for ARCore.

A phone that is not on this list can still run Orion Vision OS, but it has no room tracking: the windows follow your
head instead of staying in the room.

Listed here means ARCore certified by Google. It does not mean tested with Orion Vision OS. The alpha is early and I can
only test on the phones I own.

## Tested

| Phone | Chipset | Status |
|---|---|---|
| Samsung Galaxy S22 Ultra | Snapdragon | Works. It gets hot. |

If you try another phone, tell me how it went. More tested phones are coming.

## About the list

- Source: [ARCore supported devices](https://developers.google.com/ar/devices), fetched 2026-11-20.
- 1686 models from 48 brands, both Google's Android (Google Play) table and its Android (China) table.
- **Depth API** says whether Google lists the model as supporting the ARCore Depth API (1333 of 1686 models do).
- **Notes** are Google's own comments for the model, such as the minimum Android version.
- Xiaomi rows are split into Xiaomi, Redmi and POCO by model name.
- The raw data is in [data/arcore-devices.json](data/arcore-devices.json).

## Brands

- [ASUS](#asus) (16)
- [Balmuda](#balmuda) (1)
- [Bluebird](#bluebird) (3)
- [Brain](#brain) (1)
- [Datalogic](#datalogic) (8)
- [FCNT](#fcnt) (15)
- [Fujitsu](#fujitsu) (2)
- [General Mobile](#general-mobile) (1)
- [GETAC](#getac) (2)
- [Google](#google) (41)
- [Honeywell](#honeywell) (7)
- [Honor](#honor) (21)
- [HTC](#htc) (3)
- [Huawei](#huawei) (20)
- [Hurricane](#hurricane) (1)
- [Infinix](#infinix) (48)
- [itel](#itel) (1)
- [Kyocera](#kyocera) (19)
- [Lenovo](#lenovo) (30)
- [LG](#lg) (35)
- [LitByLeia](#litbyleia) (1)
- [Luxshare](#luxshare) (5)
- [Micromax](#micromax) (1)
- [Motorola](#motorola) (133)
- [Nokia (HMD Global)](#nokia-hmd-global) (15)
- [Nothing](#nothing) (12)
- [OnePlus](#oneplus) (86)
- [OPPO](#oppo) (225)
- [Pepperl+Fuchs](#pepperlfuchs) (2)
- [POCO](#poco) (23)
- [Point Mobile](#point-mobile) (2)
- [Rakuten](#rakuten) (1)
- [realme](#realme) (110)
- [Redmi](#redmi) (64)
- [Samsung](#samsung) (254)
- [Sharp](#sharp) (34)
- [Sony](#sony) (28)
- [TCL](#tcl) (1)
- [TECNO](#tecno) (54)
- [UMX](#umx) (1)
- [Uniscope](#uniscope) (1)
- [Unitech](#unitech) (8)
- [Vinsmart](#vinsmart) (2)
- [vivo](#vivo) (241)
- [Wiko](#wiko) (1)
- [Xiaomi](#xiaomi) (47)
- [Zebra](#zebra) (46)
- [ZTE](#zte) (13)

## ASUS

| Model | Depth API | Notes |
|---|---|---|
| ROG Phone | No |  |
| ROG Phone 5 | Yes |  |
| ROG Phone 6 (AI2201) (AI2201) | Yes |  |
| ROG Phone 6D Ultimate (AI2201) (AI2201) | Yes |  |
| ROG Phone 7 (AI2205) (AI2205) | Yes |  |
| ROG Phone 8 series | Yes |  |
| ROG Phone 9 | Yes |  |
| ROG Phone II | No |  |
| ROG Phone III | Yes |  |
| Zenfone 10 (AI2302) (AI2302) | Yes |  |
| Zenfone 6 | No |  |
| Zenfone 7/7 Pro | Yes |  |
| Zenfone 8 | Yes |  |
| Zenfone 9 | Yes |  |
| Zenfone AR | No |  |
| Zenfone ARES | No |  |

## Balmuda

| Model | Depth API | Notes |
|---|---|---|
| Balmuda Phone | Yes |  |

## Bluebird

| Model | Depth API | Notes |
|---|---|---|
| HF550X | Yes |  |
| S70 | Yes |  |
| X40 | Yes |  |

## Brain

| Model | Depth API | Notes |
|---|---|---|
| Natural AI Phone | Yes |  |

## Datalogic

| Model | Depth API | Notes |
|---|---|---|
| Falcon X60 | Yes |  |
| Falcon X65 | Yes |  |
| Memor 12 | Yes |  |
| Memor 17 | Yes |  |
| Memor 30 | Yes |  |
| Memor 35 | Yes |  |
| Skorpio X40 | Yes |  |
| Skorpio X45 | Yes |  |

## FCNT

| Model | Depth API | Notes |
|---|---|---|
| arrows Alpha2 F-51G | Yes |  |
| arrows Alpha2 M10 | Yes |  |
| arrows BZ03 | Yes |  |
| arrows N F-51C | Yes |  |
| arrows We A101FC | No |  |
| arrows We F-51B | No |  |
| arrows We FCG01 | No |  |
| arrows We2 A402FC | No |  |
| arrows We2 F-52E | Yes |  |
| arrows We2 FCG02 | Yes |  |
| arrows We2 M07 | Yes |  |
| arrows We2 Plus F-51E | Yes |  |
| arrows We2 Plus M06 | Yes |  |
| arrows We3 | Yes |  |
| F-53E | Yes |  |

## Fujitsu

| Model | Depth API | Notes |
|---|---|---|
| arrows 5G F-51A | Yes |  |
| arrows NX9 F-52A | Yes |  |

## General Mobile

| Model | Depth API | Notes |
|---|---|---|
| GM 9 Plus | No |  |

## GETAC

| Model | Depth API | Notes |
|---|---|---|
| ZX10G2 | Yes |  |
| ZX80 | Yes |  |

## Google

| Model | Depth API | Notes |
|---|---|---|
| Nexus 5X | No | Requires Android 8.0 or later |
| Nexus 6P | No | Requires Android 8.0 or later |
| Pixel | No |  |
| Pixel 10 | Yes |  |
| Pixel 10 Pro | Yes |  |
| Pixel 10 Pro Fold | Yes |  |
| Pixel 10 Pro XL | Yes |  |
| Pixel 10a | Yes |  |
| Pixel 11 | Yes |  |
| Pixel 11 Pro | Yes |  |
| Pixel 11 Pro Fold | Yes |  |
| Pixel 11 Pro XL | Yes |  |
| Pixel 2 | Yes | Supports 60 fps camera capture frame rate on the rear-facing camera; Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| Pixel 2 XL | Yes | Supports 60 fps camera capture frame rate on the rear-facing camera; Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| Pixel 3 | Yes | Supports 60 fps camera capture frame rate on the rear-facing camera; When 60 fps camera capture mode is active, the camera uses fixed focus; Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| Pixel 3 XL | Yes | Supports 60 fps camera capture frame rate on the rear-facing camera; When 60 fps camera capture mode is active, the camera uses fixed focus; Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| Pixel 3a | Yes | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| Pixel 3a XL | Yes | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| Pixel 4 | Yes | Supports 60 fps camera capture frame rate on the rear-facing camera on Android 10 Dec 2019 OTA or later; Supports multiple GPU texture resolutions - 1080p, 720p, 480p; Dual camera support will be rolled out in the coming weeks |
| Pixel 4 XL | Yes | Supports 60 fps camera capture frame rate on the rear-facing camera on Android 10 Dec 2019 OTA or later; Supports multiple GPU texture resolutions - 1080p, 720p, 480p; Dual camera support will be rolled out in the coming weeks |
| Pixel 4a | Yes | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| Pixel 4a 5G | Yes | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| Pixel 5 | Yes | Supports 60 fps camera capture frame rate on the rear-facing camera; Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| Pixel 5a 5G | Yes | Supports 60 fps camera capture frame rate on the rear-facing camera; Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| Pixel 6 | Yes | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| Pixel 6 Pro | Yes | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| Pixel 6a | Yes | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| Pixel 7 | Yes | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| Pixel 7 Pro | Yes | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| Pixel 7a | Yes |  |
| Pixel 8 | Yes |  |
| Pixel 8 Pro | Yes |  |
| Pixel 8a | Yes |  |
| Pixel 9 | Yes |  |
| Pixel 9 Pro | Yes |  |
| Pixel 9 Pro Fold | Yes |  |
| Pixel 9 Pro XL | Yes |  |
| Pixel 9a | Yes |  |
| Pixel Fold | Yes |  |
| Pixel Tablet | Yes |  |
| Pixel XL | No |  |

## Honeywell

| Model | Depth API | Notes |
|---|---|---|
| CK67 | Yes |  |
| CT30XP | Yes |  |
| CT37 | Yes |  |
| CT40 | Yes |  |
| CT45XP | Yes |  |
| CT70 | Yes |  |
| MobilityEdge CT70 | Yes |  |

## Honor

| Model | Depth API | Notes |
|---|---|---|
| HONOR 200 | Yes |  |
| HONOR 200 Pro | Yes |  |
| HONOR 400 | Yes |  |
| HONOR 400 Pro | Yes |  |
| HONOR 600 | Yes |  |
| HONOR 600 Pro | Yes |  |
| HONOR 70 | Yes |  |
| HONOR 90 | Yes |  |
| HONOR Magic V2 | Yes |  |
| HONOR Magic V3 | Yes |  |
| HONOR Magic V5 | Yes |  |
| HONOR Magic V6 | Yes |  |
| HONOR Magic Vs | Yes |  |
| HONOR Magic4 Pro | Yes |  |
| HONOR Magic5 | Yes |  |
| HONOR Magic5 Pro | Yes |  |
| HONOR Magic6 Lite 5G | Yes |  |
| HONOR Magic7 Lite | Yes |  |
| HONOR Magic8 Pro | Yes |  |
| HONOR X9c Smart | Yes |  |
| HONOR X9d | Yes |  |

## HTC

| Model | Depth API | Notes |
|---|---|---|
| Desire 21 Pro 5G | Yes |  |
| HTC U23 | Yes |  |
| HTC U23 pro | Yes |  |

## Huawei

| Model | Depth API | Notes |
|---|---|---|
| Honor 10 | Yes | Supports multiple GPU texture resolutions - 1440x1080, 1280x960, 480p |
| Honor 8X | No |  |
| Honor Magic 2 | No |  |
| Honor V20 | Yes | Supports multiple GPU texture resolutions - 1440x1080, 1280x960, 480p |
| Honor View 10 Lite | No |  |
| Maimang 7 | No |  |
| Mate 20 | Yes |  |
| Mate 20 Lite | Yes |  |
| Mate 20 Pro | Yes |  |
| Mate 20 X | Yes |  |
| Nova 3 | Yes | Supports multiple GPU texture resolutions - 1440x1080, 1280x960, 480p |
| Nova 3i | Yes |  |
| Nova 4 | Yes | Supports multiple GPU texture resolutions - 1440x1080, 1280x960, 480p |
| P20 | Yes | Supports multiple GPU texture resolutions - 1440x1080, 1280x960, 480p |
| P20 Pro | No | Supports multiple GPU texture resolutions - 1440x1080, 1280x960, 480p |
| P30 | Yes | Supports multiple GPU texture resolutions - 1440x1080, 1280x960, 480p |
| P30 Pro | Yes | Supports multiple GPU texture resolutions - 2048x1536, 1280x960, 480p |
| Porsche Design Mate 20 RS | No |  |
| Porsche Design Mate RS | No |  |
| Y9 2019 | No | Does not support Geospatial API |

## Hurricane

| Model | Depth API | Notes |
|---|---|---|
| vegas | No | Does not support Geospatial API |

## Infinix

| Model | Depth API | Notes |
|---|---|---|
| GT 10 Pro | Yes |  |
| GT 50 Pro | Yes |  |
| HOT 40 Pro | Yes |  |
| HOT 50 Pro+ | Yes |  |
| HOT 60 Pro+ | Yes |  |
| Infinix HOT 60 Pro | Yes |  |
| Infinix HOT 60i | Yes |  |
| Infinix HOT 70 | Yes |  |
| Infinix HOT 70 Pro 5G | Yes |  |
| Infinix NOTE 60 | Yes |  |
| Infinix NOTE 60 Ultra | Yes |  |
| Infinix Zero 40 | Yes |  |
| Infinix Zero 40 5G | Yes |  |
| Infinix ZERO Flip | Yes |  |
| Note 10 Pro | No |  |
| Note 11 | No |  |
| Note 11 Pro | Yes |  |
| Note 11S | Yes |  |
| Note 12 | No |  |
| NOTE 12 2023 | Yes |  |
| Note 12 VIP | Yes |  |
| Note 30 | Yes |  |
| Note 30 5G | Yes |  |
| Note 30 Pro | Yes |  |
| Note 30i | Yes |  |
| Note 40 | Yes |  |
| Note 40 Pro | Yes |  |
| Note 50 Pro | Yes |  |
| Note 50 Pro+ 5G | Yes |  |
| Note 50S 5G | Yes |  |
| Note 50X 5G | Yes |  |
| Note 6 | No |  |
| NOTE 60 Pro | Yes |  |
| Note 7 | No |  |
| ZERO 20 | Yes |  |
| ZERO 30 | Yes |  |
| ZERO 30 5G | Yes |  |
| ZERO 40 | Yes |  |
| ZERO 40 5G | Yes |  |
| Zero 5G | Yes |  |
| Zero 5G 2023 | Yes |  |
| Zero 8 | No |  |
| Zero 8i | No |  |
| ZERO Flip | Yes |  |
| ZERO ULTRA | Yes |  |
| ZERO X | Yes |  |
| ZERO X NEO | Yes |  |
| ZERO X Pro | Yes |  |

## itel

| Model | Depth API | Notes |
|---|---|---|
| itel S23+ | Yes |  |

## Kyocera

| Model | Depth API | Notes |
|---|---|---|
| Android One S10 | Yes |  |
| Android One S9 | Yes |  |
| DIGNO BX3 | Yes |  |
| DIGNO BX3 Plus | Yes |  |
| DIGNO BX3 カメラレス | Yes |  |
| DIGNO SANGA edition | Yes |  |
| DIGNO SX4 | Yes |  |
| DIGNO SX4 Wi-Fi | Yes |  |
| DIGNO SX5 | Yes |  |
| Duraforce Ex | Yes |  |
| DuraForce EX2 | Yes |  |
| Duraforce PRO 3 | Yes |  |
| Duraforce Ultra 5G | No |  |
| DuraSport 5G | No |  |
| KC-T305 | Yes |  |
| Torque 5G | Yes |  |
| Torque G04 | No |  |
| Torque G06 | Yes |  |
| TORQUE G07 | Yes |  |

## Lenovo

| Model | Depth API | Notes |
|---|---|---|
| Lenovo Idea Tab Pro | Yes |  |
| Lenovo Idea Tab Pro Gen 2 | No |  |
| Lenovo K13 Note | Yes |  |
| Lenovo LAVIE Tab 102K1 | Yes |  |
| Lenovo LAVIE Tab T12 12QHD1 | No |  |
| Lenovo Legion Tab (8.8",5) | Yes |  |
| Lenovo Tab 7 | Yes |  |
| Lenovo Tab Extreme | Yes |  |
| Lenovo Tab K11 Plus | Yes |  |
| Lenovo Tab K13 | No |  |
| Lenovo Tab M10 5G | Yes |  |
| Lenovo Tab M10 Plus 3rd Gen | Yes |  |
| Lenovo Tab M11 | Yes |  |
| Lenovo Tab P11 2nd Gen | Yes |  |
| Lenovo Tab P11 5G | Yes |  |
| Lenovo Tab P11 Plus | No |  |
| Lenovo Tab P11 Pro (2nd Gen) | Yes |  |
| Lenovo Tab P12 | Yes |  |
| Lenovo Tab P12 Pro | Yes |  |
| Lenovo Tab Plus | Yes |  |
| Lenovo Tab Plus Gen 2 | Yes |  |
| Lenovo ThinkTab X11 Gen 1 | Yes |  |
| Lenovo Yoga Tab | Yes |  |
| Lenovo Yoga Tab 11 | Yes |  |
| Lenovo Yoga Tab Plus | Yes |  |
| Lenovo Yoga Tab Plus Gen2 | Yes |  |
| Lenovo 启天K10 Pro | Yes |  |
| Lenovo 小新Pad Plus 2023 | Yes |  |
| 小新学习平板 | Yes |  |
| 联想平板 拯救者 Y900 13 | Yes |  |

## LG

| Model | Depth API | Notes |
|---|---|---|
| G Pad 5 10.1 FHD | No |  |
| G6 | No | Requires Android 8.0 or later |
| G7 Fit | No |  |
| G7 One | No |  |
| G7 ThinQ | No | ARCore uses the wide angle fixed focus rear facing camera for AR tracking |
| G8 ThinQ | No | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| G8S ThinQ | No |  |
| G8X ThinQ | Yes |  |
| K61 | No |  |
| K71 | No |  |
| K92 | Yes |  |
| LG Signature Edition 2017 | No | Requires Android 8.0 or later; ARCore uses the wide angle fixed focus rear facing camera for AR tracking |
| LG Signature Edition 2018 | No | ARCore uses the wide angle fixed focus rear facing camera for AR tracking |
| LG Signature Edition 2019 | No | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| Q6 | No | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| Q70 | No |  |
| Q8 | No |  |
| Q92 | Yes |  |
| style2 | No | ARCore uses the wide angle fixed focus rear facing camera for AR tracking |
| style3 | No |  |
| Stylo 5 | No |  |
| Stylo 6 | No |  |
| Stylo 7 | Yes |  |
| V30 | No | Requires Android 8.0 or later; ARCore uses the wide angle fixed focus rear facing camera for AR tracking |
| V30+ | No | Requires Android 8.0 or later; ARCore uses the wide angle fixed focus rear facing camera for AR tracking |
| V30+ JOJO | No | Requires Android 8.0 or later; ARCore uses the wide angle fixed focus rear facing camera for AR tracking |
| V35 ThinQ | Yes | ARCore uses the wide angle fixed focus rear facing camera for AR tracking |
| V40 ThinQ | No | ARCore uses the wide angle fixed focus rear facing camera for AR tracking |
| V50 ThinQ | No | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| V50S ThinQ | Yes | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| V60 ThinQ | Yes | Supports multiple GPU texture resolutions - 1080p, 720p, 480p; Supports time-of-flight (ToF) hardware depth sensor |
| V60 ThinQ 5G | Yes | Supports multiple GPU texture resolutions - 1080p, 720p, 480p; Supports time-of-flight (ToF) hardware depth sensor |
| VELVET 2 Pro | Yes |  |
| VELVET 5G | Yes |  |
| WING 5G | Yes |  |

## LitByLeia

| Model | Depth API | Notes |
|---|---|---|
| Lume Pad | Yes |  |

## Luxshare

| Model | Depth API | Notes |
|---|---|---|
| Hubbs | Yes |  |
| Revvl 8 | Yes |  |
| Revvl 8 Pro | Yes |  |
| T Phone 3 | Yes |  |
| T Phone 3 Pro | Yes |  |

## Micromax

| Model | Depth API | Notes |
|---|---|---|
| IN_Note2 | No |  |

## Motorola

| Model | Depth API | Notes |
|---|---|---|
| moto g 5G | Yes |  |
| moto g 5G (2022) | Yes |  |
| moto g max | Yes |  |
| moto g power | No | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| moto g power (2021) | Yes |  |
| moto g power (2022) | No |  |
| moto g power 5G (2023) | Yes |  |
| moto g pro | No | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| moto g stylus | No | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| moto g stylus (2021) | Yes |  |
| moto g stylus (2022) | No |  |
| moto g stylus (2023) | Yes |  |
| moto g stylus - 2026 | Yes |  |
| moto g stylus 5G | Yes |  |
| moto g stylus 5G (2022) | Yes |  |
| moto g stylus 5G (2023) | Yes |  |
| moto g stylus 5G (2025) | Yes |  |
| moto g(10) | No |  |
| moto g(100) | Yes |  |
| moto g(30) | No |  |
| moto g(40) fusion | No |  |
| moto g(50) | No |  |
| moto g(50) 5G | Yes |  |
| moto g(60) | No |  |
| moto g(60)s | No |  |
| moto g200 5G | Yes |  |
| moto g24 | Yes |  |
| moto g31 | No |  |
| moto g32 | Yes |  |
| moto g34 5G | Yes |  |
| moto g35 5G | Yes |  |
| moto g37 | Yes |  |
| moto g37 M-51G | Yes |  |
| moto g42 | Yes |  |
| moto g47 | Yes |  |
| moto g51 5G | Yes |  |
| moto g52 | Yes |  |
| moto g52j 5G | Yes |  |
| moto g53 | Yes |  |
| moto g53 5G | Yes |  |
| moto g54 5G | Yes |  |
| moto g55 5G | Yes |  |
| moto g56 5G | Yes |  |
| moto g62 5G | Yes |  |
| moto g67 | Yes |  |
| moto g67 power 5G | Yes |  |
| moto g71 5G | Yes |  |
| moto g72 | Yes |  |
| moto g73 5G | Yes |  |
| moto g75 5G | Yes |  |
| moto g77 | Yes |  |
| moto g77 power | Yes |  |
| moto g82 5G | Yes |  |
| moto g84 5G | Yes |  |
| moto g86 5G | Yes |  |
| moto g87 | Yes |  |
| moto g96 5G | Yes |  |
| moto g⁵ˢ plus | No | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| moto g⁶ | No | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| moto g⁶ plus | No | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| moto g⁷ | No |  |
| moto g⁷ play | No |  |
| moto g⁷ plus | No |  |
| moto g⁷ power | No |  |
| moto g⁸ | No | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| moto g⁸ play | No | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| moto g⁸ plus | No | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| moto g⁸ power | No | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| moto g⁸ power lite | No | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| moto g⁹ play | No |  |
| moto g⁹ plus | Yes |  |
| moto g⁹ power | Yes |  |
| moto tab g62 | Yes |  |
| moto tab g62 LTE | Yes |  |
| moto x40 | No | Requires Android 8.0 or later |
| moto x⁴ | No | Requires Android 8.0 or later |
| moto z² force | No | Requires Android 8.0 or later |
| moto z³ | No |  |
| moto z³ play | No |  |
| moto z⁴ | No |  |
| motorola edge | Yes |  |
| motorola edge (2021) | Yes |  |
| motorola edge (2022) | Yes |  |
| motorola edge (2023) | Yes |  |
| motorola edge - 2026 | Yes |  |
| motorola edge 20 | Yes |  |
| motorola edge 20 lite | Yes |  |
| motorola edge 20 pro | Yes |  |
| motorola edge 30 | Yes |  |
| motorola edge 30 fusion | Yes |  |
| motorola edge 30 neo | Yes |  |
| motorola edge 30 Pro | Yes |  |
| motorola edge 30 ultra | Yes |  |
| motorola edge 40 | Yes |  |
| motorola edge 40 neo | Yes |  |
| motorola edge 50 neo | Yes |  |
| motorola edge 60 fusion | Yes |  |
| motorola edge 60 stylus | Yes |  |
| motorola edge 70 fusion | Yes |  |
| motorola edge 70 fusion + | Yes |  |
| motorola edge 70 max | Yes |  |
| motorola edge 70 pro | Yes |  |
| motorola edge 70 pro+ | Yes |  |
| motorola edge plus | Yes |  |
| motorola edge plus (2022) | Yes |  |
| motorola edge s | Yes |  |
| motorola one | No |  |
| motorola one 5G | Yes |  |
| motorola one action | No |  |
| motorola one fusion | Yes |  |
| motorola one fusion+ | Yes |  |
| motorola one hyper | No | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| motorola one macro | No |  |
| motorola one power | No |  |
| motorola one vision | No |  |
| motorola one zoom | No |  |
| motorola razr 2026 | Yes |  |
| motorola Razr 40 | Yes |  |
| motorola Razr 40 Ultra | Yes |  |
| motorola Razr 50D M-51E | Yes |  |
| motorola razr 60d M-51F | Yes |  |
| motorola razr 70 | Yes |  |
| motorola razr 70 plus | Yes |  |
| motorola razr 70 ultra | Yes |  |
| motorola razr fold | Yes |  |
| motorola razr fold 2026 | Yes |  |
| motorola razr plus 2026 | Yes |  |
| motorola razr ultra 2026 | Yes |  |
| motorola Razr(2020) | Yes |  |
| motorola Razr(2022) | Yes |  |
| motorola signature | Yes |  |
| motorola signature 27 | Yes |  |
| ThinkPhone by Motorola | No |  |

## Nokia (HMD Global)

| Model | Depth API | Notes |
|---|---|---|
| Nokia 3.4 | No |  |
| Nokia 5.4 | No |  |
| Nokia 6 (2018) | No | Also known as Nokia 6.1 |
| Nokia 6.1 Plus | No |  |
| Nokia 6.2 | No | Requires Android 10.0 or later |
| Nokia 7 Plus | No |  |
| Nokia 7.1 | No |  |
| Nokia 7.2 | No | Requires Android 10.0 or later |
| Nokia 8 | No | Requires Android 8.0 or later |
| Nokia 8 Sirocco | No |  |
| Nokia 8.1 | No |  |
| Nokia 8.3 5G | No |  |
| Nokia G50 | Yes | Requires Android 13 or later |
| Nokia X10 | Yes | Requires Android 13 or later |
| Nokia X30 5G | Yes |  |

## Nothing

| Model | Depth API | Notes |
|---|---|---|
| CMF by Nothing Phone 1 | Yes |  |
| Nothing Phone (1) | Yes |  |
| Nothing Phone (2) | Yes |  |
| Nothing Phone (2) Pro | Yes |  |
| Nothing Phone (2a) | Yes |  |
| Nothing Phone (2a) Plus | Yes |  |
| Nothing Phone (3) | Yes |  |
| Nothing Phone (3a) | Yes |  |
| Nothing Phone (3a) Pro | Yes |  |
| Nothing Phone (4a) | Yes |  |
| Nothing Phone (4a) Pro | Yes |  |
| Nothing Phone (4b) | Yes |  |

## OnePlus

| Model | Depth API | Notes |
|---|---|---|
| Nord CE5 | Yes |  |
| OnePlus 10 Pro | Yes |  |
| OnePlus 10 Pro 5G | Yes |  |
| OnePlus 10R 5G | Yes |  |
| OnePlus 10T 5G | Yes |  |
| OnePlus 11 5G | Yes |  |
| OnePlus 11 5G 中国版 | Yes |  |
| OnePlus 11R 5G | Yes |  |
| OnePlus 12 | Yes |  |
| OnePlus 12R | Yes |  |
| OnePlus 13 | Yes |  |
| OnePlus 13R | Yes |  |
| OnePlus 13S | Yes |  |
| OnePlus 13T | Yes |  |
| OnePlus 15 | Yes |  |
| OnePlus 15R | Yes |  |
| OnePlus 15T | Yes |  |
| OnePlus 16 | Yes |  |
| OnePlus 3T | No | Requires Android 8.0 or later |
| OnePlus 5 | No |  |
| OnePlus 5T | No |  |
| OnePlus 6 | Yes | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| OnePlus 6T | Yes | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| OnePlus 7 | Yes | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| OnePlus 7 Pro | Yes | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| OnePlus 7 Pro 5G | Yes | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| OnePlus 7T | Yes | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| OnePlus 7T Pro | Yes | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| OnePlus 8 | Yes |  |
| OnePlus 8 Pro | Yes | Does not support Geospatial API |
| OnePlus 8T | Yes |  |
| OnePlus 9 | Yes |  |
| OnePlus 9 Pro | Yes |  |
| OnePlus 9R | Yes |  |
| OnePlus 9RT 5G | Yes |  |
| OnePlus Ace | Yes |  |
| Oneplus Ace 2 Pro | Yes |  |
| OnePlus Ace 3 | Yes |  |
| Oneplus Ace 3 Pro | Yes |  |
| OnePlus Ace 3V | Yes |  |
| OnePlus Ace 5 | Yes |  |
| OnePlus Ace 5 Pro | Yes |  |
| OnePlus Ace 5 竞速版 | Yes |  |
| OnePlus Ace 5 至尊版 | Yes |  |
| OnePlus Ace 6 | Yes |  |
| OnePlus Ace 6 至尊版 | Yes |  |
| OnePlus Ace 7 | Yes |  |
| OnePlus Ace 7 Pro | Yes |  |
| OnePlus Ace Pro | Yes |  |
| OnePlus Ace 竞速版 | Yes |  |
| OnePlus N10 | Yes |  |
| OnePlus Nord | Yes |  |
| OnePlus Nord 2 5G | Yes |  |
| OnePlus Nord 2T 5G | Yes |  |
| OnePlus Nord 3 5G | Yes |  |
| OnePlus Nord 4 | Yes |  |
| OnePlus Nord 5 | Yes |  |
| OnePlus Nord 6 | Yes |  |
| OnePlus Nord CE | Yes |  |
| OnePlus Nord CE 2 | No |  |
| OnePlus Nord CE 2 Lite 5G | Yes |  |
| OnePlus Nord CE 3 5G | Yes |  |
| OnePlus Nord CE 3 Lite 5G | Yes |  |
| OnePlus Nord CE4 | Yes |  |
| OnePlus Nord CE4 Lite 5G | Yes |  |
| OnePlus Nord CE6 Lite | Yes |  |
| OnePlus Nord N20 5G | Yes |  |
| OnePlus Nord N200 5G | Yes |  |
| OnePlus Nord N30 5G | Yes |  |
| OnePlus Nord N30 SE 5G | Yes |  |
| OnePlus Open | Yes |  |
| OnePlus Pad | Yes |  |
| OnePlus Pad 4 | Yes |  |
| OnePlus Pad Go | Yes |  |
| Oneplus Pad2 | Yes |  |
| OnePlus Turbo 6 | Yes |  |
| Open | Yes |  |
| PHP110 | Yes |  |
| PLY110 | Yes |  |
| PYS110 | Yes |  |
| 一加 Ace 6T | Yes |  |
| 一加 Turbo 6X Pro | Yes |  |
| 一加平板 2 | Yes |  |
| 一加平板 2 Pro | Yes |  |
| 一加平板 3 Pro | Yes |  |
| 一加平板Pro | Yes |  |

## OPPO

| Model | Depth API | Notes |
|---|---|---|
| A1 Pro 5G | Yes |  |
| A2 5G | Yes |  |
| A3 5G | Yes |  |
| A3 Pro 5G | Yes |  |
| A3i Plus 5G | Yes |  |
| A5 5G | Yes |  |
| A5 Pro 5G | Yes |  |
| A52 | No |  |
| A53 5G | No |  |
| A6 Pro 5G | Yes |  |
| A6s Pro 5G | Yes |  |
| A7 Pro 5G | Yes |  |
| A7 Pro Max 5G | Yes |  |
| A72 | No |  |
| A72 5G | No |  |
| A77 5G | Yes |  |
| A78 5G | Yes |  |
| A79 5G | Yes |  |
| A92 | No |  |
| A92s | No |  |
| A93 5G | No |  |
| A94 | Yes |  |
| A96 5G | Yes |  |
| A98 5G | Yes |  |
| Cayman-C-RMX5062 | Yes |  |
| CPH2527 | Yes |  |
| F11 Pro | No |  |
| F15 | No |  |
| F17 Pro | No |  |
| F19 Pro+ | Yes |  |
| F21 Pro 5G | Yes |  |
| F21s Pro 5G | Yes |  |
| F25 Pro 5G | Yes |  |
| F27 Pro+ 5G | Yes |  |
| F29 5G | Yes |  |
| F29 Pro 5G | Yes |  |
| F31 Pro 5G | Yes |  |
| F31 Pro+ 5G | Yes |  |
| F33 Pro 5G | Yes |  |
| F35 5G | Yes |  |
| F35 Pro 5G | Yes |  |
| Find N2 | Yes |  |
| Find N2 Flip | Yes |  |
| Find N2 Flip 中国版 | Yes |  |
| Find N3 | Yes |  |
| Find N3 Flip | Yes |  |
| Find N5 | Yes |  |
| Find N5 卫星通信版 | Yes |  |
| Find N6 | Yes |  |
| Find N6 卫星通信版 | Yes |  |
| Find X10 | Yes |  |
| Find X10 E | Yes |  |
| Find X10 Pro Max | Yes |  |
| Find X2 | Yes |  |
| Find X2 Pro | Yes |  |
| Find X3 | Yes |  |
| Find X3 Pro | Yes |  |
| Find X5 | Yes |  |
| Find X5 Pro | Yes |  |
| Find X6 | Yes |  |
| Find X6 Pro | Yes |  |
| Find X7 | Yes |  |
| Find X7 Ultra | Yes |  |
| Find X8 | Yes |  |
| Find X8 Pro | Yes |  |
| Find X8 Pro 卫星通信版 | Yes |  |
| Find X8 Ultra | Yes |  |
| Find X8 Ultra 卫星通信版 | Yes |  |
| Find X8s | Yes |  |
| Find X8s+ | Yes |  |
| Find X9 | Yes |  |
| Find X9 Pro | Yes |  |
| Find X9 Pro 卫星通信版 | Yes |  |
| Find X9 Ultra | Yes |  |
| Find X9 Ultra 卫星通信版 | Yes |  |
| Find X9s | Yes |  |
| Find X9s Pro | Yes |  |
| K10 Pro 5G | No |  |
| K11 5G | Yes |  |
| K12 5G | Yes |  |
| K12 Plus | Yes |  |
| K12s 5G | Yes |  |
| K12x 5G | Yes |  |
| K13 5G | Yes |  |
| K13 Turbo 5G | Yes |  |
| K13 Turbo Pro 5G | Yes |  |
| K14 Plus 5G | Yes |  |
| K15 Pro | Yes |  |
| K15 Pro+ | Yes |  |
| K3 | No | Supports multiple GPU texture resolutions - 1440x1080, 1280x960, 480p |
| K5 | No | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| K7x | Yes |  |
| K9 5G | No |  |
| K9x 5G | No |  |
| Lafa-RMX5210 | Yes |  |
| OnePlus Ace 5 竞速版 | Yes |  |
| OnePlus Nord CE6 | Yes |  |
| OPD2506 | Yes |  |
| OPPO A3 Pro 5G | Yes |  |
| OPPO A5 5G | Yes |  |
| OPPO A5 Plus 5G | Yes |  |
| OPPO F27 Pro+ 5G | Yes |  |
| OPPO F29 5G | Yes |  |
| OPPO K11 5G | Yes |  |
| OPPO K11x 5G | Yes |  |
| OPPO K15 | Yes |  |
| OPPO Pad 2 | Yes |  |
| OPPO Pad 3 | Yes |  |
| OPPO Pad 3 Pro | Yes |  |
| OPPO Pad 5 | Yes |  |
| OPPO Pad 6 | Yes |  |
| OPPO Pad Neo | Yes |  |
| OPPO Reno10 5G | Yes |  |
| OPPO Reno10 Pro 5G | Yes |  |
| OPPO Reno10 Pro+ 5G | Yes |  |
| Pad 2 | Yes |  |
| Pad 3 | Yes |  |
| Pad 3 Pro | Yes |  |
| Pad 4 Pro | Yes |  |
| Pad 5 Pro | Yes |  |
| Pad Mini | Yes |  |
| PFFM20 | Yes |  |
| PGAM10 | Yes |  |
| PGBM10 | Yes |  |
| PGJM10 | Yes |  |
| Pista-RMX5010 | Yes |  |
| PLG110 | Yes |  |
| PLJ110 | Yes |  |
| PLK110 | Yes |  |
| PLL110 | Yes |  |
| PLN110 | Yes |  |
| PLQ110 | Yes |  |
| PLV110 | Yes |  |
| PLW110 | Yes |  |
| PYC110 | Yes |  |
| R17 Pro | No |  |
| RE6025L1 | Yes |  |
| Reno | No |  |
| Reno 10 5G | Yes |  |
| Reno 10 Pro 5G | Yes |  |
| Reno 10 Pro+ 5G | Yes |  |
| Reno 10x Zoom | No | Supports multiple GPU texture resolutions - 1440x1080, 1280x960, 480p |
| Reno 11 | Yes |  |
| Reno 11 Pro | Yes |  |
| Reno A | No | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| Reno Ace | Yes |  |
| Reno Ace 2 | No |  |
| Reno Z | No |  |
| Reno10 5G | Yes |  |
| Reno10 Pro 5G | Yes |  |
| Reno10 Pro+ 5G | Yes |  |
| Reno11 | Yes |  |
| Reno11 A | Yes |  |
| Reno11 F 5G | Yes |  |
| Reno11 Pro | Yes |  |
| Reno12 | Yes |  |
| Reno12 5G | Yes |  |
| Reno12 F 5G | Yes |  |
| Reno12 F/FS 5G | Yes |  |
| Reno12 Pro | Yes |  |
| Reno12 Pro 5G | Yes |  |
| Reno13 | Yes |  |
| Reno13 5G | Yes |  |
| Reno13 A | Yes |  |
| Reno13 F | Yes |  |
| Reno13 F 5G | Yes |  |
| Reno13 Pro | Yes |  |
| Reno13 Pro 5G | Yes |  |
| Reno14 | Yes |  |
| Reno14 5G | Yes |  |
| Reno14 F 5G | Yes |  |
| Reno14 FS 5G | Yes |  |
| Reno14 Pro | Yes |  |
| Reno14 Pro 5G | Yes |  |
| Reno15 | Yes |  |
| Reno15 5G | Yes |  |
| Reno15 A | Yes |  |
| Reno15 C 5G | Yes |  |
| Reno15 F 5G | Yes |  |
| Reno15 FS 5G | Yes |  |
| Reno15 Pro | Yes |  |
| Reno15 Pro 5G | Yes |  |
| Reno15 Pro Max 5G | Yes |  |
| Reno15 Pro Mini 5G | Yes |  |
| Reno15c | Yes |  |
| Reno16 5G | Yes |  |
| Reno16 F 5G | Yes |  |
| Reno16 FS 5G | Yes |  |
| Reno16 Pro | Yes |  |
| Reno16 Pro 5G | Yes |  |
| Reno16c 5G | Yes |  |
| Reno2 | No | Supports multiple GPU texture resolutions - 1440x1080, 1280x960, 480p |
| Reno2 F | No |  |
| Reno2 Z | No | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| Reno3 | No |  |
| Reno3 5G | Yes |  |
| Reno3 A | No |  |
| Reno3 Pro | No |  |
| Reno3 Pro 5G | No |  |
| Reno4 4G | No |  |
| Reno4 SE 5G | Yes |  |
| Reno5 | Yes |  |
| Reno5 5G | No |  |
| Reno5 A | Yes |  |
| Reno5 K 5G | No |  |
| Reno5 Pro 4G | No |  |
| Reno5 Pro 5G | Yes |  |
| Reno5 Pro+ 5G | Yes |  |
| Reno6 Pro+ 5G | No |  |
| Reno7 5G | Yes |  |
| Reno7 A | Yes |  |
| Reno7 Pro 5G | Yes |  |
| Reno7 SE 5G | Yes |  |
| Reno7 Z 5G | Yes |  |
| Reno8 5G | Yes |  |
| Reno8 Pro+ 5G | Yes |  |
| Reno8 T | Yes |  |
| Reno8 T 5G | Yes |  |
| Reno8 Z 5G | Yes |  |
| Reno9 5G | Yes |  |
| Reno9 A | Yes |  |
| Reno9 Pro 5G | Yes |  |
| Reno9 Pro+ 5G | Yes |  |
| 一加 Ace 2 Pro | Yes |  |
| 一加 Ace 竞速版 | Yes |  |

## Pepperl+Fuchs

| Model | Depth API | Notes |
|---|---|---|
| Smart-Ex 03 | Yes |  |
| Smart-Ex 203 | Yes |  |

## POCO

| Model | Depth API | Notes |
|---|---|---|
| POCO F4 | Yes |  |
| POCO F4 GT | Yes |  |
| POCO F5 | Yes |  |
| POCO F5 Pro | Yes |  |
| Poco F7 | Yes |  |
| POCO F8 Pro | Yes |  |
| POCO F9 Pro | Yes |  |
| POCO F9 Ultra | Yes |  |
| POCO M2 Pro | No |  |
| POCO M4 Pro | Yes |  |
| POCO M7 Pro 5G | Yes |  |
| POCO M8 5G | Yes |  |
| POCO M8 Pro 5G | Yes |  |
| POCO X2 | No |  |
| POCO X3 | No |  |
| POCO X3 NFC | No |  |
| POCO X3 Pro | Yes |  |
| POCO X4 GT | Yes |  |
| POCO X4 Pro 5G | Yes |  |
| POCO X5 Pro 5G | Yes |  |
| POCO X7 Pro | Yes |  |
| POCO X8 Pro | Yes |  |
| Pocophone F1 | Yes |  |

## Point Mobile

| Model | Depth API | Notes |
|---|---|---|
| MF52e | Yes |  |
| PM95 | Yes |  |

## Rakuten

| Model | Depth API | Notes |
|---|---|---|
| Hand5G | Yes |  |

## realme

| Model | Depth API | Notes |
|---|---|---|
| 10 Pro+ 5G | No |  |
| 5 | No |  |
| 5 Pro | No |  |
| 6 | No |  |
| 6 Pro | No |  |
| 7 | No |  |
| 7 Pro | No |  |
| 7i | No |  |
| 8 Pro | No |  |
| Narzo 20 Pro | No |  |
| Narzo 60x 5G | Yes |  |
| NARZO 70 5G | Yes |  |
| NARZO 70 Pro 5G | Yes |  |
| Q | No |  |
| Q2 Pro 5G | No |  |
| Q3 5G | No |  |
| Q3 Pro Play | No |  |
| realme 10 Pro 5G | Yes |  |
| realme 10 Pro+ 5G | Yes |  |
| realme 11 5G | Yes |  |
| realme 11 Pro 5G | Yes |  |
| realme 11 Pro+ | Yes |  |
| realme 11 Pro+ 5G | Yes |  |
| realme 11x 5G | Yes |  |
| realme 12+ 5G | Yes |  |
| realme 13 5G | Yes |  |
| realme 13 Pro 5G | Yes |  |
| realme 13+ 5G | Yes |  |
| realme 14 5G | Yes |  |
| realme 14 Pro 5G | Yes |  |
| realme 14 Pro+ 5G | Yes |  |
| realme 15 5G | Yes |  |
| realme 15 Pro 5G | Yes |  |
| realme 15T | Yes |  |
| realme 16 5G | Yes |  |
| realme 16 Pro 5G | Yes |  |
| realme 16 Pro+ 5G | Yes |  |
| realme 8 5G | No |  |
| realme 9 5G | Yes |  |
| realme 9 Pro 5G | Yes |  |
| realme 9 Pro+ | Yes |  |
| realme C63 5G | Yes |  |
| realme GT 2 Pro | Yes |  |
| realme GT 3 240W | Yes |  |
| realme GT 5 | Yes |  |
| realme GT 5 240W | Yes |  |
| realme GT 5G | No |  |
| realme GT 7 Pro | Yes |  |
| realme GT 7T | Yes |  |
| realme GT Explorer Master Edition | Yes |  |
| realme GT Neo | Yes |  |
| realme GT Neo 3 | Yes |  |
| realme GT Neo 3 150W | Yes |  |
| realme GT Neo 3T | Yes |  |
| realme GT Neo 5 | Yes |  |
| realme GT Neo 5 240W | Yes |  |
| realme GT Neo5 | Yes |  |
| realme NARZO 70 Turbo 5G | Yes |  |
| realme P1 5G | Yes |  |
| realme P1 Speed 5G | Yes |  |
| realme P3 5G | Yes |  |
| realme P3 Pro 5G | Yes |  |
| realme P3 Ultra 5G | Yes |  |
| realme P4 Power 5G | Yes |  |
| realme P4 Pro 5G | Yes |  |
| realme P4s 5G | Yes |  |
| realme v15 5G | No |  |
| realme V5 5G | No |  |
| RMX3771 | Yes |  |
| RMX5061 | Yes |  |
| RMX5200 | Yes |  |
| RMX5210 | Yes |  |
| V5 5G | No |  |
| X | No |  |
| X Lite | No |  |
| X2 | No |  |
| X2 Pro | No |  |
| X3 | No |  |
| X3 Super Zoom | No |  |
| X50 Pro | No |  |
| X50 Pro Player | No |  |
| X50t 5G | No |  |
| X7 5G | No |  |
| X7 Pro 5G | No |  |
| XT | No |  |
| 真我 16 Pro+ 5G | Yes |  |
| 真我 P4 Power 5G | Yes |  |
| 真我10 Pro | Yes |  |
| 真我11 Pro+ | Yes |  |
| 真我13 Pro | Yes |  |
| 真我13 Pro+ | Yes |  |
| 真我14 | Yes |  |
| 真我14 Pro | Yes |  |
| 真我14 Pro+ | Yes |  |
| 真我15 | Yes |  |
| 真我15 Pro | Yes |  |
| 真我15T | Yes |  |
| 真我GT | No |  |
| 真我GT6 | Yes |  |
| 真我GT7 | Yes |  |
| 真我GT7 Pro | Yes |  |
| 真我GT8 | Yes |  |
| 真我Neo7 | Yes |  |
| 真我Neo7 SE | Yes |  |
| 真我Neo7 Turbo | Yes |  |
| 真我Neo7x | Yes |  |
| 真我Neo8 | Yes |  |
| 真我V13 5G | No |  |
| 真我V50 | Yes |  |
| 真我V50s | Yes |  |

## Redmi

| Model | Depth API | Notes |
|---|---|---|
| Redmi 10X 4G | No |  |
| REDMI K100 Pro | Yes |  |
| REDMI K100 Pro Max | Yes |  |
| Redmi K20 | No |  |
| Redmi K20 Pro | No |  |
| Redmi K30 | No | 4G version only |
| Redmi K30 Pro | No |  |
| Redmi K40 | Yes |  |
| Redmi K40 Gaming | No |  |
| Redmi K40 Pro/Pro+ | No |  |
| Redmi K40S | Yes |  |
| Redmi K50 5G | Yes |  |
| Redmi K50G | Yes |  |
| Redmi K50i | Yes |  |
| Redmi K60 | Yes |  |
| Redmi K60 Ultra | Yes |  |
| Redmi Note 10 | Yes |  |
| Redmi Note 10 5G | Yes |  |
| Redmi Note 10 Pro | No |  |
| Redmi Note 10 Pro Max | Yes |  |
| Redmi Note 10S | No |  |
| Redmi Note 11 | Yes |  |
| Redmi Note 11 Pro | Yes |  |
| Redmi Note 11 Pro 5G | Yes |  |
| Redmi Note 11 Pro+ | Yes |  |
| Redmi Note 11 Pro+ 5G | Yes |  |
| Redmi Note 11E Pro | Yes |  |
| Redmi Note 11S | Yes |  |
| Redmi Note 11S 5G | Yes |  |
| Redmi Note 11T Pro | Yes |  |
| Redmi Note 11T Pro+ | Yes |  |
| Redmi Note 12 DISCOVERY EDITION | Yes |  |
| Redmi Note 12 Pro | Yes |  |
| Redmi Note 12 Pro Speed | Yes |  |
| Redmi Note 12 Pro+ 5G | Yes |  |
| Redmi Note 12 Turbo | Yes |  |
| Redmi Note 13 Pro+ | Yes |  |
| Redmi Note 14 | Yes |  |
| Redmi Note 14 5G | Yes |  |
| REDMI Note 15 | Yes |  |
| REDMI Note 15 5G | Yes |  |
| REDMI Note 15 Pro | Yes |  |
| REDMI Note 15 Pro 5G | Yes |  |
| REDMI Note 15 Pro+ | Yes |  |
| REDMI Note 15 Pro+5G | Yes |  |
| REDMI Note 15 SE 5G | Yes |  |
| Redmi Note 7 | No | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| Redmi Note 7 Pro | No |  |
| Redmi Note 8 | No |  |
| Redmi Note 8 Pro | No |  |
| Redmi Note 8T | No |  |
| Redmi Note 9 | No |  |
| Redmi Note 9 (5G) | Yes |  |
| Redmi Note 9 Pro | No |  |
| Redmi Note 9 Pro Max | No |  |
| Redmi Note 9S | No |  |
| Redmi Pad 2 4G | Yes |  |
| REDMI Pad 2 9.7 4G | Yes |  |
| Redmi Pad 2 Pro 5G | Yes |  |
| REDMI Pad 2 SE 4G | Yes |  |
| Redmi Pad 2 Wi-Fi + Cellular | Yes |  |
| Redmi Pad Pro | Yes |  |
| Redmi Pad Pro 5G | Yes |  |
| REDMI Turbo 4 Pro | Yes |  |

## Samsung

| Model | Depth API | Notes |
|---|---|---|
| Galaxy A13 5G | No |  |
| Galaxy A14 5G | No |  |
| Galaxy A15 5G | Yes |  |
| Galaxy A16 5G | Yes |  |
| Galaxy A17 5G | Yes |  |
| Galaxy A20 | No |  |
| Galaxy A20e | No |  |
| Galaxy A20s | No |  |
| Galaxy A22 | No |  |
| Galaxy A22 5G | No |  |
| Galaxy A23 | No |  |
| Galaxy A23 5G | No |  |
| Galaxy A24 | No |  |
| Galaxy A25 5G | No |  |
| Galaxy A26 5G | Yes |  |
| Galaxy A27 5G | Yes |  |
| Galaxy A3 (2017) | No | Requires Android 8.0 or later; ARCore always runs with auto focus mode enabled on the rear facing camera; Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| Galaxy A30 | No |  |
| Galaxy A30s | No |  |
| Galaxy A31 | No |  |
| Galaxy A32 | No |  |
| Galaxy A32 5G | No |  |
| Galaxy A33 5G | No |  |
| Galaxy A34 5G | No |  |
| Galaxy A35 5G | Yes |  |
| Galaxy A36 5G | Yes |  |
| Galaxy A37 5G | Yes |  |
| Galaxy A40 | No |  |
| Galaxy A41 | No |  |
| Galaxy A42 5G | Yes |  |
| Galaxy A5 (2017) | No | Supports multiple GPU texture resolutions - 1440x1080, 960x720, 480p |
| Galaxy A50 | No | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| Galaxy A50s | No | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| Galaxy A51 | No |  |
| Galaxy A51 5G | Yes |  |
| Galaxy A52 | Yes |  |
| Galaxy A52 5G | Yes |  |
| Galaxy A52s 5G | Yes |  |
| Galaxy A53 5G | Yes |  |
| Galaxy A54 5G | Yes |  |
| Galaxy A55 5G | Yes |  |
| Galaxy A56 5G | Yes |  |
| Galaxy A57 5G | Yes |  |
| Galaxy A6 (2018) | No |  |
| Galaxy A60 | No |  |
| Galaxy A7 (2017) | No | Some models only support OpenGL ES 3.0 and earlier |
| Galaxy A7 (2018) | No | Some models only support OpenGL ES 3.0 and earlier; Requires Android 9.0 or later |
| Galaxy A70 | No |  |
| Galaxy A70s | No | Requires Android 10 or later |
| Galaxy A71 | No |  |
| Galaxy A71 5G | Yes |  |
| Galaxy A72 | Yes |  |
| Galaxy A73 5G | Yes |  |
| Galaxy A8 | No |  |
| Galaxy A8+ (2018) | No |  |
| Galaxy A80 | Yes | Supports time-of-flight (ToF) hardware depth sensor |
| Galaxy A90 5G | Yes |  |
| Galaxy Buddy3 | Yes |  |
| Galaxy Buddy4 | Yes |  |
| Galaxy Buddy5 | Yes |  |
| Galaxy F14 5G | Yes |  |
| Galaxy F15 5G | Yes |  |
| Galaxy F17 5G | Yes |  |
| Galaxy F22 | No |  |
| Galaxy F23 5G | No |  |
| Galaxy F34 5G | Yes |  |
| Galaxy F36 5G | Yes |  |
| Galaxy F41 | No |  |
| Galaxy F42 5G / Wide5 | No |  |
| Galaxy F54 5G | Yes |  |
| Galaxy F56 5G | Yes |  |
| Galaxy F62 | No |  |
| Galaxy F70 5G | Yes |  |
| Galaxy F70 Pro 5G | Yes |  |
| Galaxy Fold | Yes |  |
| Galaxy J5 (2017) (SM-J530) | No | SM-J530 models; Some models only support OpenGL ES 3.0 and earlier; Supports multiple GPU texture resolutions - 960x720, 480p |
| Galaxy J5 Pro (SM-J530) | No | SM-J530 models; Some models only support OpenGL ES 3.0 and earlier; Supports multiple GPU texture resolutions - 960x720, 480p |
| Galaxy J7 (2017) (SM-J730) | No | SM-J730 models; Some models only support OpenGL ES 3.0 and earlier; Certain models only support OpenGL ES 3.1 and earlier |
| Galaxy J7 Pro (SM-J730) | No | SM-J730 models; Some models only support OpenGL ES 3.0 and earlier; Certain models only support OpenGL ES 3.1 and earlier |
| Galaxy Jump3 | Yes |  |
| Galaxy Jump4 | Yes |  |
| Galaxy Jump5 | Yes |  |
| Galaxy M14 5G | Yes |  |
| Galaxy M15 5G | Yes |  |
| Galaxy M16 5G | Yes |  |
| Galaxy M16 5G. | Yes |  |
| Galaxy M17 5G | Yes |  |
| Galaxy M20 | No | Requires Android 10 or later |
| Galaxy M21 | No |  |
| Galaxy M22 | No |  |
| Galaxy M23 5G | No |  |
| Galaxy M30s | No |  |
| Galaxy M31 | No |  |
| Galaxy M31s | No |  |
| Galaxy M32 | No |  |
| Galaxy M33 5G | No |  |
| Galaxy M34 5G | Yes |  |
| Galaxy M35 5G | Yes |  |
| Galaxy M36 5G | Yes |  |
| Galaxy M36 5G. | Yes |  |
| Galaxy M47 5G | Yes |  |
| Galaxy M51 | No |  |
| Galaxy M52 5G | Yes |  |
| Galaxy M53 5G | Yes |  |
| Galaxy M54 5G | Yes |  |
| Galaxy M56 5G | Yes |  |
| Galaxy M62 | No |  |
| Galaxy Note10 | Yes | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| Galaxy Note10 5G | Yes | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| Galaxy Note10 Lite | Yes |  |
| Galaxy Note10+ | Yes | Supports multiple GPU texture resolutions - 1080p, 720p, 480p; Supports time-of-flight (ToF) hardware depth sensor |
| Galaxy Note10+ 5G | Yes | Supports multiple GPU texture resolutions - 1080p, 720p, 480p; Supports time-of-flight (ToF) hardware depth sensor |
| Galaxy Note20 5G | Yes |  |
| Galaxy Note20 Ultra 5G | Yes |  |
| Galaxy Note8 | Yes | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| Galaxy Note9 | Yes |  |
| Galaxy Quantum2 | Yes |  |
| Galaxy Quantum3 | Yes |  |
| Galaxy Quantum5 | Yes |  |
| Galaxy Quantum6 | Yes |  |
| Galaxy Quantum7 | Yes |  |
| Galaxy S10 5G | Yes | Supports multiple GPU texture resolutions - 1080p, 720p, 480p; Supports time-of-flight (ToF) hardware depth sensor |
| Galaxy S10 Exynos | Yes | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| Galaxy S10 Lite | Yes |  |
| Galaxy S10 Qualcomm | Yes | Supports multiple GPU texture resolutions - 1440x1080, 1280x960, 480p |
| Galaxy S10+ Exynos | Yes | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| Galaxy S10+ Qualcomm | Yes | Supports multiple GPU texture resolutions - 1440x1080, 1280x960, 480p |
| Galaxy S10e Exynos | Yes | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| Galaxy S10e Qualcomm | Yes | Supports multiple GPU texture resolutions - 1440x1080, 1280x960, 480p |
| Galaxy S20 | Yes |  |
| Galaxy S20 5G | Yes |  |
| Galaxy S20 FE 5G | No |  |
| Galaxy S20 FE. | Yes |  |
| Galaxy S20 Ultra 5G | Yes | Supports time-of-flight (ToF) hardware depth sensor |
| Galaxy S20+ | Yes | Supports time-of-flight (ToF) hardware depth sensor |
| Galaxy S20+ 5G | Yes | Supports time-of-flight (ToF) hardware depth sensor |
| Galaxy S21 5G | Yes |  |
| Galaxy S21 FE 5G | Yes |  |
| Galaxy S21 Ultra 5G | Yes |  |
| Galaxy S21+ 5G | Yes |  |
| Galaxy S22 5G | Yes |  |
| Galaxy S22 Ultra 5G | Yes |  |
| Galaxy S22+ 5G | Yes |  |
| Galaxy S23 | Yes |  |
| Galaxy S23 FE | Yes |  |
| Galaxy S23 Ultra | Yes |  |
| Galaxy S23+ | Yes |  |
| Galaxy S24 | Yes |  |
| Galaxy S24 FE | Yes |  |
| Galaxy S24 Ultra | Yes |  |
| Galaxy S24+ | Yes |  |
| Galaxy S25 | Yes |  |
| Galaxy S25 Edge | Yes |  |
| Galaxy S25 FE | Yes |  |
| Galaxy S25 Ultra | Yes |  |
| Galaxy S25+ | Yes |  |
| Galaxy S26 | Yes |  |
| Galaxy S26 FE | Yes |  |
| Galaxy S26 Ultra | Yes |  |
| Galaxy S26+ | Yes |  |
| Galaxy S7 | No | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| Galaxy S7 edge | No | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| Galaxy S8 | Yes | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| Galaxy S8+ | Yes | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| Galaxy S9 Exynos | Yes | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| Galaxy S9 Qualcomm | Yes | Supports multiple GPU texture resolutions - 2048x1536, 1280x960, 480p |
| Galaxy S9+ Exynos | Yes | Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| Galaxy S9+ Qualcomm | Yes | Supports multiple GPU texture resolutions - 2048x1536, 1280x960, 480p |
| Galaxy Tab A11 Plus | Yes |  |
| Galaxy Tab A11+ | Yes |  |
| Galaxy Tab A11+ 5G | Yes |  |
| Galaxy Tab A7 | No |  |
| Galaxy Tab A8 | No |  |
| Galaxy Tab A9+ | Yes |  |
| Galaxy Tab A9+ 5G | Yes |  |
| Galaxy Tab Active 3 | No |  |
| Galaxy Tab Active Pro | No |  |
| Galaxy Tab Active4 Pro 5G | Yes |  |
| Galaxy Tab Active5 | Yes |  |
| Galaxy Tab Active5 5G | Yes |  |
| Galaxy Tab Active5 Pro | Yes |  |
| Galaxy Tab Active5 Pro 5G | Yes |  |
| Galaxy Tab S10 FE | Yes |  |
| Galaxy Tab S10 FE 5G | Yes |  |
| Galaxy Tab S10 FE+ | Yes |  |
| Galaxy Tab S10 FE+ 5G | Yes |  |
| Galaxy Tab S10 Lite | Yes |  |
| Galaxy Tab S10 Lite 5G | Yes |  |
| Galaxy Tab S10 Ultra | Yes |  |
| Galaxy Tab S10 Ultra 5G | Yes |  |
| Galaxy Tab S10+ | Yes |  |
| Galaxy Tab S10+ 5G | Yes |  |
| Galaxy Tab S11 | Yes |  |
| Galaxy Tab S11 5G | Yes |  |
| Galaxy Tab S11 Ultra | Yes |  |
| Galaxy Tab S11 Ultra 5G | Yes |  |
| Galaxy Tab S12 Ultra | Yes |  |
| Galaxy Tab S12 Ultra 5G | Yes |  |
| Galaxy Tab S12+ | Yes |  |
| Galaxy Tab S12+ 5G | Yes |  |
| Galaxy Tab S3 | No | ARCore always runs with auto focus mode enabled on the rear facing camera |
| Galaxy Tab S4 | No | Supports multiple GPU texture resolutions - 1440x1080, 960x720, 480p |
| Galaxy Tab S5e | No |  |
| Galaxy Tab S6 | No |  |
| Galaxy Tab S6 Lite | No |  |
| Galaxy Tab S7 | Yes |  |
| Galaxy Tab S7 FE | Yes |  |
| Galaxy Tab S7 FE 5G | Yes |  |
| Galaxy Tab S7+ | Yes |  |
| Galaxy Tab S7+ Lite | Yes |  |
| Galaxy Tab S8 | Yes |  |
| Galaxy Tab S8 Ultra | Yes |  |
| Galaxy Tab S8+ | Yes |  |
| Galaxy Tab S9 | Yes |  |
| Galaxy Tab S9 5G | Yes |  |
| Galaxy Tab S9 FE | Yes |  |
| Galaxy Tab S9 FE 5G | Yes |  |
| Galaxy Tab S9 FE+ | Yes |  |
| Galaxy Tab S9 FE+ 5G | Yes |  |
| Galaxy Tab S9 Ultra | Yes |  |
| Galaxy Tab S9 Ultra 5G | Yes |  |
| Galaxy Tab S9+ | Yes |  |
| Galaxy Tab S9+ 5G | Yes |  |
| Galaxy Wide7 | Yes |  |
| Galaxy Wide8 | Yes |  |
| Galaxy Wide9 | Yes |  |
| Galaxy XCover Pro | No |  |
| Galaxy XCover6 Pro | No |  |
| Galaxy XCover7 | Yes |  |
| Galaxy XCover7 Pro | Yes |  |
| Galaxy Z Flip | Yes |  |
| Galaxy Z Flip 5G | Yes |  |
| Galaxy Z Flip3 5G | Yes |  |
| Galaxy Z Flip4 | Yes |  |
| Galaxy Z Flip5 | Yes |  |
| Galaxy Z Flip6 | Yes |  |
| Galaxy Z Flip7 | Yes |  |
| Galaxy Z Flip7 FE | Yes |  |
| Galaxy Z Flip8 | Yes |  |
| Galaxy Z Fold Special Edition | Yes |  |
| Galaxy Z Fold2 5G | Yes |  |
| Galaxy Z Fold3 5G | Yes |  |
| Galaxy Z Fold4. | Yes |  |
| Galaxy Z Fold5 | Yes |  |
| Galaxy Z Fold5. | Yes |  |
| Galaxy Z Fold6 | Yes |  |
| Galaxy Z Fold7 | Yes |  |
| Galaxy Z Fold7. | Yes |  |
| Galaxy Z Fold8 | Yes |  |
| Galaxy Z Fold8 Ultra | Yes |  |
| Galaxy Z TriFold | Yes |  |
| 心系天下 三星 W25 | Yes |  |
| 心系天下 三星 W25 Flip | Yes |  |
| 心系天下 三星 W26 | Yes |  |

## Sharp

| Model | Depth API | Notes |
|---|---|---|
| AQUOS R10 | Yes |  |
| AQUOS R11 | Yes |  |
| AQUOS R3 | Yes |  |
| AQUOS R5G | Yes | Supports time-of-flight (ToF) hardware depth sensor |
| AQUOS R6 | Yes |  |
| AQUOS R7 | Yes |  |
| AQUOS R8 | Yes |  |
| AQUOS R8 Pro | Yes |  |
| AQUOS R9 Pro | Yes |  |
| AQUOS sense10 | Yes |  |
| AQUOS sense3 | No |  |
| AQUOS sense3 basic | No |  |
| AQUOS sense3 plus | No |  |
| AQUOS sense4 | Yes |  |
| AQUOS sense4 basic | Yes |  |
| AQUOS sense4 lite | Yes |  |
| AQUOS sense4 plus | No |  |
| AQUOS sense5G | Yes |  |
| AQUOS sense6 | Yes |  |
| AQUOS sense6s | Yes |  |
| AQUOS sense7 | Yes |  |
| AQUOS sense7 Plus | Yes |  |
| AQUOS sense8 | Yes |  |
| AQUOS sense9 | Yes |  |
| AQUOS wish5 | Yes |  |
| AQUOS wish5s | Yes |  |
| AQUOS wish6 | Yes |  |
| AQUOS zero2 | Yes |  |
| AQUOS zero5G basic | Yes |  |
| AQUOS zero5G basic DX | Yes |  |
| AQUOS zero6 | Yes |  |
| Leitz Phone1 | Yes |  |
| Leitz Phone2 | Yes |  |
| S7 | No |  |

## Sony

| Model | Depth API | Notes |
|---|---|---|
| Xperia 1 | Yes |  |
| Xperia 1 II | Yes |  |
| Xperia 1 III | Yes |  |
| Xperia 1 IV | Yes |  |
| Xperia 1 Professional Edition | No |  |
| Xperia 1 V | Yes |  |
| Xperia 1 VII | Yes |  |
| Xperia 1 VIII | Yes |  |
| Xperia 10 III | Yes |  |
| Xperia 10 IV | Yes |  |
| Xperia 10 V | Yes |  |
| Xperia 10 VII | Yes |  |
| Xperia 10 VIII | Yes |  |
| Xperia 5 | Yes |  |
| Xperia 5 II | Yes |  |
| Xperia 5 III | Yes |  |
| Xperia 5 IV | Yes |  |
| Xperia 5 V | Yes |  |
| Xperia Ace III | Yes |  |
| Xperia PRO | Yes |  |
| Xperia PRO-I | Yes |  |
| Xperia XZ Premium | No | Requires Android 8.0 or later; Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| Xperia XZ1 | No | Requires Android 8.0 or later |
| Xperia XZ1 Compact | No | Requires Android 8.0 or later |
| Xperia XZ2 | Yes | Requires Android 8.0 or later with software update after Aug 2018 (security patch level 2018-08-05 or later) |
| Xperia XZ2 Compact | Yes | Requires Android 8.0 or later with software update after Aug 2018 (security patch level 2018-08-05 or later) |
| Xperia XZ2 Premium | Yes | Requires Android 8.0 or later with software update after Aug 2018 (security patch level 2018-08-05 or later) |
| Xperia XZ3 | Yes |  |

## TCL

| Model | Depth API | Notes |
|---|---|---|
| 10 5G UW | Yes |  |

## TECNO

| Model | Depth API | Notes |
|---|---|---|
| Camon 12 Pro | No |  |
| Camon 16 Premier | No |  |
| Camon 16 Pro | No |  |
| Camon 17 Pro | No |  |
| Camon 18 Premier | Yes |  |
| Camon 18P | Yes |  |
| Camon 19 Pro | Yes |  |
| Camon 19 Pro 5G | Yes |  |
| Camon 20 Premier 5G | Yes |  |
| Camon 20 Pro | Yes |  |
| Camon 20 Pro 5G | Yes |  |
| Camon 20s Pro 5G | Yes |  |
| Camon 30s | No |  |
| Camon 30s Pro | Yes |  |
| Camon 40 | Yes |  |
| Camon 40 5G | Yes |  |
| Camon 40 Premiere 5G | Yes |  |
| Camon 40 Pro | Yes |  |
| GT 30 Pro | Yes |  |
| Infinix Zero 40 | Yes |  |
| Infinix Zero 40 5G | Yes |  |
| Infinix ZERO Flip | Yes |  |
| itel P65 | Yes |  |
| Megapad 11 | Yes |  |
| Note 50X 5G | Yes |  |
| Phantom 9 | No |  |
| Phantom V Flip 5G | Yes |  |
| Phantom V Fold | Yes |  |
| Phantom V Fold2 5G | Yes |  |
| Phantom X | Yes |  |
| Phantom X2 5G | Yes |  |
| Phantom X2 Pro 5G | Yes |  |
| Pova 2 | No |  |
| Pova 4 | Yes |  |
| Pova 4 Pro | Yes |  |
| Pova 5 | Yes |  |
| Pova 5 Pro 5G | Yes |  |
| Pova 5G | No |  |
| Pova 7 5G | Yes |  |
| Pova 7 Neo | Yes |  |
| Pova 7 Pro 5G | Yes |  |
| Pova 7 Ultra 5G | Yes |  |
| Pova Curve 5G | Yes |  |
| SPARK 20 Pro+ | Yes |  |
| SPARK 30 Pro | Yes |  |
| SPARK 40 Pro+ | Yes |  |
| SPARK Slim 5G | Yes |  |
| TECNO CAMON 50 Pro 5G | Yes |  |
| TECNO CAMON 50 Ultra 5G | Yes |  |
| TECNO CAMON Slim | Yes |  |
| TECNO CAMON Slim 5G | Yes |  |
| TECNO POVA 8 5G | Yes |  |
| TECNO POVA 8 Pro 5G | Yes |  |
| TECNO POVA Curve 2 5G | Yes |  |

## UMX

| Model | Depth API | Notes |
|---|---|---|
| U3AR | No | Device without Front Camera, doesn't support ARCore Front Camera |

## Uniscope

| Model | Depth API | Notes |
|---|---|---|
| DT610 | Yes |  |

## Unitech

| Model | Depth API | Notes |
|---|---|---|
| EA660 | Yes |  |
| NAUTIZ X21 | Yes |  |
| Nordalp-X21-Pro | Yes |  |
| PA768 | Yes |  |
| PA768e | Yes |  |
| RT112 | Yes |  |
| Spectra MobileMapper6 | Yes |  |
| Trimble TDC6 | Yes |  |

## Vinsmart

| Model | Depth API | Notes |
|---|---|---|
| Aris Pro | No |  |
| Live 4 | Yes |  |

## vivo

| Model | Depth API | Notes |
|---|---|---|
| 2061 | Yes |  |
| I2009 | No |  |
| I2011 | Yes |  |
| I2012 | Yes |  |
| I2017 | Yes |  |
| I2202 | Yes |  |
| I2505 | Yes |  |
| iQOO | No |  |
| iQOO 10 | Yes |  |
| iQOO 10 Pro | Yes |  |
| iQOO 11 | Yes |  |
| iQOO 11 Pro | Yes |  |
| iQOO 11s | Yes |  |
| iQOO 12 | Yes |  |
| iQOO 12 Pro | Yes |  |
| iQOO 13 | Yes |  |
| iQOO 15 Ultra | Yes |  |
| iQOO 15R | Yes |  |
| iQOO 15T | Yes |  |
| iQOO 16 | Yes |  |
| iQOO 3 4G | No |  |
| iQOO 3 5G | No |  |
| iQOO 5 5G | No |  |
| iQOO 5 Pro 5G | No |  |
| iQOO 8 Pro | Yes |  |
| iQOO 9 Pro | Yes |  |
| iQOO 9 SE | Yes |  |
| iQOO 9T | Yes |  |
| iQOO Neo 10R | Yes |  |
| iQOO Neo10 | Yes |  |
| iQOO Neo10 Pro+ | Yes |  |
| iQOO Neo11 | Yes |  |
| iQOO Neo11 至尊版 | Yes |  |
| iQOO Neo12 | Yes |  |
| iQOO Neo3 5G | No |  |
| iQOO Neo5 SE | Yes |  |
| iQOO Neo5S | Yes |  |
| iQOO Neo6 | Yes |  |
| iQOO Neo6 SE | Yes |  |
| iQOO Neo7 | Yes |  |
| iQOO Neo7 Pro | Yes |  |
| iQOO Neo7 SE | Yes |  |
| iQOO Neo7 竞速版 | Yes |  |
| iQOO Neo8 | Yes |  |
| iQOO Neo8 Pro | Yes |  |
| iQOO Neo9 | Yes |  |
| iQOO Neo9 Pro | Yes |  |
| iQOO Neo9S Pro+ | Yes |  |
| iQOO Pad | Yes |  |
| iQOO Pad Ultra | Yes |  |
| iQOO U1 | No |  |
| iQOO Z10 5G | Yes |  |
| iQOO Z10 Turbo | Yes |  |
| iQOO Z10R 5G | Yes |  |
| iQOO Z10x | Yes |  |
| iQOO Z10X 5G | Yes |  |
| iQOO Z11 | Yes |  |
| iQOO Z11 5G | Yes |  |
| iQOO Z11 Turbo | Yes |  |
| iQOO Z11S | Yes |  |
| iQOO Z11x | Yes |  |
| iQOO Z11x 5G | Yes |  |
| iQOO Z1x | No |  |
| iQOO Z3 | No |  |
| iQOO Z5 6000mAh | Yes |  |
| iQOO Z7 | Yes |  |
| iQOO Z7 5G | Yes |  |
| iQOO Z7 Pro 5G | Yes |  |
| iQOO Z7s 5G | Yes |  |
| iQOO Z7x | Yes |  |
| iQOO Z7x 5G | Yes |  |
| iQOO Z8x | Yes |  |
| iQOO Z9s 5G | Yes |  |
| iQOO Z9s Pro 5G | Yes |  |
| JOVI T1 5G | Yes |  |
| JOVI V70 5G | Yes |  |
| JOVI V80 | Yes |  |
| JOVI X300 FE | Yes |  |
| JOVI X300 Ultra | Yes |  |
| JOVI Y600 Pro 5G | Yes |  |
| Nex 3 | No | Supports multiple GPU texture resolutions - 1440x1080, 1280x960, 480p |
| NEX 3 4G/5G | No |  |
| Nex 3 5G | No | Supports multiple GPU texture resolutions - 1440x1080, 1280x960, 480p |
| NEX Dual Display Edition | No |  |
| NEX S | No |  |
| Pad2 | Yes |  |
| Pad5 | No |  |
| Pad5 Pro | Yes |  |
| Pad6 Pro | Yes |  |
| PD2436 | Yes |  |
| PD2502 | Yes |  |
| PD2506 | Yes |  |
| PD2509 | Yes |  |
| S15 Pro | Yes |  |
| S16 | Yes |  |
| S16 Pro | Yes |  |
| S17 | Yes |  |
| S17 Pro | Yes |  |
| S17e | Yes |  |
| S18 | Yes |  |
| S18e | Yes |  |
| S2 | Yes |  |
| S20 | Yes |  |
| S20 Pro | Yes |  |
| S30 | Yes |  |
| S30 Pro Mini | Yes |  |
| S50 | Yes |  |
| S50 Pro mini | Yes |  |
| S60 | Yes |  |
| S60 元气版 | Yes |  |
| S60t | Yes |  |
| S7 5G | No |  |
| T2 5G | Yes |  |
| T2 Pro 5G | Yes |  |
| T3 Pro 5G | Yes |  |
| T4 5G | Yes |  |
| T4 Pro | Yes |  |
| T4 Ultra | Yes |  |
| T4x 5G | Yes |  |
| T5 5G | Yes |  |
| T5 Pro 5G | Yes |  |
| T5x 5G | Yes |  |
| V17 | No |  |
| V20 | No |  |
| V20 Pro | No |  |
| V2041 | Yes |  |
| V2045 | Yes |  |
| V2046 | Yes |  |
| V2046A | No |  |
| V2047A | No |  |
| V2050 | Yes |  |
| V2056A | No |  |
| V2073A | No |  |
| V2105 | Yes |  |
| V2124 | Yes |  |
| V2126 | Yes |  |
| V2130 | Yes |  |
| V2132 | Yes |  |
| V2133A | Yes |  |
| V2148A | Yes |  |
| V2163A | Yes |  |
| V2171A | No |  |
| V2172A | No |  |
| V2202 | Yes |  |
| V2203A | Yes |  |
| V2220A | Yes |  |
| V2282A | Yes |  |
| V2314A | Yes |  |
| V2417A | Yes |  |
| V25 | Yes |  |
| V25 Pro | Yes |  |
| V2505A | Yes |  |
| V25e | Yes |  |
| V27 Pro | Yes |  |
| V27e | Yes |  |
| V29 | Yes |  |
| V29 Lite 5G | Yes |  |
| V29e | Yes |  |
| V29e 5G | Yes |  |
| V30 Lite 5G | Yes |  |
| V30 SE | Yes |  |
| V40 Lite 5G | Yes |  |
| V40 Pro | Yes |  |
| V40 SE 5G | Yes |  |
| V40e | Yes |  |
| V50 | Yes |  |
| V50 Lite 5G | Yes |  |
| V50e | Yes |  |
| V60 Lite 5G | Yes |  |
| V60e | Yes |  |
| V70 | Yes |  |
| V70 Elite | Yes |  |
| V70 FE | Yes |  |
| V70 Lite | Yes |  |
| V70 Lite 5G | Yes |  |
| V80 | Yes |  |
| V80 Lite 5G | Yes |  |
| X Flip | Yes |  |
| X Fold | Yes |  |
| X Fold2 | Yes |  |
| X Fold6 | Yes |  |
| X Note | No |  |
| X100 | Yes |  |
| X100 Pro | Yes |  |
| X200 | Yes |  |
| X200 FE | Yes |  |
| X200 Pro | Yes |  |
| X200 Pro mini | Yes |  |
| X200 Pro 卫星通信版 | Yes |  |
| X200 Ultra | Yes |  |
| X200T | Yes |  |
| X23 | No |  |
| X300 | Yes |  |
| X300 E | Yes |  |
| X300 FE | Yes |  |
| X300 Pro | Yes |  |
| X300 Ultra | Yes |  |
| X300 Ultra 卫星通信版 | Yes |  |
| X300s | Yes |  |
| X50 | No |  |
| X50 5G | No |  |
| X50 Pro | No |  |
| X50 Pro+ | No |  |
| X500 E | Yes |  |
| X500 Pro | Yes |  |
| X500 Pro Max | Yes |  |
| X500 Pro Max 卫星通信版 | Yes |  |
| X50e 5G | No |  |
| X60 Pro | Yes |  |
| X80 | Yes |  |
| X80 Lite 5G | Yes |  |
| X80 Pro | Yes |  |
| X80 Pro 天玑9000版 | Yes |  |
| X90 | Yes |  |
| X90 Pro | Yes |  |
| X90 Pro+ | Yes |  |
| Y100 | Yes |  |
| Y100 5G | Yes |  |
| Y100A | Yes |  |
| Y200 5G | Yes |  |
| Y200e 5G | Yes |  |
| Y27 5G | Yes |  |
| Y300 | Yes |  |
| Y300 Pro | Yes |  |
| Y31t 5G | Yes |  |
| Y36 5G | Yes |  |
| Y39 5G | Yes |  |
| Y400 5G | Yes |  |
| Y400 Pro 5G | Yes |  |
| Y500 | Yes |  |
| Y500 Pro | Yes |  |
| Y51 Pro 5G | Yes |  |
| Y51s | No |  |
| Y600 Pro | Yes |  |
| Y600 Pro AI版 | Yes |  |
| Y600 Turbo | Yes |  |
| Y600k Turbo | Yes |  |
| Y6m | Yes |  |
| Y70s | No |  |
| Y78 5G | Yes |  |
| Y78+ | No |  |

## Wiko

| Model | Depth API | Notes |
|---|---|---|
| View 3 Pro | No |  |

## Xiaomi

| Model | Depth API | Notes |
|---|---|---|
| Leitzphone powered by Xiaomi | Yes |  |
| Mi 10 | No |  |
| Mi 10 Lite | Yes |  |
| Mi 10 Lite 5G | Yes |  |
| Mi 10 Lite Zoom | No |  |
| Mi 10 Pro | Yes |  |
| Mi 10 Ultra | No |  |
| Mi 10i | Yes |  |
| Mi 10T Pro | No |  |
| Mi 11 | No |  |
| Mi 11 Pro | Yes |  |
| Mi 11 Ultra | Yes | Supports 60 fps camera capture frame rate on the rear-facing camera; Supports multiple GPU texture resolutions - 1080p, 720p, 480p |
| Mi 8 | No |  |
| Mi 8 SE | No |  |
| Mi 9 | No |  |
| Mi 9 Lite | No |  |
| Mi 9 SE | No |  |
| Mi A3 | No |  |
| Mi Mix 2S | No | Supports multiple GPU texture resolutions - 1920x1440, 1280x960, 480p |
| Mi Mix 3 | No |  |
| Mi Note 10 | No |  |
| Mi Note 10 Lite | No |  |
| Mi Note 11 Lite | No |  |
| Mi Note 11 Lite 5G | Yes |  |
| Pad 5 | Yes |  |
| Pad 6 | Yes |  |
| Xiaomi 11T | Yes |  |
| Xiaomi 12 | Yes |  |
| Xiaomi 12 Lite | Yes |  |
| Xiaomi 12 Pro | Yes |  |
| Xiaomi 12T Pro | Yes |  |
| Xiaomi 12X | Yes |  |
| Xiaomi 13 | Yes |  |
| Xiaomi 13 Pro | Yes |  |
| Xiaomi 13 Ultra | Yes |  |
| Xiaomi 13T | Yes |  |
| Xiaomi 14T | Yes |  |
| Xiaomi 14T Pro | Yes |  |
| Xiaomi 15 | Yes |  |
| Xiaomi 15 Ultra | Yes |  |
| Xiaomi 17 | Yes |  |
| Xiaomi 17 Pro | Yes |  |
| Xiaomi 17 Pro Max | Yes |  |
| Xiaomi 17T | Yes |  |
| Xiaomi 17T Pro | Yes |  |
| Xiaomi Pad 6S Pro 12.4 | Yes |  |
| Xiaomi Pad 8 | Yes |  |

## Zebra

| Model | Depth API | Notes |
|---|---|---|
| EC50 WLAN Enterprise Computer | Yes |  |
| EC55 WWAN Enterprise Computer | Yes |  |
| EM45 | Yes |  |
| ET401 | Yes |  |
| ET40L 10" Enterprise Tablet | Yes |  |
| ET40S 8" Enterprise Tablet | Yes |  |
| ET45L 10" Enterprise Tablet | Yes |  |
| ET45S 8" Enterprise Tablet | Yes |  |
| ET51L 10" Enterprise Tablet | Yes |  |
| ET56 10" Enterprise Tablet | Yes |  |
| ET56L 10" Enterprise Tablet | Yes |  |
| ET56s 8" Enterprise Tablet | Yes |  |
| ET60 | Yes |  |
| ET65 | Yes |  |
| FR55 | Yes |  |
| HC20 | Yes |  |
| HC25 | Yes |  |
| HC50 | Yes |  |
| HC55 | Yes |  |
| MC20 | Yes |  |
| MC3400 | Yes |  |
| MC3450 | Yes |  |
| MC9400 | Yes |  |
| MC9450 | Yes |  |
| TC21 WLAN Touch Computer | No |  |
| TC22 | Yes |  |
| TC22R | Yes |  |
| TC26 WWAN Touch Computer | No |  |
| TC27 | Yes |  |
| TC501 | Yes |  |
| TC52 WLAN Touch Computer | No |  |
| TC52ax WLAN Touch Computer | Yes |  |
| TC52x WLAN Touch Computer | Yes |  |
| TC53 | Yes |  |
| TC53 WLAN Touch Computer | Yes |  |
| TC53E | Yes |  |
| TC57 WWAN Touch Computer | No |  |
| TC57x WWAN Touch Computer | Yes |  |
| TC58 | Yes |  |
| TC58 WWAN Touch Computer | Yes |  |
| TC58E | Yes |  |
| TC701 | Yes |  |
| TC72 WLAN Touch Computer | No |  |
| TC73 | Yes |  |
| TC77 WWAN Touch Computer | No |  |
| TC78 | Yes |  |

## ZTE

| Model | Depth API | Notes |
|---|---|---|
| A302ZT | Yes |  |
| A303ZT | Yes |  |
| A403ZT | Yes |  |
| A404ZT | Yes |  |
| A505ZT | Yes |  |
| Libero 5G | No |  |
| Libero 5G II | No |  |
| Libero 5G III | Yes |  |
| Lume Pad | Yes |  |
| nubia Neo 2 5G | Yes |  |
| nubia Pad 3D | Yes |  |
| nubia S2e | Yes |  |
| REDMAGIC 7Pro | Yes |  |
