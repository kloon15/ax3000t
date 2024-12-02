# Collection of OpenWrt patches for Xiaomi AX3000T

## [AN8855](./patches/AN8855-r241130.patch)

- Adds support for Airoha AN8855 switch
- Issue/PR: https://github.com/openwrt/openwrt/pull/16709

## [Foresee F35SQA002G](./patches/F35SQA002G.patch) and [Foresee F35SQA001G](./patches/F35SQA001G.patch)

- Adds support for Foresee F35SQA002G and F35SQA001G NANDs
- Issue/PR: https://github.com/openwrt/openwrt/pull/16915

## [SPI NAND use cache first](./patches/mtd-nand-spi-Use-write_cache-first.patch)

- Fixes random issues with Foresee NANDs
- Issue/PR: https://github.com/openwrt/openwrt/pull/16915#issuecomment-2487184967

## [NMBM fix for Winbond](./patches/Winbond-NMBM-fix.patch)

- Fixes `NMBM configuration mismatch` on Winbond NANDs
- Issue/PR: https://github.com/openwrt/openwrt/issues/16972

## [Remove ACK when TXS is lost](./patches/Remove-ACK-when-TXS-is-lost.patch)

- Should help with WiFi issues when connection is unreliable/too far away (UNVERIFIED)
- Issue/PR: https://github.com/openwrt/mt76/issues/922

## [Patch NVRAM params on boot](./patches/Patch-NVRAM-params-on-boot.patch)

- Prevents router from getting soft-bricked after 6 reboots
- Issue/PR: https://forum.openwrt.org/t/openwrt-support-for-xiaomi-ax3000t/180490/1373
