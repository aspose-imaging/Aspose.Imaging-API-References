---
title: "EmfPlusPenOptionalData"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusPenOptionalData-objektet specificerar valfri data för en grafikpenna"
type: docs
weight: 65
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusPenOptionalData extends EmfPlusStructureObjectType
```

EmfPlusPenOptionalData-objektet specificerar valfri data för en grafikpenna
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusPenOptionalData()](#EmfPlusPenOptionalData--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getTransformMatrix()](#getTransformMatrix--) | Hämtar eller anger ett valfritt EmfPlusTransformMatrix‑objekt (section 2.2.2.47) som specificerar en transform från världsrummet till enhetsrummet för pennan. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | Hämtar eller anger ett valfritt EmfPlusTransformMatrix‑objekt (section 2.2.2.47) som specificerar en transform från världsrummet till enhetsrummet för pennan. |
| [getStartCap()](#getStartCap--) | Hämtar eller anger ett valfritt 32‑bitars signerat heltal som specificerar formen för början av en linje i fältet CustomStartCapData. |
| [setStartCap(int value)](#setStartCap-int-) | Hämtar eller anger ett valfritt 32‑bitars signerat heltal som specificerar formen för början av en linje i fältet CustomStartCapData. |
| [getEndCap()](#getEndCap--) | Hämtar eller anger ett valfritt 32‑bitars signerat heltal som specificerar formen för slutet av en linje i fältet CustomEndCapData. |
| [setEndCap(int value)](#setEndCap-int-) | Hämtar eller anger ett valfritt 32‑bitars signerat heltal som specificerar formen för slutet av en linje i fältet CustomEndCapData. |
| [getJoin()](#getJoin--) | Hämtar eller anger ett valfritt 32‑bitars signerat heltal som specificerar hur två linjer som ritas med samma penna och vars ändar möts ska förenas. |
| [setJoin(int value)](#setJoin-int-) | Hämtar eller anger ett valfritt 32‑bitars signerat heltal som specificerar hur två linjer som ritas med samma penna och vars ändar möts ska förenas. |
| [getMiterLimit()](#getMiterLimit--) | Hämtar eller anger ett valfritt 32‑bitars flyttal som specificerar miter‑gränsen, vilket är det maximalt tillåtna förhållandet mellan miter‑längd och linjebredd. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Hämtar eller anger ett valfritt 32‑bitars flyttal som specificerar miter‑gränsen, vilket är det maximalt tillåtna förhållandet mellan miter‑längd och linjebredd. |
| [getLineStyle()](#getLineStyle--) | Hämtar eller anger ett valfritt 32‑bitars signerat heltal som specificerar stilen som används för linjer som ritas med detta penna‑objekt. |
| [setLineStyle(int value)](#setLineStyle-int-) | Hämtar eller anger ett valfritt 32‑bitars signerat heltal som specificerar stilen som används för linjer som ritas med detta penna‑objekt. |
| [getDashedLineCapType()](#getDashedLineCapType--) | Hämtar eller anger ett valfritt 32‑bitars signerat heltal som specificerar formen för båda ändarna av varje streck i en streckad linje. |
| [setDashedLineCapType(int value)](#setDashedLineCapType-int-) | Hämtar eller anger ett valfritt 32‑bitars signerat heltal som specificerar formen för båda ändarna av varje streck i en streckad linje. |
| [getDashOffset()](#getDashOffset--) | Hämtar eller anger ett valfritt 32‑bitars flyttal som specificerar avståndet från början av en linje till början av det första mellanrummet i ett streckat linjemönster. |
| [setDashOffset(float value)](#setDashOffset-float-) | Hämtar eller anger ett valfritt 32‑bitars flyttal som specificerar avståndet från början av en linje till början av det första mellanrummet i ett streckat linjemönster. |
| [getDashedLineData()](#getDashedLineData--) | Hämtar eller anger ett valfritt EmfPlusDashedLineData‑objekt (section 2.2.2.16) som specificerar längderna på streck och mellanrum i en anpassad streckad linje. |
| [setDashedLineData(EmfPlusDashedLineData value)](#setDashedLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusDashedLineData-) | Hämtar eller anger ett valfritt EmfPlusDashedLineData‑objekt (section 2.2.2.16) som specificerar längderna på streck och mellanrum i en anpassad streckad linje. |
| [getPenAlignment()](#getPenAlignment--) | Hämtar eller anger ett valfritt 32‑bitars signerat heltal som specificerar fördelningen av penndjupet i förhållande till koordinaterna för den linje som ritas. |
| [setPenAlignment(int value)](#setPenAlignment-int-) | Hämtar eller anger ett valfritt 32‑bitars signerat heltal som specificerar fördelningen av penndjupet i förhållande till koordinaterna för den linje som ritas. |
| [getCompoundLineData()](#getCompoundLineData--) | Hämtar eller anger ett valfritt EmfPlusCompoundLineData‑objekt (section 2.2.2.9) som specificerar en array av flyttal som definierar en sammansatt linje för en penna, vilken består av parallella linjer och mellanrum. |
| [setCompoundLineData(EmfPlusCompoundLineData value)](#setCompoundLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCompoundLineData-) | Hämtar eller anger ett valfritt EmfPlusCompoundLineData‑objekt (section 2.2.2.9) som specificerar en array av flyttal som definierar en sammansatt linje för en penna, vilken består av parallella linjer och mellanrum. |
| [getCustomStartCapData()](#getCustomStartCapData--) | Hämtar eller anger ett valfritt EmfPlusCustomStartCapData‑objekt (section 2.2.2.15) som definierar den anpassade startkapformen, vilken är den form som ska användas i början av en linje som ritas med denna penna. |
| [setCustomStartCapData(EmfPlusCustomStartCapData value)](#setCustomStartCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomStartCapData-) | Hämtar eller anger ett valfritt EmfPlusCustomStartCapData‑objekt (section 2.2.2.15) som definierar den anpassade startkapformen, vilken är den form som ska användas i början av en linje som ritas med denna penna. |
| [getCustomEndCapData()](#getCustomEndCapData--) | Hämtar eller anger ett valfritt EmfPlusCustomEndCapData‑objekt (section 2.2.2.11) som definierar den anpassade slutkapformen, vilken är den form som ska användas i slutet av en linje som ritas med denna penna. |
| [setCustomEndCapData(EmfPlusCustomEndCapData value)](#setCustomEndCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomEndCapData-) | Hämtar eller anger ett valfritt EmfPlusCustomEndCapData‑objekt (section 2.2.2.11) som definierar den anpassade slutkapformen, vilken är den form som ska användas i slutet av en linje som ritas med denna penna. |
### EmfPlusPenOptionalData() {#EmfPlusPenOptionalData--}
```
public EmfPlusPenOptionalData()
```


### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


Hämtar eller anger ett valfritt EmfPlusTransformMatrix‑objekt (section 2.2.2.47) som specificerar en transform från världsrummet till enhetsrummet för pennan. Detta fält MÅSTE finnas om PenDataTransform‑flaggan är satt i PenDataFlags‑fältet för EmfPlusPenData‑objektet.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


Hämtar eller anger ett valfritt EmfPlusTransformMatrix‑objekt (section 2.2.2.47) som specificerar en transform från världsrummet till enhetsrummet för pennan. Detta fält MÅSTE finnas om PenDataTransform‑flaggan är satt i PenDataFlags‑fältet för EmfPlusPenData‑objektet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getStartCap() {#getStartCap--}
```
public int getStartCap()
```


Hämtar eller anger ett valfritt 32‑bitars signerat heltal som specificerar formen för början av en linje i fältet CustomStartCapData. Detta fält MÅSTE finnas om PenDataStartCap‑flaggan är satt i PenDataFlags‑fältet för EmfPlusPenData‑objektet, och värdet MÅSTE definieras i LineCapType‑enumerationen (section 2.1.1.18).

**Returns:**
int
### setStartCap(int value) {#setStartCap-int-}
```
public void setStartCap(int value)
```


Hämtar eller anger ett valfritt 32‑bitars signerat heltal som specificerar formen för början av en linje i fältet CustomStartCapData. Detta fält MÅSTE finnas om PenDataStartCap‑flaggan är satt i PenDataFlags‑fältet för EmfPlusPenData‑objektet, och värdet MÅSTE definieras i LineCapType‑enumerationen (section 2.1.1.18).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getEndCap() {#getEndCap--}
```
public int getEndCap()
```


Hämtar eller anger ett valfritt 32‑bitars signerat heltal som specificerar formen för slutet av en linje i fältet CustomEndCapData. Detta fält MÅSTE finnas om PenDataEndCap‑flaggan är satt i PenDataFlags‑fältet för EmfPlusPenData‑objektet, och värdet MÅSTE definieras i LineCapType‑enumerationen.

**Returns:**
int
### setEndCap(int value) {#setEndCap-int-}
```
public void setEndCap(int value)
```


Hämtar eller anger ett valfritt 32‑bitars signerat heltal som specificerar formen för slutet av en linje i fältet CustomEndCapData. Detta fält MÅSTE finnas om PenDataEndCap‑flaggan är satt i PenDataFlags‑fältet för EmfPlusPenData‑objektet, och värdet MÅSTE definieras i LineCapType‑enumerationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getJoin() {#getJoin--}
```
public int getJoin()
```


Hämtar eller anger ett valfritt 32‑bitars signerat heltal som specificerar hur två linjer som ritas med samma penna och vars ändar möts ska förenas. Detta fält MÅSTE vara närvarande om PenDataJoin‑flaggan är satt i PenDataFlags‑fältet i EmfPlusPenData‑objektet, och värdet MÅSTE vara definierat i LineJoinType‑enumerationen (avsnitt 2.1.1.19).

**Returns:**
int
### setJoin(int value) {#setJoin-int-}
```
public void setJoin(int value)
```


Hämtar eller anger ett valfritt 32‑bitars signerat heltal som specificerar hur två linjer som ritas med samma penna och vars ändar möts ska förenas. Detta fält MÅSTE vara närvarande om PenDataJoin‑flaggan är satt i PenDataFlags‑fältet i EmfPlusPenData‑objektet, och värdet MÅSTE vara definierat i LineJoinType‑enumerationen (avsnitt 2.1.1.19).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getMiterLimit() {#getMiterLimit--}
```
public float getMiterLimit()
```


Hämtar eller anger ett valfritt 32‑bitars flyttal som specificerar snittgränsen, vilket är det maximalt tillåtna förhållandet mellan snittlängd och linjebredd. Snittlängden är avståndet från skärningspunkten mellan linjens väggar på insidan av föreningen till skärningspunkten mellan linjens väggar på utsidan av föreningen. Snittlängden kan bli stor när vinkeln mellan två linjer är liten. Detta fält MÅSTE vara närvarande om PenDataMiterLimit‑flaggan är satt i PenDataFlags‑fältet i EmfPlusPenData‑objektet.

**Returns:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public void setMiterLimit(float value)
```


Hämtar eller anger ett valfritt 32‑bitars flyttal som specificerar snittgränsen, vilket är det maximalt tillåtna förhållandet mellan snittlängd och linjebredd. Snittlängden är avståndet från skärningspunkten mellan linjens väggar på insidan av föreningen till skärningspunkten mellan linjens väggar på utsidan av föreningen. Snittlängden kan bli stor när vinkeln mellan två linjer är liten. Detta fält MÅSTE vara närvarande om PenDataMiterLimit‑flaggan är satt i PenDataFlags‑fältet i EmfPlusPenData‑objektet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getLineStyle() {#getLineStyle--}
```
public int getLineStyle()
```


Hämtar eller anger ett valfritt 32‑bitars signerat heltal som specificerar stil som används för linjer som ritas med detta penna‑objekt. Detta fält MÅSTE vara närvarande om PenDataLineStyle‑flaggan är satt i PenDataFlags‑fältet i EmfPlusPenData‑objektet, och värdet MÅSTE vara definierat i LineStyle‑enumerationen (avsnitt 2.1.1.20).

**Returns:**
int
### setLineStyle(int value) {#setLineStyle-int-}
```
public void setLineStyle(int value)
```


Hämtar eller anger ett valfritt 32‑bitars signerat heltal som specificerar stil som används för linjer som ritas med detta penna‑objekt. Detta fält MÅSTE vara närvarande om PenDataLineStyle‑flaggan är satt i PenDataFlags‑fältet i EmfPlusPenData‑objektet, och värdet MÅSTE vara definierat i LineStyle‑enumerationen (avsnitt 2.1.1.20).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getDashedLineCapType() {#getDashedLineCapType--}
```
public int getDashedLineCapType()
```


Hämtar eller anger ett valfritt 32‑bitars signerat heltal som specificerar formen för båda ändarna av varje streck i en streckad linje. Detta fält MÅSTE vara närvarande om PenDataDashedLineCap‑flaggan är satt i PenDataFlags‑fältet i EmfPlusPenData‑objektet, och värdet MÅSTE vara definierat i DashedLineCapType‑enumerationen (avsnitt 2.1.1.10).

**Returns:**
int
### setDashedLineCapType(int value) {#setDashedLineCapType-int-}
```
public void setDashedLineCapType(int value)
```


Hämtar eller anger ett valfritt 32‑bitars signerat heltal som specificerar formen för båda ändarna av varje streck i en streckad linje. Detta fält MÅSTE vara närvarande om PenDataDashedLineCap‑flaggan är satt i PenDataFlags‑fältet i EmfPlusPenData‑objektet, och värdet MÅSTE vara definierat i DashedLineCapType‑enumerationen (avsnitt 2.1.1.10).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getDashOffset() {#getDashOffset--}
```
public float getDashOffset()
```


Hämtar eller anger ett valfritt 32‑bitars flyttal som specificerar avståndet från början av en linje till början av det första mellanrummet i ett streckat linjemönster. Detta fält MÅSTE vara närvarande om PenDataDashedLineOffset‑flaggan är satt i PenDataFlags‑fältet i EmfPlusPenData‑objektet.

**Returns:**
float
### setDashOffset(float value) {#setDashOffset-float-}
```
public void setDashOffset(float value)
```


Hämtar eller anger ett valfritt 32‑bitars flyttal som specificerar avståndet från början av en linje till början av det första mellanrummet i ett streckat linjemönster. Detta fält MÅSTE vara närvarande om PenDataDashedLineOffset‑flaggan är satt i PenDataFlags‑fältet i EmfPlusPenData‑objektet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getDashedLineData() {#getDashedLineData--}
```
public EmfPlusDashedLineData getDashedLineData()
```


Hämtar eller anger ett valfritt EmfPlusDashedLineData‑objekt (avsnitt 2.2.2.16) som specificerar längderna på streck och mellanrum i en anpassad streckad linje. Detta fält MÅSTE vara närvarande om PenDataDashedLine‑flaggan är satt i PenDataFlags‑fältet i EmfPlusPenData‑objektet.

**Returns:**
[EmfPlusDashedLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusdashedlinedata)
### setDashedLineData(EmfPlusDashedLineData value) {#setDashedLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusDashedLineData-}
```
public void setDashedLineData(EmfPlusDashedLineData value)
```


Hämtar eller anger ett valfritt EmfPlusDashedLineData‑objekt (avsnitt 2.2.2.16) som specificerar längderna på streck och mellanrum i en anpassad streckad linje. Detta fält MÅSTE vara närvarande om PenDataDashedLine‑flaggan är satt i PenDataFlags‑fältet i EmfPlusPenData‑objektet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfPlusDashedLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusdashedlinedata) |  |

### getPenAlignment() {#getPenAlignment--}
```
public int getPenAlignment()
```


Hämtar eller anger ett valfritt 32‑bitars signerat heltal som specificerar fördelningen av pennbredden i förhållande till koordinaterna för den linje som ritas. Detta fält MÅSTE vara närvarande om PenDataNonCenter‑flaggan är satt i PenDataFlags‑fältet i EmfPlusPenData‑objektet, och värdet MÅSTE vara definierat i PenAlignment‑enumerationen (avsnitt 2.1.1.24).

**Returns:**
int
### setPenAlignment(int value) {#setPenAlignment-int-}
```
public void setPenAlignment(int value)
```


Hämtar eller anger ett valfritt 32‑bitars signerat heltal som specificerar fördelningen av pennbredden i förhållande till koordinaterna för den linje som ritas. Detta fält MÅSTE vara närvarande om PenDataNonCenter‑flaggan är satt i PenDataFlags‑fältet i EmfPlusPenData‑objektet, och värdet MÅSTE vara definierat i PenAlignment‑enumerationen (avsnitt 2.1.1.24).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getCompoundLineData() {#getCompoundLineData--}
```
public EmfPlusCompoundLineData getCompoundLineData()
```


Hämtar eller anger ett valfritt EmfPlusCompoundLineData‑objekt (avsnitt 2.2.2.9) som specificerar en array av flyttal som definierar den sammansatta linjen för en penna, vilken består av parallella linjer och mellanrum. Detta fält MÅSTE vara närvarande om PenDataCompoundLine‑flaggan är satt i PenDataFlags‑fältet i EmfPlusPenData‑objektet.

**Returns:**
[EmfPlusCompoundLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompoundlinedata)
### setCompoundLineData(EmfPlusCompoundLineData value) {#setCompoundLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCompoundLineData-}
```
public void setCompoundLineData(EmfPlusCompoundLineData value)
```


Hämtar eller anger ett valfritt EmfPlusCompoundLineData‑objekt (avsnitt 2.2.2.9) som specificerar en array av flyttal som definierar den sammansatta linjen för en penna, vilken består av parallella linjer och mellanrum. Detta fält MÅSTE vara närvarande om PenDataCompoundLine‑flaggan är satt i PenDataFlags‑fältet i EmfPlusPenData‑objektet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfPlusCompoundLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompoundlinedata) |  |

### getCustomStartCapData() {#getCustomStartCapData--}
```
public EmfPlusCustomStartCapData getCustomStartCapData()
```


Hämtar eller anger ett valfritt EmfPlusCustomStartCapData‑objekt (avsnitt 2.2.2.15) som definierar den anpassade startkapformen, vilken är den form som ska användas i början av en linje som ritas med denna penna. Den kan vara någon av olika former, såsom en kvadrat, cirkel eller diamant. Detta fält MÅSTE vara närvarande om PenDataCustomStartCap‑flaggan är satt i PenDataFlags‑fältet i EmfPlusPenData‑objektet.

**Returns:**
[EmfPlusCustomStartCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomstartcapdata)
### setCustomStartCapData(EmfPlusCustomStartCapData value) {#setCustomStartCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomStartCapData-}
```
public void setCustomStartCapData(EmfPlusCustomStartCapData value)
```


Hämtar eller anger ett valfritt EmfPlusCustomStartCapData‑objekt (avsnitt 2.2.2.15) som definierar den anpassade startkapformen, vilken är den form som ska användas i början av en linje som ritas med denna penna. Den kan vara någon av olika former, såsom en kvadrat, cirkel eller diamant. Detta fält MÅSTE vara närvarande om PenDataCustomStartCap‑flaggan är satt i PenDataFlags‑fältet i EmfPlusPenData‑objektet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfPlusCustomStartCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomstartcapdata) |  |

### getCustomEndCapData() {#getCustomEndCapData--}
```
public EmfPlusCustomEndCapData getCustomEndCapData()
```


Hämtar eller anger ett valfritt EmfPlusCustomEndCapData‑objekt (avsnitt 2.2.2.11) som definierar den anpassade slutkapformen, vilken är den form som ska användas i slutet av en linje som ritas med denna penna. Den kan vara någon av olika former, såsom en kvadrat, cirkel eller diamant. Detta fält MÅSTE vara närvarande om PenDataCustomEndCap‑flaggan är satt i PenDataFlags‑fältet i EmfPlusPenData‑objektet.

**Returns:**
[EmfPlusCustomEndCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomendcapdata)
### setCustomEndCapData(EmfPlusCustomEndCapData value) {#setCustomEndCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomEndCapData-}
```
public void setCustomEndCapData(EmfPlusCustomEndCapData value)
```


Hämtar eller anger ett valfritt EmfPlusCustomEndCapData‑objekt (avsnitt 2.2.2.11) som definierar den anpassade slutkapformen, vilken är den form som ska användas i slutet av en linje som ritas med denna penna. Den kan vara någon av olika former, såsom en kvadrat, cirkel eller diamant. Detta fält MÅSTE vara närvarande om PenDataCustomEndCap‑flaggan är satt i PenDataFlags‑fältet i EmfPlusPenData‑objektet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfPlusCustomEndCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomendcapdata) |  |

