---
title: "EmfPlusBitmap Klasse"
type: docs
weight: 50
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/
---

**Summary:** The EmfPlusBitmap object specifies a bitmap that contains a graphics image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBitmap

**Inheritance:** EmfPlusBaseImageData

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusBitmap()](#EmfPlusBitmap__1) | Initialisiert eine neue Instanz der EmfPlusBitmap Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| bitmap_data | [EmfPlusBaseBitmapData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata/) | r/w | Liest oder schreibt Bitmap‑Daten<br/>            BitmapData (variabel): Daten variabler Länge, die das Bitmap‑Datenobjekt definieren, das im Feld Type angegeben ist. Der<br/>            Inhalt und das Format der Daten können für jeden Bitmap‑Typ unterschiedlich sein. |
| height | int | r/w | Liest oder schreibt die Bitmap‑Höhe<br/>            Height (4 Bytes): Eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die Höhe in Pixeln des von der Bitmap belegten Bereichs angibt.<br/>            Ist das Bild komprimiert, ist dieser Wert gemäß dem Feld Type undefiniert und MUSS ignoriert werden. |
| pixel_format | [EmfPlusPixelFormat](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixelformat/) | r/w | Liest oder schreibt das Pixel‑Format<br/>            PixelFormat (4 Bytes): Eine 32‑Bit vorzeichenlose Ganzzahl, die das Format der Pixel angibt, aus denen das Bitmap‑Bild besteht.<br/>            Die unterstützten Pixel‑Formate sind in der Aufzählung [EmfPlusPixelFormat](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixelformat/) (Abschnitt 2.1.1.25) angegeben.<br/>            Ist das Bild komprimiert, ist dieser Wert gemäß dem Feld Type undefiniert und MUSS ignoriert werden. |
| stride | int | r/w | Liest oder schreibt den Stride des Bildes<br/>            Stride (4 Bytes): Eine 32‑Bit vorzeichenbehaftete Ganzzahl, die den Byte‑Versatz zwischen dem Beginn einer Scan‑Zeile und der nächsten angibt. Dieser Wert ist die Anzahl der Bytes pro Pixel, die im Feld PixelFormat angegeben ist, multipliziert mit der Breite in Pixeln, die im Feld Width angegeben ist. Der Wert dieses Feldes MUSS ein Vielfaches von vier sein.<br/>            Ist das Bild komprimiert, ist dieser Wert gemäß dem Feld Type undefiniert und MUSS ignoriert werden. |
| type | [EmfPlusBitmapDataType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbitmapdatatype/) | r/w | Liest oder schreibt den Typ des Bildes<br/>            Type (4 Bytes): Eine 32‑Bit vorzeichenlose Ganzzahl, die den Datentyp im Feld BitmapData angibt. Dieser Wert MUSS in der Aufzählung [EmfPlusBitmapDataType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbitmapdatatype/) (Abschnitt 2.1.1.2) definiert sein. |
| width | int | r/w | Liest oder schreibt die Bildbreite<br/>            Width (4 Bytes): Eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die Breite in Pixeln des von der Bitmap belegten Bereichs angibt.<br/>            Ist das Bild komprimiert, ist dieser Wert gemäß dem Feld Type undefiniert und MUSS ignoriert werden. |


### Constructor: EmfPlusBitmap() {#EmfPlusBitmap__1}


```
 EmfPlusBitmap() 
```

Initialisiert eine neue Instanz der EmfPlusBitmap Klasse

