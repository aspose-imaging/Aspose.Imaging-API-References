---
title: "WmfDeviceIndependentBitmap"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das DeviceIndependentBitmap-Objekt definiert ein Bild im geräteunabhängigen Bitmap‑DIB-Format."
type: docs
weight: 27
url: /de/java/com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfDeviceIndependentBitmap extends MetaObject
```

Das DeviceIndependentBitmap-Objekt definiert ein Bild im geräteunabhängigen Bitmap-Format (DIB).
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [WmfDeviceIndependentBitmap()](#WmfDeviceIndependentBitmap--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getHeader()](#getHeader--) | Liest oder setzt entweder ein BitmapCoreHeader-Objekt (Abschnitt 2.2.2.2) oder ein BitmapInfoHeader-Objekt (Abschnitt 2.2.2.3), das Informationen über das Bild angibt. |
| [setHeader(WmfBitmapBaseHeader value)](#setHeader-com.aspose.imaging.fileformats.wmf.objects.WmfBitmapBaseHeader-) | Liest oder setzt entweder ein BitmapCoreHeader-Objekt (Abschnitt 2.2.2.2) oder ein BitmapInfoHeader-Objekt (Abschnitt 2.2.2.3), das Informationen über das Bild angibt. |
| [getColorsData()](#getColorsData--) | Liest oder setzt ein optionales Array entweder von RGBQuad-Objekten (Abschnitt 2.2.2.20) oder von 16‑Bit‑Ganzzahlen ohne Vorzeichen, die eine Farbpalette definieren. |
| [setColorsData(byte[] value)](#setColorsData-byte---) | Liest oder setzt ein optionales Array entweder von RGBQuad-Objekten (Abschnitt 2.2.2.20) oder von 16‑Bit‑Ganzzahlen ohne Vorzeichen, die eine Farbpalette definieren. |
| [getAData()](#getAData--) | Liest oder setzt ein Byte‑Array, das das Bild definiert. |
| [setAData(byte[] value)](#setAData-byte---) | Liest oder setzt ein Byte‑Array, das das Bild definiert. |
| [getCachedImage()](#getCachedImage--) | Liest das zwischengespeicherte Rasterbild. |
| [setCachedImage(byte[] value)](#setCachedImage-byte---) | Setzt das zwischengespeicherte Rasterbild. |
### WmfDeviceIndependentBitmap() {#WmfDeviceIndependentBitmap--}
```
public WmfDeviceIndependentBitmap()
```


### getHeader() {#getHeader--}
```
public WmfBitmapBaseHeader getHeader()
```


Liest oder setzt entweder ein BitmapCoreHeader-Objekt (Abschnitt 2.2.2.2) oder ein BitmapInfoHeader-Objekt (Abschnitt 2.2.2.3), das Informationen über das Bild angibt.

**Returns:**
[WmfBitmapBaseHeader](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader)
### setHeader(WmfBitmapBaseHeader value) {#setHeader-com.aspose.imaging.fileformats.wmf.objects.WmfBitmapBaseHeader-}
```
public void setHeader(WmfBitmapBaseHeader value)
```


Liest oder setzt entweder ein BitmapCoreHeader-Objekt (Abschnitt 2.2.2.2) oder ein BitmapInfoHeader-Objekt (Abschnitt 2.2.2.3), das Informationen über das Bild angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [WmfBitmapBaseHeader](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader) |  |

### getColorsData() {#getColorsData--}
```
public byte[] getColorsData()
```


Liest oder setzt ein optionales Array entweder von RGBQuad-Objekten (Abschnitt 2.2.2.20) oder von 16‑Bit‑Ganzzahlen ohne Vorzeichen, die eine Farbpalette definieren. Die Größe und der Inhalt dieses Feldes SOLLTEN aus dem Metadatei‑Datensatz oder -Objekt, das dieses DeviceIndependentBitmap enthält, sowie aus den Informationen im DIBHeaderInfo‑Feld ermittelt werden. Siehe die Aufzählungen ColorUsage (Abschnitt 2.1.1.6) und BitCount (Abschnitt 2.1.1.3) für weitere Details.

**Returns:**
byte[]
### setColorsData(byte[] value) {#setColorsData-byte---}
```
public void setColorsData(byte[] value)
```


Liest oder setzt ein optionales Array entweder von RGBQuad-Objekten (Abschnitt 2.2.2.20) oder von 16‑Bit‑Ganzzahlen ohne Vorzeichen, die eine Farbpalette definieren. Die Größe und der Inhalt dieses Feldes SOLLTEN aus dem Metadatei‑Datensatz oder -Objekt, das dieses DeviceIndependentBitmap enthält, sowie aus den Informationen im DIBHeaderInfo‑Feld ermittelt werden. Siehe die Aufzählungen ColorUsage (Abschnitt 2.1.1.6) und BitCount (Abschnitt 2.1.1.3) für weitere Details.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### getAData() {#getAData--}
```
public byte[] getAData()
```


Liest oder setzt ein Byte‑Array, das das Bild definiert. Größe und Format dieser Daten werden durch die Informationen im DIBHeaderInfo‑Feld bestimmt.

**Returns:**
byte[]
### setAData(byte[] value) {#setAData-byte---}
```
public void setAData(byte[] value)
```


Liest oder setzt ein Byte‑Array, das das Bild definiert. Größe und Format dieser Daten werden durch die Informationen im DIBHeaderInfo‑Feld bestimmt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### getCachedImage() {#getCachedImage--}
```
public final byte[] getCachedImage()
```


Liest das zwischengespeicherte Rasterbild.

Wert: Das zwischengespeicherte Bild.

**Returns:**
byte[]
### setCachedImage(byte[] value) {#setCachedImage-byte---}
```
public void setCachedImage(byte[] value)
```


Setzt das zwischengespeicherte Rasterbild.

Wert: Das zwischengespeicherte Bild.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

