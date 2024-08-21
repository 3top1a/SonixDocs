---
layout: home
title: "Home"
nav_order: 0
---

# SonixQMK

![SonixQMK Logo](https://avatars.githubusercontent.com/u/79227208?s=75&v=4)

The SonixQMK community has ported many Sonix MCU boards from the like of Womier, Redragon, Keychron to the open source keyboard firmware QMK. 

This website assists you with installation of QMK and gives information on the boards. We would like to remind you that QMK, Sonix nor the manufacturers of these boards have any association with this website. Please understand that the SonixQMK is full of volunteers and we cannot help you with every issue, please attempt to figure it out on your own. Have fun!

---

# What is a Sonix Board?
In the past several years, a bunch of low-cost mechanical keyboards from several vendors started to use a common family of MCUs: the Sonix SN32. Currently there are two companies that are rebranding the Sonix SN32 Family: EVision and HFD.

While these boards can have nice hardware, usually they come with questionable software that doesn't allow the user to fully customize the experience with the keyboard (Macros, RGB Lighting, Remapping).

---
# Status
This project is still in development, maintained purely on volunteers. We recommend you having a copy of the stock firmware for your keyboard before flashing the port.

<Details markdown="block">
<summary>We currently support the following MCUs:</summary>

{% include table.html data=site.data.mcus %}

Please note that some MCUs may be marked slightly differently. For example, `SN32F248BFG` indicates the `SN32F248` chip model in a "Green" LQFP package variant. Refer to the appropriate datasheet for more information.
For example, the datasheet for the SN32F248 series can be found [here](https://www.sonix.com.tw/article-en-998-21395#).

</Details>


**To see a list of compatible keyboards click [here]({{site.baseurl}}/compatible_kb)**
