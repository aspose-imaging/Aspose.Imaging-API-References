---
title: "EmfPlusBrightnessContrastEffect"
second_title: "Aspose.Imaging för Java API-referens"
description: "BrightnessContrastEffect-objektet specificerar en utvidgning eller sammandragning av de ljusaste och mörkaste områdena i en bild."
type: docs
weight: 23
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbrightnesscontrasteffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusBrightnessContrastEffect extends EmfPlusImageEffectsObjectType
```

BrightnessContrastEffect-objektet specificerar en utvidgning eller sammandragning av de ljusaste och mörkaste områdena i en bild.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusBrightnessContrastEffect()](#EmfPlusBrightnessContrastEffect--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBrightnessLevel()](#getBrightnessLevel--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar ljusstyrkenivån. |
| [setBrightnessLevel(int value)](#setBrightnessLevel-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar ljusstyrkenivån. |
| [getContrastLevel()](#getContrastLevel--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar kontrastnivån. |
| [setContrastLevel(int value)](#setContrastLevel-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar kontrastnivån. |
### EmfPlusBrightnessContrastEffect() {#EmfPlusBrightnessContrastEffect--}
```
public EmfPlusBrightnessContrastEffect()
```


### getBrightnessLevel() {#getBrightnessLevel--}
```
public int getBrightnessLevel()
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar ljusstyrkenivån. Detta värde MÅSTE vara i intervallet -255 till 255, med följande effekter: -255 \\u2264 värde < 0 När värdet minskar bör bildens ljusstyrka MINSKA. 0 Ett värde på 0 anger att ljusstyrkan INTE får förändras. 0 < värde \\u2264 255 När värdet ökar bör bildens ljusstyrka ÖKA.

**Returns:**
int
### setBrightnessLevel(int value) {#setBrightnessLevel-int-}
```
public void setBrightnessLevel(int value)
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar ljusstyrkenivån. Detta värde MÅSTE vara i intervallet -255 till 255, med följande effekter: -255 \\u2264 värde < 0 När värdet minskar bör bildens ljusstyrka MINSKA. 0 Ett värde på 0 anger att ljusstyrkan INTE får förändras. 0 < värde \\u2264 255 När värdet ökar bör bildens ljusstyrka ÖKA.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getContrastLevel() {#getContrastLevel--}
```
public int getContrastLevel()
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar kontrastnivån. Detta värde MÅSTE vara i intervallet -100 till 100, med följande effekter: -100 \\u2264 värde < 0 När värdet minskar bör bildens kontrast MINSKA. 0 Ett värde på 0 anger att kontrasten INTE får förändras. 0 < värde \\u2264 100 När värdet ökar bör bildens kontrast ÖKA.

**Returns:**
int
### setContrastLevel(int value) {#setContrastLevel-int-}
```
public void setContrastLevel(int value)
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar kontrastnivån. Detta värde MÅSTE vara i intervallet -100 till 100, med följande effekter: -100 \\u2264 värde < 0 När värdet minskar bör bildens kontrast MINSKA. 0 Ett värde på 0 anger att kontrasten INTE får förändras. 0 < värde \\u2264 100 När värdet ökar bör bildens kontrast ÖKA.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

