---
title: "EmfPlusTextureBrushOptionalData"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusTextureBrushOptionalData-objektet specificerar valfri data för en texturpensel."
type: docs
weight: 78
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusTextureBrushOptionalData extends EmfPlusStructureObjectType
```

EmfPlusTextureBrushOptionalData-objektet specificerar valfri data för en texturpensel.

Obs! Varje fält i detta objekt är valfritt och kan saknas i OptionalData-fältet för ett EmfPlusTextureBrushData-objekt (avsnitt 2.2.2.45), beroende på BrushData-flaggor (avsnitt 2.1.2.1) som är inställda i dess BrushDataFlags-fält. Även om det inte är praktiskt att representera varje möjlig kombination av närvarande eller frånvarande fält, specificerar detta avsnitt deras relativa ordning i objektet. Implementatören ansvarar för att avgöra vilka fält som faktiskt är närvarande i en given metafilpost, och för att avkoda data för enskilda fält separat och på lämpligt sätt.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusTextureBrushOptionalData()](#EmfPlusTextureBrushOptionalData--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getTransformMatrix()](#getTransformMatrix--) | Hämtar eller anger ett valfritt EmfPlusTransformMatrix-objekt (avsnitt 2.2.2.47) som specificerar en transform från världsrummet till enhetsrummet för texturpenseln. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | Hämtar eller anger ett valfritt EmfPlusTransformMatrix-objekt (avsnitt 2.2.2.47) som specificerar en transform från världsrummet till enhetsrummet för texturpenseln. |
| [getImageObject()](#getImageObject--) | Hämtar eller anger ett valfritt EmfPlusImage-objekt (avsnitt 2.2.1.4) som specificerar penselns textur. |
| [setImageObject(EmfPlusImage value)](#setImageObject-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImage-) | Hämtar eller anger ett valfritt EmfPlusImage-objekt (avsnitt 2.2.1.4) som specificerar penselns textur. |
### EmfPlusTextureBrushOptionalData() {#EmfPlusTextureBrushOptionalData--}
```
public EmfPlusTextureBrushOptionalData()
```


### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


Hämtar eller anger ett valfritt EmfPlusTransformMatrix-objekt (avsnitt 2.2.2.47) som specificerar en transform från världsrummet till enhetsrummet för texturpenseln. Detta fält MÅSTE vara närvarande om BrushDataTransform-flaggan är inställd i BrushDataFlags-fältet för EmfPlusTextureBrushData-objektet.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


Hämtar eller anger ett valfritt EmfPlusTransformMatrix-objekt (avsnitt 2.2.2.47) som specificerar en transform från världsrummet till enhetsrummet för texturpenseln. Detta fält MÅSTE vara närvarande om BrushDataTransform-flaggan är inställd i BrushDataFlags-fältet för EmfPlusTextureBrushData-objektet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getImageObject() {#getImageObject--}
```
public EmfPlusImage getImageObject()
```


Hämtar eller anger ett valfritt EmfPlusImage-objekt (avsnitt 2.2.1.4) som specificerar penselns textur. Detta fält MÅSTE vara närvarande om storleken på EmfPlusObject-posten (avsnitt 2.3.5.1) som definierar denna texturpensel är tillräckligt stor för att rymma ett EmfPlusImage-objekt utöver de obligatoriska fälten i EmfPlusTextureBrushData-objektet och eventuellt ett EmfPlusTransformMatrix-objekt.

**Returns:**
[EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage)
### setImageObject(EmfPlusImage value) {#setImageObject-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImage-}
```
public void setImageObject(EmfPlusImage value)
```


Hämtar eller anger ett valfritt EmfPlusImage-objekt (avsnitt 2.2.1.4) som specificerar penselns textur. Detta fält MÅSTE vara närvarande om storleken på EmfPlusObject-posten (avsnitt 2.3.5.1) som definierar denna texturpensel är tillräckligt stor för att rymma ett EmfPlusImage-objekt utöver de obligatoriska fälten i EmfPlusTextureBrushData-objektet och eventuellt ett EmfPlusTransformMatrix-objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage) |  |

