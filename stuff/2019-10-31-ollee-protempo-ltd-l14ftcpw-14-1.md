---
Title: "Ollee/Protempo Ltd L14FTCPW 14.1""
permalink:  "/stuff/:year-:month-:day-:title"
---

<img src="https://cdn.shopify.com/s/files/1/1781/9857/products/ollee-14.1_2048x2048.jpg">

This laptop is among the worst laptops available on the market - wait, no, it's the single most worst laptop available on the market. But short on a money, it's **great** Linux Laptop.

This is that rare gem, for $199 - it's just good enough for a basic laptop for any linux user or enthusiast.

Okay, So I purchased this laptop from [PC Traders Ltd](//pctraders.co.nz) for $199 - for a basic laptop, this is literally as basic as you can get. Shipped with Windows 10, having 32GB storage is a complete joke; especially when you find out that if you lose the the drivers, the laptop is effectively junk - due to the integrated wireless module on the PCB that I'm going to losely refer to as the motherboard, contains a Broadcom B43455 Wireless AC & Bluetooth module. The drivers of which are ... completely unavailable for the Windows market.

When I mean unavailable, I mean **unavailable** - there is no support website for this laptop, there's no product page for this laptop, there's not even a windows driver for the wireless module on Broadcom's website for this module itself.

The only way to make this laptop functional again is to run it as a Linux laptop, but when you consider that it's running an Intel Atom Quad Core processor, 4G RAM, 32G storage, one bonus is that it has a 1080p panel, allowing for some moderately serious usage with a chosen Linux distro - this laptop does shine.

**Specifications**

<ul class="specs">
    <li><strong>Processor</strong> <a href="//ark.intel.com/content/www/us/en/ark/products/93361/intel-atom-x5-z8350-processor-2m-cache-up-to-1-92-ghz.html">Intel Atom x5-Z8350</a> (4C4T, 2M Cache, up to 1.92G, CherryTrail)</li>
    <li><strong>Memory</strong> 4GB DDR3 Onboard Soldered (No DIMM Slots)</li>
    <li><strong>Storage</strong> 32GB EMMC Onboard</li>
    <li><strong>Wireless</strong> Broadcom BCM43455 WiFi 802.11ac + BT V4.0</li>
    <li><strong>Connectivity</strong> USB 2.0 &amp; USB 3.0, Mini-HDMI.</li>
    <li><strong>Display</strong>1920x1080 "Full HD" TN Panel</li>
</ul>

### BIOS / UEFI

The UEFI setup on this has a traditional AMIBIOS design, blue & grey, but its incredibly limited in its function.

It only allows changing the date/time, Setup Prompt time, NumLock state, Quiet & Fast Boot, Boot Selection and Override, including the required save changes options.

There are no options regarding Secure Boot, enabling or disabling Legacy Support or anything of the like.

### Wireless

In order to get Linux (any distro) to work nicely with the B43455 module, you'll need to install the drivers for the card.

- [RPI Distro - Firmware-NonFree](https://github.com/RPi-Distro/firmware-nonfree)

Download this github package, extract the bcrm folder, copy the content to

<pre>
/usr/lib/firmware/bcrm
</pre>

and the wireless card should operate fully when you reboot.

<h3>Pros &amp; Cons</h3>

<ul class="pro">
  <li><strong>Full HD Display Panel</strong> is included, for the price - it could have easily come with a lower res display.</li>
  <li><strong>Massive Battery</strong>, with close to 8hrs battery life - this thing is going to last all day!  </li>
  <li><strong>Plastic casing &amp; construction</strong> makes this laptop quite durable, I probably wouldn't recommend dropping it off a desk, but it would survive a rough life with children, teenagers or a spare PC floating around the house.</li>
  <li><strong>Linux</strong> naturally, take your pick. Pop!_OS, Xubuntu, Lubuntu, Debian, Elementary OS, Fedora, antiX, OpenSUSE, Linux Lite, Q4OS, NixOS, GhostBSD.</li>
</ul>
<ul class="neutral">
  <li><strong>Affordable</strong>, for $200-300 - you get what you pay for, but when it comes using this on Linux, it's a complete bargain.</li>
</ul>
<ul class="con">
  <li><strong>32G Storage</strong>, is pathetic. Renders the laptop effectively useless when it comes to Windows. <em>Whoever decided on 32G should be shot!</em></li>
  <li><strong>No Driver Payload</strong> is located on the hard drive. After inspecting another similar laptop, I saw no driver folder located on the drive, to be used if the laptop was needed to be reinstalled.</li>
  <li><strong>Windows 10</strong> is probably the worst Operating System that could be pre-loaded on this laptop.</li>
</ul>


# Where to Buy

- [PC Traders Ltd](https://pctraders.co.nz/collections/laptops/products/ollee-l14ftcpw-factory-refurbished-intel-cherrytrail-z8350-dual-core-turbo-1-9-ghz-14-1-full-hd-1920-x-1080-4gb-ram-32gb-emcm-wifi-802-11-ac-bt-v4-0-usb-2-0-usb-3-0-mini-hdmi)

_This laptop was purchased independently with my own funds. This is not a sponsored article._
