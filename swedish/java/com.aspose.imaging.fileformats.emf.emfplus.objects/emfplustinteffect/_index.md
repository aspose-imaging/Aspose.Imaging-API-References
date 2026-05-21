---
title: "EmfPlusTintEffect"
second_title: "Aspose.Imaging för Java API-referens"
description: "TintEffect-objektet specificerar en tillsats av svart eller vitt till en angiven nyans i en bild."
type: docs
weight: 79
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustinteffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusTintEffect extends EmfPlusImageEffectsObjectType
```

TintEffect-objektet specificerar en tillsats av svart eller vitt till en angiven nyans i en bild.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusTintEffect()](#EmfPlusTintEffect--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getHue()](#getHue--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar nyansen som toningseffekten tillämpas på. |
| [setHue(int value)](#setHue-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar nyansen som toningseffekten tillämpas på. |
| [getAmount()](#getAmount--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar hur mycket nyansen förstärks eller försvagas. |
| [setAmount(int value)](#setAmount-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar hur mycket nyansen förstärks eller försvagas. |
### EmfPlusTintEffect() {#EmfPlusTintEffect--}
```
public EmfPlusTintEffect()
```


### getHue() {#getHue--}
```
public int getHue()
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar nyansen som toningseffekten tillämpas på. -180 \\u2264 value < 0 Färgen vid en specificerad moturs rotation av färghjulet, med början från blå. 0 Ett värde på 0 specificerar färgen blå på färghjulet. 0 < value \\u2264 180 Färgen vid en specificerad medurs rotation av färghjulet, med början från blå.

**Returns:**
int
### setHue(int value) {#setHue-int-}
```
public void setHue(int value)
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar nyansen som toningseffekten tillämpas på. -180 \\u2264 value < 0 Färgen vid en specificerad moturs rotation av färghjulet, med början från blå. 0 Ett värde på 0 specificerar färgen blå på färghjulet. 0 < value \\u2264 180 Färgen vid en specificerad medurs rotation av färghjulet, med början från blå.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getAmount() {#getAmount--}
```
public int getAmount()
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar hur mycket nyansen förstärks eller försvagas. -100 \\u2264 value < 0 Negativa värden specificerar hur mycket nyansen försvagas, vilket motsvarar tillsats av svart. 0 Ett värde på 0 specificerar att toningen INTE FÅR ändras. 0 < value \\u2264 100 Positiva värden specificerar hur mycket nyansen förstärks, vilket motsvarar tillsats av vitt.

Värde: Mängden.

**Returns:**
int
### setAmount(int value) {#setAmount-int-}
```
public void setAmount(int value)
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar hur mycket nyansen förstärks eller försvagas. -100 \\u2264 value < 0 Negativa värden specificerar hur mycket nyansen försvagas, vilket motsvarar tillsats av svart. 0 Ett värde på 0 specificerar att toningen INTE FÅR ändras. 0 < value \\u2264 100 Positiva värden specificerar hur mycket nyansen förstärks, vilket motsvarar tillsats av vitt.

Värde: Mängden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

