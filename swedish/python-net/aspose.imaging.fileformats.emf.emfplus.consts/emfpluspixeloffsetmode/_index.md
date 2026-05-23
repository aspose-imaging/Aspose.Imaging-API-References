---
title: "EmfPlusPixelOffsetMode Enumeration"
type: docs
weight: 350
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixeloffsetmode/
---

PixelOffsetMode‑uppräkningen definierar hur pixlar förskjuts, vilket anger avvägningen mellan renderingshastighet och kvalitet.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusPixelOffsetMode

## **Members**
| **Member name** | **Description** |
| :- | :- |
| PIXEL_OFFSET_MODE_DEFAULT | Pixlar är centrerade på heltalskoordinater, vilket prioriterar hastighet framför kvalitet. |
| PIXEL_OFFSET_MODE_HALF | Pixlar är centrerade på halvtalskoordinater, vilket betyder att pixeln täcker området från 0 till 1 på både x- och y-axlarna och dess centrum är vid (0.5,0.5). Genom att förskjuta pixlar under rendering kan renderingskvaliteten förbättras på bekostnad av renderingshastigheten. |
| PIXEL_OFFSET_MODE_HIGH_QUALITY | Pixlar är centrerade på halvtalskoordinater, precis som med PixelOffsetModeHalf. Högre kvalitet på bekostnad av hastighet anges. |
| PIXEL_OFFSET_MODE_HIGH_SPEED | Pixlar är centrerade på heltalskoordinater, precis som med PixelOffsetModeNone. Högre hastighet på bekostnad av kvalitet anges. |
| PIXEL_OFFSET_MODE_NONE | Pixlar är centrerade på origo, vilket betyder att pixeln täcker området från -0.5 till 0.5 på både x- och y-axlarna och dess centrum är vid (0,0). |
