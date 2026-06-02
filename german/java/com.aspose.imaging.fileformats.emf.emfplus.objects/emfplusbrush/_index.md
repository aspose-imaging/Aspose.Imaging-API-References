---
title: "EmfPlusBrush"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das EmfPlusBrush-Objekt gibt einen Grafikpinsel zum Füllen von Regionen an."
type: docs
weight: 24
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusBrush extends EmfPlusGraphicsObjectType
```

Das EmfPlusBrush-Objekt gibt einen Grafikpinsel zum Füllen von Regionen an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusBrush()](#EmfPlusBrush--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBrushData()](#getBrushData--) | Liest oder setzt die Brush-Daten. Variable-Längendaten, die das im Feld Type angegebene Pinselobjekt definieren. |
| [setBrushData(EmfPlusBaseBrushData value)](#setBrushData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData-) | Liest oder setzt die Brush-Daten. Variable-Längendaten, die das im Feld Type angegebene Pinselobjekt definieren. |
| [getType()](#getType--) | Liest oder setzt den Typ. |
| [setType(int value)](#setType-int-) | Liest oder setzt den Typ. |
### EmfPlusBrush() {#EmfPlusBrush--}
```
public EmfPlusBrush()
```


### getBrushData() {#getBrushData--}
```
public EmfPlusBaseBrushData getBrushData()
```


Liest oder setzt die Brush-Daten. Variable-Längendaten, die das im Feld Type angegebene Pinselobjekt definieren. Der Inhalt und das Format der Daten können je nach Pinseltyp unterschiedlich sein. EmfPlusHatchBrushData (section 2.2.2.20) (done) EmfPlusLinearGradientBrushData object (section 2.2.2.24) (done) EmfPlusPathGradientBrushData object (section 2.2.2.29) (done) EmfPlusSolidBrushData object (section 2.2.2.43) (done) EmfPlusTextureBrushData object (section 2.2.2.45) (done)

Wert: Die Brush-Daten.

**Returns:**
[EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
### setBrushData(EmfPlusBaseBrushData value) {#setBrushData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData-}
```
public void setBrushData(EmfPlusBaseBrushData value)
```


Liest oder setzt die Brush-Daten. Variable-Längendaten, die das im Feld Type angegebene Pinselobjekt definieren. Der Inhalt und das Format der Daten können je nach Pinseltyp unterschiedlich sein. EmfPlusHatchBrushData (section 2.2.2.20) (done) EmfPlusLinearGradientBrushData object (section 2.2.2.24) (done) EmfPlusPathGradientBrushData object (section 2.2.2.29) (done) EmfPlusSolidBrushData object (section 2.2.2.43) (done) EmfPlusTextureBrushData object (section 2.2.2.45) (done)

Wert: Die Brush-Daten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata) |  |

### getType() {#getType--}
```
public int getType()
```


Liest oder setzt den Typ.

Wert: Eine 32-Bit-vorzeichenlose Ganzzahl, die den Pinseltyp angibt, welcher den Inhalt des Feldes BrushData bestimmt. Dieser Wert MUSS in der `EmfPlusBrushType`-Aufzählung definiert sein.

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Liest oder setzt den Typ.

Wert: Eine 32-Bit-vorzeichenlose Ganzzahl, die den Pinseltyp angibt, welcher den Inhalt des Feldes BrushData bestimmt. Dieser Wert MUSS in der `EmfPlusBrushType`-Aufzählung definiert sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

