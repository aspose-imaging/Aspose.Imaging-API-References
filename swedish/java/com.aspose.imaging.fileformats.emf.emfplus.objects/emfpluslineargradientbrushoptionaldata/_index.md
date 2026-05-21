---
title: "EmfPlusLinearGradientBrushOptionalData"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusLinearGradientBrushOptionalData-objektet specificerar valfri data för en linjär gradientpensel."
type: docs
weight: 54
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusLinearGradientBrushOptionalData extends EmfPlusStructureObjectType
```

EmfPlusLinearGradientBrushOptionalData-objektet specificerar valfri data för en linjär gradientpensel.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusLinearGradientBrushOptionalData()](#EmfPlusLinearGradientBrushOptionalData--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getTransformMatrix()](#getTransformMatrix--) | Hämtar eller anger ett valfritt EmfPlusTransformMatrix-objekt (avsnitt 2.2.2.47) som specificerar en transformation från världsrummet till enhetligt utrymme för den linjära gradientpenseln. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | Hämtar eller anger ett valfritt EmfPlusTransformMatrix-objekt (avsnitt 2.2.2.47) som specificerar en transformation från världsrummet till enhetligt utrymme för den linjära gradientpenseln. |
| [getBlendPattern()](#getBlendPattern--) | Hämtar eller anger ett valfritt blandningsmönster för den linjära gradientpenseln. |
| [setBlendPattern(EmfPlusBlendBase[] value)](#setBlendPattern-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase---) | Hämtar eller anger ett valfritt blandningsmönster för den linjära gradientpenseln. |
| [getBlendPatternAsPresetColors()](#getBlendPatternAsPresetColors--) | Hämtar blandningsmönstret som förinställda färger. |
| [getBlendPatternAsBlendFactorsH()](#getBlendPatternAsBlendFactorsH--) | Hämtar blandningsmönstret som horisontella blandningsfaktorer. |
| [getBlendPatternAsBlendFactorsV()](#getBlendPatternAsBlendFactorsV--) | Hämtar blandningsmönstret som vertikala blandningsfaktorer. |
### EmfPlusLinearGradientBrushOptionalData() {#EmfPlusLinearGradientBrushOptionalData--}
```
public EmfPlusLinearGradientBrushOptionalData()
```


### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


Hämtar eller anger ett valfritt EmfPlusTransformMatrix-objekt (avsnitt 2.2.2.47) som specificerar en transformation från världsrummet till enhetligt utrymme för den linjära gradientpenseln. Detta fält MÅSTE vara närvarande om BrushDataTransform‑flaggan är satt i BrushDataFlags‑fältet för EmfPlusLinearGradientBrushData‑objektet.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


Hämtar eller anger ett valfritt EmfPlusTransformMatrix-objekt (avsnitt 2.2.2.47) som specificerar en transformation från världsrummet till enhetligt utrymme för den linjära gradientpenseln. Detta fält MÅSTE vara närvarande om BrushDataTransform‑flaggan är satt i BrushDataFlags‑fältet för EmfPlusLinearGradientBrushData‑objektet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getBlendPattern() {#getBlendPattern--}
```
public EmfPlusBlendBase[] getBlendPattern()
```


Hämtar eller anger ett valfritt blandningsmönster för den linjära gradientpenseln. Om detta fält är närvarande MÅSTE det innehålla antingen ett EmfPlusBlendColors-objekt (avsnitt 2.2.2.4) eller ett eller två EmfPlusBlendFactors-objekt (avsnitt 2.2.2.5), men det FÅR INTE innehålla båda. Tabellen nedan visar de giltiga kombinationerna av EmfPlusLinearGradientBrushData BrushData‑flaggor och motsvarande blandningsmönster: EmfPlusBlendFactors

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase[]
### setBlendPattern(EmfPlusBlendBase[] value) {#setBlendPattern-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase---}
```
public void setBlendPattern(EmfPlusBlendBase[] value)
```


Hämtar eller anger ett valfritt blandningsmönster för den linjära gradientpenseln. Om detta fält är närvarande MÅSTE det innehålla antingen ett EmfPlusBlendColors-objekt (avsnitt 2.2.2.4) eller ett eller två EmfPlusBlendFactors-objekt (avsnitt 2.2.2.5), men det FÅR INTE innehålla båda. Tabellen nedan visar de giltiga kombinationerna av EmfPlusLinearGradientBrushData BrushData‑flaggor och motsvarande blandningsmönster: EmfPlusBlendFactors

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfPlusBlendBase\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase) |  |

### getBlendPatternAsPresetColors() {#getBlendPatternAsPresetColors--}
```
public EmfPlusBlendColors getBlendPatternAsPresetColors()
```


Hämtar blandningsmönstret som förinställda färger.

Värde: Blandningsmönstret som förinställda färger.

**Returns:**
[EmfPlusBlendColors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors)
### getBlendPatternAsBlendFactorsH() {#getBlendPatternAsBlendFactorsH--}
```
public EmfPlusBlendFactors getBlendPatternAsBlendFactorsH()
```


Hämtar blandningsmönstret som horisontella blandningsfaktorer.

Värde: Blandningsmönstret som horisontella blandningsfaktorer.

**Returns:**
[EmfPlusBlendFactors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors)
### getBlendPatternAsBlendFactorsV() {#getBlendPatternAsBlendFactorsV--}
```
public EmfPlusBlendFactors getBlendPatternAsBlendFactorsV()
```


Hämtar blandningsmönstret som vertikala blandningsfaktorer.

Värde: Blandningsmönstret som vertikala blandningsfaktorer.

**Returns:**
[EmfPlusBlendFactors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors)
