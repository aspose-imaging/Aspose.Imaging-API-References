---
title: "EmfPlusPenOptionalData"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto EmfPlusPenOptionalData specifica dati opzionali per una penna grafica"
type: docs
weight: 65
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusPenOptionalData extends EmfPlusStructureObjectType
```

L'oggetto EmfPlusPenOptionalData specifica dati opzionali per una penna grafica
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusPenOptionalData()](#EmfPlusPenOptionalData--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getTransformMatrix()](#getTransformMatrix--) | Ottiene o imposta un oggetto opzionale EmfPlusTransformMatrix (sezione 2.2.2.47) che specifica una trasformazione dallo spazio mondo allo spazio dispositivo per la penna. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | Ottiene o imposta un oggetto opzionale EmfPlusTransformMatrix (sezione 2.2.2.47) che specifica una trasformazione dallo spazio mondo allo spazio dispositivo per la penna. |
| [getStartCap()](#getStartCap--) | Ottiene o imposta un intero opzionale a 32 bit con segno che specifica la forma per l'inizio di una linea nel campo CustomStartCapData. |
| [setStartCap(int value)](#setStartCap-int-) | Ottiene o imposta un intero opzionale a 32 bit con segno che specifica la forma per l'inizio di una linea nel campo CustomStartCapData. |
| [getEndCap()](#getEndCap--) | Ottiene o imposta un intero opzionale a 32 bit con segno che specifica la forma per la fine di una linea nel campo CustomEndCapData. |
| [setEndCap(int value)](#setEndCap-int-) | Ottiene o imposta un intero opzionale a 32 bit con segno che specifica la forma per la fine di una linea nel campo CustomEndCapData. |
| [getJoin()](#getJoin--) | Ottiene o imposta un intero opzionale a 32 bit con segno che specifica come unire due linee disegnate dalla stessa penna i cui estremi si incontrano. |
| [setJoin(int value)](#setJoin-int-) | Ottiene o imposta un intero opzionale a 32 bit con segno che specifica come unire due linee disegnate dalla stessa penna i cui estremi si incontrano. |
| [getMiterLimit()](#getMiterLimit--) | Ottiene o imposta un valore opzionale a 32 bit in virgola mobile che specifica il limite di spigolo, ovvero il rapporto massimo consentito tra la lunghezza dello spigolo e la larghezza della linea. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Ottiene o imposta un valore opzionale a 32 bit in virgola mobile che specifica il limite di spigolo, ovvero il rapporto massimo consentito tra la lunghezza dello spigolo e la larghezza della linea. |
| [getLineStyle()](#getLineStyle--) | Ottiene o imposta un intero opzionale a 32 bit con segno che specifica lo stile usato per le linee disegnate con questo oggetto penna. |
| [setLineStyle(int value)](#setLineStyle-int-) | Ottiene o imposta un intero opzionale a 32 bit con segno che specifica lo stile usato per le linee disegnate con questo oggetto penna. |
| [getDashedLineCapType()](#getDashedLineCapType--) | Ottiene o imposta un intero opzionale a 32 bit con segno che specifica la forma per entrambe le estremità di ogni tratto in una linea tratteggiata. |
| [setDashedLineCapType(int value)](#setDashedLineCapType-int-) | Ottiene o imposta un intero opzionale a 32 bit con segno che specifica la forma per entrambe le estremità di ogni tratto in una linea tratteggiata. |
| [getDashOffset()](#getDashOffset--) | Ottiene o imposta un valore opzionale a 32 bit in virgola mobile che specifica la distanza dall'inizio di una linea all'inizio del primo spazio in un modello di linea tratteggiata. |
| [setDashOffset(float value)](#setDashOffset-float-) | Ottiene o imposta un valore opzionale a 32 bit in virgola mobile che specifica la distanza dall'inizio di una linea all'inizio del primo spazio in un modello di linea tratteggiata. |
| [getDashedLineData()](#getDashedLineData--) | Ottiene o imposta un oggetto opzionale EmfPlusDashedLineData (sezione 2.2.2.16) che specifica le lunghezze dei tratti e degli spazi in una linea tratteggiata personalizzata. |
| [setDashedLineData(EmfPlusDashedLineData value)](#setDashedLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusDashedLineData-) | Ottiene o imposta un oggetto opzionale EmfPlusDashedLineData (sezione 2.2.2.16) che specifica le lunghezze dei tratti e degli spazi in una linea tratteggiata personalizzata. |
| [getPenAlignment()](#getPenAlignment--) | Ottiene o imposta un intero opzionale a 32 bit con segno che specifica la distribuzione della larghezza della penna rispetto alle coordinate della linea in fase di disegno. |
| [setPenAlignment(int value)](#setPenAlignment-int-) | Ottiene o imposta un intero opzionale a 32 bit con segno che specifica la distribuzione della larghezza della penna rispetto alle coordinate della linea in fase di disegno. |
| [getCompoundLineData()](#getCompoundLineData--) | Ottiene o imposta un oggetto opzionale EmfPlusCompoundLineData (sezione 2.2.2.9) che specifica un array di valori in virgola mobile che definiscono la linea composta di una penna, costituita da linee parallele e spazi. |
| [setCompoundLineData(EmfPlusCompoundLineData value)](#setCompoundLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCompoundLineData-) | Ottiene o imposta un oggetto opzionale EmfPlusCompoundLineData (sezione 2.2.2.9) che specifica un array di valori in virgola mobile che definiscono la linea composta di una penna, costituita da linee parallele e spazi. |
| [getCustomStartCapData()](#getCustomStartCapData--) | Ottiene o imposta un oggetto opzionale EmfPlusCustomStartCapData (sezione 2.2.2.15) che definisce la forma personalizzata del cappuccio iniziale, ovvero la forma da utilizzare all'inizio di una linea disegnata con questa penna. |
| [setCustomStartCapData(EmfPlusCustomStartCapData value)](#setCustomStartCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomStartCapData-) | Ottiene o imposta un oggetto opzionale EmfPlusCustomStartCapData (sezione 2.2.2.15) che definisce la forma personalizzata del cappuccio iniziale, ovvero la forma da utilizzare all'inizio di una linea disegnata con questa penna. |
| [getCustomEndCapData()](#getCustomEndCapData--) | Ottiene o imposta un oggetto opzionale EmfPlusCustomEndCapData (sezione 2.2.2.11) che definisce la forma personalizzata del cappuccio finale, ovvero la forma da utilizzare alla fine di una linea disegnata con questa penna. |
| [setCustomEndCapData(EmfPlusCustomEndCapData value)](#setCustomEndCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomEndCapData-) | Ottiene o imposta un oggetto opzionale EmfPlusCustomEndCapData (sezione 2.2.2.11) che definisce la forma personalizzata del cappuccio finale, ovvero la forma da utilizzare alla fine di una linea disegnata con questa penna. |
### EmfPlusPenOptionalData() {#EmfPlusPenOptionalData--}
```
public EmfPlusPenOptionalData()
```


### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


Ottiene o imposta un oggetto opzionale EmfPlusTransformMatrix (sezione 2.2.2.47) che specifica una trasformazione dallo spazio mondo allo spazio dispositivo per la penna. Questo campo DEVE essere presente se il flag PenDataTransform è impostato nel campo PenDataFlags dell'oggetto EmfPlusPenData.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


Ottiene o imposta un oggetto opzionale EmfPlusTransformMatrix (sezione 2.2.2.47) che specifica una trasformazione dallo spazio mondo allo spazio dispositivo per la penna. Questo campo DEVE essere presente se il flag PenDataTransform è impostato nel campo PenDataFlags dell'oggetto EmfPlusPenData.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getStartCap() {#getStartCap--}
```
public int getStartCap()
```


Ottiene o imposta un intero opzionale a 32 bit con segno che specifica la forma per l'inizio di una linea nel campo CustomStartCapData. Questo campo DEVE essere presente se il flag PenDataStartCap è impostato nel campo PenDataFlags dell'oggetto EmfPlusPenData, e il valore DEVE essere definito nell'enumerazione LineCapType (sezione 2.1.1.18).

**Returns:**
int
### setStartCap(int value) {#setStartCap-int-}
```
public void setStartCap(int value)
```


Ottiene o imposta un intero opzionale a 32 bit con segno che specifica la forma per l'inizio di una linea nel campo CustomStartCapData. Questo campo DEVE essere presente se il flag PenDataStartCap è impostato nel campo PenDataFlags dell'oggetto EmfPlusPenData, e il valore DEVE essere definito nell'enumerazione LineCapType (sezione 2.1.1.18).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getEndCap() {#getEndCap--}
```
public int getEndCap()
```


Ottiene o imposta un intero opzionale a 32 bit con segno che specifica la forma per la fine di una linea nel campo CustomEndCapData. Questo campo DEVE essere presente se il flag PenDataEndCap è impostato nel campo PenDataFlags dell'oggetto EmfPlusPenData, e il valore DEVE essere definito nell'enumerazione LineCapType.

**Returns:**
int
### setEndCap(int value) {#setEndCap-int-}
```
public void setEndCap(int value)
```


Ottiene o imposta un intero opzionale a 32 bit con segno che specifica la forma per la fine di una linea nel campo CustomEndCapData. Questo campo DEVE essere presente se il flag PenDataEndCap è impostato nel campo PenDataFlags dell'oggetto EmfPlusPenData, e il valore DEVE essere definito nell'enumerazione LineCapType.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getJoin() {#getJoin--}
```
public int getJoin()
```


Ottiene o imposta un intero opzionale a 32 bit con segno che specifica come unire due linee tracciate dalla stessa penna e i cui estremi si incontrano. Questo campo DEVE essere presente se il flag PenDataJoin è impostato nel campo PenDataFlags dell'oggetto EmfPlusPenData, e il valore DEVE essere definito nell'enumerazione LineJoinType (sezione 2.1.1.19).

**Returns:**
int
### setJoin(int value) {#setJoin-int-}
```
public void setJoin(int value)
```


Ottiene o imposta un intero opzionale a 32 bit con segno che specifica come unire due linee tracciate dalla stessa penna e i cui estremi si incontrano. Questo campo DEVE essere presente se il flag PenDataJoin è impostato nel campo PenDataFlags dell'oggetto EmfPlusPenData, e il valore DEVE essere definito nell'enumerazione LineJoinType (sezione 2.1.1.19).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getMiterLimit() {#getMiterLimit--}
```
public float getMiterLimit()
```


Ottiene o imposta un valore opzionale a virgola mobile a 32 bit che specifica il limite di spigolo, ovvero il rapporto massimo consentito tra la lunghezza dello spigolo e lo spessore della linea. La lunghezza dello spigolo è la distanza dall'intersezione delle pareti della linea all'interno dell'unione all'intersezione delle pareti della linea all'esterno dell'unione. La lunghezza dello spigolo può essere grande quando l'angolo tra due linee è piccolo. Questo campo DEVE essere presente se il flag PenDataMiterLimit è impostato nel campo PenDataFlags dell'oggetto EmfPlusPenData.

**Returns:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public void setMiterLimit(float value)
```


Ottiene o imposta un valore opzionale a virgola mobile a 32 bit che specifica il limite di spigolo, ovvero il rapporto massimo consentito tra la lunghezza dello spigolo e lo spessore della linea. La lunghezza dello spigolo è la distanza dall'intersezione delle pareti della linea all'interno dell'unione all'intersezione delle pareti della linea all'esterno dell'unione. La lunghezza dello spigolo può essere grande quando l'angolo tra due linee è piccolo. Questo campo DEVE essere presente se il flag PenDataMiterLimit è impostato nel campo PenDataFlags dell'oggetto EmfPlusPenData.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getLineStyle() {#getLineStyle--}
```
public int getLineStyle()
```


Ottiene o imposta un intero opzionale a 32 bit con segno che specifica lo stile utilizzato per le linee tracciate con questo oggetto penna. Questo campo DEVE essere presente se il flag PenDataLineStyle è impostato nel campo PenDataFlags dell'oggetto EmfPlusPenData, e il valore DEVE essere definito nell'enumerazione LineStyle (sezione 2.1.1.20).

**Returns:**
int
### setLineStyle(int value) {#setLineStyle-int-}
```
public void setLineStyle(int value)
```


Ottiene o imposta un intero opzionale a 32 bit con segno che specifica lo stile utilizzato per le linee tracciate con questo oggetto penna. Questo campo DEVE essere presente se il flag PenDataLineStyle è impostato nel campo PenDataFlags dell'oggetto EmfPlusPenData, e il valore DEVE essere definito nell'enumerazione LineStyle (sezione 2.1.1.20).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getDashedLineCapType() {#getDashedLineCapType--}
```
public int getDashedLineCapType()
```


Ottiene o imposta un intero opzionale a 32 bit con segno che specifica la forma per entrambe le estremità di ogni tratto in una linea tratteggiata. Questo campo DEVE essere presente se il flag PenDataDashedLineCap è impostato nel campo PenDataFlags dell'oggetto EmfPlusPenData, e il valore DEVE essere definito nell'enumerazione DashedLineCapType (sezione 2.1.1.10).

**Returns:**
int
### setDashedLineCapType(int value) {#setDashedLineCapType-int-}
```
public void setDashedLineCapType(int value)
```


Ottiene o imposta un intero opzionale a 32 bit con segno che specifica la forma per entrambe le estremità di ogni tratto in una linea tratteggiata. Questo campo DEVE essere presente se il flag PenDataDashedLineCap è impostato nel campo PenDataFlags dell'oggetto EmfPlusPenData, e il valore DEVE essere definito nell'enumerazione DashedLineCapType (sezione 2.1.1.10).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getDashOffset() {#getDashOffset--}
```
public float getDashOffset()
```


Ottiene o imposta un valore opzionale a virgola mobile a 32 bit che specifica la distanza dall'inizio di una linea all'inizio del primo spazio in un modello di linea tratteggiata. Questo campo DEVE essere presente se il flag PenDataDashedLineOffset è impostato nel campo PenDataFlags dell'oggetto EmfPlusPenData.

**Returns:**
float
### setDashOffset(float value) {#setDashOffset-float-}
```
public void setDashOffset(float value)
```


Ottiene o imposta un valore opzionale a virgola mobile a 32 bit che specifica la distanza dall'inizio di una linea all'inizio del primo spazio in un modello di linea tratteggiata. Questo campo DEVE essere presente se il flag PenDataDashedLineOffset è impostato nel campo PenDataFlags dell'oggetto EmfPlusPenData.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getDashedLineData() {#getDashedLineData--}
```
public EmfPlusDashedLineData getDashedLineData()
```


Ottiene o imposta un oggetto opzionale EmfPlusDashedLineData (sezione 2.2.2.16) che specifica le lunghezze dei tratti e degli spazi in una linea tratteggiata personalizzata. Questo campo DEVE essere presente se il flag PenDataDashedLine è impostato nel campo PenDataFlags dell'oggetto EmfPlusPenData.

**Returns:**
[EmfPlusDashedLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusdashedlinedata)
### setDashedLineData(EmfPlusDashedLineData value) {#setDashedLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusDashedLineData-}
```
public void setDashedLineData(EmfPlusDashedLineData value)
```


Ottiene o imposta un oggetto opzionale EmfPlusDashedLineData (sezione 2.2.2.16) che specifica le lunghezze dei tratti e degli spazi in una linea tratteggiata personalizzata. Questo campo DEVE essere presente se il flag PenDataDashedLine è impostato nel campo PenDataFlags dell'oggetto EmfPlusPenData.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfPlusDashedLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusdashedlinedata) |  |

### getPenAlignment() {#getPenAlignment--}
```
public int getPenAlignment()
```


Ottiene o imposta un intero opzionale a 32 bit con segno che specifica la distribuzione della larghezza della penna rispetto alle coordinate della linea tracciata. Questo campo DEVE essere presente se il flag PenDataNonCenter è impostato nel campo PenDataFlags dell'oggetto EmfPlusPenData, e il valore DEVE essere definito nell'enumerazione PenAlignment (sezione 2.1.1.24).

**Returns:**
int
### setPenAlignment(int value) {#setPenAlignment-int-}
```
public void setPenAlignment(int value)
```


Ottiene o imposta un intero opzionale a 32 bit con segno che specifica la distribuzione della larghezza della penna rispetto alle coordinate della linea tracciata. Questo campo DEVE essere presente se il flag PenDataNonCenter è impostato nel campo PenDataFlags dell'oggetto EmfPlusPenData, e il valore DEVE essere definito nell'enumerazione PenAlignment (sezione 2.1.1.24).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getCompoundLineData() {#getCompoundLineData--}
```
public EmfPlusCompoundLineData getCompoundLineData()
```


Ottiene o imposta un oggetto opzionale EmfPlusCompoundLineData (sezione 2.2.2.9) che specifica un array di valori a virgola mobile che definiscono la linea composta di una penna, costituita da linee parallele e spazi. Questo campo DEVE essere presente se il flag PenDataCompoundLine è impostato nel campo PenDataFlags dell'oggetto EmfPlusPenData.

**Returns:**
[EmfPlusCompoundLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompoundlinedata)
### setCompoundLineData(EmfPlusCompoundLineData value) {#setCompoundLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCompoundLineData-}
```
public void setCompoundLineData(EmfPlusCompoundLineData value)
```


Ottiene o imposta un oggetto opzionale EmfPlusCompoundLineData (sezione 2.2.2.9) che specifica un array di valori a virgola mobile che definiscono la linea composta di una penna, costituita da linee parallele e spazi. Questo campo DEVE essere presente se il flag PenDataCompoundLine è impostato nel campo PenDataFlags dell'oggetto EmfPlusPenData.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfPlusCompoundLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompoundlinedata) |  |

### getCustomStartCapData() {#getCustomStartCapData--}
```
public EmfPlusCustomStartCapData getCustomStartCapData()
```


Ottiene o imposta un oggetto opzionale EmfPlusCustomStartCapData (sezione 2.2.2.15) che definisce la forma personalizzata del cappuccio iniziale, ovvero la forma da utilizzare all'inizio di una linea tracciata con questa penna. Può essere una delle varie forme, come un quadrato, un cerchio o un diamante. Questo campo DEVE essere presente se il flag PenDataCustomStartCap è impostato nel campo PenDataFlags dell'oggetto EmfPlusPenData.

**Returns:**
[EmfPlusCustomStartCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomstartcapdata)
### setCustomStartCapData(EmfPlusCustomStartCapData value) {#setCustomStartCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomStartCapData-}
```
public void setCustomStartCapData(EmfPlusCustomStartCapData value)
```


Ottiene o imposta un oggetto opzionale EmfPlusCustomStartCapData (sezione 2.2.2.15) che definisce la forma personalizzata del cappuccio iniziale, ovvero la forma da utilizzare all'inizio di una linea tracciata con questa penna. Può essere una delle varie forme, come un quadrato, un cerchio o un diamante. Questo campo DEVE essere presente se il flag PenDataCustomStartCap è impostato nel campo PenDataFlags dell'oggetto EmfPlusPenData.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfPlusCustomStartCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomstartcapdata) |  |

### getCustomEndCapData() {#getCustomEndCapData--}
```
public EmfPlusCustomEndCapData getCustomEndCapData()
```


Ottiene o imposta un oggetto opzionale EmfPlusCustomEndCapData (sezione 2.2.2.11) che definisce la forma personalizzata del cappuccio finale, ovvero la forma da utilizzare alla fine di una linea tracciata con questa penna. Può essere una delle varie forme, come un quadrato, un cerchio o un diamante. Questo campo DEVE essere presente se il flag PenDataCustomEndCap è impostato nel campo PenDataFlags dell'oggetto EmfPlusPenData.

**Returns:**
[EmfPlusCustomEndCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomendcapdata)
### setCustomEndCapData(EmfPlusCustomEndCapData value) {#setCustomEndCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomEndCapData-}
```
public void setCustomEndCapData(EmfPlusCustomEndCapData value)
```


Ottiene o imposta un oggetto opzionale EmfPlusCustomEndCapData (sezione 2.2.2.11) che definisce la forma personalizzata del cappuccio finale, ovvero la forma da utilizzare alla fine di una linea tracciata con questa penna. Può essere una delle varie forme, come un quadrato, un cerchio o un diamante. Questo campo DEVE essere presente se il flag PenDataCustomEndCap è impostato nel campo PenDataFlags dell'oggetto EmfPlusPenData.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfPlusCustomEndCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomendcapdata) |  |

