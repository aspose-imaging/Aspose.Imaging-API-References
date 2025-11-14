---
title: EmfRop4 Class
type: docs
weight: 1010
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfrop4/
---

**Summary:** A quaternary raster operation, which specifies ternary raster operations for <br/>            the foreground and background colors of a bitmap. These values define how the color data of <br/>            the source rectangle is to be combined with the color data of the destination rectangle.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfRop4

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfRop4(dword_data)](#EmfRop4_dword_data_1) | Initializes a new instance of the [EmfRop4](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrop4/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| background_rop3 | System.Byte | r | Gets the background ROP3.<br/>            The unsigned, most-significant 8 bits of a 24-bit ternary <br/>            raster operation value from the WMF Ternary Raster Operation enumeration ([MS-WMF] section 2.1.1.31). This code defines how to combine the background color data of <br/>            the source and destination bitmaps and brush pattern. |
| foreground_rop3 | System.Byte | r | Gets the foreground ROP3.<br/>            The unsigned, most-significant 8 bits of a 24-bit ternary <br/>            raster operation value from the WMF Ternary Raster Operation enumeration. This <br/>            code defines how to combine the foreground color data of the source and destination <br/>            bitmaps and brush pattern. |


### Constructor: EmfRop4(dword_data) {#EmfRop4_dword_data_1}


```
 EmfRop4(dword_data) 
```

Initializes a new instance of the [EmfRop4](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrop4/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dword_data | int | The dword data. |

