---
title: "EmfPlusHatchBrushData"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das EmfPlusHatchBrushData-Objekt gibt ein Schraffurmuster für einen Grafik-Pinsel an."
type: docs
weight: 45
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplushatchbrushdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
```
public final class EmfPlusHatchBrushData extends EmfPlusBaseBrushData
```

Das EmfPlusHatchBrushData-Objekt gibt ein Schraffurmuster für einen Grafik-Pinsel an.

Grafik‑Pinsel werden durch `EmfPlusBrush`‑Objekte (Abschnitt 2.2.1.1) angegeben. Ein Schraffurpinsel malt einen Hintergrund und zeichnet ein Muster aus Linien, Punkten, Strichen, Quadraten und Kreuzschraffurlinien über diesem Hintergrund. Der Schraffurpinsel definiert zwei Farben: eine für den Hintergrund und eine für das Muster über dem Hintergrund. Die Farbe des Hintergrunds wird Hintergrundfarbe genannt, und die Farbe des Musters wird Vordergrundfarbe genannt.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusHatchBrushData()](#EmfPlusHatchBrushData--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBackArgb32Color()](#getBackArgb32Color--) | Liest oder setzt ein 32‑Bit EmfPlusArgb‑Objekt, das die Farbe angibt, die zum Malen des Hintergrunds des Schraffurmusters verwendet wird. |
| [setBackArgb32Color(int value)](#setBackArgb32Color-int-) | Liest oder setzt ein 32‑Bit EmfPlusArgb‑Objekt, das die Farbe angibt, die zum Malen des Hintergrunds des Schraffurmusters verwendet wird. |
| [getForeArgb32Color()](#getForeArgb32Color--) | Liest oder setzt ein 32‑Bit EmfPlusArgb‑Objekt, das die Farbe angibt, die zum Zeichnen der Linien des Schraffurmusters verwendet wird. |
| [setForeArgb32Color(int value)](#setForeArgb32Color-int-) | Liest oder setzt ein 32‑Bit EmfPlusArgb‑Objekt, das die Farbe angibt, die zum Zeichnen der Linien des Schraffurmusters verwendet wird. |
| [getHatchStyle()](#getHatchStyle--) | Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der den Schraffur‑Stil des Pinsels angibt. |
| [setHatchStyle(int value)](#setHatchStyle-int-) | Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der den Schraffur‑Stil des Pinsels angibt. |
### EmfPlusHatchBrushData() {#EmfPlusHatchBrushData--}
```
public EmfPlusHatchBrushData()
```


### getBackArgb32Color() {#getBackArgb32Color--}
```
public int getBackArgb32Color()
```


Liest oder setzt ein 32‑Bit EmfPlusArgb‑Objekt, das die Farbe angibt, die zum Malen des Hintergrunds des Schraffurmusters verwendet wird.

**Returns:**
int
### setBackArgb32Color(int value) {#setBackArgb32Color-int-}
```
public void setBackArgb32Color(int value)
```


Liest oder setzt ein 32‑Bit EmfPlusArgb‑Objekt, das die Farbe angibt, die zum Malen des Hintergrunds des Schraffurmusters verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getForeArgb32Color() {#getForeArgb32Color--}
```
public int getForeArgb32Color()
```


Liest oder setzt ein 32‑Bit EmfPlusArgb‑Objekt, das die Farbe angibt, die zum Zeichnen der Linien des Schraffurmusters verwendet wird.

**Returns:**
int
### setForeArgb32Color(int value) {#setForeArgb32Color-int-}
```
public void setForeArgb32Color(int value)
```


Liest oder setzt ein 32‑Bit EmfPlusArgb‑Objekt, das die Farbe angibt, die zum Zeichnen der Linien des Schraffurmusters verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getHatchStyle() {#getHatchStyle--}
```
public int getHatchStyle()
```


Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der den Schraffur‑Stil des Pinsels angibt. Er MUSS in der `EmfPlusHatchStyle`‑Aufzählung definiert sein.

**Returns:**
int
### setHatchStyle(int value) {#setHatchStyle-int-}
```
public void setHatchStyle(int value)
```


Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der den Schraffur‑Stil des Pinsels angibt. Er MUSS in der `EmfPlusHatchStyle`‑Aufzählung definiert sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

