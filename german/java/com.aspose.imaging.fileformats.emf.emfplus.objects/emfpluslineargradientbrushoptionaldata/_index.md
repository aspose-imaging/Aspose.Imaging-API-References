---
title: "EmfPlusLinearGradientBrushOptionalData"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das EmfPlusLinearGradientBrushOptionalData-Objekt gibt optionale Daten für einen linearen Farbverlaufs-Pinsel an."
type: docs
weight: 54
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusLinearGradientBrushOptionalData extends EmfPlusStructureObjectType
```

Das EmfPlusLinearGradientBrushOptionalData-Objekt gibt optionale Daten für einen linearen Farbverlaufs-Pinsel an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusLinearGradientBrushOptionalData()](#EmfPlusLinearGradientBrushOptionalData--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getTransformMatrix()](#getTransformMatrix--) | Liest oder setzt ein optionales EmfPlusTransformMatrix‑Objekt (Abschnitt 2.2.2.47), das eine Transformation vom Welt‑ in den Geräte‑Raum für den linearen Verlaufs‑Pinsel angibt. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | Liest oder setzt ein optionales EmfPlusTransformMatrix‑Objekt (Abschnitt 2.2.2.47), das eine Transformation vom Welt‑ in den Geräte‑Raum für den linearen Verlaufs‑Pinsel angibt. |
| [getBlendPattern()](#getBlendPattern--) | Liest oder setzt ein optionales Mischmuster für den linearen Verlaufs‑Pinsel. |
| [setBlendPattern(EmfPlusBlendBase[] value)](#setBlendPattern-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase---) | Liest oder setzt ein optionales Mischmuster für den linearen Verlaufs‑Pinsel. |
| [getBlendPatternAsPresetColors()](#getBlendPatternAsPresetColors--) | Liest das Mischmuster als vordefinierte Farben. |
| [getBlendPatternAsBlendFactorsH()](#getBlendPatternAsBlendFactorsH--) | Liest das Mischmuster als Mischfaktoren h. |
| [getBlendPatternAsBlendFactorsV()](#getBlendPatternAsBlendFactorsV--) | Liest das Mischmuster als Mischfaktoren v. |
### EmfPlusLinearGradientBrushOptionalData() {#EmfPlusLinearGradientBrushOptionalData--}
```
public EmfPlusLinearGradientBrushOptionalData()
```


### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


Liest oder setzt ein optionales EmfPlusTransformMatrix‑Objekt (Abschnitt 2.2.2.47), das eine Transformation vom Welt‑ in den Geräte‑Raum für den linearen Verlaufs‑Pinsel angibt. Dieses Feld MUSS vorhanden sein, wenn das BrushDataTransform‑Flag im Feld BrushDataFlags des EmfPlusLinearGradientBrushData‑Objekts gesetzt ist.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


Liest oder setzt ein optionales EmfPlusTransformMatrix‑Objekt (Abschnitt 2.2.2.47), das eine Transformation vom Welt‑ in den Geräte‑Raum für den linearen Verlaufs‑Pinsel angibt. Dieses Feld MUSS vorhanden sein, wenn das BrushDataTransform‑Flag im Feld BrushDataFlags des EmfPlusLinearGradientBrushData‑Objekts gesetzt ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getBlendPattern() {#getBlendPattern--}
```
public EmfPlusBlendBase[] getBlendPattern()
```


Liest oder setzt ein optionales Mischmuster für den linearen Verlaufs‑Pinsel. Wenn dieses Feld vorhanden ist, MUSS es entweder ein EmfPlusBlendColors‑Objekt (Abschnitt 2.2.2.4) oder ein oder zwei EmfPlusBlendFactors‑Objekte (Abschnitt 2.2.2.5) enthalten, darf jedoch nicht beides enthalten. Die nachstehende Tabelle zeigt die gültigen Kombinationen der BrushData‑Flags von EmfPlusLinearGradientBrushData und die entsprechenden Mischmuster: EmfPlusBlendFactors

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase[]
### setBlendPattern(EmfPlusBlendBase[] value) {#setBlendPattern-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase---}
```
public void setBlendPattern(EmfPlusBlendBase[] value)
```


Liest oder setzt ein optionales Mischmuster für den linearen Verlaufs‑Pinsel. Wenn dieses Feld vorhanden ist, MUSS es entweder ein EmfPlusBlendColors‑Objekt (Abschnitt 2.2.2.4) oder ein oder zwei EmfPlusBlendFactors‑Objekte (Abschnitt 2.2.2.5) enthalten, darf jedoch nicht beides enthalten. Die nachstehende Tabelle zeigt die gültigen Kombinationen der BrushData‑Flags von EmfPlusLinearGradientBrushData und die entsprechenden Mischmuster: EmfPlusBlendFactors

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfPlusBlendBase\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase) |  |

### getBlendPatternAsPresetColors() {#getBlendPatternAsPresetColors--}
```
public EmfPlusBlendColors getBlendPatternAsPresetColors()
```


Liest das Mischmuster als vordefinierte Farben.

Wert: Das Mischmuster als vordefinierte Farben.

**Returns:**
[EmfPlusBlendColors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors)
### getBlendPatternAsBlendFactorsH() {#getBlendPatternAsBlendFactorsH--}
```
public EmfPlusBlendFactors getBlendPatternAsBlendFactorsH()
```


Liest das Mischmuster als Mischfaktoren h.

Wert: Das Mischmuster als Mischfaktoren h.

**Returns:**
[EmfPlusBlendFactors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors)
### getBlendPatternAsBlendFactorsV() {#getBlendPatternAsBlendFactorsV--}
```
public EmfPlusBlendFactors getBlendPatternAsBlendFactorsV()
```


Liest das Mischmuster als Mischfaktoren v.

Wert: Das Mischmuster als Mischfaktoren v.

**Returns:**
[EmfPlusBlendFactors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors)
