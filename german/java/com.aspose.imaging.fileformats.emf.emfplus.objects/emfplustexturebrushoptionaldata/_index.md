---
title: "EmfPlusTextureBrushOptionalData"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das EmfPlusTextureBrushOptionalData-Objekt gibt optionale Daten für einen Texturpinsel an."
type: docs
weight: 78
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusTextureBrushOptionalData extends EmfPlusStructureObjectType
```

Das EmfPlusTextureBrushOptionalData-Objekt gibt optionale Daten für einen Texturpinsel an.

Hinweis: Jedes Feld dieses Objekts ist optional und könnte im OptionalData‑Feld eines EmfPlusTextureBrushData‑Objekts (Abschnitt 2.2.2.45) nicht vorhanden sein, abhängig von den im BrushDataFlags‑Feld gesetzten BrushData‑Flags (Abschnitt 2.1.2.1). Obwohl es nicht praktikabel ist, jede mögliche Kombination von vorhandenen oder fehlenden Feldern darzustellen, gibt dieser Abschnitt ihre relative Reihenfolge im Objekt an. Der Implementierer ist dafür verantwortlich, zu bestimmen, welche Felder in einem gegebenen Metadatei‑Eintrag tatsächlich vorhanden sind, und die Daten für einzelne Felder separat und angemessen zu unmarshallen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusTextureBrushOptionalData()](#EmfPlusTextureBrushOptionalData--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getTransformMatrix()](#getTransformMatrix--) | Liest oder schreibt ein optionales EmfPlusTransformMatrix‑Objekt (Abschnitt 2.2.2.47), das eine Welt‑zu‑Geräte‑Transformation für den Texturpinsel angibt. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | Liest oder schreibt ein optionales EmfPlusTransformMatrix‑Objekt (Abschnitt 2.2.2.47), das eine Welt‑zu‑Geräte‑Transformation für den Texturpinsel angibt. |
| [getImageObject()](#getImageObject--) | Liest oder schreibt ein optionales EmfPlusImage‑Objekt (Abschnitt 2.2.1.4), das die Pinseltextur angibt. |
| [setImageObject(EmfPlusImage value)](#setImageObject-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImage-) | Liest oder schreibt ein optionales EmfPlusImage‑Objekt (Abschnitt 2.2.1.4), das die Pinseltextur angibt. |
### EmfPlusTextureBrushOptionalData() {#EmfPlusTextureBrushOptionalData--}
```
public EmfPlusTextureBrushOptionalData()
```


### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


Liest oder schreibt ein optionales EmfPlusTransformMatrix‑Objekt (Abschnitt 2.2.2.47), das eine Welt‑zu‑Geräte‑Transformation für den Texturpinsel angibt. Dieses Feld MUSS vorhanden sein, wenn das BrushDataTransform‑Flag im BrushDataFlags‑Feld des EmfPlusTextureBrushData‑Objekts gesetzt ist.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


Liest oder schreibt ein optionales EmfPlusTransformMatrix‑Objekt (Abschnitt 2.2.2.47), das eine Welt‑zu‑Geräte‑Transformation für den Texturpinsel angibt. Dieses Feld MUSS vorhanden sein, wenn das BrushDataTransform‑Flag im BrushDataFlags‑Feld des EmfPlusTextureBrushData‑Objekts gesetzt ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getImageObject() {#getImageObject--}
```
public EmfPlusImage getImageObject()
```


Liest oder schreibt ein optionales EmfPlusImage‑Objekt (Abschnitt 2.2.1.4), das die Pinseltextur angibt. Dieses Feld MUSS vorhanden sein, wenn die Größe des EmfPlusObject‑Eintrags (Abschnitt 2.3.5.1), der diesen Texturpinsel definiert, groß genug ist, um zusätzlich zu den erforderlichen Feldern des EmfPlusTextureBrushData‑Objekts ein EmfPlusImage‑Objekt und optional ein EmfPlusTransformMatrix‑Objekt aufzunehmen.

**Returns:**
[EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage)
### setImageObject(EmfPlusImage value) {#setImageObject-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImage-}
```
public void setImageObject(EmfPlusImage value)
```


Liest oder schreibt ein optionales EmfPlusImage‑Objekt (Abschnitt 2.2.1.4), das die Pinseltextur angibt. Dieses Feld MUSS vorhanden sein, wenn die Größe des EmfPlusObject‑Eintrags (Abschnitt 2.3.5.1), der diesen Texturpinsel definiert, groß genug ist, um zusätzlich zu den erforderlichen Feldern des EmfPlusTextureBrushData‑Objekts ein EmfPlusImage‑Objekt und optional ein EmfPlusTransformMatrix‑Objekt aufzunehmen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage) |  |

