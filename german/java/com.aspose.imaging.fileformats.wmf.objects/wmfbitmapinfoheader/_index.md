---
title: "WmfBitmapInfoHeader"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das BitmapInfoHeader-Objekt enthält Informationen über die Abmessungen und das Farbformat eines geräteunabhängigen Bitmaps (DIB)."
type: docs
weight: 16
url: /de/java/com.aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfBitmapBaseHeader](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader)
```
public class WmfBitmapInfoHeader extends WmfBitmapBaseHeader
```

Das BitmapInfoHeader-Objekt enthält Informationen über die Abmessungen und das Farbformat einer geräteunabhängigen Bitmap (DIB).
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [WmfBitmapInfoHeader()](#WmfBitmapInfoHeader--) |  |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [STRUCTURE_SIZE](#STRUCTURE-SIZE) | Die Strukturgröße |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getWidth()](#getWidth--) | Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die Breite des DIB in Pixeln definiert. |
| [setWidth(int value)](#setWidth-int-) | Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die Breite des DIB in Pixeln definiert. |
| [getHeight()](#getHeight--) | Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die Höhe des DIB in Pixeln definiert. |
| [setHeight(int value)](#setHeight-int-) | Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die Höhe des DIB in Pixeln definiert. |
| [getCompression()](#getCompression--) | Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die den Komprimierungsmodus des DIB definiert. |
| [setCompression(int value)](#setCompression-int-) | Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die den Komprimierungsmodus des DIB definiert. |
| [getImageSize()](#getImageSize--) | Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die die Größe des Bildes in Bytes definiert. |
| [setImageSize(int value)](#setImageSize-int-) | Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die die Größe des Bildes in Bytes definiert. |
| [getXPelsPerMeter()](#getXPelsPerMeter--) | Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die horizontale Auflösung des Zielgeräts für das DIB in Pixel pro Meter definiert. |
| [setXPelsPerMeter(int value)](#setXPelsPerMeter-int-) | Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die horizontale Auflösung des Zielgeräts für das DIB in Pixel pro Meter definiert. |
| [getYPelsPerMeter()](#getYPelsPerMeter--) | Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die vertikale Auflösung des Zielgeräts für das DIB in Pixel pro Meter definiert. |
| [setYPelsPerMeter(int value)](#setYPelsPerMeter-int-) | Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die vertikale Auflösung des Zielgeräts für das DIB in Pixel pro Meter definiert. |
| [getColorUsed()](#getColorUsed--) | Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die die Anzahl der Indizes in der vom DIB verwendeten Farbpalette wie folgt angibt: Wenn dieser Wert null ist, verwendet das DIB die maximale Anzahl von Farben, die dem BitCount‑Wert entsprechen. |
| [setColorUsed(int value)](#setColorUsed-int-) | Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die die Anzahl der Indizes in der vom DIB verwendeten Farbpalette wie folgt angibt: Wenn dieser Wert null ist, verwendet das DIB die maximale Anzahl von Farben, die dem BitCount‑Wert entsprechen. |
| [getColorImportant()](#getColorImportant--) | Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die die Anzahl der Farbindizes definiert, die für die Anzeige des DIB erforderlich sind. |
| [setColorImportant(int value)](#setColorImportant-int-) | Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die die Anzahl der Farbindizes definiert, die für die Anzeige des DIB erforderlich sind. |
### WmfBitmapInfoHeader() {#WmfBitmapInfoHeader--}
```
public WmfBitmapInfoHeader()
```


### STRUCTURE_SIZE {#STRUCTURE-SIZE}
```
public static final int STRUCTURE_SIZE
```


Die Strukturgröße

### getWidth() {#getWidth--}
```
public int getWidth()
```


Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die Breite des DIB in Pixeln definiert. Dieser Wert MUSS positiv sein. Dieses Feld SOLLTE die Breite der dekomprimierten Bilddatei angeben, wenn der Komprimierungswert JPEG‑ oder PNG‑Format angibt.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die Breite des DIB in Pixeln definiert. Dieser Wert MUSS positiv sein. Dieses Feld SOLLTE die Breite der dekomprimierten Bilddatei angeben, wenn der Komprimierungswert JPEG‑ oder PNG‑Format angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die Höhe des DIB in Pixeln definiert. Dieser Wert DARF NICHT null sein. Ist dieser Wert positiv, ist das DIB ein Bottom‑Up‑Bitmap und sein Ursprung ist die linke untere Ecke. Ist dieser Wert negativ, ist das DIB ein Top‑Down‑Bitmap und sein Ursprung ist die linke obere Ecke. Top‑Down‑Bitmaps unterstützen keine Kompression. Dieses Feld SOLLTE die Höhe der dekomprimierten Bilddatei angeben, wenn der Komprimierungswert JPEG‑ oder PNG‑Format angibt.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die Höhe des DIB in Pixeln definiert. Dieser Wert DARF NICHT null sein. Ist dieser Wert positiv, ist das DIB ein Bottom‑Up‑Bitmap und sein Ursprung ist die linke untere Ecke. Ist dieser Wert negativ, ist das DIB ein Top‑Down‑Bitmap und sein Ursprung ist die linke obere Ecke. Top‑Down‑Bitmaps unterstützen keine Kompression. Dieses Feld SOLLTE die Höhe der dekomprimierten Bilddatei angeben, wenn der Komprimierungswert JPEG‑ oder PNG‑Format angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getCompression() {#getCompression--}
```
public int getCompression()
```


Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die den Komprimierungsmodus des DIB definiert. Dieser Wert MUSS in der Komprimierungs‑Aufzählung (Abschnitt 2.1.1.7) enthalten sein. Dieser Wert DARF kein komprimiertes Format angeben, wenn das DIB ein Top‑Down‑Bitmap ist, wie durch den Höhenwert angezeigt wird.

**Returns:**
int
### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die den Komprimierungsmodus des DIB definiert. Dieser Wert MUSS in der Komprimierungs‑Aufzählung (Abschnitt 2.1.1.7) enthalten sein. Dieser Wert DARF kein komprimiertes Format angeben, wenn das DIB ein Top‑Down‑Bitmap ist, wie durch den Höhenwert angezeigt wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getImageSize() {#getImageSize--}
```
public int getImageSize()
```


Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die die Größe des Bildes in Bytes definiert. Ist der Komprimierungswert BI\_RGB, SOLLTE dieser Wert null sein und MUSS ignoriert werden. Ist der Komprimierungswert BI\_JPEG oder BI\_PNG, MUSS dieser Wert die Größe des JPEG‑ bzw. PNG‑Bildpuffers angeben.

**Returns:**
int
### setImageSize(int value) {#setImageSize-int-}
```
public void setImageSize(int value)
```


Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die die Größe des Bildes in Bytes definiert. Ist der Komprimierungswert BI\_RGB, SOLLTE dieser Wert null sein und MUSS ignoriert werden. Ist der Komprimierungswert BI\_JPEG oder BI\_PNG, MUSS dieser Wert die Größe des JPEG‑ bzw. PNG‑Bildpuffers angeben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getXPelsPerMeter() {#getXPelsPerMeter--}
```
public int getXPelsPerMeter()
```


Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die horizontale Auflösung des Zielgeräts für das DIB in Pixel pro Meter definiert.

**Returns:**
int
### setXPelsPerMeter(int value) {#setXPelsPerMeter-int-}
```
public void setXPelsPerMeter(int value)
```


Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die horizontale Auflösung des Zielgeräts für das DIB in Pixel pro Meter definiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getYPelsPerMeter() {#getYPelsPerMeter--}
```
public int getYPelsPerMeter()
```


Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die vertikale Auflösung des Zielgeräts für das DIB in Pixel pro Meter definiert.

**Returns:**
int
### setYPelsPerMeter(int value) {#setYPelsPerMeter-int-}
```
public void setYPelsPerMeter(int value)
```


Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die vertikale Auflösung des Zielgeräts für das DIB in Pixel pro Meter definiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getColorUsed() {#getColorUsed--}
```
public int getColorUsed()
```


Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die die Anzahl der Indizes in der vom DIB verwendeten Farbpalette wie folgt angibt: Ist dieser Wert null, verwendet das DIB die maximale Anzahl von Farben, die dem BitCount‑Wert entsprechen. Ist dieser Wert ungleich null und ist der BitCount‑Wert kleiner als 16, gibt dieser Wert die Anzahl der vom DIB verwendeten Farben an. Ist dieser Wert ungleich null und ist der BitCount‑Wert 16 oder größer, gibt dieser Wert die Größe der Farbpalette an, die zur Optimierung der Systempalette‑Leistung verwendet wird. Hinweis: Ist dieser Wert ungleich null und größer als die maximal mögliche Größe der Farbpalette basierend auf dem BitCount‑Wert, SOLLTE die maximale Farbpalettengröße angenommen werden.

**Returns:**
int
### setColorUsed(int value) {#setColorUsed-int-}
```
public void setColorUsed(int value)
```


Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die die Anzahl der Indizes in der vom DIB verwendeten Farbpalette wie folgt angibt: Ist dieser Wert null, verwendet das DIB die maximale Anzahl von Farben, die dem BitCount‑Wert entsprechen. Ist dieser Wert ungleich null und ist der BitCount‑Wert kleiner als 16, gibt dieser Wert die Anzahl der vom DIB verwendeten Farben an. Ist dieser Wert ungleich null und ist der BitCount‑Wert 16 oder größer, gibt dieser Wert die Größe der Farbpalette an, die zur Optimierung der Systempalette‑Leistung verwendet wird. Hinweis: Ist dieser Wert ungleich null und größer als die maximal mögliche Größe der Farbpalette basierend auf dem BitCount‑Wert, SOLLTE die maximale Farbpalettengröße angenommen werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getColorImportant() {#getColorImportant--}
```
public int getColorImportant()
```


Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die die Anzahl der Farbindizes definiert, die für die Anzeige des DIB erforderlich sind. Ist dieser Wert null, werden alle Farbindizes benötigt.

**Returns:**
int
### setColorImportant(int value) {#setColorImportant-int-}
```
public void setColorImportant(int value)
```


Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die die Anzahl der Farbindizes definiert, die für die Anzeige des DIB erforderlich sind. Ist dieser Wert null, werden alle Farbindizes benötigt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

