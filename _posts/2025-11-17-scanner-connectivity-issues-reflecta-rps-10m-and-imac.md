---
title: "Scanner Connectivity Issues: Reflecta RPS 10M and iMAC"
date: 2025-11-17 09:30:42
status: publish
type: post
link: https://kevinfoust.com/2025/11/17/scanner-connectivity-issues-reflecta-rps-10m-and-imac/
slug: scanner-connectivity-issues-reflecta-rps-10m-and-imac
categories: [Scanning]
tags: [Reflecta RPS 10M, Scanning, SilverFast9 Ai, Troubleshooting]
---

# Scanner Connectivity Issues: Reflecta RPS 10M and iMAC
When I got new film scanner, I was surprised to find a USB 2.0 connector on the back. I hadn't even considered that it would have such an archaic connector. "Back in the day" this was the connector that was common on printers, and some external hard drives enclosures (spinning disks in those days). It worked fine and we had no other choices back then.  Get [geeked on USB connectors](https://en.wikipedia.org/wiki/USB#Connector_type_quick_reference) here.

The iMac I use is a M1 version from 2021 running Tahoe 26.1 It is a pretty recent computer. It has a USB 3.1 and USB C connectors, four of them, two with power. I figured that a USBC to USB2.0 type B (square version) cable would do the job.

That *sort of* worked. Sometimes SilverFast Ai would start and sometimes it wouldn't. It would hang initialising. Sometimes I couldn't adjust the framing on the scanner. I even tried ritualising the startup and that helped but it still wasn't solid. It didn't inspire confidence for long term usability. Other scanning software was also a touchy with this setup. CyberViewX, the OEM software, had most the same issues as SilverFast. VueScan seemed to somehow bulldoze past whatever issues bugged the other two software packages, but I wasn't inspired to switch. 

I started thinking about the possibility of a connection problem. Some web research located [this page](http://d2.scanace.com.tw/Newweb/Troubleshooting/Connectivity_issues_with_my_new_scanner.pdf) Pacific Image Electronics. They sell the PrimeFilm XA Plus which is the same as the Reflecta RPS 10M or 10S scanner. Their instructions are pretty clear; you need to run the signals through a USB hub to handle getting from USB3.0 to USB2.0 for these scanning devices.

![](https://kevinfoust.com/wp-content/uploads/2025/11/L1007945-1024x683.jpg)

I found a hub in a local electronic store.  It is a two port hub, made in China, is reasonably cheap, and comes with a couple of cables.

Once added between the iMac and the scanner everything works well.  Give it a try if your scanner connection seems flaky.