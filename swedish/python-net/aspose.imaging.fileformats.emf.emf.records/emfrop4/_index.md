---
title: "EmfRop4 klass"
type: docs
weight: 1010
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.records/emfrop4/
---

**Summary:** A quaternary raster operation, which specifies ternary raster operations for <br/>            the foreground and background colors of a bitmap. These values define how the color data of <br/>            the source rectangle is to be combined with the color data of the destination rectangle.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfRop4

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfRop4(dword_data)](#EmfRop4_dword_data_1) | Initierar en ny instans av klassen [EmfRop4](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrop4/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| background_rop3 | System.Byte | r | Hämtar bakgrunds‑ROP3.<br/>            De osignerade, mest signifikanta 8 bitarna av ett 24‑bitars ternärt <br/>            rasteroperationsvärde från WMF Ternary Raster Operation‑enumerationen ([MS-WMF] avsnitt 2.1.1.31). Denna kod definierar hur bakgrundsfärgsdata från <br/>            käll‑ och destinations‑bitmapar samt penselmönster kombineras. |
| foreground_rop3 | System.Byte | r | Hämtar förgrunds‑ROP3.<br/>            De osignerade, mest signifikanta 8 bitarna av ett 24‑bitars ternärt <br/>            rasteroperationsvärde från WMF Ternary Raster Operation‑enumerationen. Denna <br/>            kod definierar hur förgrundsfärgsdata från käll‑ och destinations‑bitmapar samt penselmönster kombineras. |


### Constructor: EmfRop4(dword_data) {#EmfRop4_dword_data_1}


```
 EmfRop4(dword_data) 
```

Initierar en ny instans av klassen [EmfRop4](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrop4/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dword_data | int | DWORD‑data. |

