# NU40 Dev Kit

## 🌳 NU40 Dev Kit Device Tree for NCS

To compile and flash the application firmware to the NU40 Dev Kit, you need to install the board definition files or the board’s devicetree in Zephyr within the nRF Connect SDK. Zephyr uses devicetree to describe the hardware available on its supported boards and their initial configuration.

## 📁 Fetching NU40 Dev Kit Board Definition Files

Since the NU40 Dev Kit board definition files are not yet included in the Zephyr mainstream, developers should directly download the board files, extract/unzip them, and copy the `nu40_b_dev02` folder into the NCS directory:

```
ncs/v2.7.0/zephyr/boards/arm
```
> Replace `v2.7.0` with the version installed on your computer

You should now see a folder named `nu40_b_dev02` among other supported board files:

```
└── ncs/
    └── v2.7.0/
        ├── zephyr/
        │   └── boards/
        │       └── arm/
        │           ├── ...
        │           ├── ...
        │           ├── nu40_b_dev02
        │           └── ...
        ├── bootloader
        ├── modules
        ├── nrf
        ├── tools
        ├── toolchain
        └── ...
```
