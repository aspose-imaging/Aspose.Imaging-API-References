---
title: "EmfPlusTextureBrushData"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusTextureBrushData-objektet specificerar en texturbild för en grafikpensel."
type: docs
weight: 77
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
```
public final class EmfPlusTextureBrushData extends EmfPlusBaseBrushData
```

EmfPlusTextureBrushData-objektet specificerar en texturbild för en grafikpensel.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusTextureBrushData()](#EmfPlusTextureBrushData--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBrushDataFlags()](#getBrushDataFlags--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar data i OptionalData-fältet. |
| [setBrushDataFlags(int value)](#setBrushDataFlags-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar data i OptionalData-fältet. |
| [getWrapMode()](#getWrapMode--) | Hämtar eller anger ett 32-bitars signerat heltal från WrapMode‑enumerationen (avsnitt 2.1.1.34) som specificerar hur texturbilden ska upprepas över en form när bilden är mindre än det område som fylls. |
| [setWrapMode(int value)](#setWrapMode-int-) | Hämtar eller anger ett 32-bitars signerat heltal från WrapMode‑enumerationen (avsnitt 2.1.1.34) som specificerar hur texturbilden ska upprepas över en form när bilden är mindre än det område som fylls. |
| [getOptionalData()](#getOptionalData--) | Hämtar eller anger ett valfritt EmfPlusTextureBrushOptionalData‑objekt (avsnitt 2.2.2.46) som specificerar ytterligare data för texturpenseln. |
| [setOptionalData(EmfPlusTextureBrushOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTextureBrushOptionalData-) | Hämtar eller anger ett valfritt EmfPlusTextureBrushOptionalData‑objekt (avsnitt 2.2.2.46) som specificerar ytterligare data för texturpenseln. |
### EmfPlusTextureBrushData() {#EmfPlusTextureBrushData--}
```
public EmfPlusTextureBrushData()
```


### getBrushDataFlags() {#getBrushDataFlags--}
```
public int getBrushDataFlags()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar data i OptionalData-fältet. Detta värde MÅSTE bestå av BrushData‑flaggor (avsnitt 2.1.2.1). Följande flaggor är relevanta för en texturpensel: BrushDataTransform, BrushDataIsGammaCorrected, BrushDataDoNotTransform

**Returns:**
int
### setBrushDataFlags(int value) {#setBrushDataFlags-int-}
```
public void setBrushDataFlags(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar data i OptionalData-fältet. Detta värde MÅSTE bestå av BrushData‑flaggor (avsnitt 2.1.2.1). Följande flaggor är relevanta för en texturpensel: BrushDataTransform, BrushDataIsGammaCorrected, BrushDataDoNotTransform

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Hämtar eller anger ett 32-bitars signerat heltal från WrapMode‑enumerationen (avsnitt 2.1.1.34) som specificerar hur texturbilden ska upprepas över en form när bilden är mindre än det område som fylls.

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Hämtar eller anger ett 32-bitars signerat heltal från WrapMode‑enumerationen (avsnitt 2.1.1.34) som specificerar hur texturbilden ska upprepas över en form när bilden är mindre än det område som fylls.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusTextureBrushOptionalData getOptionalData()
```


Hämtar eller anger ett valfritt EmfPlusTextureBrushOptionalData‑objekt (avsnitt 2.2.2.46) som specificerar ytterligare data för texturpenseln. Det specifika innehållet i detta fält bestäms av värdet i BrushDataFlags‑fältet.

**Returns:**
[EmfPlusTextureBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata)
### setOptionalData(EmfPlusTextureBrushOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTextureBrushOptionalData-}
```
public void setOptionalData(EmfPlusTextureBrushOptionalData value)
```


Hämtar eller anger ett valfritt EmfPlusTextureBrushOptionalData‑objekt (avsnitt 2.2.2.46) som specificerar ytterligare data för texturpenseln. Det specifika innehållet i detta fält bestäms av värdet i BrushDataFlags‑fältet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfPlusTextureBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata) |  |

