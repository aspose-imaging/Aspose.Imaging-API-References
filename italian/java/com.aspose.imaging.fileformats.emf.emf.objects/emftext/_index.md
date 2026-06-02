---
title: "EmfText"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto EmrText contiene valori per l'output di testo."
type: docs
weight: 35
url: /it/java/com.aspose.imaging.fileformats.emf.emf.objects/emftext/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfText extends EmfObject
```

L'oggetto EmrText contiene valori per l'output di testo.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfText()](#EmfText--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getReference()](#getReference--) | Ottiene o imposta un oggetto WMF PointL ([MS-WMF] sezione 2.2.2.15) che specifica le coordinate del punto di riferimento usato per posizionare la stringa. |
| [setReference(Point value)](#setReference-com.aspose.imaging.Point-) | Ottiene o imposta un oggetto WMF PointL ([MS-WMF] sezione 2.2.2.15) che specifica le coordinate del punto di riferimento usato per posizionare la stringa. |
| [getChars()](#getChars--) | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di caratteri nella stringa |
| [setChars(int value)](#setChars-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di caratteri nella stringa |
| [getOptions()](#getOptions--) | Ottiene o imposta un intero senza segno a 32 bit che specifica come utilizzare il rettangolo specificato nel campo Rectangle. |
| [setOptions(int value)](#setOptions-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica come utilizzare il rettangolo specificato nel campo Rectangle. |
| [getRectangle()](#getRectangle--) | Ottiene o imposta un oggetto WMF RectL opzionale ([MS-WMF] sezione 2.2.2.19) che definisce un rettangolo di ritaglio e/o opacizzazione in unità logiche. |
| [setRectangle(Rectangle value)](#setRectangle-com.aspose.imaging.Rectangle-) | Ottiene o imposta un oggetto WMF RectL opzionale ([MS-WMF] sezione 2.2.2.19) che definisce un rettangolo di ritaglio e/o opacizzazione in unità logiche. |
| [getStringBuffer()](#getStringBuffer--) | Ottiene o imposta il buffer della stringa di caratteri UndefinedSpace1 (variabile): un numero opzionale di byte inutilizzati. |
| [setStringBuffer(String value)](#setStringBuffer-java.lang.String-) | Ottiene o imposta il buffer della stringa di caratteri UndefinedSpace1 (variabile): un numero opzionale di byte inutilizzati. |
| [getGlyphIndexBuffer()](#getGlyphIndexBuffer--) | Ottiene il buffer opzionale degli indici dei glifi. |
| [setGlyphIndexBuffer(int[] value)](#setGlyphIndexBuffer-int---) | Imposta il buffer opzionale degli indici dei glifi. |
| [getDxBuffer()](#getDxBuffer--) | Ottiene o imposta il buffer opzionale della spaziatura dei caratteri UndefinedSpace2 (variabile): un numero opzionale di byte inutilizzati. |
| [setDxBuffer(int[] value)](#setDxBuffer-int---) | Ottiene o imposta il buffer opzionale della spaziatura dei caratteri UndefinedSpace2 (variabile): un numero opzionale di byte inutilizzati. |
### EmfText() {#EmfText--}
```
public EmfText()
```


### getReference() {#getReference--}
```
public Point getReference()
```


Ottiene o imposta un oggetto WMF PointL ([MS-WMF] sezione 2.2.2.15) che specifica le coordinate del punto di riferimento usato per posizionare la stringa. Il punto di riferimento è definito dall'ultimo record EMR\_SETTEXTALIGN (sezione 2.3.11.25). Se non è stato impostato alcun record di questo tipo, l'allineamento predefinito è TA\_LEFT,TA\_TOP.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setReference(Point value) {#setReference-com.aspose.imaging.Point-}
```
public void setReference(Point value)
```


Ottiene o imposta un oggetto WMF PointL ([MS-WMF] sezione 2.2.2.15) che specifica le coordinate del punto di riferimento usato per posizionare la stringa. Il punto di riferimento è definito dall'ultimo record EMR\_SETTEXTALIGN (sezione 2.3.11.25). Se non è stato impostato alcun record di questo tipo, l'allineamento predefinito è TA\_LEFT,TA\_TOP.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getChars() {#getChars--}
```
public int getChars()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di caratteri nella stringa

**Returns:**
int
### setChars(int value) {#setChars-int-}
```
public void setChars(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di caratteri nella stringa

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getOptions() {#getOptions--}
```
public int getOptions()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica come utilizzare il rettangolo specificato nel campo Rectangle. Questo campo può essere una combinazione di più valori dell'enumerazione ExtTextOutOptions (sezione 2.1.11).

**Returns:**
int
### setOptions(int value) {#setOptions-int-}
```
public void setOptions(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica come utilizzare il rettangolo specificato nel campo Rectangle. Questo campo può essere una combinazione di più valori dell'enumerazione ExtTextOutOptions (sezione 2.1.11).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Ottiene o imposta un oggetto WMF RectL opzionale ([MS-WMF] sezione 2.2.2.19) che definisce un rettangolo di ritaglio e/o opacizzazione in unità logiche. Questo rettangolo è applicato all'output di testo eseguito dal record contenente.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setRectangle(Rectangle value) {#setRectangle-com.aspose.imaging.Rectangle-}
```
public void setRectangle(Rectangle value)
```


Ottiene o imposta un oggetto WMF RectL opzionale ([MS-WMF] sezione 2.2.2.19) che definisce un rettangolo di ritaglio e/o opacizzazione in unità logiche. Questo rettangolo è applicato all'output di testo eseguito dal record contenente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getStringBuffer() {#getStringBuffer--}
```
public String getStringBuffer()
```


Ottiene o imposta il buffer della stringa di caratteri UndefinedSpace1 (variabile): un numero opzionale di byte inutilizzati. Il campo OutputString non è obbligatorio che segua immediatamente la parte precedente di questa struttura. OutputString (variabile): un array di caratteri che specificano la stringa da emettere. La posizione di questo campo è specificata dal valore di offString in byte dall'inizio di questo record. Il numero di caratteri è specificato dal valore di Chars.

**Returns:**
java.lang.String
### setStringBuffer(String value) {#setStringBuffer-java.lang.String-}
```
public void setStringBuffer(String value)
```


Ottiene o imposta il buffer della stringa di caratteri UndefinedSpace1 (variabile): un numero opzionale di byte inutilizzati. Il campo OutputString non è obbligatorio che segua immediatamente la parte precedente di questa struttura. OutputString (variabile): un array di caratteri che specificano la stringa da emettere. La posizione di questo campo è specificata dal valore di offString in byte dall'inizio di questo record. Il numero di caratteri è specificato dal valore di Chars.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getGlyphIndexBuffer() {#getGlyphIndexBuffer--}
```
public int[] getGlyphIndexBuffer()
```


Ottiene il buffer opzionale degli indici dei glifi. Se le opzioni hanno il flag ETO\_GLYPH\_INDEX, i codici dei caratteri in una stringa di testo in output sono in realtà indici dei glifi dei caratteri in un font TrueType (enumerazione ExtTextOutOptions 2.1.11). Gli indici dei glifi sono specifici del font, quindi per visualizzare correttamente i caratteri durante la riproduzione, il font utilizzato DEVE essere identico al font usato per generare gli indici.

**Returns:**
int[] - il buffer opzionale degli indici dei glifi.
### setGlyphIndexBuffer(int[] value) {#setGlyphIndexBuffer-int---}
```
public void setGlyphIndexBuffer(int[] value)
```


Imposta il buffer opzionale degli indici dei glifi. Se le opzioni hanno il flag ETO\_GLYPH\_INDEX, i codici dei caratteri in una stringa di testo in output sono in realtà indici dei glifi dei caratteri in un font TrueType (enumerazione ExtTextOutOptions 2.1.11). Gli indici dei glifi sono specifici del font, quindi per visualizzare correttamente i caratteri durante la riproduzione, il font utilizzato DEVE essere identico al font usato per generare gli indici.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] | il buffer opzionale degli indici dei glifi. |

### getDxBuffer() {#getDxBuffer--}
```
public int[] getDxBuffer()
```


Ottiene o imposta il buffer opzionale della spaziatura dei caratteri UndefinedSpace2 (variabile): un numero opzionale di byte inutilizzati. Il campo OutputDx non è obbligatorio che segua immediatamente la parte precedente di questa struttura. OutputDx (variabile): un array di interi senza segno a 32 bit che specificano la spaziatura di output tra le origini delle celle di caratteri adiacenti in unità logiche. La posizione di questo campo è specificata dal valore di offDx in byte dall'inizio di questo record. Se la spaziatura è definita, questo campo contiene lo stesso numero di valori dei caratteri nella stringa di output. Se il campo Options dell'oggetto EmrText contiene il flag ETO\_PDY, allora questo buffer contiene il doppio dei valori rispetto ai caratteri nella stringa di output, uno offset orizzontale e uno verticale per ciascuno, in quest'ordine. Se è specificato ETO\_RTLREADING, i caratteri sono disposti da destra a sinistra invece che da sinistra a destra. Nessun'altra opzione influisce sull'interpretazione di questo campo.

**Returns:**
int[]
### setDxBuffer(int[] value) {#setDxBuffer-int---}
```
public void setDxBuffer(int[] value)
```


Ottiene o imposta il buffer opzionale della spaziatura dei caratteri UndefinedSpace2 (variabile): un numero opzionale di byte inutilizzati. Il campo OutputDx non è obbligatorio che segua immediatamente la parte precedente di questa struttura. OutputDx (variabile): un array di interi senza segno a 32 bit che specificano la spaziatura di output tra le origini delle celle di caratteri adiacenti in unità logiche. La posizione di questo campo è specificata dal valore di offDx in byte dall'inizio di questo record. Se la spaziatura è definita, questo campo contiene lo stesso numero di valori dei caratteri nella stringa di output. Se il campo Options dell'oggetto EmrText contiene il flag ETO\_PDY, allora questo buffer contiene il doppio dei valori rispetto ai caratteri nella stringa di output, uno offset orizzontale e uno verticale per ciascuno, in quest'ordine. Se è specificato ETO\_RTLREADING, i caratteri sono disposti da destra a sinistra invece che da sinistra a destra. Nessun'altra opzione influisce sull'interpretazione di questo campo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] |  |

