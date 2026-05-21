---
title: "EmfPlusPathGradientBrushOptionalData"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das EmfPlusPathGradientBrushOptionalData-Objekt gibt optionale Daten für einen Pfadverlauf-Pinsel an."
type: docs
weight: 60
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusPathGradientBrushOptionalData extends EmfPlusStructureObjectType
```

Das EmfPlusPathGradientBrushOptionalData-Objekt gibt optionale Daten für einen Pfadverlauf-Pinsel an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusPathGradientBrushOptionalData()](#EmfPlusPathGradientBrushOptionalData--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getTransformMatrix()](#getTransformMatrix--) | Liest oder setzt ein optionales EmfPlusTransformMatrix‑Objekt (Abschnitt 2.2.2.47), das eine Welt‑zu‑Geräte‑Raum‑Transformation für den Pfad‑Verlaufs‑Pinsel angibt. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | Liest oder setzt ein optionales EmfPlusTransformMatrix‑Objekt (Abschnitt 2.2.2.47), das eine Welt‑zu‑Geräte‑Raum‑Transformation für den Pfad‑Verlaufs‑Pinsel angibt. |
| [getBlendPattern()](#getBlendPattern--) | Liest oder setzt ein optionales Mischmuster für den Pfadverlauf-Pinsel. |
| [setBlendPattern(EmfPlusBlendBase value)](#setBlendPattern-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase-) | Liest oder setzt ein optionales Mischmuster für den Pfadverlauf-Pinsel. |
| [getFocusScaleData()](#getFocusScaleData--) | Liest oder setzt ein optionales EmfPlusFocusScaleData-Objekt (Abschnitt 2.2.2.18), das Fokus‑Skalen für den Pfadverlauf-Pinsel angibt. |
| [setFocusScaleData(EmfPlusFocusScaleData value)](#setFocusScaleData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusFocusScaleData-) | Liest oder setzt ein optionales EmfPlusFocusScaleData-Objekt (Abschnitt 2.2.2.18), das Fokus‑Skalen für den Pfadverlauf-Pinsel angibt. |
### EmfPlusPathGradientBrushOptionalData() {#EmfPlusPathGradientBrushOptionalData--}
```
public EmfPlusPathGradientBrushOptionalData()
```


### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


Liest oder setzt ein optionales EmfPlusTransformMatrix-Objekt (Abschnitt 2.2.2.47), das eine Welt‑zu‑Geräte‑Transformation für den Pfadverlauf-Pinsel angibt. Dieses Feld MUSS vorhanden sein, wenn das BrushDataTransform‑Flag im BrushDataFlags‑Feld des EmfPlusPathGradientBrushData‑Objekts gesetzt ist.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


Liest oder setzt ein optionales EmfPlusTransformMatrix-Objekt (Abschnitt 2.2.2.47), das eine Welt‑zu‑Geräte‑Transformation für den Pfadverlauf-Pinsel angibt. Dieses Feld MUSS vorhanden sein, wenn das BrushDataTransform‑Flag im BrushDataFlags‑Feld des EmfPlusPathGradientBrushData‑Objekts gesetzt ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getBlendPattern() {#getBlendPattern--}
```
public EmfPlusBlendBase getBlendPattern()
```


Liest oder setzt ein optionales Mischmuster für den Pfadverlauf-Pinsel. Wenn dieses Feld vorhanden ist, MUSS es entweder ein EmfPlusBlendColors‑Objekt (Abschnitt 2.2.2.4) oder ein EmfPlusBlendFactors‑Objekt (Abschnitt 2.2.2.5) enthalten, darf jedoch nicht beide enthalten. Die nachstehende Tabelle zeigt die gültigen Kombinationen der EmfPlusPathGradientBrushData‑BrushData‑Flags und der entsprechenden Mischmuster:

**Returns:**
[EmfPlusBlendBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase)
### setBlendPattern(EmfPlusBlendBase value) {#setBlendPattern-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase-}
```
public void setBlendPattern(EmfPlusBlendBase value)
```


Liest oder setzt ein optionales Mischmuster für den Pfadverlauf-Pinsel. Wenn dieses Feld vorhanden ist, MUSS es entweder ein EmfPlusBlendColors‑Objekt (Abschnitt 2.2.2.4) oder ein EmfPlusBlendFactors‑Objekt (Abschnitt 2.2.2.5) enthalten, darf jedoch nicht beide enthalten. Die nachstehende Tabelle zeigt die gültigen Kombinationen der EmfPlusPathGradientBrushData‑BrushData‑Flags und der entsprechenden Mischmuster:

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfPlusBlendBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase) |  |

### getFocusScaleData() {#getFocusScaleData--}
```
public EmfPlusFocusScaleData getFocusScaleData()
```


Liest oder setzt ein optionales EmfPlusFocusScaleData‑Objekt (Abschnitt 2.2.2.18), das Fokus‑Skalen für den Pfadverlauf-Pinsel angibt. Dieses Feld MUSS vorhanden sein, wenn das BrushDataFocusScales‑Flag im BrushDataFlags‑Feld des EmfPlusPathGradientBrushData‑Objekts gesetzt ist.

**Returns:**
[EmfPlusFocusScaleData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata)
### setFocusScaleData(EmfPlusFocusScaleData value) {#setFocusScaleData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusFocusScaleData-}
```
public void setFocusScaleData(EmfPlusFocusScaleData value)
```


Liest oder setzt ein optionales EmfPlusFocusScaleData‑Objekt (Abschnitt 2.2.2.18), das Fokus‑Skalen für den Pfadverlauf-Pinsel angibt. Dieses Feld MUSS vorhanden sein, wenn das BrushDataFocusScales‑Flag im BrushDataFlags‑Feld des EmfPlusPathGradientBrushData‑Objekts gesetzt ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfPlusFocusScaleData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata) |  |

