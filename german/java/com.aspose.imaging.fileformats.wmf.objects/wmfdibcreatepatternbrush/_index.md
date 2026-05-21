---
title: "WmfDibCreatePatternBrush"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der META_DIBCREATEPATTERNBRUSH-Datensatz erstellt einen Brush-Objektabschnitt 2.2.1.1 mit einem Muster, das durch einen DeviceIndependentBitmap DIB-Objektabschnitt 2.2.2.9 angegeben wird."
type: docs
weight: 29
url: /de/java/com.aspose.imaging.fileformats.wmf.objects/wmfdibcreatepatternbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject), [com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfgraphicobject)
```
public class WmfDibCreatePatternBrush extends WmfGraphicObject
```

Der META\_DIBCREATEPATTERNBRUSH-Datensatz erstellt ein Brush-Objekt (Abschnitt 2.2.1.1) mit einem Muster, das durch ein DeviceIndependentBitmap (DIB)-Objekt (Abschnitt 2.2.2.9) angegeben wird.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [WmfDibCreatePatternBrush()](#WmfDibCreatePatternBrush--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getStyle()](#getStyle--) | Liest oder setzt den Stil. |
| [setStyle(int value)](#setStyle-int-) | Liest oder setzt den Stil. |
| [getColorUsage()](#getColorUsage--) | Liest oder setzt die Farbnutzung. |
| [setColorUsage(int value)](#setColorUsage-int-) | Liest oder setzt die Farbnutzung. |
| [getSourceBitmap()](#getSourceBitmap--) | Liest oder setzt das Quell-Bitmap. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Liest oder setzt das Quell-Bitmap. |
### WmfDibCreatePatternBrush() {#WmfDibCreatePatternBrush--}
```
public WmfDibCreatePatternBrush()
```


### getStyle() {#getStyle--}
```
public int getStyle()
```


Liest oder setzt den Stil.

Wert: Die zulässigen Werte für dieses Feld sind wie folgt definiert: Wenn der Wert nicht BS\_PATTERN ist, muss BS\_DIBPATTERNPT angenommen werden. Diese Werte sind in der BrushStyle‑Aufzählung (Abschnitt 2.1.1.4) angegeben.

**Returns:**
int
### setStyle(int value) {#setStyle-int-}
```
public void setStyle(int value)
```


Liest oder setzt den Stil.

Wert: Die zulässigen Werte für dieses Feld sind wie folgt definiert: Wenn der Wert nicht BS\_PATTERN ist, muss BS\_DIBPATTERNPT angenommen werden. Diese Werte sind in der BrushStyle‑Aufzählung (Abschnitt 2.1.1.4) angegeben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getColorUsage() {#getColorUsage--}
```
public int getColorUsage()
```


Liest oder setzt die Farbnutzung.

Wert: Das Colors‑Feld eines DIB‑Objekts enthält explizite RGB‑Werte oder Indizes in eine Palette.

**Returns:**
int
### setColorUsage(int value) {#setColorUsage-int-}
```
public void setColorUsage(int value)
```


Liest oder setzt die Farbnutzung.

Wert: Das Colors‑Feld eines DIB‑Objekts enthält explizite RGB‑Werte oder Indizes in eine Palette.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Liest oder setzt das Quell-Bitmap.

Wert: Variable‑Bit‑DIB‑Objektdaten, die das in der Bürste zu verwendende Muster definieren.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Liest oder setzt das Quell-Bitmap.

Wert: Variable‑Bit‑DIB‑Objektdaten, die das in der Bürste zu verwendende Muster definieren.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

