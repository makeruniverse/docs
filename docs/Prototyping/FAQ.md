# Frequently Asked Questions

!!! warning
    Only use gluestick on printplates/beds which are __EXPLICITLY__ labeled. Using gluestick on other printplates/beds _will_ damage them. If something bad happens contact staff and grab isopropyl alcohol and clean the bed as soon as possible.

## What slicer should I use?
To be compatible with all printers we strongly recommend using [OrcaSlicer](https://github.com/SoftFever/OrcaSlicer)

### How to install OrcaSlicer?
Install with brew: `brew install orcaslicer`
AUR: `orca-slicer`
Or download follow the install instructions on the [GitHub page](https://github.com/SoftFever/OrcaSlicer#how-to-install).

## How do I connect OrcaSlicer to Creatly K1 with pure Klipper Firmware?
You can get the IP address of your Creatly K1 by going to the printer menu and selecting `Settings` and then `Network`.
Make sure your PC is connected to `hpi_studio` WiFi.
Enter the IP Address like shown in the image above and click `Test`. If the test is successful you can click `Connect` and start printing. After slicing you can click `Print` to start printing.

## Where can I find the web Interface of the Creatly K1s?
Make sure your PS is connected to `hpi_studio` WiFi.
Select `Settings` and then `Network`. Then enter the IP Address in your browser. Make sure to append `4408` as port. Example: ![http://172.22.0.254:4408](http://172.22.0.254:4408)
