---
title: "Epson Print Layout: “Image Not Loaded” Error"
date: 2025-12-04 06:58:23
status: publish
type: post
link: https://kevinfoust.com/2025/12/04/epson-print-layout-image-not-loaded-error/
slug: epson-print-layout-image-not-loaded-error
categories: [Printing]
tags: [EPL, Epson Print Layout, Epson SC-P900, Printing, Troubleshooting]
---

# Epson Print Layout: “Image Not Loaded” Error
*Why Your TIFFs Won’t Open — and the Simple 16-Bit Fix*

## Epson Print Layout “Image Not Found” — The Fix

I recently bought an **Epson SC-P900** printer. Wow. I love this thing. Being able to proof and print at **A4** (a bit larger than 8.5" × 11") right at home has already become a normal part of my workflow.

After about three weeks of completely trouble-free printing, something unexpected happened inside **Epson Print Layout (EPL)**: an **“Image not loaded”** error.

![](https://i0.wp.com/kevinfoust.com/wp-content/uploads/2025/12/Screenshot-2025-12-04-at-07.27.20.png?fit=370%2C202&ssl=1)

No matter what I tried, EPL refused to load **.tiff** files — whether exported from Photoshop or Lightroom. Strangely, **.jpg** files loaded fine, but that’s not the workflow I want. My print pipeline depends on exporting a **finished .tif file**, not making last-minute adjustments inside EPL that aren’t saved or tied to a specific print.

### The Cause

After a bit of digging, the culprit became clear:

**Epson Print Layout does *not* accept 32-bit TIFF files.**

Here’s the relevant part from the Lightroom export dialog:

![](https://i0.wp.com/kevinfoust.com/wp-content/uploads/2025/12/Screenshot-2025-12-04-at-07.33.38.png?fit=700%2C758&ssl=1)

If you export a **32-bit TIFF**, EPL can’t read it and throws the “Image not loaded” error every time.

### The Fix

Fortunately, the solution is simple:

> 

**Export TIFF files at 16-bit instead of 32-bit.**

Once I switched to 16-bit exports, EPL loaded every file without hesitation.

![](https://i0.wp.com/kevinfoust.com/wp-content/uploads/2025/12/Screenshot-2025-12-04-at-07.37.26.png?fit=658%2C716&ssl=1)

## **Final Thoughts**

If you run into the same issue, check your export settings before tearing your hair out. EPL is perfectly happy with **16-bit TIFFs**, and that keeps your high-quality print workflow intact.

One more thing...   From the EPL manual.  8 and 16 bit TIFF files are the only way.

![](https://i0.wp.com/kevinfoust.com/wp-content/uploads/2025/12/epl-data-formats.jpg?fit=1024%2C726&ssl=1)*Screenshot*