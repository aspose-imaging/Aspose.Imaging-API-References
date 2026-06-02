---
title: "EmfPlusDrawDriverString"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EmfPlusDrawDriverString specifica l'output di testo con posizioni dei caratteri."
type: docs
weight: 20
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawDriverString extends EmfPlusDrawingRecordType
```

Il record EmfPlusDrawDriverString specifica l'output di testo con posizioni dei caratteri.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusDrawDriverString(EmfPlusRecord source)](#EmfPlusDrawDriverString-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inizializza una nuova istanza della classe `EmfPlusDrawDriverString`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getObjectId()](#getObjectId--) | Ottiene l'identificatore dell'oggetto. |
| [setObjectId(byte value)](#setObjectId-byte-) | Imposta l'identificatore dell'oggetto. |
| [getBrushId()](#getBrushId--) | Ottiene l'identificatore del pennello Un intero senza segno a 32 bit che specifica sia il colore di primo piano del testo sia un pennello grafico, a seconda del valore del flag S nei Flags |
| [setBrushId(int value)](#setBrushId-int-) | Imposta l'identificatore del pennello Un intero senza segno a 32 bit che specifica o il colore di primo piano del testo o un pennello grafico, a seconda del valore del flag S nei Flags |
| [getDriverStringOptionsFlags()](#getDriverStringOptionsFlags--) | Ottiene le flag delle opzioni della stringa del driver Un intero senza segno a 32 bit che specifica la spaziatura, l'orientamento e la qualità del rendering per la stringa. |
| [setDriverStringOptionsFlags(int value)](#setDriverStringOptionsFlags-int-) | Imposta le flag delle opzioni della stringa del driver Un intero senza segno a 32 bit che specifica la spaziatura, l'orientamento e la qualità del rendering per la stringa. |
| [getGlyphCount()](#getGlyphCount--) | Ottiene il conteggio dei glifi Un intero senza segno a 32 bit che specifica il numero di glifi nella stringa |
| [setGlyphCount(int value)](#setGlyphCount-int-) | Imposta il conteggio dei glifi Un intero senza segno a 32 bit che specifica il numero di glifi nella stringa |
| [getGlyphPos()](#getGlyphPos--) | Ottiene l'array delle posizioni dei glifi Un array di oggetti EmfPlusPointF (sezione 2.2.2.36) che specificano la posizione di output di ogni glifo di carattere. |
| [setGlyphPos(PointF[] value)](#setGlyphPos-com.aspose.imaging.PointF---) | Imposta l'array delle posizioni dei glifi Un array di oggetti EmfPlusPointF (sezione 2.2.2.36) che specificano la posizione di output di ogni glifo di carattere. |
| [getGlyphs()](#getGlyphs--) | Ottiene l'array dei glifi Un array di valori a 16 bit che definiscono la stringa di testo da disegnare. |
| [setGlyphs(short[] value)](#setGlyphs-short---) | Imposta l'array dei glifi Un array di valori a 16 bit che definiscono la stringa di testo da disegnare. |
| [isColor()](#isColor--) | Ottiene o imposta un valore che indica se questa istanza è a colori. |
| [setColor(boolean value)](#setColor-boolean-) | Imposta un valore che indica se questa istanza è a colori. |
| [getMatrixPresent()](#getMatrixPresent--) | Ottiene se il flag della matrice presente Un intero senza segno a 32 bit che specifica se una matrice di trasformazione è presente nel campo TransformMatrix 0 - nessuna matrice presente. |
| [setMatrixPresent(int value)](#setMatrixPresent-int-) | Imposta se il flag della matrice presente Un intero senza segno a 32 bit che specifica se una matrice di trasformazione è presente nel campo TransformMatrix 0 - nessuna matrice presente. |
| [getTransformMatrix()](#getTransformMatrix--) | Ottiene la matrice di trasformazione Un oggetto opzionale EmfPlusTransformMatrix (sezione 2.2.2.47) che specifica la trasformazione da applicare a ciascun valore nell'array di testo. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | Imposta la matrice di trasformazione Un oggetto opzionale EmfPlusTransformMatrix (sezione 2.2.2.47) che specifica la trasformazione da applicare a ciascun valore nell'array di testo. |
### EmfPlusDrawDriverString(EmfPlusRecord source) {#EmfPlusDrawDriverString-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawDriverString(EmfPlusRecord source)
```


Inizializza una nuova istanza della classe `EmfPlusDrawDriverString`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La sorgente. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Ottiene l'identificatore dell'oggetto. L'indice della EMF+ Object Table di un `` oggetto (sezione 2.2.1.3) per renderizzare il testo. Il valore DEVE essere compreso tra 0 e 63, inclusi.

**Returns:**
byte - L'identificatore dell'oggetto.
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Imposta l'identificatore dell'oggetto. L'indice della EMF+ Object Table di un `` oggetto (sezione 2.2.1.3) per renderizzare il testo. Il valore DEVE essere compreso tra 0 e 63, inclusi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte | L'identificatore dell'oggetto. |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Ottiene l'identificatore del pennello Un intero senza segno a 32 bit che specifica sia il colore di primo piano del testo sia un pennello grafico, a seconda del valore del flag S nei Flags

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Imposta l'identificatore del pennello Un intero senza segno a 32 bit che specifica o il colore di primo piano del testo o un pennello grafico, a seconda del valore del flag S nei Flags

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getDriverStringOptionsFlags() {#getDriverStringOptionsFlags--}
```
public int getDriverStringOptionsFlags()
```


Ottiene le flag delle opzioni della stringa del driver Un intero senza segno a 32 bit che specifica la spaziatura, l'orientamento e la qualità del rendering per la stringa.

**Returns:**
int
### setDriverStringOptionsFlags(int value) {#setDriverStringOptionsFlags-int-}
```
public void setDriverStringOptionsFlags(int value)
```


Imposta le flag delle opzioni della stringa del driver Un intero senza segno a 32 bit che specifica la spaziatura, l'orientamento e la qualità del rendering per la stringa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getGlyphCount() {#getGlyphCount--}
```
public int getGlyphCount()
```


Ottiene il conteggio dei glifi Un intero senza segno a 32 bit che specifica il numero di glifi nella stringa

**Returns:**
int
### setGlyphCount(int value) {#setGlyphCount-int-}
```
public void setGlyphCount(int value)
```


Imposta il conteggio dei glifi Un intero senza segno a 32 bit che specifica il numero di glifi nella stringa

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getGlyphPos() {#getGlyphPos--}
```
public PointF[] getGlyphPos()
```


Ottiene l'array delle posizioni dei glifi Un array di oggetti EmfPlusPointF (sezione 2.2.36) che specificano la posizione di output di ogni glifo di carattere. DEVE esserci un numero di elementi pari a GlyphCount, che hanno una corrispondenza uno-a-uno con gli elementi nell'array Glyphs. Le posizioni dei glifi sono calcolate dalla posizione del primo glifo se il flag DriverStringOptionsRealizedAdvance nelle flag DriverStringOptions è impostato. In questo caso, GlyphPos specifica solo la posizione del primo glifo.

**Returns:**
com.aspose.imaging.PointF[]
### setGlyphPos(PointF[] value) {#setGlyphPos-com.aspose.imaging.PointF---}
```
public void setGlyphPos(PointF[] value)
```


Imposta l'array delle posizioni dei glifi Un array di oggetti EmfPlusPointF (sezione 2.2.36) che specificano la posizione di output di ogni glifo di carattere. DEVE esserci un numero di elementi pari a GlyphCount, che hanno una corrispondenza uno-a-uno con gli elementi nell'array Glyphs. Le posizioni dei glifi sono calcolate dalla posizione del primo glifo se il flag DriverStringOptionsRealizedAdvance nelle flag DriverStringOptions è impostato. In questo caso, GlyphPos specifica solo la posizione del primo glifo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

### getGlyphs() {#getGlyphs--}
```
public short[] getGlyphs()
```


Ottiene l'array dei glifi Un array di valori a 16 bit che definiscono la stringa di testo da disegnare. Se il flag DriverStringOptionsCmapLookup nel campo DriverStringOptionsFlags è impostato, ogni valore in questo array specifica un carattere Unicode. Altrimenti, ogni valore specifica un indice a un glifo di carattere nell'oggetto EmfPlusFont specificato dal valore ObjectId nel campo Flags.

**Returns:**
short[]
### setGlyphs(short[] value) {#setGlyphs-short---}
```
public void setGlyphs(short[] value)
```


Imposta l'array dei glifi Un array di valori a 16 bit che definiscono la stringa di testo da disegnare. Se il flag DriverStringOptionsCmapLookup nel campo DriverStringOptionsFlags è impostato, ogni valore in questo array specifica un carattere Unicode. Altrimenti, ogni valore specifica un indice a un glifo di carattere nell'oggetto EmfPlusFont specificato dal valore ObjectId nel campo Flags.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short[] |  |

### isColor() {#isColor--}
```
public boolean isColor()
```


Ottiene o imposta un valore che indica se questa istanza è a colori. Questo bit indica il tipo di dati nel campo BrushId. Se impostato, BrushId specifica il valore di colore in un oggetto EmfPlusARGB (sezione 2.2.2.1). Se non impostato, BrushId contiene l'indice della EMF+ Object Table di un oggetto EmfPlusBrush (sezione 2.2.1.1).

**Returns:**
boolean - `true` se questa istanza è a colori; altrimenti, `false`.
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


Imposta un valore che indica se questa istanza è a colori. Questo bit indica il tipo di dati nel campo BrushId. Se impostato, BrushId specifica il valore di colore in un oggetto EmfPlusARGB (sezione 2.2.2.1). Se non impostato, BrushId contiene l'indice della EMF+ Object Table di un oggetto EmfPlusBrush (sezione 2.2.1.1).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | `true` se questa istanza è a colori; altrimenti, `false`. |

### getMatrixPresent() {#getMatrixPresent--}
```
public int getMatrixPresent()
```


Ottiene il flag MatrixPresent, un intero senza segno a 32 bit che specifica se una matrice di trasformazione è presente nel campo TransformMatrix: 0 - nessuna matrice presente. 1 - la matrice di trasformazione è nel campo TransformMatrix.

**Returns:**
int
### setMatrixPresent(int value) {#setMatrixPresent-int-}
```
public void setMatrixPresent(int value)
```


Imposta il flag MatrixPresent, un intero senza segno a 32 bit che specifica se una matrice di trasformazione è presente nel campo TransformMatrix: 0 - nessuna matrice presente. 1 - la matrice di trasformazione è nel campo TransformMatrix.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


Ottiene la matrice di trasformazione, un oggetto opzionale EmfPlusTransformMatrix (sezione 2.2.2.47) che specifica la trasformazione da applicare a ciascun valore nell'array di testo. La presenza di questi dati è determinata dal campo MatrixPresent.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


Imposta la matrice di trasformazione, un oggetto opzionale EmfPlusTransformMatrix (sezione 2.2.2.47) che specifica la trasformazione da applicare a ciascun valore nell'array di testo. La presenza di questi dati è determinata dal campo MatrixPresent.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

