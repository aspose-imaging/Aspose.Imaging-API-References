---
title: "EmfPlusPathGradientBrushOptionalData"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusPathGradientBrushOptionalData-objektet specificerar valfri data för en bangradientpensel."
type: docs
weight: 60
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusPathGradientBrushOptionalData extends EmfPlusStructureObjectType
```

EmfPlusPathGradientBrushOptionalData-objektet specificerar valfri data för en bangradientpensel.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusPathGradientBrushOptionalData()](#EmfPlusPathGradientBrushOptionalData--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getTransformMatrix()](#getTransformMatrix--) | Hämtar eller anger ett valfritt EmfPlusTransformMatrix‑objekt (avsnitt 2.2.2.47) som specificerar en transform från världsrummet till enhetsrummet för path‑gradientpenseln. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | Hämtar eller anger ett valfritt EmfPlusTransformMatrix‑objekt (avsnitt 2.2.2.47) som specificerar en transform från världsrummet till enhetsrummet för path‑gradientpenseln. |
| [getBlendPattern()](#getBlendPattern--) | Hämtar eller anger ett valfritt blandningsmönster för path gradient brush. |
| [setBlendPattern(EmfPlusBlendBase value)](#setBlendPattern-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase-) | Hämtar eller anger ett valfritt blandningsmönster för path gradient brush. |
| [getFocusScaleData()](#getFocusScaleData--) | Hämtar eller anger ett valfritt EmfPlusFocusScaleData‑objekt (avsnitt 2.2.2.18) som specificerar fokusskalor för path gradient brush. |
| [setFocusScaleData(EmfPlusFocusScaleData value)](#setFocusScaleData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusFocusScaleData-) | Hämtar eller anger ett valfritt EmfPlusFocusScaleData‑objekt (avsnitt 2.2.2.18) som specificerar fokusskalor för path gradient brush. |
### EmfPlusPathGradientBrushOptionalData() {#EmfPlusPathGradientBrushOptionalData--}
```
public EmfPlusPathGradientBrushOptionalData()
```


### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


Hämtar eller anger ett valfritt EmfPlusTransformMatrix‑objekt (avsnitt 2.2.2.47) som specificerar en transform från världsrummet till enhetsrummet för path gradient brush. Detta fält MÅSTE vara närvarande om BrushDataTransform‑flaggan är satt i BrushDataFlags‑fältet i EmfPlusPathGradientBrushData‑objektet.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


Hämtar eller anger ett valfritt EmfPlusTransformMatrix‑objekt (avsnitt 2.2.2.47) som specificerar en transform från världsrummet till enhetsrummet för path gradient brush. Detta fält MÅSTE vara närvarande om BrushDataTransform‑flaggan är satt i BrushDataFlags‑fältet i EmfPlusPathGradientBrushData‑objektet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getBlendPattern() {#getBlendPattern--}
```
public EmfPlusBlendBase getBlendPattern()
```


Hämtar eller anger ett valfritt blandningsmönster för path gradient brush. Om detta fält är närvarande, MÅSTE det innehålla antingen ett EmfPlusBlendColors‑objekt (avsnitt 2.2.2.4) eller ett EmfPlusBlendFactors‑objekt (avsnitt 2.2.2.5), men det FÅR INTE innehålla båda. Tabellen nedan visar de giltiga kombinationerna av EmfPlusPathGradientBrushData BrushData‑flaggor och motsvarande blandningsmönster:

**Returns:**
[EmfPlusBlendBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase)
### setBlendPattern(EmfPlusBlendBase value) {#setBlendPattern-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase-}
```
public void setBlendPattern(EmfPlusBlendBase value)
```


Hämtar eller anger ett valfritt blandningsmönster för path gradient brush. Om detta fält är närvarande, MÅSTE det innehålla antingen ett EmfPlusBlendColors‑objekt (avsnitt 2.2.2.4) eller ett EmfPlusBlendFactors‑objekt (avsnitt 2.2.2.5), men det FÅR INTE innehålla båda. Tabellen nedan visar de giltiga kombinationerna av EmfPlusPathGradientBrushData BrushData‑flaggor och motsvarande blandningsmönster:

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfPlusBlendBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase) |  |

### getFocusScaleData() {#getFocusScaleData--}
```
public EmfPlusFocusScaleData getFocusScaleData()
```


Hämtar eller anger ett valfritt EmfPlusFocusScaleData‑objekt (avsnitt 2.2.2.18) som specificerar fokusskalor för path gradient brush. Detta fält MÅSTE vara närvarande om BrushDataFocusScales‑flaggan är satt i BrushDataFlags‑fältet i EmfPlusPathGradientBrushData‑objektet.

**Returns:**
[EmfPlusFocusScaleData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata)
### setFocusScaleData(EmfPlusFocusScaleData value) {#setFocusScaleData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusFocusScaleData-}
```
public void setFocusScaleData(EmfPlusFocusScaleData value)
```


Hämtar eller anger ett valfritt EmfPlusFocusScaleData‑objekt (avsnitt 2.2.2.18) som specificerar fokusskalor för path gradient brush. Detta fält MÅSTE vara närvarande om BrushDataFocusScales‑flaggan är satt i BrushDataFlags‑fältet i EmfPlusPathGradientBrushData‑objektet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfPlusFocusScaleData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata) |  |

