---
title: "EmfGradientFill"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_GRADIENTFILL specifica il riempimento di rettangoli o triangoli con gradienti di colore."
type: docs
weight: 65
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfgradientfill/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfGradientFill extends EmfDrawingRecordType
```

Il record EMR\_GRADIENTFILL specifica il riempimento di rettangoli o triangoli con gradienti di colore.

Un record EMR\_GRADIENTFILL che specifica che i tre vertici di un triangolo DEVONO riempire la figura con gradienti lisci di colori.[85] Un record EMR\_GRADIENTFILL che specifica che i vertici superiore sinistro e inferiore destro di un rettangolo DEVONO riempire la figura con gradienti lisci di colore. Esistono due modalità di riempimento gradiente nell'enumerazione GradientFill che possono essere usate quando si disegna un rettangolo. Nella modalità GRADIENT\_FILL\_RECT\_H, il rettangolo è riempito da sinistra a destra. Nella modalità GRADIENT\_FILL\_RECT\_V, il rettangolo è riempito dall'alto verso il basso. Nota: un record EMR\_GRADIENTFILL DEVE ignorare i campi Alpha negli oggetti TriVertex. Un record EMR\_ALPHABLEND (sezione 2.3.1.1) che segue immediatamente il record EMR\_GRADIENTFILL può essere usato per applicare un gradiente di trasparenza alfa all'area riempita.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfGradientFill(EmfRecord source)](#EmfGradientFill-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfGradientFill`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBounds()](#getBounds--) | Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che specifica un rettangolo di delimitazione, in unità del dispositivo inclusive-inclusive. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che specifica un rettangolo di delimitazione, in unità del dispositivo inclusive-inclusive. |
| [getNVer()](#getNVer--) | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di vertici. |
| [setNVer(int value)](#setNVer-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di vertici. |
| [getNTri()](#getNTri--) | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di rettangoli o triangoli da riempire. |
| [setNTri(int value)](#setNTri-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di rettangoli o triangoli da riempire. |
| [getUlMode()](#getUlMode--) | Ottiene o imposta un intero senza segno a 32 bit che specifica la modalità di riempimento gradiente. |
| [setUlMode(int value)](#setUlMode-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica la modalità di riempimento gradiente. |
| [getVertexData()](#getVertexData--) | Ottiene o imposta gli oggetti che specificano i vertici di rettangoli o triangoli e i colori corrispondenti. |
| [setVertexData(EmfVertexData value)](#setVertexData-com.aspose.imaging.fileformats.emf.emf.records.EmfVertexData-) | Ottiene o imposta gli oggetti che specificano i vertici di rettangoli o triangoli e i colori corrispondenti. |
### EmfGradientFill(EmfRecord source) {#EmfGradientFill-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfGradientFill(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfGradientFill`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che specifica un rettangolo di delimitazione, in unità del dispositivo inclusive-inclusive.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che specifica un rettangolo di delimitazione, in unità del dispositivo inclusive-inclusive.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getNVer() {#getNVer--}
```
public int getNVer()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di vertici.

**Returns:**
int
### setNVer(int value) {#setNVer-int-}
```
public void setNVer(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di vertici.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getNTri() {#getNTri--}
```
public int getNTri()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di rettangoli o triangoli da riempire.

**Returns:**
int
### setNTri(int value) {#setNTri-int-}
```
public void setNTri(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di rettangoli o triangoli da riempire.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getUlMode() {#getUlMode--}
```
public int getUlMode()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la modalità di riempimento gradiente. Il valore DEVE essere nell'enumerazione GradientFill (sezione 2.1.15).

**Returns:**
int
### setUlMode(int value) {#setUlMode-int-}
```
public void setUlMode(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la modalità di riempimento gradiente. Il valore DEVE essere nell'enumerazione GradientFill (sezione 2.1.15).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getVertexData() {#getVertexData--}
```
public EmfVertexData getVertexData()
```


Ottiene o imposta gli oggetti che specificano i vertici di rettangoli o triangoli e i colori corrispondenti.

**Returns:**
[EmfVertexData](../../com.aspose.imaging.fileformats.emf.emf.records/emfvertexdata)
### setVertexData(EmfVertexData value) {#setVertexData-com.aspose.imaging.fileformats.emf.emf.records.EmfVertexData-}
```
public void setVertexData(EmfVertexData value)
```


Ottiene o imposta gli oggetti che specificano i vertici di rettangoli o triangoli e i colori corrispondenti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfVertexData](../../com.aspose.imaging.fileformats.emf.emf.records/emfvertexdata) |  |

