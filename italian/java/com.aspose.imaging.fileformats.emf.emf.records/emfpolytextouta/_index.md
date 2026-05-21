---
title: "EmfPolyTextOutA"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_POLYTEXTOUTA disegna una o più stringhe di testo ASCII utilizzando il carattere corrente e i colori del testo."
type: docs
weight: 97
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPolyTextOutA extends EmfDrawingRecordType
```

Il record EMR\_POLYTEXTOUTA disegna una o più stringhe di testo ASCII utilizzando il carattere corrente e i colori del testo.

Il carattere e i colori del testo utilizzati per l'output sono specificati dalle proprietà nello stato corrente del contesto del dispositivo di riproduzione. EMR\_POLYTEXTOUTA DEVE essere emulato con una serie di record EMR\_EXTTEXTOUTW (sezione 2.3.5.7), uno per stringa. Ciò richiede che la stringa di testo ASCII in ogni oggetto EmrText sia convertita nella codifica Unicode UTF16-LE.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPolyTextOutA(EmfRecord source)](#EmfPolyTextOutA-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfPolyTextOutA`. |
| [EmfPolyTextOutA()](#EmfPolyTextOutA--) | Inizializza una nuova istanza della classe [EmfPolyTextOutA](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolytextouta). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBounds()](#getBounds--) | Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19), che specifica il rettangolo di delimitazione in unità del dispositivo. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19), che specifica il rettangolo di delimitazione in unità del dispositivo. |
| [getIGraphicsMode()](#getIGraphicsMode--) | Ottiene o imposta un intero senza segno a 32 bit che specifica la modalità grafica corrente, dall'enumerazione GraphicsMode (sezione 2.1.16). |
| [setIGraphicsMode(int value)](#setIGraphicsMode-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica la modalità grafica corrente, dall'enumerazione GraphicsMode (sezione 2.1.16). |
| [getExScale()](#getExScale--) | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica la scala X dalle unità di pagina a unità di .01 mm se la modalità grafica è GM\_COMPATIBLE. |
| [setExScale(float value)](#setExScale-float-) | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica la scala X dalle unità di pagina a unità di .01 mm se la modalità grafica è GM\_COMPATIBLE. |
| [getEyScale()](#getEyScale--) | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica la scala Y dalle unità di pagina a unità di .01 mm se la modalità grafica è GM\_COMPATIBLE. |
| [setEyScale(float value)](#setEyScale-float-) | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica la scala Y dalle unità di pagina a unità di .01 mm se la modalità grafica è GM\_COMPATIBLE. |
| [getAEmrText()](#getAEmrText--) | Ottiene o imposta un array di oggetti EmrText (sezione 2.2.5) che specificano le stringhe di output in caratteri ASCII a 8 bit, con attributi di testo e valori di spaziatura. |
| [setAEmrText(EmfText[] value)](#setAEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText---) | Ottiene o imposta un array di oggetti EmrText (sezione 2.2.5) che specificano le stringhe di output in caratteri ASCII a 8 bit, con attributi di testo e valori di spaziatura. |
### EmfPolyTextOutA(EmfRecord source) {#EmfPolyTextOutA-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyTextOutA(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfPolyTextOutA`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### EmfPolyTextOutA() {#EmfPolyTextOutA--}
```
public EmfPolyTextOutA()
```


Inizializza una nuova istanza della classe [EmfPolyTextOutA](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolytextouta).

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19), che specifica il rettangolo di delimitazione in unità del dispositivo.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19), che specifica il rettangolo di delimitazione in unità del dispositivo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getIGraphicsMode() {#getIGraphicsMode--}
```
public int getIGraphicsMode()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la modalità grafica corrente, dall'enumerazione GraphicsMode (sezione 2.1.16).

**Returns:**
int
### setIGraphicsMode(int value) {#setIGraphicsMode-int-}
```
public void setIGraphicsMode(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la modalità grafica corrente, dall'enumerazione GraphicsMode (sezione 2.1.16).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getExScale() {#getExScale--}
```
public float getExScale()
```


Ottiene o imposta un valore a virgola mobile a 32 bit che specifica la scala X dalle unità di pagina a unità di .01 mm se la modalità grafica è GM\_COMPATIBLE.

**Returns:**
float
### setExScale(float value) {#setExScale-float-}
```
public void setExScale(float value)
```


Ottiene o imposta un valore a virgola mobile a 32 bit che specifica la scala X dalle unità di pagina a unità di .01 mm se la modalità grafica è GM\_COMPATIBLE.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getEyScale() {#getEyScale--}
```
public float getEyScale()
```


Ottiene o imposta un valore a virgola mobile a 32 bit che specifica la scala Y dalle unità di pagina a unità di .01 mm se la modalità grafica è GM\_COMPATIBLE.

**Returns:**
float
### setEyScale(float value) {#setEyScale-float-}
```
public void setEyScale(float value)
```


Ottiene o imposta un valore a virgola mobile a 32 bit che specifica la scala Y dalle unità di pagina a unità di .01 mm se la modalità grafica è GM\_COMPATIBLE.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getAEmrText() {#getAEmrText--}
```
public EmfText[] getAEmrText()
```


Ottiene o imposta un array di oggetti EmrText (sezione 2.2.5) che specificano le stringhe di output in caratteri ASCII a 8 bit, con attributi di testo e valori di spaziatura. Il numero di oggetti EmrText è specificato da cStrings.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfText[]
### setAEmrText(EmfText[] value) {#setAEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText---}
```
public void setAEmrText(EmfText[] value)
```


Ottiene o imposta un array di oggetti EmrText (sezione 2.2.5) che specificano le stringhe di output in caratteri ASCII a 8 bit, con attributi di testo e valori di spaziatura. Il numero di oggetti EmrText è specificato da cStrings.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfText\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emftext) |  |

