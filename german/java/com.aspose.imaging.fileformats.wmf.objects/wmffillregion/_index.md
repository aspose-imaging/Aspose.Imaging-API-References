---
title: "WmfFillRegion"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der META_FILLREGION‑Datensatz füllt eine Region mit einem angegebenen Pinsel."
type: docs
weight: 37
url: /de/java/com.aspose.imaging.fileformats.wmf.objects/wmffillregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject)
```
public class WmfFillRegion extends WmfObject
```

Der META\_FILLREGION-Datensatz füllt eine Region mit einem angegebenen Pinsel.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [WmfFillRegion()](#WmfFillRegion--) | Initialisiert eine neue Instanz der `WmfFillRegion`-Klasse. |
| [WmfFillRegion(WmfGraphicObject region, WmfGraphicObject brush)](#WmfFillRegion-com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject-com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject-) | Initialisiert eine neue Instanz der `WmfFillRegion`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRegionIndex()](#getRegionIndex--) | Liest oder setzt den Index des Bereichs. |
| [setRegionIndex(int value)](#setRegionIndex-int-) | Liest oder setzt den Index des Bereichs. |
| [getBrushIndex()](#getBrushIndex--) | Liest oder setzt den Index des Pinsels. |
| [setBrushIndex(int value)](#setBrushIndex-int-) | Liest oder setzt den Index des Pinsels. |
### WmfFillRegion() {#WmfFillRegion--}
```
public WmfFillRegion()
```


Initialisiert eine neue Instanz der `WmfFillRegion`-Klasse.

### WmfFillRegion(WmfGraphicObject region, WmfGraphicObject brush) {#WmfFillRegion-com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject-com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject-}
```
public WmfFillRegion(WmfGraphicObject region, WmfGraphicObject brush)
```


Initialisiert eine neue Instanz der `WmfFillRegion`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| region | [WmfGraphicObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfgraphicobject) | Der Bereich. |
| brush | [WmfGraphicObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfgraphicobject) | Der Pinsel. |

### getRegionIndex() {#getRegionIndex--}
```
public int getRegionIndex()
```


Liest oder setzt den Index des Bereichs.

Wert: Index in die WMF-Objekttabelle, um die zu füllende Region zu erhalten.

**Returns:**
int
### setRegionIndex(int value) {#setRegionIndex-int-}
```
public void setRegionIndex(int value)
```


Liest oder setzt den Index des Bereichs.

Wert: Index in die WMF-Objekttabelle, um die zu füllende Region zu erhalten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getBrushIndex() {#getBrushIndex--}
```
public int getBrushIndex()
```


Liest oder setzt den Index des Pinsels.

Wert: Index in die WMF-Objekttabelle, um den Pinsel zu erhalten, der zum Füllen der Region verwendet wird.

**Returns:**
int
### setBrushIndex(int value) {#setBrushIndex-int-}
```
public void setBrushIndex(int value)
```


Liest oder setzt den Index des Pinsels.

Wert: Index in die WMF-Objekttabelle, um den Pinsel zu erhalten, der zum Füllen der Region verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

