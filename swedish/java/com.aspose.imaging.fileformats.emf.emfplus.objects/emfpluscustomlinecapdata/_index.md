---
title: "EmfPlusCustomLineCapData"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusCustomLineCapData-objektet specificerar standarddata för en anpassad linjekapsling."
type: docs
weight: 36
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomBaseLineCap](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustombaselinecap)
```
public final class EmfPlusCustomLineCapData extends EmfPlusCustomBaseLineCap
```

EmfPlusCustomLineCapData-objektet specificerar standarddata för en anpassad linjekapsling.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusCustomLineCapData()](#EmfPlusCustomLineCapData--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCustomLineCapDataFlags()](#getCustomLineCapDataFlags--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar data i OptionalData-fältet. |
| [setCustomLineCapDataFlags(int value)](#setCustomLineCapDataFlags-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar data i OptionalData-fältet. |
| [getBaseCap()](#getBaseCap--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar värdet från LineCap‑enumerationen (avsnitt 2.1.1.18) som den anpassade linjekappen baseras på. |
| [setBaseCap(int value)](#setBaseCap-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar värdet från LineCap‑enumerationen (avsnitt 2.1.1.18) som den anpassade linjekappen baseras på. |
| [getBaseInset()](#getBaseInset--) | Hämtar eller anger ett 32-bitars flyttal som specificerar avståndet mellan början av linjekappen och slutet av linjen. |
| [setBaseInset(float value)](#setBaseInset-float-) | Hämtar eller anger ett 32-bitars flyttal som specificerar avståndet mellan början av linjekappen och slutet av linjen. |
| [getStrokeStartCap()](#getStrokeStartCap--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar värdet i LineCap‑enumerationen som indikerar vilken linjekapp som används i början av den linje som ska ritas. |
| [setStrokeStartCap(int value)](#setStrokeStartCap-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar värdet i LineCap‑enumerationen som indikerar vilken linjekapp som används i början av den linje som ska ritas. |
| [getStrokeEndCap()](#getStrokeEndCap--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar värdet i LineCap‑enumerationen som indikerar vilken linjekapp som ska användas i slutet av den linje som ska ritas. |
| [setStrokeEndCap(int value)](#setStrokeEndCap-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar värdet i LineCap‑enumerationen som indikerar vilken linjekapp som ska användas i slutet av den linje som ska ritas. |
| [getStrokeJoin()](#getStrokeJoin--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar värdet i LineJoin‑enumerationen (avsnitt 2.1.1.19), vilket anger hur två linjer som ritas med samma penna och vars ändar möts ska förenas. |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar värdet i LineJoin‑enumerationen (avsnitt 2.1.1.19), vilket anger hur två linjer som ritas med samma penna och vars ändar möts ska förenas. |
| [getStrokeMiterLimit()](#getStrokeMiterLimit--) | Hämtar eller anger ett 32-bitars flyttal som innehåller gränsen för tjockleken på föreningen i ett snedställt hörn genom att ange det maximalt tillåtna förhållandet mellan snedställt längd och linjebredd. |
| [setStrokeMiterLimit(float value)](#setStrokeMiterLimit-float-) | Hämtar eller anger ett 32-bitars flyttal som innehåller gränsen för tjockleken på föreningen i ett snedställt hörn genom att ange det maximalt tillåtna förhållandet mellan snedställt längd och linjebredd. |
| [getWidthScale()](#getWidthScale--) | Hämtar eller anger ett 32‑bit flyttal som specificerar hur mycket den anpassade linjekappen ska skalas i förhållande till bredden på EmfPlusPen‑objektet (avsnitt 2.2.1.7) som används för att rita linjerna. |
| [setWidthScale(float value)](#setWidthScale-float-) | Hämtar eller anger ett 32‑bit flyttal som specificerar hur mycket den anpassade linjekappen ska skalas i förhållande till bredden på EmfPlusPen‑objektet (avsnitt 2.2.1.7) som används för att rita linjerna. |
| [getFillHotSpot()](#getFillHotSpot--) | Hämtar eller anger EmfPlusPointF‑objektet som för närvarande inte används. |
| [setFillHotSpot(PointF value)](#setFillHotSpot-com.aspose.imaging.PointF-) | Hämtar eller anger EmfPlusPointF‑objektet som för närvarande inte används. |
| [getStrokeHotSpot()](#getStrokeHotSpot--) | Hämtar eller anger EmfPlusPointF‑objektet som för närvarande inte används. |
| [setStrokeHotSpot(PointF value)](#setStrokeHotSpot-com.aspose.imaging.PointF-) | Hämtar eller anger EmfPlusPointF‑objektet som för närvarande inte används. |
| [getOptionalData()](#getOptionalData--) | Hämtar eller anger det valfria EmfPlusCustomLineCapOptionalData‑objektet (avsnitt 2.2.2.14) som specificerar ytterligare data för den anpassade grafiklinjekappen. |
| [setOptionalData(EmfPlusCustomLineCapOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomLineCapOptionalData-) | Hämtar eller anger det valfria EmfPlusCustomLineCapOptionalData‑objektet (avsnitt 2.2.2.14) som specificerar ytterligare data för den anpassade grafiklinjekappen. |
### EmfPlusCustomLineCapData() {#EmfPlusCustomLineCapData--}
```
public EmfPlusCustomLineCapData()
```


### getCustomLineCapDataFlags() {#getCustomLineCapDataFlags--}
```
public int getCustomLineCapDataFlags()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar data i OptionalData-fältet.

**Returns:**
int
### setCustomLineCapDataFlags(int value) {#setCustomLineCapDataFlags-int-}
```
public void setCustomLineCapDataFlags(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar data i OptionalData-fältet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getBaseCap() {#getBaseCap--}
```
public int getBaseCap()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar värdet från LineCap‑enumerationen (avsnitt 2.1.1.18) som den anpassade linjekappen baseras på.

**Returns:**
int
### setBaseCap(int value) {#setBaseCap-int-}
```
public void setBaseCap(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar värdet från LineCap‑enumerationen (avsnitt 2.1.1.18) som den anpassade linjekappen baseras på.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getBaseInset() {#getBaseInset--}
```
public float getBaseInset()
```


Hämtar eller anger ett 32-bitars flyttal som specificerar avståndet mellan början av linjekappen och slutet av linjen.

**Returns:**
float
### setBaseInset(float value) {#setBaseInset-float-}
```
public void setBaseInset(float value)
```


Hämtar eller anger ett 32-bitars flyttal som specificerar avståndet mellan början av linjekappen och slutet av linjen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getStrokeStartCap() {#getStrokeStartCap--}
```
public int getStrokeStartCap()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar värdet i LineCap‑enumerationen som indikerar vilken linjekapp som används i början av den linje som ska ritas.

**Returns:**
int
### setStrokeStartCap(int value) {#setStrokeStartCap-int-}
```
public void setStrokeStartCap(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar värdet i LineCap‑enumerationen som indikerar vilken linjekapp som används i början av den linje som ska ritas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getStrokeEndCap() {#getStrokeEndCap--}
```
public int getStrokeEndCap()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar värdet i LineCap‑enumerationen som indikerar vilken linjekapp som ska användas i slutet av den linje som ska ritas.

**Returns:**
int
### setStrokeEndCap(int value) {#setStrokeEndCap-int-}
```
public void setStrokeEndCap(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar värdet i LineCap‑enumerationen som indikerar vilken linjekapp som ska användas i slutet av den linje som ska ritas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getStrokeJoin() {#getStrokeJoin--}
```
public int getStrokeJoin()
```


Hämtar eller anger ett 32‑bit osignerat heltal som specificerar värdet i LineJoin‑enumerationen (avsnitt 2.1.1.19), vilken anger hur två linjer som ritas med samma penna och vars ändar möts ska förenas. Vid skärningspunkten mellan de två linjeändarna gör en linjesammanslagning anslutningen mer kontinuerlig.

**Returns:**
int
### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public void setStrokeJoin(int value)
```


Hämtar eller anger ett 32‑bit osignerat heltal som specificerar värdet i LineJoin‑enumerationen (avsnitt 2.1.1.19), vilken anger hur två linjer som ritas med samma penna och vars ändar möts ska förenas. Vid skärningspunkten mellan de två linjeändarna gör en linjesammanslagning anslutningen mer kontinuerlig.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getStrokeMiterLimit() {#getStrokeMiterLimit--}
```
public float getStrokeMiterLimit()
```


Hämtar eller anger ett 32-bitars flyttal som innehåller gränsen för tjockleken på föreningen i ett snedställt hörn genom att ange det maximalt tillåtna förhållandet mellan snedställt längd och linjebredd.

**Returns:**
float
### setStrokeMiterLimit(float value) {#setStrokeMiterLimit-float-}
```
public void setStrokeMiterLimit(float value)
```


Hämtar eller anger ett 32-bitars flyttal som innehåller gränsen för tjockleken på föreningen i ett snedställt hörn genom att ange det maximalt tillåtna förhållandet mellan snedställt längd och linjebredd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getWidthScale() {#getWidthScale--}
```
public float getWidthScale()
```


Hämtar eller anger ett 32‑bit flyttal som specificerar hur mycket den anpassade linjekappen ska skalas i förhållande till bredden på EmfPlusPen‑objektet (avsnitt 2.2.1.7) som används för att rita linjerna.

**Returns:**
float
### setWidthScale(float value) {#setWidthScale-float-}
```
public void setWidthScale(float value)
```


Hämtar eller anger ett 32‑bit flyttal som specificerar hur mycket den anpassade linjekappen ska skalas i förhållande till bredden på EmfPlusPen‑objektet (avsnitt 2.2.1.7) som används för att rita linjerna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getFillHotSpot() {#getFillHotSpot--}
```
public PointF getFillHotSpot()
```


Hämtar eller anger EmfPlusPointF‑objektet som för närvarande inte används. Det MÅSTE sättas till \\{0.0, 0.0\\}.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### setFillHotSpot(PointF value) {#setFillHotSpot-com.aspose.imaging.PointF-}
```
public void setFillHotSpot(PointF value)
```


Hämtar eller anger EmfPlusPointF‑objektet som för närvarande inte används. Det MÅSTE sättas till \\{0.0, 0.0\\}.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

### getStrokeHotSpot() {#getStrokeHotSpot--}
```
public PointF getStrokeHotSpot()
```


Hämtar eller anger EmfPlusPointF‑objektet som för närvarande inte används. Det MÅSTE sättas till \\{0.0, 0.0\\}.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### setStrokeHotSpot(PointF value) {#setStrokeHotSpot-com.aspose.imaging.PointF-}
```
public void setStrokeHotSpot(PointF value)
```


Hämtar eller anger EmfPlusPointF‑objektet som för närvarande inte används. Det MÅSTE sättas till \\{0.0, 0.0\\}.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusCustomLineCapOptionalData getOptionalData()
```


Hämtar eller anger det valfria EmfPlusCustomLineCapOptionalData‑objektet (avsnitt 2.2.2.14) som specificerar ytterligare data för den anpassade grafiklinjekappen. De specifika innehållen i detta fält bestäms av värdet i CustomLineCapDataFlags‑fältet.

**Returns:**
[EmfPlusCustomLineCapOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata)
### setOptionalData(EmfPlusCustomLineCapOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomLineCapOptionalData-}
```
public void setOptionalData(EmfPlusCustomLineCapOptionalData value)
```


Hämtar eller anger det valfria EmfPlusCustomLineCapOptionalData‑objektet (avsnitt 2.2.2.14) som specificerar ytterligare data för den anpassade grafiklinjekappen. De specifika innehållen i detta fält bestäms av värdet i CustomLineCapDataFlags‑fältet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfPlusCustomLineCapOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata) |  |

