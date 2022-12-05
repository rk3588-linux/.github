# RK3588 Linux

An implementation of all the necessary components to build, boot, and
install Linux on the RK3588 SoC. This includes writing the device
tree, device drivers, and Kernel configuration. This is meant to be a
learning experience on the ARM64 architecture, writing device drivers,
and what it takes to port arm64 based platforms to Linux.

## TODO
- [ ] Create minimal U-Boot Image
  - [ ] Create minimal DTS for RK3588 SoC
    - [ ] Add CPUs
    - [ ] Add Timer Device
    - [ ] Add Interrupt Controller Device
    - [ ] Add SDMMC Device
    - [ ] Add UART Device
  - [ ] Implement RK3588 Drivers
    - [ ] Write UART Driver
    - [ ] Write SDMMC Driver
-----
- [ ] Create minimal Linux Image
  - [ ] Create minimal DTS for RK3588 SoC
    - [ ] Add CPUs
    - [ ] Add Timer Device
    - [ ] Add Interrupt Controller Device
    - [ ] Add UART Device
  - [ ] Implement RK3588 Drivers
    - [ ] Write UART driver
-----
- [ ] Write RK3588 Linux Drivers / Expand DTS
  - [ ] Write GPIO Driver
  - [ ] Write SPI Driver
  - [ ] Write I2C Driver
  - [ ] Write Ethernet Driver
