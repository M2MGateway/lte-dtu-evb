# Network (MBIM)

## on Ubuntu

```bash
apt install usb-modeswitch libmbim-utils ppp
nmcli connection add type gsm ifname cdc-wdm0 con-name lte apn internet
```

## References

- <https://r-pi.cn/d/25-4bme909s-4glte-me909>
- <https://core.docs.ubuntu.com/en/stacks/network/network-manager/docs/configure-cellular-connections>
