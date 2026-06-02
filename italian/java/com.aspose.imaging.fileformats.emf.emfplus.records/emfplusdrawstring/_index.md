---
title: "EmfPlusDrawString"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EmfPlusDrawString specifica l'output di testo con formattazione della stringa"
type: docs
weight: 28
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawString extends EmfPlusDrawingRecordType
```

Il record EmfPlusDrawString specifica l'output di testo con formattazione della stringa
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusDrawString(EmfPlusRecord source)](#EmfPlusDrawString-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inizializza una nuova istanza della classe `EmfPlusDrawString`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isColor()](#isColor--) | Ottiene o imposta un valore che indica se questa istanza è a colori. |
| [setColor(boolean value)](#setColor-boolean-) | Ottiene o imposta un valore che indica se questa istanza è a colori. |
| [getObjectId()](#getObjectId--) | Ottiene o imposta l'identificatore dell'oggetto. |
| [setObjectId(byte value)](#setObjectId-byte-) | Ottiene o imposta l'identificatore dell'oggetto. |
| [getBrushId()](#getBrushId--) | Ottiene o imposta l'identificatore del pennello, un intero senza segno a 32 bit che specifica il pennello, il cui contenuto è determinato dal bit S nel campo Flags. |
| [setBrushId(int value)](#setBrushId-int-) | Ottiene o imposta l'identificatore del pennello, un intero senza segno a 32 bit che specifica il pennello, il cui contenuto è determinato dal bit S nel campo Flags. |
| [getFormatId()](#getFormatId--) | Ottiene o imposta l'identificatore del formato, un intero senza segno a 32 bit che specifica l'indice di un oggetto opzionale EmfPlusStringFormat (sezione 2.2.1.9) nella Tabella Oggetti EMF+. |
| [setFormatId(int value)](#setFormatId-int-) | Ottiene o imposta l'identificatore del formato, un intero senza segno a 32 bit che specifica l'indice di un oggetto opzionale EmfPlusStringFormat (sezione 2.2.1.9) nella Tabella Oggetti EMF+. |
| [getLength()](#getLength--) | Ottiene o imposta la lunghezza, un intero senza segno a 32 bit che specifica il numero di caratteri nella stringa. |
| [setLength(int value)](#setLength-int-) | Ottiene o imposta la lunghezza, un intero senza segno a 32 bit che specifica il numero di caratteri nella stringa. |
| [getLayoutRect()](#getLayoutRect--) | Ottiene o imposta il rettangolo di layout, un oggetto EmfPlusRectF (sezione 2.2.2.39) che definisce l'area di delimitazione della destinazione che riceverà la stringa. |
| [setLayoutRect(RectangleF value)](#setLayoutRect-com.aspose.imaging.RectangleF-) | Ottiene o imposta il rettangolo di layout, un oggetto EmfPlusRectF (sezione 2.2.2.39) che definisce l'area di delimitazione della destinazione che riceverà la stringa. |
| [getStringData()](#getStringData--) | Ottiene o imposta i dati della stringa, un array di caratteri Unicode a 16 bit che specifica la stringa da disegnare. |
| [setStringData(String value)](#setStringData-java.lang.String-) | Ottiene o imposta i dati della stringa, un array di caratteri Unicode a 16 bit che specifica la stringa da disegnare. |
### EmfPlusDrawString(EmfPlusRecord source) {#EmfPlusDrawString-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawString(EmfPlusRecord source)
```


Inizializza una nuova istanza della classe `EmfPlusDrawString`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La sorgente. |

### isColor() {#isColor--}
```
public boolean isColor()
```


Ottiene o imposta un valore che indica se questa istanza è a colori. Se impostato, BrushId specifica un colore come oggetto EmfPlusARGB (sezione 2.2.2.1). Se non impostato, BrushId contiene l'indice di un oggetto EmfPlusBrush (sezione 2.2.1.1) nella Tabella Oggetti EMF+.

Valore: `true` se questa istanza è a colori; altrimenti, `false`.

**Returns:**
boolean
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


Ottiene o imposta un valore che indica se questa istanza è a colori. Se impostato, BrushId specifica un colore come oggetto EmfPlusARGB (sezione 2.2.2.1). Se non impostato, BrushId contiene l'indice di un oggetto EmfPlusBrush (sezione 2.2.1.1) nella Tabella Oggetti EMF+.

Valore: `true` se questa istanza è a colori; altrimenti, `false`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Ottiene o imposta l'identificatore dell'oggetto. L'indice di un oggetto EmfPlusFont (sezione 2.2.1.3) nella Tabella Oggetti EMF+ per renderizzare il testo. Il valore DEVE essere compreso tra 0 e 63, inclusi.

Valore: L'identificatore dell'oggetto.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Ottiene o imposta l'identificatore dell'oggetto. L'indice di un oggetto EmfPlusFont (sezione 2.2.1.3) nella Tabella Oggetti EMF+ per renderizzare il testo. Il valore DEVE essere compreso tra 0 e 63, inclusi.

Valore: L'identificatore dell'oggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Ottiene o imposta l'identificatore del pennello, un intero senza segno a 32 bit che specifica il pennello, il cui contenuto è determinato dal bit S nel campo Flags. Questa definizione è usata per dipingere il colore del testo in primo piano; cioè, solo i glifi stessi.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Ottiene o imposta l'identificatore del pennello, un intero senza segno a 32 bit che specifica il pennello, il cui contenuto è determinato dal bit S nel campo Flags. Questa definizione è usata per dipingere il colore del testo in primo piano; cioè, solo i glifi stessi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getFormatId() {#getFormatId--}
```
public int getFormatId()
```


Ottiene o imposta l'identificatore del formato, un intero senza segno a 32 bit che specifica l'indice di un oggetto opzionale EmfPlusStringFormat (sezione 2.2.1.9) nella Tabella Oggetti EMF+. Questo oggetto specifica le informazioni di layout del testo e le manipolazioni di visualizzazione da applicare a una stringa.

**Returns:**
int
### setFormatId(int value) {#setFormatId-int-}
```
public void setFormatId(int value)
```


Ottiene o imposta l'identificatore del formato, un intero senza segno a 32 bit che specifica l'indice di un oggetto opzionale EmfPlusStringFormat (sezione 2.2.1.9) nella Tabella Oggetti EMF+. Questo oggetto specifica le informazioni di layout del testo e le manipolazioni di visualizzazione da applicare a una stringa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getLength() {#getLength--}
```
public int getLength()
```


Ottiene o imposta la lunghezza, un intero senza segno a 32 bit che specifica il numero di caratteri nella stringa.

**Returns:**
int
### setLength(int value) {#setLength-int-}
```
public void setLength(int value)
```


Ottiene o imposta la lunghezza, un intero senza segno a 32 bit che specifica il numero di caratteri nella stringa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getLayoutRect() {#getLayoutRect--}
```
public RectangleF getLayoutRect()
```


Ottiene o imposta il rettangolo di layout, un oggetto EmfPlusRectF (sezione 2.2.2.39) che definisce l'area di delimitazione della destinazione che riceverà la stringa.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setLayoutRect(RectangleF value) {#setLayoutRect-com.aspose.imaging.RectangleF-}
```
public void setLayoutRect(RectangleF value)
```


Ottiene o imposta il rettangolo di layout, un oggetto EmfPlusRectF (sezione 2.2.2.39) che definisce l'area di delimitazione della destinazione che riceverà la stringa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getStringData() {#getStringData--}
```
public String getStringData()
```


Ottiene o imposta i dati della stringa, un array di caratteri Unicode a 16 bit che specifica la stringa da disegnare.

**Returns:**
java.lang.String
### setStringData(String value) {#setStringData-java.lang.String-}
```
public void setStringData(String value)
```


Ottiene o imposta i dati della stringa, un array di caratteri Unicode a 16 bit che specifica la stringa da disegnare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

