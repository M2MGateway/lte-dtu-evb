# Available module

## LTE modules

| Provider        | Connector   | Product Name              | Category  | Status |
| --------------- | ----------- | ------------------------- | --------- | ------ |
| Huawei          | M.2 (B Key) | ME909s                    | LTE CAT.4 |        |
| Quectel         | M.2 (B Key) | [EM06][em06]              | LTE CAT.6 |        |
| Quectel         | Mini-PCIe   | [EC20 R2.1][ec20-r21]     | LTE CAT.4 | TESTED |
| Quectel         | Mini-PCIe   | [EC25][ec25]              | LTE CAT.4 |        |
| Quectel         | Mini-PCIe   | [EC200S-CN][ec200s-cn]    | LTE CAT.1 |        |
| Quectel         | Mini-PCIe   | [EC200T][ec200t]          | LTE CAT.4 | TESTED |
| Sierra Wireless | M.2 (B Key) | [AirPrime EM7455][em7455] | LTE CAT.6 |        |

[ec20-r21]: https://www.quectel.com/product/ec20r21minipcie.htm
[ec200s-cn]: https://www.quectel.com/cn/product/ec200s.htm
[ec200t]: https://www.quectel.com/cn/product/ec200t.htm
[ec25]: https://www.quectel.com/product/ec20r21minipcie.htm
[em06]: https://www.quectel.com/cn/product/em06.htm
[em7455]: https://www.sierrawireless.com/products-and-solutions/embedded-solutions/products/em7455/

## USB Wi-Fi dongle

| Company  | Name            | Standard            | Max speed | Driver    | Mode   | Status |
| -------- | --------------- | ------------------- | --------- | --------- | ------ | ------ |
| Broadcom | BCM43236        | Wi-Fi 4 (Dual band) | 300 Mbps  | brcmfmac  | STA    |        |
| MediaTek | MT7601          | Wi-Fi 4             | 300 Mbps  | mt76x0    | STA    | TESTED |
| MediaTek | MT7632          | Wi-Fi 5 + BT 4.0    | 866 Mbps  | mt76x0    | STA    |        |
| MediaTek | RT2571          | Wi-Fi 4             | 150 Mbps  | rt2500usb | STA    |        |
| MediaTek | RT2770          | Wi-Fi 4             | 300 Mbps  | rt2800usb | STA    |        |
| MediaTek | RT3070          | Wi-Fi 4             | 150 Mbps  | rt2x00    | STA    |        |
| MediaTek | RT3572          | Wi-Fi 4 (Dual band) | 300 Mbps  | rt2x00    | STA    |        |
| MediaTek | RT5572          | Wi-Fi 4 (Dual band) | 300 Mbps  | rt2x00    | STA    |        |
| Qualcomm | AR7010 + AR9280 | Wi-Fi 4 (Dual band) | 300 Mbps  | ar9170usb | STA/AP |        |
| Qualcomm | AR7010 + AR9287 | Wi-Fi 4             | 150 Mbps  | ar9170usb | STA/AP |        |
| Qualcomm | AR9271          | Wi-Fi 4             | 150 Mbps  | ar9170usb | STA/AP |        |
| Realtek  | RTL8187         | Wi-Fi 4             | 150 Mbps  | rtl8xxxu  | STA/AP |        |
| Realtek  | RTL8188         | Wi-Fi 4             | 150 Mbps  | rtl8xxxu  | STA/AP |        |
| Realtek  | RTL8191         | Wi-Fi 4             | 300 Mbps  | rtl8xxxu  | STA/AP |        |
| Realtek  | RTL8192         | Wi-Fi 4             | 300 Mbps  | rtl8xxxu  | STA/AP |        |
| Realtek  | RTL8723         | Wi-Fi 4 + BT 4.0    | 150 Mbps  | rtl8xxxu  | STA/AP |        |
| Realtek  | RTL8811         | Wi-Fi 5             | 866 Mbps  | rtl8xxxu  | STA    |        |
| Realtek  | RTL8812         | Wi-Fi 5             | 866 Mbps  | rtl8xxxu  | STA    |        |
| Realtek  | RTL8821         | Wi-Fi 5 + BT 4.2    | 866 Mbps  | rtl8xxxu  | STA    |        |

see <https://wireless.wiki.kernel.org/en/users/drivers>

see <https://elinux.org/RPi_USB_Wi-Fi_Adapters>
