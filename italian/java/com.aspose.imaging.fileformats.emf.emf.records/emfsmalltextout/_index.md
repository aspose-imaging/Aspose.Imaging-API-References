---
title: "EmfSmallTextOut"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_SMALLTEXTOUT emette una stringa."
type: docs
weight: 147
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfSmallTextOut extends EmfDrawingRecordType
```

Il record EMR\_SMALLTEXTOUT emette una stringa.

Se ETO\_SMALL\_CHARS è impostato nel campo fuOptions, TextString contiene codici a 8 bit per i caratteri, derivati dai byte meno significativi dei codici carattere Unicode UTF16-LE a 16 bit, in cui il byte più significativo è considerato 0. Se ETO\_NO\_RECT è impostato nel campo fuOptions, il campo Bounds non è incluso nel record.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfSmallTextOut(EmfRecord source)](#EmfSmallTextOut-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfSmallTextOut`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getX()](#getX--) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata x del punto in cui posizionare la stringa. |
| [setX(int value)](#setX-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata x del punto in cui posizionare la stringa. |
| [getY()](#getY--) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata y del punto in cui posizionare la stringa. |
| [setY(int value)](#setY-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata y del punto in cui posizionare la stringa. |
| [getCChars()](#getCChars--) | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di caratteri a 16 bit nella stringa. |
| [setCChars(int value)](#setCChars-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di caratteri a 16 bit nella stringa. |
| [getFuOptions()](#getFuOptions--) | Ottiene o imposta un intero senza segno a 32 bit che specifica le opzioni di output del testo da utilizzare. |
| [setFuOptions(int value)](#setFuOptions-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica le opzioni di output del testo da utilizzare. |
| [getIGraphicsMode()](#getIGraphicsMode--) | Ottiene o imposta un intero senza segno a 32 bit che specifica la modalità grafica, dall'enumerazione GraphicsMode (sezione 2.1.16). |
| [setIGraphicsMode(int value)](#setIGraphicsMode-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica la modalità grafica, dall'enumerazione GraphicsMode (sezione 2.1.16). |
| [getExScale()](#getExScale--) | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica di quanto scalare il testo nella direzione x. |
| [setExScale(float value)](#setExScale-float-) | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica di quanto scalare il testo nella direzione x. |
| [getEyScale()](#getEyScale--) | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica di quanto scalare il testo nella direzione y. |
| [setEyScale(float value)](#setEyScale-float-) | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica di quanto scalare il testo nella direzione y. |
| [getBounds()](#getBounds--) | Ottiene o imposta un oggetto opzionale WMF RectL a 128 bit ([MS-WMF] sezione 2.2.2.19) che specifica il rettangolo di delimitazione in unità dispositivo. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Ottiene o imposta un oggetto opzionale WMF RectL a 128 bit ([MS-WMF] sezione 2.2.2.19) che specifica il rettangolo di delimitazione in unità dispositivo. |
| [getTextString()](#getTextString--) | Ottiene o imposta una stringa a lunghezza variabile che contiene la stringa di testo da disegnare, in codici a 8 bit o a 16 bit, in base al valore del campo fuOptions. |
| [setTextString(String value)](#setTextString-java.lang.String-) | Ottiene o imposta una stringa a lunghezza variabile che contiene la stringa di testo da disegnare, in codici a 8 bit o a 16 bit, in base al valore del campo fuOptions. |
### EmfSmallTextOut(EmfRecord source) {#EmfSmallTextOut-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSmallTextOut(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfSmallTextOut`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### getX() {#getX--}
```
public int getX()
```


Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata x del punto in cui posizionare la stringa.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata x del punto in cui posizionare la stringa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getY() {#getY--}
```
public int getY()
```


Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata y del punto in cui posizionare la stringa.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata y del punto in cui posizionare la stringa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getCChars() {#getCChars--}
```
public int getCChars()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di caratteri a 16 bit nella stringa. La stringa NON è terminata da null.

**Returns:**
int
### setCChars(int value) {#setCChars-int-}
```
public void setCChars(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di caratteri a 16 bit nella stringa. La stringa NON è terminata da null.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getFuOptions() {#getFuOptions--}
```
public int getFuOptions()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica le opzioni di output del testo da utilizzare. Queste opzioni sono specificate da uno o una combinazione di valori dell'enumerazione ExtTextOutOptions (sezione 2.1.11).

**Returns:**
int
### setFuOptions(int value) {#setFuOptions-int-}
```
public void setFuOptions(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica le opzioni di output del testo da utilizzare. Queste opzioni sono specificate da uno o una combinazione di valori dell'enumerazione ExtTextOutOptions (sezione 2.1.11).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getIGraphicsMode() {#getIGraphicsMode--}
```
public int getIGraphicsMode()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la modalità grafica, dall'enumerazione GraphicsMode (sezione 2.1.16).

**Returns:**
int
### setIGraphicsMode(int value) {#setIGraphicsMode-int-}
```
public void setIGraphicsMode(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la modalità grafica, dall'enumerazione GraphicsMode (sezione 2.1.16).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getExScale() {#getExScale--}
```
public float getExScale()
```


Ottiene o imposta un valore a virgola mobile a 32 bit che specifica di quanto scalare il testo nella direzione x.

**Returns:**
float
### setExScale(float value) {#setExScale-float-}
```
public void setExScale(float value)
```


Ottiene o imposta un valore a virgola mobile a 32 bit che specifica di quanto scalare il testo nella direzione x.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getEyScale() {#getEyScale--}
```
public float getEyScale()
```


Ottiene o imposta un valore a virgola mobile a 32 bit che specifica di quanto scalare il testo nella direzione y.

**Returns:**
float
### setEyScale(float value) {#setEyScale-float-}
```
public void setEyScale(float value)
```


Ottiene o imposta un valore a virgola mobile a 32 bit che specifica di quanto scalare il testo nella direzione y.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Ottiene o imposta un oggetto opzionale WMF RectL a 128 bit ([MS-WMF] sezione 2.2.2.19) che specifica il rettangolo di delimitazione in unità dispositivo.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Ottiene o imposta un oggetto opzionale WMF RectL a 128 bit ([MS-WMF] sezione 2.2.2.19) che specifica il rettangolo di delimitazione in unità dispositivo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getTextString() {#getTextString--}
```
public String getTextString()
```


Ottiene o imposta una stringa a lunghezza variabile che contiene la stringa di testo da disegnare, in codici a 8 bit o a 16 bit, in base al valore del campo fuOptions.

**Returns:**
java.lang.String
### setTextString(String value) {#setTextString-java.lang.String-}
```
public void setTextString(String value)
```


Ottiene o imposta una stringa a lunghezza variabile che contiene la stringa di testo da disegnare, in codici a 8 bit o a 16 bit, in base al valore del campo fuOptions.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

