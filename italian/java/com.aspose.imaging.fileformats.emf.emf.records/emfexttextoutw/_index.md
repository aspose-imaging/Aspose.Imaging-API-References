---
title: "EmfExtTextOutW"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "La registrazione EMR_EXTTEXTOUTW disegna una stringa di testo ASCII usando il carattere corrente e i colori del testo."
type: docs
weight: 57
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfExtTextOutW extends EmfDrawingRecordType
```

Il record EMR\_EXTTEXTOUTW disegna una stringa di testo ASCII usando il carattere corrente e i colori del testo.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfExtTextOutW(EmfRecord source)](#EmfExtTextOutW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfExtTextOutW`. |
| [EmfExtTextOutW()](#EmfExtTextOutW--) | Inizializza una nuova istanza della classe `EmfExtTextOutW`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBounds()](#getBounds--) | Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19). |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19). |
| [getIGraphicsMode()](#getIGraphicsMode--) | Ottiene o imposta un intero senza segno a 32 bit che specifica la modalità grafica dall'enumerazione GraphicsMode (sezione 2.1.16). |
| [setIGraphicsMode(int value)](#setIGraphicsMode-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica la modalità grafica dall'enumerazione GraphicsMode (sezione 2.1.16). |
| [getExScale()](#getExScale--) | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica il fattore di scala da applicare lungo l'asse X per convertire le unità di spazio pagina in unità di .01 mm. |
| [setExScale(float value)](#setExScale-float-) | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica il fattore di scala da applicare lungo l'asse X per convertire le unità di spazio pagina in unità di .01 mm. |
| [getEyScale()](#getEyScale--) | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica il fattore di scala da applicare lungo l'asse Y per convertire le unità di spazio pagina in unità di .01 mm. |
| [setEyScale(float value)](#setEyScale-float-) | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica il fattore di scala da applicare lungo l'asse Y per convertire le unità di spazio pagina in unità di .01 mm. |
| [getWEmrText()](#getWEmrText--) | Ottiene o imposta un oggetto EmrText (sezione 2.2.5) che specifica la stringa di output in caratteri Unicode UTF16-LE a 16 bit, con attributi di testo e valori di spaziatura. |
| [setWEmrText(EmfText value)](#setWEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText-) | Ottiene o imposta un oggetto EmrText (sezione 2.2.5) che specifica la stringa di output in caratteri Unicode UTF16-LE a 16 bit, con attributi di testo e valori di spaziatura. |
### EmfExtTextOutW(EmfRecord source) {#EmfExtTextOutW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtTextOutW(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfExtTextOutW`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### EmfExtTextOutW() {#EmfExtTextOutW--}
```
public EmfExtTextOutW()
```


Inizializza una nuova istanza della classe `EmfExtTextOutW`.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19). Non è utilizzato e DEVE essere ignorato al ricevimento.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19). Non è utilizzato e DEVE essere ignorato al ricevimento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getIGraphicsMode() {#getIGraphicsMode--}
```
public int getIGraphicsMode()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la modalità grafica dall'enumerazione GraphicsMode (sezione 2.1.16).

**Returns:**
int
### setIGraphicsMode(int value) {#setIGraphicsMode-int-}
```
public void setIGraphicsMode(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la modalità grafica dall'enumerazione GraphicsMode (sezione 2.1.16).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getExScale() {#getExScale--}
```
public float getExScale()
```


Ottiene o imposta un valore a virgola mobile a 32 bit che specifica il fattore di scala da applicare lungo l'asse X per convertire le unità di spazio pagina in unità di .01 mm. Questo DOVREBBE essere usato solo se la modalità grafica specificata da iGraphicsMode è GM\_COMPATIBLE.

**Returns:**
float
### setExScale(float value) {#setExScale-float-}
```
public void setExScale(float value)
```


Ottiene o imposta un valore a virgola mobile a 32 bit che specifica il fattore di scala da applicare lungo l'asse X per convertire le unità di spazio pagina in unità di .01 mm. Questo DOVREBBE essere usato solo se la modalità grafica specificata da iGraphicsMode è GM\_COMPATIBLE.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getEyScale() {#getEyScale--}
```
public float getEyScale()
```


Ottiene o imposta un valore a virgola mobile a 32 bit che specifica il fattore di scala da applicare lungo l'asse Y per convertire le unità di spazio pagina in unità di .01 mm. Questo DOVREBBE essere usato solo se la modalità grafica specificata da iGraphicsMode è GM\_COMPATIBLE.

**Returns:**
float
### setEyScale(float value) {#setEyScale-float-}
```
public void setEyScale(float value)
```


Ottiene o imposta un valore a virgola mobile a 32 bit che specifica il fattore di scala da applicare lungo l'asse Y per convertire le unità di spazio pagina in unità di .01 mm. Questo DOVREBBE essere usato solo se la modalità grafica specificata da iGraphicsMode è GM\_COMPATIBLE.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getWEmrText() {#getWEmrText--}
```
public EmfText getWEmrText()
```


Ottiene o imposta un oggetto EmrText (sezione 2.2.5) che specifica la stringa di output in caratteri Unicode UTF16-LE a 16 bit, con attributi di testo e valori di spaziatura.

**Returns:**
[EmfText](../../com.aspose.imaging.fileformats.emf.emf.objects/emftext)
### setWEmrText(EmfText value) {#setWEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText-}
```
public void setWEmrText(EmfText value)
```


Ottiene o imposta un oggetto EmrText (sezione 2.2.5) che specifica la stringa di output in caratteri Unicode UTF16-LE a 16 bit, con attributi di testo e valori di spaziatura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfText](../../com.aspose.imaging.fileformats.emf.emf.objects/emftext) |  |

