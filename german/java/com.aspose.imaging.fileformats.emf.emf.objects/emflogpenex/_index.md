---
title: "EmfLogPenEx"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das LogPenEx-Objekt gibt die Stilbreite und Farbe eines erweiterten logischen Stifts an."
type: docs
weight: 28
url: /de/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogpenex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfBasePen](../../com.aspose.imaging.fileformats.emf.emf.objects/emfbasepen)
```
public final class EmfLogPenEx extends EmfBasePen
```

Das LogPenEx‑Objekt gibt Stil, Breite und Farbe eines erweiterten logischen Pens an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfLogPenEx()](#EmfLogPenEx--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPenStyle()](#getPenStyle--) | Liest oder setzt den Stiftstil |
| [setPenStyle(int value)](#setPenStyle-int-) | Liest oder setzt den Stiftstil |
| [getWidth()](#getWidth--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Breite der vom Stift gezeichneten Linie angibt. |
| [setWidth(int value)](#setWidth-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Breite der vom Stift gezeichneten Linie angibt. |
| [getBrushStyle()](#getBrushStyle--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die einen Pinselstil für den Stift aus der WMF BrushStyle‑Aufzählung ([MS-WMF] Abschnitt 2.1.1.4) angibt. |
| [setBrushStyle(int value)](#setBrushStyle-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die einen Pinselstil für den Stift aus der WMF BrushStyle‑Aufzählung ([MS-WMF] Abschnitt 2.1.1.4) angibt. |
| [getArgb32ColorRef()](#getArgb32ColorRef--) | Liest oder setzt ein WMF ColorRef‑Objekt ([MS-WMF] Abschnitt 2.2.2.8). |
| [setArgb32ColorRef(int value)](#setArgb32ColorRef-int-) | Liest oder setzt ein WMF ColorRef‑Objekt ([MS-WMF] Abschnitt 2.2.2.8). |
| [getBrushHatch()](#getBrushHatch--) | Liest oder setzt das Schraffurmuster des Pinsels. |
| [setBrushHatch(int value)](#setBrushHatch-int-) | Liest oder setzt das Schraffurmuster des Pinsels. |
| [getNumStyleEntities()](#getNumStyleEntities--) | Liest die Anzahl der Elemente im Array, das im Feld StyleEntry angegeben ist. |
| [getStyleEntry()](#getStyleEntry--) | Liest oder setzt ein optionales Array von 32‑Bit‑vorzeichenlosen Ganzzahlen, das die Längen von Strichen und Lücken in der vom Stift gezeichneten Linie definiert, wenn der Wert von PenStyle PS\_USERSTYLE ist. |
| [setStyleEntry(int[] value)](#setStyleEntry-int---) | Liest oder setzt ein optionales Array von 32‑Bit‑vorzeichenlosen Ganzzahlen, das die Längen von Strichen und Lücken in der vom Stift gezeichneten Linie definiert, wenn der Wert von PenStyle PS\_USERSTYLE ist. |
| [getBrushDibPattern()](#getBrushDibPattern--) | Liest oder setzt das DIB‑Muster des Pinsels. |
| [setBrushDibPattern(WmfDeviceIndependentBitmap value)](#setBrushDibPattern-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Liest oder setzt das DIB‑Muster des Pinsels. |
### EmfLogPenEx() {#EmfLogPenEx--}
```
public EmfLogPenEx()
```


### getPenStyle() {#getPenStyle--}
```
public int getPenStyle()
```


Liest oder setzt den Stiftstil

**Returns:**
int
### setPenStyle(int value) {#setPenStyle-int-}
```
public void setPenStyle(int value)
```


Liest oder setzt den Stiftstil

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Breite der vom Stift gezeichneten Linie angibt. Wenn der Stifttyp im Feld PenStyle PS\_GEOMETRIC ist, ist dieser Wert die Breite in logischen Einheiten; andernfalls wird die Breite in Geräteeinheiten angegeben. Wenn der Stifttyp im Feld PenStyle PS\_COSMETIC ist, MUSS dieser Wert 0x00000001 sein.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Breite der vom Stift gezeichneten Linie angibt. Wenn der Stifttyp im Feld PenStyle PS\_GEOMETRIC ist, ist dieser Wert die Breite in logischen Einheiten; andernfalls wird die Breite in Geräteeinheiten angegeben. Wenn der Stifttyp im Feld PenStyle PS\_COSMETIC ist, MUSS dieser Wert 0x00000001 sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getBrushStyle() {#getBrushStyle--}
```
public int getBrushStyle()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die einen Pinselstil für den Stift aus der WMF BrushStyle‑Aufzählung ([MS-WMF] Abschnitt 2.1.1.4) angibt. Wenn der Stifttyp im Feld PenStyle PS\_GEOMETRIC ist, MUSS dieser Wert entweder BS\_SOLID oder BS\_HATCHED sein. Der Wert dieses Feldes kann BS\_NULL sein, jedoch nur, wenn der im PenStyle angegebene Linienstil PS\_NULL ist. Der BS\_NULL‑Stil SOLLTE verwendet werden, um einen Pinsel zu spezifizieren, der keine Wirkung hat.

**Returns:**
int
### setBrushStyle(int value) {#setBrushStyle-int-}
```
public void setBrushStyle(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die einen Pinselstil für den Stift aus der WMF BrushStyle‑Aufzählung ([MS-WMF] Abschnitt 2.1.1.4) angibt. Wenn der Stifttyp im Feld PenStyle PS\_GEOMETRIC ist, MUSS dieser Wert entweder BS\_SOLID oder BS\_HATCHED sein. Der Wert dieses Feldes kann BS\_NULL sein, jedoch nur, wenn der im PenStyle angegebene Linienstil PS\_NULL ist. Der BS\_NULL‑Stil SOLLTE verwendet werden, um einen Pinsel zu spezifizieren, der keine Wirkung hat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getArgb32ColorRef() {#getArgb32ColorRef--}
```
public int getArgb32ColorRef()
```


Liest oder setzt ein WMF ColorRef‑Objekt ([MS-WMF] Abschnitt 2.2.2.8). Die Interpretation dieses Feldes hängt vom BrushStyle‑Wert ab, wie in der späteren Tabelle dieses Abschnitts gezeigt.

Wert: Die 32‑Bit‑ARGB‑Farbe

**Returns:**
int
### setArgb32ColorRef(int value) {#setArgb32ColorRef-int-}
```
public void setArgb32ColorRef(int value)
```


Liest oder setzt ein WMF ColorRef‑Objekt ([MS-WMF] Abschnitt 2.2.2.8). Die Interpretation dieses Feldes hängt vom BrushStyle‑Wert ab, wie in der späteren Tabelle dieses Abschnitts gezeigt.

Wert: Die 32‑Bit‑ARGB‑Farbe

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getBrushHatch() {#getBrushHatch--}
```
public int getBrushHatch()
```


Liest oder setzt das Schraffurmuster des Pinsels. Die Definition dieses Feldes hängt vom BrushStyle‑Wert ab, wie in der späteren Tabelle dieses Abschnitts gezeigt.

**Returns:**
int
### setBrushHatch(int value) {#setBrushHatch-int-}
```
public void setBrushHatch(int value)
```


Liest oder setzt das Schraffurmuster des Pinsels. Die Definition dieses Feldes hängt vom BrushStyle‑Wert ab, wie in der späteren Tabelle dieses Abschnitts gezeigt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getNumStyleEntities() {#getNumStyleEntities--}
```
public int getNumStyleEntities()
```


Liest die Anzahl der Elemente im Array, das im Feld StyleEntry angegeben ist. Dieser Wert SOLLTE Null sein, wenn PenStyle nicht PS\_USERSTYLE angibt.

**Returns:**
int
### getStyleEntry() {#getStyleEntry--}
```
public int[] getStyleEntry()
```


Liest oder setzt ein optionales Array von 32‑Bit‑vorzeichenlosen Ganzzahlen, das die Längen von Strichen und Lücken in der vom Stift gezeichneten Linie definiert, wenn der Wert von PenStyle PS\_USERSTYLE ist. Das Array enthält eine Anzahl von Einträgen, die durch NumStyleEntries angegeben wird, wird jedoch verwendet, als würde es unendlich wiederholt. Der erste Eintrag im Array gibt die Länge des ersten Strichs an. Der zweite Eintrag gibt die Länge der ersten Lücke an. Danach wechseln sich Längen von Strichen und Lücken ab. Wenn der Stifttyp im Feld PenStyle PS\_GEOMETRIC ist, werden die Längen in logischen Einheiten angegeben; andernfalls werden die Längen in Geräteeinheiten angegeben.

**Returns:**
int[]
### setStyleEntry(int[] value) {#setStyleEntry-int---}
```
public void setStyleEntry(int[] value)
```


Liest oder setzt ein optionales Array von 32‑Bit‑vorzeichenlosen Ganzzahlen, das die Längen von Strichen und Lücken in der vom Stift gezeichneten Linie definiert, wenn der Wert von PenStyle PS\_USERSTYLE ist. Das Array enthält eine Anzahl von Einträgen, die durch NumStyleEntries angegeben wird, wird jedoch verwendet, als würde es unendlich wiederholt. Der erste Eintrag im Array gibt die Länge des ersten Strichs an. Der zweite Eintrag gibt die Länge der ersten Lücke an. Danach wechseln sich Längen von Strichen und Lücken ab. Wenn der Stifttyp im Feld PenStyle PS\_GEOMETRIC ist, werden die Längen in logischen Einheiten angegeben; andernfalls werden die Längen in Geräteeinheiten angegeben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] |  |

### getBrushDibPattern() {#getBrushDibPattern--}
```
public WmfDeviceIndependentBitmap getBrushDibPattern()
```


Liest oder setzt das DIB‑Muster des Pinsels.

Wert: Das Pinsel-DIB-Muster.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setBrushDibPattern(WmfDeviceIndependentBitmap value) {#setBrushDibPattern-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setBrushDibPattern(WmfDeviceIndependentBitmap value)
```


Liest oder setzt das DIB‑Muster des Pinsels.

Wert: Das Pinsel-DIB-Muster.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

