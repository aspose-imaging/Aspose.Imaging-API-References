---
title: "EmfPolyTextOutW"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_POLYTEXTOUTW disegna una o più stringhe di testo Unicode usando il carattere corrente e i colori del testo."
type: docs
weight: 98
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPolyTextOutW extends EmfDrawingRecordType
```

Il record EMR\_POLYTEXTOUTW disegna una o più stringhe di testo Unicode utilizzando il carattere corrente e i colori del testo.

Il carattere e i colori del testo usati per l'output sono specificati dalle proprietà nello stato corrente del contesto del dispositivo di riproduzione. EMR\_POLYTEXTOUTW DOVREBBE essere emulato con una serie di record EMR\_EXTTEXTOUTW (sezione 2.3.5.7), uno per stringa.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPolyTextOutW(EmfRecord source)](#EmfPolyTextOutW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfPolyTextOutW`. |
| [EmfPolyTextOutW()](#EmfPolyTextOutW--) | Inizializza una nuova istanza della classe `EmfPolyTextOutW`. |
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
| [getWEmrText()](#getWEmrText--) | Ottiene o imposta un array di oggetti EmrText (sezione 2.2.5) che specificano le stringhe di output in caratteri Unicode UTF16-LE a 16 bit, con attributi di testo e valori di spaziatura. |
| [setWEmrText(EmfText[] value)](#setWEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText---) | Ottiene o imposta un array di oggetti EmrText (sezione 2.2.5) che specificano le stringhe di output in caratteri Unicode UTF16-LE a 16 bit, con attributi di testo e valori di spaziatura. |
### EmfPolyTextOutW(EmfRecord source) {#EmfPolyTextOutW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyTextOutW(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfPolyTextOutW`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### EmfPolyTextOutW() {#EmfPolyTextOutW--}
```
public EmfPolyTextOutW()
```


Inizializza una nuova istanza della classe `EmfPolyTextOutW`.

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

### getWEmrText() {#getWEmrText--}
```
public EmfText[] getWEmrText()
```


Ottiene o imposta un array di oggetti EmrText (sezione 2.2.5) che specificano le stringhe di output in caratteri Unicode UTF16-LE a 16 bit, con attributi di testo e valori di spaziatura. Il numero di oggetti EmrText è specificato da cStrings.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfText[]
### setWEmrText(EmfText[] value) {#setWEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText---}
```
public void setWEmrText(EmfText[] value)
```


Ottiene o imposta un array di oggetti EmrText (sezione 2.2.5) che specificano le stringhe di output in caratteri Unicode UTF16-LE a 16 bit, con attributi di testo e valori di spaziatura. Il numero di oggetti EmrText è specificato da cStrings.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfText\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emftext) |  |

