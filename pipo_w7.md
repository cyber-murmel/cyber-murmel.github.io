# Installing Arch Linux on a Pipo W7 Tablet
Yesterday I bough the cheapest tablet I could find at one of the stalls at
[Golden Computer Arcade, Hong Kong](https://en.tripadvisor.com.hk/Attraction_Review-g294217-d3749584-Reviews-Golden_Computer_Arcade-Hong_Kong.html).
It's a [PIPO W7](https://www.pipo-store.com/pipo-w7-windows-8-1-1gb-16gb-tablet.html)
which ran Windows. Although it was super cheap (389 HKD = 49.63 USD = 40.33 Euro)
it was reasonably performant.

When I bought it, I asked the seller whether it can run Linux. He responded "no",
but I think he meant that currently no Linux is installed, but Windows.

## Specification

| Spec    | Value                                                                      |
|---------|----------------------------------------------------------------------------|
| CPU     | 1.33GHz Intel Atom Z3735G Quad Core 2MB L2 Cache                           |
| RAM     | 1GB                                                                        |
| GPU     | Intel HD Z3700 Series                                                      |
| ROM     | 16GB                                                                       |
| Screen  | 7 Inch 1280x800 IPS capacitive multi touch                                 |
| Battery | 3Ah                                                                        |
| Wifi    | 802.11 b/g/n                                                               |
| Misc    | Bluetooth, USB OTG, Mini HDMI, Gravity Sensor, 3.5mmA Audio Jack, Micro SD |

## Booting from USB
In the box was next to the Tablet itself the Mirco-USB charging cable and a
Micro-USB OTG cable. This is needed for getting into the system setting, because
you can only boot into them by pressing *Esc* or *Del* at boot.

In my case, stuff like *Secure Boot* was not enabled, but I may be different for you.
The first thing I did was disabling *Quiet Boot* just to be greeted by the nice
American Megatrends screen every boot.

![BIOS](img/pipo_w7_bios.jpg)
![BIOS](img/pipo_w7_secure_boot.jpg)
![BIOS](img/pipo_w7_mega.jpg)

At the Golden Computer Arcade I also bought a USB3.0 hub, so I can simultaneously
connect a keyboard and the boot stick. I also could have tried booting from SD card,
but I didn't.

![Bootet Arch Linux](img/pipo_w7_arch.jpg)
