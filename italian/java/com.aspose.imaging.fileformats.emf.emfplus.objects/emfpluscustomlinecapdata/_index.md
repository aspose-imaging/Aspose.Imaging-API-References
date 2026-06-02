---
title: "EmfPlusCustomLineCapData"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto EmfPlusCustomLineCapData specifica i dati predefiniti per un capolinea personalizzato."
type: docs
weight: 36
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomBaseLineCap](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustombaselinecap)
```
public final class EmfPlusCustomLineCapData extends EmfPlusCustomBaseLineCap
```

L'oggetto EmfPlusCustomLineCapData specifica i dati predefiniti per un capolinea personalizzato.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusCustomLineCapData()](#EmfPlusCustomLineCapData--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCustomLineCapDataFlags()](#getCustomLineCapDataFlags--) | Ottiene o imposta un intero senza segno a 32 bit che specifica i dati nel campo OptionalData |
| [setCustomLineCapDataFlags(int value)](#setCustomLineCapDataFlags-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica i dati nel campo OptionalData |
| [getBaseCap()](#getBaseCap--) | Ottiene o imposta un intero senza segno a 32 bit che specifica il valore dell'enumerazione LineCap (sezione 2.1.1.18) su cui si basa la linea personalizzata. |
| [setBaseCap(int value)](#setBaseCap-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica il valore dell'enumerazione LineCap (sezione 2.1.1.18) su cui si basa la linea personalizzata. |
| [getBaseInset()](#getBaseInset--) | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica la distanza tra l'inizio della linea di chiusura e la fine della linea. |
| [setBaseInset(float value)](#setBaseInset-float-) | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica la distanza tra l'inizio della linea di chiusura e la fine della linea. |
| [getStrokeStartCap()](#getStrokeStartCap--) | Ottiene o imposta un intero senza segno a 32 bit che specifica il valore nell'enumerazione LineCap che indica la linea di chiusura usata all'inizio della linea da disegnare |
| [setStrokeStartCap(int value)](#setStrokeStartCap-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica il valore nell'enumerazione LineCap che indica la linea di chiusura usata all'inizio della linea da disegnare |
| [getStrokeEndCap()](#getStrokeEndCap--) | Ottiene o imposta un intero senza segno a 32 bit che specifica il valore nell'enumerazione LineCap che indica quale linea di chiusura deve essere usata alla fine della linea da disegnare. |
| [setStrokeEndCap(int value)](#setStrokeEndCap-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica il valore nell'enumerazione LineCap che indica quale linea di chiusura deve essere usata alla fine della linea da disegnare. |
| [getStrokeJoin()](#getStrokeJoin--) | Ottiene o imposta un intero senza segno a 32 bit che specifica il valore nell'enumerazione LineJoin (sezione 2.1.1.19), che indica come unire due linee disegnate dalla stessa penna e i cui estremi si incontrano. |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica il valore nell'enumerazione LineJoin (sezione 2.1.1.19), che indica come unire due linee disegnate dalla stessa penna e i cui estremi si incontrano. |
| [getStrokeMiterLimit()](#getStrokeMiterLimit--) | Ottiene o imposta un valore a virgola mobile a 32 bit che contiene il limite dello spessore dell'unione in un angolo a spigolo impostando il rapporto massimo consentito tra la lunghezza dello spigolo e la larghezza della linea. |
| [setStrokeMiterLimit(float value)](#setStrokeMiterLimit-float-) | Ottiene o imposta un valore a virgola mobile a 32 bit che contiene il limite dello spessore dell'unione in un angolo a spigolo impostando il rapporto massimo consentito tra la lunghezza dello spigolo e la larghezza della linea. |
| [getWidthScale()](#getWidthScale--) | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica la quantità con cui scalare il cappuccio di linea personalizzato rispetto alla larghezza dell'oggetto EmfPlusPen (sezione 2.2.1.7) utilizzato per disegnare le linee. |
| [setWidthScale(float value)](#setWidthScale-float-) | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica la quantità con cui scalare il cappuccio di linea personalizzato rispetto alla larghezza dell'oggetto EmfPlusPen (sezione 2.2.1.7) utilizzato per disegnare le linee. |
| [getFillHotSpot()](#getFillHotSpot--) | Ottiene o imposta l'oggetto EmfPlusPointF che non è attualmente utilizzato. |
| [setFillHotSpot(PointF value)](#setFillHotSpot-com.aspose.imaging.PointF-) | Ottiene o imposta l'oggetto EmfPlusPointF che non è attualmente utilizzato. |
| [getStrokeHotSpot()](#getStrokeHotSpot--) | Ottiene o imposta l'oggetto EmfPlusPointF che non è attualmente utilizzato. |
| [setStrokeHotSpot(PointF value)](#setStrokeHotSpot-com.aspose.imaging.PointF-) | Ottiene o imposta l'oggetto EmfPlusPointF che non è attualmente utilizzato. |
| [getOptionalData()](#getOptionalData--) | Ottiene o imposta l'oggetto opzionale EmfPlusCustomLineCapOptionalData (sezione 2.2.2.14) che specifica dati aggiuntivi per il cappuccio di linea grafica personalizzato. |
| [setOptionalData(EmfPlusCustomLineCapOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomLineCapOptionalData-) | Ottiene o imposta l'oggetto opzionale EmfPlusCustomLineCapOptionalData (sezione 2.2.2.14) che specifica dati aggiuntivi per il cappuccio di linea grafica personalizzato. |
### EmfPlusCustomLineCapData() {#EmfPlusCustomLineCapData--}
```
public EmfPlusCustomLineCapData()
```


### getCustomLineCapDataFlags() {#getCustomLineCapDataFlags--}
```
public int getCustomLineCapDataFlags()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica i dati nel campo OptionalData

**Returns:**
int
### setCustomLineCapDataFlags(int value) {#setCustomLineCapDataFlags-int-}
```
public void setCustomLineCapDataFlags(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica i dati nel campo OptionalData

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getBaseCap() {#getBaseCap--}
```
public int getBaseCap()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il valore dell'enumerazione LineCap (sezione 2.1.1.18) su cui si basa la linea personalizzata.

**Returns:**
int
### setBaseCap(int value) {#setBaseCap-int-}
```
public void setBaseCap(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il valore dell'enumerazione LineCap (sezione 2.1.1.18) su cui si basa la linea personalizzata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getBaseInset() {#getBaseInset--}
```
public float getBaseInset()
```


Ottiene o imposta un valore a virgola mobile a 32 bit che specifica la distanza tra l'inizio della linea di chiusura e la fine della linea.

**Returns:**
float
### setBaseInset(float value) {#setBaseInset-float-}
```
public void setBaseInset(float value)
```


Ottiene o imposta un valore a virgola mobile a 32 bit che specifica la distanza tra l'inizio della linea di chiusura e la fine della linea.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getStrokeStartCap() {#getStrokeStartCap--}
```
public int getStrokeStartCap()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il valore nell'enumerazione LineCap che indica la linea di chiusura usata all'inizio della linea da disegnare

**Returns:**
int
### setStrokeStartCap(int value) {#setStrokeStartCap-int-}
```
public void setStrokeStartCap(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il valore nell'enumerazione LineCap che indica la linea di chiusura usata all'inizio della linea da disegnare

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getStrokeEndCap() {#getStrokeEndCap--}
```
public int getStrokeEndCap()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il valore nell'enumerazione LineCap che indica quale linea di chiusura deve essere usata alla fine della linea da disegnare.

**Returns:**
int
### setStrokeEndCap(int value) {#setStrokeEndCap-int-}
```
public void setStrokeEndCap(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il valore nell'enumerazione LineCap che indica quale linea di chiusura deve essere usata alla fine della linea da disegnare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getStrokeJoin() {#getStrokeJoin--}
```
public int getStrokeJoin()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il valore nell'enumerazione LineJoin (sezione 2.1.1.19), la quale indica come unire due linee disegnate dalla stessa penna i cui estremi si incontrano. All'intersezione dei due estremi della linea, un'unione di linea rende la connessione più continua.

**Returns:**
int
### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public void setStrokeJoin(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il valore nell'enumerazione LineJoin (sezione 2.1.1.19), la quale indica come unire due linee disegnate dalla stessa penna i cui estremi si incontrano. All'intersezione dei due estremi della linea, un'unione di linea rende la connessione più continua.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getStrokeMiterLimit() {#getStrokeMiterLimit--}
```
public float getStrokeMiterLimit()
```


Ottiene o imposta un valore a virgola mobile a 32 bit che contiene il limite dello spessore dell'unione in un angolo a spigolo impostando il rapporto massimo consentito tra la lunghezza dello spigolo e la larghezza della linea.

**Returns:**
float
### setStrokeMiterLimit(float value) {#setStrokeMiterLimit-float-}
```
public void setStrokeMiterLimit(float value)
```


Ottiene o imposta un valore a virgola mobile a 32 bit che contiene il limite dello spessore dell'unione in un angolo a spigolo impostando il rapporto massimo consentito tra la lunghezza dello spigolo e la larghezza della linea.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getWidthScale() {#getWidthScale--}
```
public float getWidthScale()
```


Ottiene o imposta un valore a virgola mobile a 32 bit che specifica la quantità con cui scalare il cappuccio di linea personalizzato rispetto alla larghezza dell'oggetto EmfPlusPen (sezione 2.2.1.7) utilizzato per disegnare le linee.

**Returns:**
float
### setWidthScale(float value) {#setWidthScale-float-}
```
public void setWidthScale(float value)
```


Ottiene o imposta un valore a virgola mobile a 32 bit che specifica la quantità con cui scalare il cappuccio di linea personalizzato rispetto alla larghezza dell'oggetto EmfPlusPen (sezione 2.2.1.7) utilizzato per disegnare le linee.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getFillHotSpot() {#getFillHotSpot--}
```
public PointF getFillHotSpot()
```


Ottiene o imposta l'oggetto EmfPlusPointF che non è attualmente utilizzato. Deve essere impostato a \{0.0, 0.0\}.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### setFillHotSpot(PointF value) {#setFillHotSpot-com.aspose.imaging.PointF-}
```
public void setFillHotSpot(PointF value)
```


Ottiene o imposta l'oggetto EmfPlusPointF che non è attualmente utilizzato. Deve essere impostato a \{0.0, 0.0\}.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

### getStrokeHotSpot() {#getStrokeHotSpot--}
```
public PointF getStrokeHotSpot()
```


Ottiene o imposta l'oggetto EmfPlusPointF che non è attualmente utilizzato. Deve essere impostato a \{0.0, 0.0\}.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### setStrokeHotSpot(PointF value) {#setStrokeHotSpot-com.aspose.imaging.PointF-}
```
public void setStrokeHotSpot(PointF value)
```


Ottiene o imposta l'oggetto EmfPlusPointF che non è attualmente utilizzato. Deve essere impostato a \{0.0, 0.0\}.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusCustomLineCapOptionalData getOptionalData()
```


Ottiene o imposta l'oggetto opzionale EmfPlusCustomLineCapOptionalData (sezione 2.2.2.14) che specifica dati aggiuntivi per il cappuccio di linea grafica personalizzato. Il contenuto specifico di questo campo è determinato dal valore del campo CustomLineCapDataFlags.

**Returns:**
[EmfPlusCustomLineCapOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata)
### setOptionalData(EmfPlusCustomLineCapOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomLineCapOptionalData-}
```
public void setOptionalData(EmfPlusCustomLineCapOptionalData value)
```


Ottiene o imposta l'oggetto opzionale EmfPlusCustomLineCapOptionalData (sezione 2.2.2.14) che specifica dati aggiuntivi per il cappuccio di linea grafica personalizzato. Il contenuto specifico di questo campo è determinato dal valore del campo CustomLineCapDataFlags.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfPlusCustomLineCapOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata) |  |

