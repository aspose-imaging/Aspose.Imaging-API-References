---
title: "EmfPlusPenData"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusPenData-objektet specificerar egenskaper för en grafikpenna."
type: docs
weight: 64
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusPenData extends EmfPlusStructureObjectType
```

EmfPlusPenData-objektet specificerar egenskaper för en grafikpenna.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusPenData()](#EmfPlusPenData--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPenDataFlags()](#getPenDataFlags--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar data i fältet OptionalData. |
| [setPenDataFlags(int value)](#setPenDataFlags-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar data i fältet OptionalData. |
| [getPenUnit()](#getPenUnit--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar mätenheterna för pennan. |
| [setPenUnit(int value)](#setPenUnit-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar mätenheterna för pennan. |
| [getPenWidth()](#getPenWidth--) | Hämtar eller anger ett 32-bitars flyttal som specificerar bredden på linjen som pennan ritar i de enheter som anges av fältet PenUnit. |
| [setPenWidth(float value)](#setPenWidth-float-) | Hämtar eller anger ett 32-bitars flyttal som specificerar bredden på linjen som pennan ritar i de enheter som anges av fältet PenUnit. |
| [getOptionalData()](#getOptionalData--) | Hämtar eller anger ett valfritt EmfPlusPenOptionalData-objekt (avsnitt 2.2.2.34) som specificerar ytterligare data för pennaobjektet. |
| [setOptionalData(EmfPlusPenOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPenOptionalData-) | Hämtar eller anger ett valfritt EmfPlusPenOptionalData-objekt (avsnitt 2.2.2.34) som specificerar ytterligare data för pennaobjektet. |
### EmfPlusPenData() {#EmfPlusPenData--}
```
public EmfPlusPenData()
```


### getPenDataFlags() {#getPenDataFlags--}
```
public int getPenDataFlags()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar data i fältet OptionalData. Detta värde MÅSTE bestå av PenData-flaggor (avsnitt 2.1.2.7).

**Returns:**
int
### setPenDataFlags(int value) {#setPenDataFlags-int-}
```
public void setPenDataFlags(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar data i fältet OptionalData. Detta värde MÅSTE bestå av PenData-flaggor (avsnitt 2.1.2.7).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getPenUnit() {#getPenUnit--}
```
public int getPenUnit()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar mätenheterna för pennan. Värdet MÅSTE vara från uppräkningen UnitType (avsnitt 2.1.1.33).

**Returns:**
int
### setPenUnit(int value) {#setPenUnit-int-}
```
public void setPenUnit(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar mätenheterna för pennan. Värdet MÅSTE vara från uppräkningen UnitType (avsnitt 2.1.1.33).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getPenWidth() {#getPenWidth--}
```
public float getPenWidth()
```


Hämtar eller anger ett 32-bitars flyttal som specificerar bredden på linjen som pennan ritar i de enheter som anges av fältet PenUnit. Om en bredd på noll anges används ett minimivärde, som bestäms av enheterna.

**Returns:**
float
### setPenWidth(float value) {#setPenWidth-float-}
```
public void setPenWidth(float value)
```


Hämtar eller anger ett 32-bitars flyttal som specificerar bredden på linjen som pennan ritar i de enheter som anges av fältet PenUnit. Om en bredd på noll anges används ett minimivärde, som bestäms av enheterna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusPenOptionalData getOptionalData()
```


Hämtar eller anger ett valfritt EmfPlusPenOptionalData-objekt (avsnitt 2.2.2.34) som specificerar ytterligare data för pennaobjektet. Det specifika innehållet i detta fält bestäms av värdet i fältet PenDataFlags.

**Returns:**
[EmfPlusPenOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata)
### setOptionalData(EmfPlusPenOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPenOptionalData-}
```
public void setOptionalData(EmfPlusPenOptionalData value)
```


Hämtar eller anger ett valfritt EmfPlusPenOptionalData-objekt (avsnitt 2.2.2.34) som specificerar ytterligare data för pennaobjektet. Det specifika innehållet i detta fält bestäms av värdet i fältet PenDataFlags.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfPlusPenOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata) |  |

