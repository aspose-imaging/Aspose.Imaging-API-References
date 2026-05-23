---
title: "EmfGraphicsMode uppräkning"
type: docs
weight: 150
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/
---

GraphicsMode‑enumerationen används för att ange hur formdata, såsom rektangelkoordinater, ska tolkas.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfGraphicsMode

## **Members**
| **Member name** | **Description** |
| :- | :- |
| GM_ADVANCED | TrueType-textutmatning MÅSTE fullt ut följa den aktuella world-to-device‑transformeringen i uppspelningsenhetens kontext.<br/>Bågar MÅSTE ritas i moturs riktning i world space; dock MÅSTE både bågkontrollpunkterna och själva bågarna fullt ut respektera den aktuella world-to-device‑transformeringen i uppspelningsenhetens kontext.<br/>world-to-device‑transformen KAN modifieras direkt genom att använda EMR_MODIFYWORLDTRANSFORM eller EMR_SETWORLDTRANSFORM poster, eller indirekt genom att ändra fönster‑ och viewport‑utbredningar och ursprung, med EMR_SETWINDOWEXTEX (section 2.3.11.30) och EMR_SETVIEWPORTEXTEX (section 2.3.11.28) poster, samt EMR_SETWINDOWORGEX (section 2.3.11.31) och EMR_SETVIEWPORTORGEX (section 2.3.11.30) poster, respektive.<br/>I grafikläget GM_ADVANCED MÅSTE de nedersta och högra kanterna inkluderas när rektanglar ritas. |
| GM_COMPATIBLE | TrueType-text MÅSTE skrivas från vänster till höger och med rätt sida uppåt, även om resten av grafiken <br/>            roteras kring x-axeln eller y-axeln på grund av den aktuella world-to-device‑transformeringen i <br/>            uppspelningsenhetens kontext. Endast textens höjd SKA skalas. Bågar MÅSTE ritas med den aktuella bågriktningen i uppspelningsenhetens kontext, men de MÅSTE INTE respektera den aktuella world-to-device‑transformeringen, vilket kan kräva en rotation kring x-axeln eller y-axeln.<br/>            world-to-device‑transformeringen SKA endast modifieras genom att ändra fönster‑ och viewport‑utbredningar och ursprung, med EMR_SETWINDOWEXTEX (section 2.3.11.30) och EMR_SETVIEWPORTEXTEX <br/>            (section 2.3.11.28) poster, samt EMR_SETWINDOWORGEX (section 2.3.11.31) och EMR_SETVIEWPORTORGEX <br/>            (section 2.3.11.30) poster, respektive. Att ändra transformeringen direkt genom att använda EMR_MODIFYWORLDTRANSFORM (section 2.3.12.1) eller EMR_SETWORLDTRANSFORM (section 2.3.12.2) poster KAN INTE stödjas.<br/>            I grafikläget GM_COMPATIBLE MÅSTE de nedersta och högra kanterna exkluderas när rektanglar ritas |
