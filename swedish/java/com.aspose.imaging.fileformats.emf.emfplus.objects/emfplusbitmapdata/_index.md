---
title: "EmfPlusBitmapData"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusBitmapData-objektet specificerar en bitmapbild med pixeldata."
type: docs
weight: 15
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmapdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBitmapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata)
```
public final class EmfPlusBitmapData extends EmfPlusBaseBitmapData
```

EmfPlusBitmapData-objektet specificerar en bitmapbild med pixeldata.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusBitmapData()](#EmfPlusBitmapData--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getColors()](#getColors--) | Hämtar eller anger palettfärgerna Colors (variabel): Ett valfritt `EmfPlusPalette`-objekt (avsnitt 2.2.2.28), som specificerar färgpaletten som används i pixeldata. |
| [setColors(EmfPlusPalette value)](#setColors-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPalette-) | Hämtar eller anger palettfärgerna Colors (variabel): Ett valfritt `EmfPlusPalette`-objekt (avsnitt 2.2.2.28), som specificerar färgpaletten som används i pixeldata. |
| [getPixelData()](#getPixelData--) | Hämtar eller anger pixeldata PixelData (variabel): En array av byte som specificerar pixeldata. |
| [setPixelData(byte[] value)](#setPixelData-byte---) | Hämtar eller anger pixeldata PixelData (variabel): En array av byte som specificerar pixeldata. |
### EmfPlusBitmapData() {#EmfPlusBitmapData--}
```
public EmfPlusBitmapData()
```


### getColors() {#getColors--}
```
public EmfPlusPalette getColors()
```


Hämtar eller anger palettfärgerna Colors (variabel): Ett valfritt `EmfPlusPalette`-objekt (avsnitt 2.2.2.28), som specificerar färgpaletten som används i pixeldata. Detta fält MÅSTE finnas om I‑flaggan är satt i PixelFormat-fältet i `EmfPlusBitmap`-objektet.

Värde: färgerna.

**Returns:**
[EmfPlusPalette](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette)
### setColors(EmfPlusPalette value) {#setColors-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPalette-}
```
public void setColors(EmfPlusPalette value)
```


Hämtar eller anger palettfärgerna Colors (variabel): Ett valfritt `EmfPlusPalette`-objekt (avsnitt 2.2.2.28), som specificerar färgpaletten som används i pixeldata. Detta fält MÅSTE finnas om I‑flaggan är satt i PixelFormat-fältet i `EmfPlusBitmap`-objektet.

Värde: färgerna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfPlusPalette](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette) |  |

### getPixelData() {#getPixelData--}
```
public byte[] getPixelData()
```


Hämtar eller anger pixeldata PixelData (variabel): En array av byte som specificerar pixeldata. Storleken och formatet på dessa data kan beräknas från fält i EmfPlusBitmap-objektet, inklusive pixelformatet från `Consts.EmfPlusPixelFormat`‑enumerationen (avsnitt 2.1.1.25).

Värde: Pixeldata.

**Returns:**
byte[]
### setPixelData(byte[] value) {#setPixelData-byte---}
```
public void setPixelData(byte[] value)
```


Hämtar eller anger pixeldata PixelData (variabel): En array av byte som specificerar pixeldata. Storleken och formatet på dessa data kan beräknas från fält i EmfPlusBitmap-objektet, inklusive pixelformatet från `Consts.EmfPlusPixelFormat`‑enumerationen (avsnitt 2.1.1.25).

Värde: Pixeldata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

