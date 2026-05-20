---
title: "EmfPlusLinearGradientBrushData"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto EmfPlusLinearGradientBrushData specifica un gradiente lineare per un pennello grafico."
type: docs
weight: 53
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
```
public final class EmfPlusLinearGradientBrushData extends EmfPlusBaseBrushData
```

L'oggetto EmfPlusLinearGradientBrushData specifica un gradiente lineare per un pennello grafico.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusLinearGradientBrushData()](#EmfPlusLinearGradientBrushData--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBrushDataFlags()](#getBrushDataFlags--) | Ottiene o imposta i flag dei dati del pennello. |
| [setBrushDataFlags(int value)](#setBrushDataFlags-int-) | Ottiene o imposta i flag dei dati del pennello. |
| [getEndArgb32Color()](#getEndArgb32Color--) | Ottiene o imposta il colore finale. |
| [setEndArgb32Color(int value)](#setEndArgb32Color-int-) | Ottiene o imposta il colore finale. |
| [getOptionalData()](#getOptionalData--) | Ottiene o imposta i dati opzionali. |
| [setOptionalData(EmfPlusLinearGradientBrushOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinearGradientBrushOptionalData-) | Ottiene o imposta i dati opzionali. |
| [getRectF()](#getRectF--) | Ottiene o imposta il rettangolo f. |
| [setRectF(RectangleF value)](#setRectF-com.aspose.imaging.RectangleF-) | Ottiene o imposta il rettangolo f. |
| [getStartArgb32Color()](#getStartArgb32Color--) | Ottiene o imposta il colore iniziale. |
| [setStartArgb32Color(int value)](#setStartArgb32Color-int-) | Ottiene o imposta il colore iniziale. |
| [getWrapMode()](#getWrapMode--) | Ottiene o imposta la modalità di avvolgimento. |
| [setWrapMode(int value)](#setWrapMode-int-) | Ottiene o imposta la modalità di avvolgimento. |
### EmfPlusLinearGradientBrushData() {#EmfPlusLinearGradientBrushData--}
```
public EmfPlusLinearGradientBrushData()
```


### getBrushDataFlags() {#getBrushDataFlags--}
```
public int getBrushDataFlags()
```


Ottiene o imposta i flag dei dati del pennello.

Valore: BrushDataFlags (4 byte): Un intero senza segno a 32 bit che specifica i dati nel campo OptionalData. Questo valore DEVE essere composto da `EmfPlusBrushDataFlags` (sezione 2.1.2.1).

**Returns:**
int
### setBrushDataFlags(int value) {#setBrushDataFlags-int-}
```
public void setBrushDataFlags(int value)
```


Ottiene o imposta i flag dei dati del pennello.

Valore: BrushDataFlags (4 byte): Un intero senza segno a 32 bit che specifica i dati nel campo OptionalData. Questo valore DEVE essere composto da `EmfPlusBrushDataFlags` (sezione 2.1.2.1).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getEndArgb32Color() {#getEndArgb32Color--}
```
public int getEndArgb32Color()
```


Ottiene o imposta il colore finale.

Valore: Un oggetto EmfPlusARGB che specifica il colore al punto di confine finale del pennello a gradiente lineare.

**Returns:**
int
### setEndArgb32Color(int value) {#setEndArgb32Color-int-}
```
public void setEndArgb32Color(int value)
```


Ottiene o imposta il colore finale.

Valore: Un oggetto EmfPlusARGB che specifica il colore al punto di confine finale del pennello a gradiente lineare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusLinearGradientBrushOptionalData getOptionalData()
```


Ottiene o imposta i dati opzionali.

Valore: Un oggetto opzionale `EmfPlusLinearGradientBrushOptionalData` (sezione 2.2.2.25) che specifica dati aggiuntivi per il pennello a gradiente lineare. Il contenuto specifico di questo campo è determinato dal valore del campo BrushDataFlags.

**Returns:**
[EmfPlusLinearGradientBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata)
### setOptionalData(EmfPlusLinearGradientBrushOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinearGradientBrushOptionalData-}
```
public void setOptionalData(EmfPlusLinearGradientBrushOptionalData value)
```


Ottiene o imposta i dati opzionali.

Valore: Un oggetto opzionale `EmfPlusLinearGradientBrushOptionalData` (sezione 2.2.2.25) che specifica dati aggiuntivi per il pennello a gradiente lineare. Il contenuto specifico di questo campo è determinato dal valore del campo BrushDataFlags.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfPlusLinearGradientBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata) |  |

### getRectF() {#getRectF--}
```
public RectangleF getRectF()
```


Ottiene o imposta il rettangolo f.

Valore: Un oggetto EmfPlusRectF (sezione 2.2.2.39) che specifica i punti di inizio e fine della linea di gradiente. L'angolo superiore sinistro del rettangolo è il punto di inizio. L'angolo inferiore destro è il punto di fine.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectF(RectangleF value) {#setRectF-com.aspose.imaging.RectangleF-}
```
public void setRectF(RectangleF value)
```


Ottiene o imposta il rettangolo f.

Valore: Un oggetto EmfPlusRectF (sezione 2.2.2.39) che specifica i punti di inizio e fine della linea di gradiente. L'angolo superiore sinistro del rettangolo è il punto di inizio. L'angolo inferiore destro è il punto di fine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getStartArgb32Color() {#getStartArgb32Color--}
```
public int getStartArgb32Color()
```


Ottiene o imposta il colore iniziale.

Valore: Un oggetto EmfPlusARGB (sezione 2.2.2.1) che specifica il colore al punto di confine iniziale del pennello a gradiente lineare.

**Returns:**
int
### setStartArgb32Color(int value) {#setStartArgb32Color-int-}
```
public void setStartArgb32Color(int value)
```


Ottiene o imposta il colore iniziale.

Valore: Un oggetto EmfPlusARGB (sezione 2.2.2.1) che specifica il colore al punto di confine iniziale del pennello a gradiente lineare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Ottiene o imposta la modalità di avvolgimento.

Valore: Un intero con segno a 32 bit dell'enumerazione WrapMode (sezione 2.1.1.34) che specifica se dipingere l'area al di fuori del confine del pennello. Quando si dipinge al di fuori del confine, la modalità di avvolgimento specifica come il gradiente di colore viene ripetuto.

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Ottiene o imposta la modalità di avvolgimento.

Valore: Un intero con segno a 32 bit dell'enumerazione WrapMode (sezione 2.1.1.34) che specifica se dipingere l'area al di fuori del confine del pennello. Quando si dipinge al di fuori del confine, la modalità di avvolgimento specifica come il gradiente di colore viene ripetuto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

