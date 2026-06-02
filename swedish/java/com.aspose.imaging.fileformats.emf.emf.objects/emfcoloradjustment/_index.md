---
title: "EmfColorAdjustment"
second_title: "Aspose.Imaging för Java API-referens"
description: "ColorAdjustment-objektet definierar värden för att justera färgerna i källbitmapar vid bit‑block‑överföringar."
type: docs
weight: 12
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfColorAdjustment extends EmfObject
```

ColorAdjustment-objektet definierar värden för att justera färgerna i källbitmapar vid bit‑block‑överföringar.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfColorAdjustment()](#EmfColorAdjustment--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSize()](#getSize--) | Hämtar eller anger ett 16-bitars osignerat heltal som specificerar storleken i byte för detta objekt. |
| [setSize(short value)](#setSize-short-) | Hämtar eller anger ett 16-bitars osignerat heltal som specificerar storleken i byte för detta objekt. |
| [getValues()](#getValues--) | Hämtar eller anger ett 16-bitars osignerat heltal som specificerar hur utdata‑bilden ska förberedas. |
| [setValues(int value)](#setValues-int-) | Hämtar eller anger ett 16-bitars osignerat heltal som specificerar hur utdata‑bilden ska förberedas. |
| [getIlluminantIndex()](#getIlluminantIndex--) | Hämtar eller anger ett 16-bitars osignerat heltal som specificerar typen av standardljuskälla som bilden betraktas under, från Illuminant‑enumerationen (avsnitt 2.1.19). |
| [setIlluminantIndex(int value)](#setIlluminantIndex-int-) | Hämtar eller anger ett 16-bitars osignerat heltal som specificerar typen av standardljuskälla som bilden betraktas under, från Illuminant‑enumerationen (avsnitt 2.1.19). |
| [getRedGamma()](#getRedGamma--) | Hämtar eller anger ett 16-bitars osignerat heltal som specificerar det n‑te potens‑gamma‑korrektionsvärdet för den röda primärfärgen i källfärgerna. |
| [setRedGamma(short value)](#setRedGamma-short-) | Hämtar eller anger ett 16-bitars osignerat heltal som specificerar det n‑te potens‑gamma‑korrektionsvärdet för den röda primärfärgen i källfärgerna. |
| [getGreenGamma()](#getGreenGamma--) | Hämtar eller anger ett 16-bitars osignerat heltal som specificerar det n‑te potens‑gamma‑korrektionsvärdet för den gröna primärfärgen i källfärgerna. |
| [setGreenGamma(short value)](#setGreenGamma-short-) | Hämtar eller anger ett 16-bitars osignerat heltal som specificerar det n‑te potens‑gamma‑korrektionsvärdet för den gröna primärfärgen i källfärgerna. |
| [getBlueGamma()](#getBlueGamma--) | Hämtar eller anger ett 16-bitars osignerat heltal som specificerar det n‑te potens‑gamma‑korrektionsvärdet för den blåa primärfärgen i källfärgerna. |
| [setBlueGamma(short value)](#setBlueGamma-short-) | Hämtar eller anger ett 16-bitars osignerat heltal som specificerar det n‑te potens‑gamma‑korrektionsvärdet för den blåa primärfärgen i källfärgerna. |
| [getReferenceBlack()](#getReferenceBlack--) | Hämtar eller anger ett 16-bitars osignerat heltal som specificerar svartreferensen för källfärgerna. |
| [setReferenceBlack(short value)](#setReferenceBlack-short-) | Hämtar eller anger ett 16-bitars osignerat heltal som specificerar svartreferensen för källfärgerna. |
| [getReferenceWhite()](#getReferenceWhite--) | Hämtar eller anger ett 16-bitars osignerat heltal som specificerar vitreferensen för källfärgerna. |
| [setReferenceWhite(short value)](#setReferenceWhite-short-) | Hämtar eller anger ett 16-bitars osignerat heltal som specificerar vitreferensen för källfärgerna. |
| [getContrast()](#getContrast--) | Hämtar eller anger ett 16-bitars signerat heltal som specificerar mängden kontrast som ska tillämpas på källobjektet. |
| [setContrast(short value)](#setContrast-short-) | Hämtar eller anger ett 16-bitars signerat heltal som specificerar mängden kontrast som ska tillämpas på källobjektet. |
| [getBrightness()](#getBrightness--) | Hämtar eller anger ett 16-bitars signerat heltal som specificerar mängden ljusstyrka som ska tillämpas på källobjektet. |
| [setBrightness(short value)](#setBrightness-short-) | Hämtar eller anger ett 16-bitars signerat heltal som specificerar mängden ljusstyrka som ska tillämpas på källobjektet. |
| [getColorfullness()](#getColorfullness--) | Hämtar eller anger ett 16-bitars signerat heltal som specificerar mängden färgrikedom som ska tillämpas på källobjektet. |
| [setColorfullness(short value)](#setColorfullness-short-) | Hämtar eller anger ett 16-bitars signerat heltal som specificerar mängden färgrikedom som ska tillämpas på källobjektet. |
| [getRedGreenTint()](#getRedGreenTint--) | Hämtar eller anger ett 16-bitars signerat heltal som specificerar mängden röd eller grön tonjustering som ska tillämpas på källobjektet. |
| [setRedGreenTint(short value)](#setRedGreenTint-short-) | Hämtar eller anger ett 16-bitars signerat heltal som specificerar mängden röd eller grön tonjustering som ska tillämpas på källobjektet. |
### EmfColorAdjustment() {#EmfColorAdjustment--}
```
public EmfColorAdjustment()
```


### getSize() {#getSize--}
```
public short getSize()
```


Hämtar eller anger ett 16-bitars osignerat heltal som specificerar storleken i byte för detta objekt. Detta MÅSTE vara 0x0018.

**Returns:**
short
### setSize(short value) {#setSize-short-}
```
public void setSize(short value)
```


Hämtar eller anger ett 16-bitars osignerat heltal som specificerar storleken i byte för detta objekt. Detta MÅSTE vara 0x0018.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### getValues() {#getValues--}
```
public int getValues()
```


Hämtar eller anger ett 16-bitars osignerat heltal som specificerar hur utdata‑bilden ska förberedas. Detta fält kan sättas till NULL eller till någon kombination av värden i uppräkningen ColorAdjustment (avsnitt 2.1.5).

**Returns:**
int
### setValues(int value) {#setValues-int-}
```
public void setValues(int value)
```


Hämtar eller anger ett 16-bitars osignerat heltal som specificerar hur utdata‑bilden ska förberedas. Detta fält kan sättas till NULL eller till någon kombination av värden i uppräkningen ColorAdjustment (avsnitt 2.1.5).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getIlluminantIndex() {#getIlluminantIndex--}
```
public int getIlluminantIndex()
```


Hämtar eller anger ett 16-bitars osignerat heltal som specificerar typen av standardljuskälla som bilden betraktas under, från Illuminant‑enumerationen (avsnitt 2.1.19).

**Returns:**
int
### setIlluminantIndex(int value) {#setIlluminantIndex-int-}
```
public void setIlluminantIndex(int value)
```


Hämtar eller anger ett 16-bitars osignerat heltal som specificerar typen av standardljuskälla som bilden betraktas under, från Illuminant‑enumerationen (avsnitt 2.1.19).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getRedGamma() {#getRedGamma--}
```
public short getRedGamma()
```


Hämtar eller anger ett 16-bitars osignerat heltal som specificerar gamma‑korrektionens n‑te potensvärde för den röda primärfärgen i källfärgerna. Detta värde BÖR ligga i intervallet 2 500 till 65 000. Ett värde på 10 000 betyder att gamma‑korrektion INTE får utföras.

**Returns:**
short
### setRedGamma(short value) {#setRedGamma-short-}
```
public void setRedGamma(short value)
```


Hämtar eller anger ett 16-bitars osignerat heltal som specificerar gamma‑korrektionens n‑te potensvärde för den röda primärfärgen i källfärgerna. Detta värde BÖR ligga i intervallet 2 500 till 65 000. Ett värde på 10 000 betyder att gamma‑korrektion INTE får utföras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### getGreenGamma() {#getGreenGamma--}
```
public short getGreenGamma()
```


Hämtar eller anger ett 16-bitars osignerat heltal som specificerar gamma‑korrektionens n‑te potensvärde för den gröna primärfärgen i källfärgerna. Detta värde BÖR ligga i intervallet 2 500 till 65 000. Ett värde på 10 000 betyder att gamma‑korrektion INTE får utföras.

**Returns:**
short
### setGreenGamma(short value) {#setGreenGamma-short-}
```
public void setGreenGamma(short value)
```


Hämtar eller anger ett 16-bitars osignerat heltal som specificerar gamma‑korrektionens n‑te potensvärde för den gröna primärfärgen i källfärgerna. Detta värde BÖR ligga i intervallet 2 500 till 65 000. Ett värde på 10 000 betyder att gamma‑korrektion INTE får utföras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### getBlueGamma() {#getBlueGamma--}
```
public short getBlueGamma()
```


Hämtar eller anger ett 16-bitars osignerat heltal som specificerar gamma‑korrektionens n‑te potensvärde för den blåa primärfärgen i källfärgerna. Detta värde BÖR ligga i intervallet 2 500 till 65 000. Ett värde på 10 000 betyder att gamma‑korrektion INTE får utföras.

**Returns:**
short
### setBlueGamma(short value) {#setBlueGamma-short-}
```
public void setBlueGamma(short value)
```


Hämtar eller anger ett 16-bitars osignerat heltal som specificerar gamma‑korrektionens n‑te potensvärde för den blåa primärfärgen i källfärgerna. Detta värde BÖR ligga i intervallet 2 500 till 65 000. Ett värde på 10 000 betyder att gamma‑korrektion INTE får utföras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### getReferenceBlack() {#getReferenceBlack--}
```
public short getReferenceBlack()
```


Hämtar eller anger ett 16-bitars osignerat heltal som specificerar den svarta referensen för källfärgerna. Alla färger som är mörkare än detta behandlas som svarta. Detta värde BÖR ligga i intervallet 0 till 4 000.

**Returns:**
short
### setReferenceBlack(short value) {#setReferenceBlack-short-}
```
public void setReferenceBlack(short value)
```


Hämtar eller anger ett 16-bitars osignerat heltal som specificerar den svarta referensen för källfärgerna. Alla färger som är mörkare än detta behandlas som svarta. Detta värde BÖR ligga i intervallet 0 till 4 000.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### getReferenceWhite() {#getReferenceWhite--}
```
public short getReferenceWhite()
```


Hämtar eller anger ett 16-bitars osignerat heltal som specificerar den vita referensen för källfärgerna. Alla färger som är ljusare än detta behandlas som vita. Detta värde BÖR ligga i intervallet 6 000 till 10 000.

**Returns:**
short
### setReferenceWhite(short value) {#setReferenceWhite-short-}
```
public void setReferenceWhite(short value)
```


Hämtar eller anger ett 16-bitars osignerat heltal som specificerar den vita referensen för källfärgerna. Alla färger som är ljusare än detta behandlas som vita. Detta värde BÖR ligga i intervallet 6 000 till 10 000.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### getContrast() {#getContrast--}
```
public short getContrast()
```


Hämtar eller anger ett 16-bitars signerat heltal som specificerar mängden kontrast som ska tillämpas på källobjektet. Detta värde BÖR ligga i intervallet \\u2013100 till 100. Ett värde på noll betyder att kontrastjustering INTE får utföras.

**Returns:**
short
### setContrast(short value) {#setContrast-short-}
```
public void setContrast(short value)
```


Hämtar eller anger ett 16-bitars signerat heltal som specificerar mängden kontrast som ska tillämpas på källobjektet. Detta värde BÖR ligga i intervallet \\u2013100 till 100. Ett värde på noll betyder att kontrastjustering INTE får utföras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### getBrightness() {#getBrightness--}
```
public short getBrightness()
```


Hämtar eller anger ett 16-bitars signerat heltal som specificerar mängden ljusstyrka som ska tillämpas på källobjektet. Detta värde BÖR ligga i intervallet \\u2013100 till 100. Ett värde på noll betyder att ljusstyrkejustering INTE får utföras.

**Returns:**
short
### setBrightness(short value) {#setBrightness-short-}
```
public void setBrightness(short value)
```


Hämtar eller anger ett 16-bitars signerat heltal som specificerar mängden ljusstyrka som ska tillämpas på källobjektet. Detta värde BÖR ligga i intervallet \\u2013100 till 100. Ett värde på noll betyder att ljusstyrkejustering INTE får utföras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### getColorfullness() {#getColorfullness--}
```
public short getColorfullness()
```


Hämtar eller anger ett 16-bitars signerat heltal som specificerar mängden färgrikedom som ska tillämpas på källobjektet. Detta värde BÖR ligga i intervallet \\u2013100 till 100. Ett värde på noll betyder att färgrikedomjustering INTE får utföras.

**Returns:**
short
### setColorfullness(short value) {#setColorfullness-short-}
```
public void setColorfullness(short value)
```


Hämtar eller anger ett 16-bitars signerat heltal som specificerar mängden färgrikedom som ska tillämpas på källobjektet. Detta värde BÖR ligga i intervallet \\u2013100 till 100. Ett värde på noll betyder att färgrikedomjustering INTE får utföras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### getRedGreenTint() {#getRedGreenTint--}
```
public short getRedGreenTint()
```


Hämtar eller anger ett 16-bitars signerat heltal som specificerar mängden röd eller grön tonjustering som ska tillämpas på källobjektet. Detta värde BÖR ligga i intervallet \\u2013100 till 100. Positiva tal justerar mot rött och negativa tal justerar mot grönt. Ett värde på noll betyder att tonjustering INTE får utföras.

**Returns:**
short
### setRedGreenTint(short value) {#setRedGreenTint-short-}
```
public void setRedGreenTint(short value)
```


Hämtar eller anger ett 16-bitars signerat heltal som specificerar mängden röd eller grön tonjustering som ska tillämpas på källobjektet. Detta värde BÖR ligga i intervallet \\u2013100 till 100. Positiva tal justerar mot rött och negativa tal justerar mot grönt. Ett värde på noll betyder att tonjustering INTE får utföras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

