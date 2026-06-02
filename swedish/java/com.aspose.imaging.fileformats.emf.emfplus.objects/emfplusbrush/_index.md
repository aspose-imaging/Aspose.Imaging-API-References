---
title: "EmfPlusBrush"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusBrush-objektet specificerar en grafikpensel för att fylla regioner."
type: docs
weight: 24
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusBrush extends EmfPlusGraphicsObjectType
```

EmfPlusBrush-objektet specificerar en grafikpensel för att fylla regioner.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusBrush()](#EmfPlusBrush--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBrushData()](#getBrushData--) | Hämtar eller anger Brush‑data Variabel‑längd data som definierar brush‑objektet som anges i Type‑fältet. |
| [setBrushData(EmfPlusBaseBrushData value)](#setBrushData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData-) | Hämtar eller anger Brush‑data Variabel‑längd data som definierar brush‑objektet som anges i Type‑fältet. |
| [getType()](#getType--) | Hämtar eller anger typen. |
| [setType(int value)](#setType-int-) | Hämtar eller anger typen. |
### EmfPlusBrush() {#EmfPlusBrush--}
```
public EmfPlusBrush()
```


### getBrushData() {#getBrushData--}
```
public EmfPlusBaseBrushData getBrushData()
```


Hämtar eller anger Brush‑data Variabel‑längd data som definierar brush‑objektet som anges i Type‑fältet. Innehållet och formatet på data kan variera för varje brush‑typ. EmfPlusHatchBrushData (section 2.2.2.20) (done) EmfPlusLinearGradientBrushData objekt (section 2.2.2.24) (done) EmfPlusPathGradientBrushData objekt (section 2.2.2.29) (done) EmfPlusSolidBrushData objekt (section 2.2.2.43) (done) EmfPlusTextureBrushData objekt (section 2.2.2.45) (done)

Värde: Brush‑data.

**Returns:**
[EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
### setBrushData(EmfPlusBaseBrushData value) {#setBrushData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData-}
```
public void setBrushData(EmfPlusBaseBrushData value)
```


Hämtar eller anger Brush‑data Variabel‑längd data som definierar brush‑objektet som anges i Type‑fältet. Innehållet och formatet på data kan variera för varje brush‑typ. EmfPlusHatchBrushData (section 2.2.2.20) (done) EmfPlusLinearGradientBrushData objekt (section 2.2.2.24) (done) EmfPlusPathGradientBrushData objekt (section 2.2.2.29) (done) EmfPlusSolidBrushData objekt (section 2.2.2.43) (done) EmfPlusTextureBrushData objekt (section 2.2.2.45) (done)

Värde: Brush‑data.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata) |  |

### getType() {#getType--}
```
public int getType()
```


Hämtar eller anger typen.

Värde: Ett 32‑bitars osignerat heltal som specificerar brush‑typen, vilket bestämmer innehållet i BrushData‑fältet. Detta värde MÅSTE definieras i `EmfPlusBrushType`‑enumerationen.

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Hämtar eller anger typen.

Värde: Ett 32‑bitars osignerat heltal som specificerar brush‑typen, vilket bestämmer innehållet i BrushData‑fältet. Detta värde MÅSTE definieras i `EmfPlusBrushType`‑enumerationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

