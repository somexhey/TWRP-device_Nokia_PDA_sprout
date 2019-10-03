# Device Tree for Nokia 5.1 Plus / X5 (PDA_sprout)

The Nokia 5.1 Plus (codenamed _"PDA-sprout"_) is a mid-range smartphone from Nokia.
It was released in July 2018.

| Basic                   | Spec Sheet                                                                                                                     |
| -----------------------:|:------------------------------------------------------------------------------------------------------------------------------ |
| CPU                     | Octa-core 2.0 GHz Cortex-A53                                                                                                   |
| Chipset                 | Mediatek MT6771 Helio P60                                                                                                      |
| GPU                     | Mali-G72 MP3                                                                                                                   |
| Memory                  | 3/4 GB RAM                                                                                                                     |
| Shipped Android Version | 8.1                                                                                                                            |
| Storage                 | 32/64 GB                                                                                                                       |
| Battery                 | Non-removable Li-Po 3060 mAh battery                                                                                           |
| Display                 | 720 x 1520 pixels, 19:9 ratio (~287 ppi density)                                                                               |

![Nokia 5.1 Plus](http://ae01.alicdn.com/kf/HTB1EiJHJNSYBuNjSspjq6x73VXaR.jpg)

## Build instructions

```
# Compiling
$ . build/envsetup.sh
$ lunch omni_PDA_sprout-userdebug
$ make -jx recoveryimage //replace x in -jx with number of cores you want to allot for compilation

```

