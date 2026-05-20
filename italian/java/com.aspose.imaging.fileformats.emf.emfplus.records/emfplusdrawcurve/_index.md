---
title: "EmfPlusDrawCurve"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EmfPlusDrawCurve specifica il disegno di una spline cardinale NOTA ObjectID 1 byte L'indice di un oggetto EmfPlusPen sezione 2.2.1.7 nella EMF Object Table per disegnare la curva."
type: docs
weight: 19
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawCurve extends EmfPlusDrawingRecordType
```

Il record EmfPlusDrawCurve specifica il disegno di una spline cardinale NOTA: ObjectID (1 byte): L'indice di un oggetto EmfPlusPen (sezione 2.2.1.7) nella EMF+ Object Table per disegnare la curva. Il valore DEVE essere compreso tra 0 e 63, inclusi.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusDrawCurve(EmfPlusRecord source)](#EmfPlusDrawCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inizializza una nuova istanza della classe `EmfPlusDrawCurve`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCompressed()](#getCompressed--) | Ottiene o imposta un valore che indica se questo `EmfPlusDrawClosedCurve` è compresso. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Ottiene o imposta un valore che indica se questo `EmfPlusDrawClosedCurve` è compresso. |
| [getObjectId()](#getObjectId--) | Ottiene o imposta l'identificatore dell'oggetto. |
| [setObjectId(byte value)](#setObjectId-byte-) | Ottiene o imposta l'identificatore dell'oggetto. |
| [getTension()](#getTension--) | Ottiene o imposta la tensione, un numero a virgola mobile a 32 bit che specifica quanto strettamente la spline si piega mentre attraversa i punti. |
| [setTension(float value)](#setTension-float-) | Ottiene o imposta la tensione, un numero a virgola mobile a 32 bit che specifica quanto strettamente la spline si piega mentre attraversa i punti. |
| [getNumSegments()](#getNumSegments--) | Ottiene o imposta il conteggio dei segmenti Un intero senza segno a 32 bit che specifica il numero di segmenti di linea che compongono la spline. |
| [setNumSegments(int value)](#setNumSegments-int-) | Ottiene o imposta il conteggio dei segmenti Un intero senza segno a 32 bit che specifica il numero di segmenti di linea che compongono la spline. |
| [getPointData()](#getPointData--) | Ottiene o imposta un array di interi a 32 bit con segno o di numeri a virgola mobile a 32 bit di lunghezza Count che definisce i valori delle coordinate dei punti finali delle linee da tracciare. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Ottiene o imposta un array di interi a 32 bit con segno o di numeri a virgola mobile a 32 bit di lunghezza Count che definisce i valori delle coordinate dei punti finali delle linee da tracciare. |
### EmfPlusDrawCurve(EmfPlusRecord source) {#EmfPlusDrawCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawCurve(EmfPlusRecord source)
```


Inizializza una nuova istanza della classe `EmfPlusDrawCurve`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La sorgente. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Ottiene o imposta un valore che indica se questo `EmfPlusDrawClosedCurve` è compresso. Questo bit indica se il campo PointData specifica dati compressi. Se impostato, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate intere a 16 bit. Se non impostato, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate a virgola mobile a 32 bit. Nota: se il flag Relative (sotto) è impostato, questo flag è indefinito e DEVE essere ignorato

Valore: `true` se compresso; altrimenti, `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Ottiene o imposta un valore che indica se questo `EmfPlusDrawClosedCurve` è compresso. Questo bit indica se il campo PointData specifica dati compressi. Se impostato, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate intere a 16 bit. Se non impostato, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate a virgola mobile a 32 bit. Nota: se il flag Relative (sotto) è impostato, questo flag è indefinito e DEVE essere ignorato

Valore: `true` se compresso; altrimenti, `false`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Ottiene o imposta l'identificatore dell'oggetto. L'indice di un oggetto EmfPlusPen (sezione 2.2.1.7) nella EMF+ Object Table per disegnare la curva. Il valore DEVE essere compreso tra 0 e 63, inclusi.

Valore: L'identificatore dell'oggetto.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Ottiene o imposta l'identificatore dell'oggetto. L'indice di un oggetto EmfPlusPen (sezione 2.2.1.7) nella EMF+ Object Table per disegnare la curva. Il valore DEVE essere compreso tra 0 e 63, inclusi.

Valore: L'identificatore dell'oggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getTension() {#getTension--}
```
public float getTension()
```


Ottiene o imposta la tensione Un numero a virgola mobile a 32 bit che specifica quanto strettamente la spline si piega mentre passa attraverso i punti. Un valore di 0 specifica che la spline è una sequenza di linee rette. Man mano che il valore aumenta, la curva diventa più arrotondata. Per ulteriori informazioni, vedere [SPLINE77] e [PETZOLD].

**Returns:**
float
### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


Ottiene o imposta la tensione Un numero a virgola mobile a 32 bit che specifica quanto strettamente la spline si piega mentre passa attraverso i punti. Un valore di 0 specifica che la spline è una sequenza di linee rette. Man mano che il valore aumenta, la curva diventa più arrotondata. Per ulteriori informazioni, vedere [SPLINE77] e [PETZOLD].

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getNumSegments() {#getNumSegments--}
```
public int getNumSegments()
```


Ottiene o imposta il conteggio dei segmenti Un intero senza segno a 32 bit che specifica il numero di segmenti di linea che compongono la spline.

**Returns:**
int
### setNumSegments(int value) {#setNumSegments-int-}
```
public void setNumSegments(int value)
```


Ottiene o imposta il conteggio dei segmenti Un intero senza segno a 32 bit che specifica il numero di segmenti di linea che compongono la spline.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Ottiene o imposta un array di interi a 32 bit con segno o di numeri a virgola mobile a 32 bit di lunghezza Count che definisce i valori delle coordinate dei punti finali delle linee da tracciare.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Ottiene o imposta un array di interi a 32 bit con segno o di numeri a virgola mobile a 32 bit di lunghezza Count che definisce i valori delle coordinate dei punti finali delle linee da tracciare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

