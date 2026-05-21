---
title: "EmfPlusBitmapData"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das EmfPlusBitmapData-Objekt gibt ein Bitmap-Bild mit Pixeldaten an."
type: docs
weight: 15
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmapdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBitmapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata)
```
public final class EmfPlusBitmapData extends EmfPlusBaseBitmapData
```

Das EmfPlusBitmapData-Objekt gibt ein Bitmap-Bild mit Pixeldaten an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusBitmapData()](#EmfPlusBitmapData--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getColors()](#getColors--) | Liest oder setzt die Palettenfarben Colors (variabel): Ein optionales `EmfPlusPalette`-Objekt (Abschnitt 2.2.2.28), das die Farbpalette angibt, die in den Pixeldaten verwendet wird. |
| [setColors(EmfPlusPalette value)](#setColors-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPalette-) | Liest oder setzt die Palettenfarben Colors (variabel): Ein optionales `EmfPlusPalette`-Objekt (Abschnitt 2.2.2.28), das die Farbpalette angibt, die in den Pixeldaten verwendet wird. |
| [getPixelData()](#getPixelData--) | Liest oder setzt Pixeldaten PixelData (variabel): Ein Array von Bytes, das die Pixeldaten angibt. |
| [setPixelData(byte[] value)](#setPixelData-byte---) | Liest oder setzt Pixeldaten PixelData (variabel): Ein Array von Bytes, das die Pixeldaten angibt. |
### EmfPlusBitmapData() {#EmfPlusBitmapData--}
```
public EmfPlusBitmapData()
```


### getColors() {#getColors--}
```
public EmfPlusPalette getColors()
```


Liest oder setzt die Palettenfarben Colors (variabel): Ein optionales `EmfPlusPalette`-Objekt (Abschnitt 2.2.2.28), das die Farbpalette angibt, die in den Pixeldaten verwendet wird. Dieses Feld MUSS vorhanden sein, wenn das I‑Flag im PixelFormat‑Feld des `EmfPlusBitmap`‑Objekts gesetzt ist.

Wert: Die Farben.

**Returns:**
[EmfPlusPalette](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette)
### setColors(EmfPlusPalette value) {#setColors-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPalette-}
```
public void setColors(EmfPlusPalette value)
```


Liest oder setzt die Palettenfarben Colors (variabel): Ein optionales `EmfPlusPalette`-Objekt (Abschnitt 2.2.2.28), das die Farbpalette angibt, die in den Pixeldaten verwendet wird. Dieses Feld MUSS vorhanden sein, wenn das I‑Flag im PixelFormat‑Feld des `EmfPlusBitmap`‑Objekts gesetzt ist.

Wert: Die Farben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfPlusPalette](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette) |  |

### getPixelData() {#getPixelData--}
```
public byte[] getPixelData()
```


Liest oder setzt Pixeldaten PixelData (variabel): Ein Array von Bytes, das die Pixeldaten angibt. Größe und Format dieser Daten können aus den Feldern des EmfPlusBitmap‑Objekts berechnet werden, einschließlich des Pixelformats aus der Aufzählung `Consts.EmfPlusPixelFormat` (Abschnitt 2.1.1.25).

Wert: Die Pixeldaten.

**Returns:**
byte[]
### setPixelData(byte[] value) {#setPixelData-byte---}
```
public void setPixelData(byte[] value)
```


Liest oder setzt Pixeldaten PixelData (variabel): Ein Array von Bytes, das die Pixeldaten angibt. Größe und Format dieser Daten können aus den Feldern des EmfPlusBitmap‑Objekts berechnet werden, einschließlich des Pixelformats aus der Aufzählung `Consts.EmfPlusPixelFormat` (Abschnitt 2.1.1.25).

Wert: Die Pixeldaten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

