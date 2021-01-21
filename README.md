# a300-oc
This is a community-effort to be able to run X300 BIOS on the A300 or at least be able to restore O/C functions from earlier A300 BIOS Version for A300.

This repository contains findings and images (maybe in future also patched versions) \
There should be a small Wiki with read-ups for new members of the project to find \
according information.

**Currently:**
|Version|AGESA|Platform|Notes|
|--|--|--|--|
|3.70|v1|A300| latest, updated on release|
|3.60S|v2 beta|A300| no SOC VID|
|3.60R|v2 beta|A300| latest with SOC VID|
|1.46|v2 beta|X300| runs on A300, o/c visible but not working |
|||||

Important tools:
- UEFItool -- https://github.com/LongSoft/UEFITool
- PSPtool -- https://github.com/PSPReverse/PSPTool
- ...

Subject-related Read-Ups:
- Knoll Activator Chip -- https://itigic.com/de/knoll-activator-use-a-ryzen-cpu-without-an-amd-chipset/ [de-DE]
- Patching Intel's UEFI -- https://drive.google.com/file/d/0B7WYx7u6HJh_a25SdENtenZKdWc/edit [Tools, Patching, Example]
- Re-Enable Hidden UEFI-Opttions Menus -- https://habr.com/ru/post/211879/ [ru-RU, please use translator]

Ressources:
- https://store.emprgroup.com.au/p-531110-01lm570.aspx -- Lenovo, Knoll-based (Chipset-less) AM4 board
- https://www.bios-mods.com/forum/
- https://habr.com/ru/company/acronis/blog/535848/ -- Developing own UEFI-Driver, Start-Guide, Understanding
