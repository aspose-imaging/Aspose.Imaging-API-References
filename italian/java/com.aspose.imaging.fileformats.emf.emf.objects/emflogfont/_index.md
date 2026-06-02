---
title: "EmfLogFont"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto LogFont specifica gli attributi di base di un font logico."
type: docs
weight: 22
url: /it/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogfont/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public class EmfLogFont extends EmfObject
```

L'oggetto LogFont specifica gli attributi di base di un font logico.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfLogFont()](#EmfLogFont--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getHeight()](#getHeight--) | Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza, in unità logiche, della cella del carattere o del carattere del font. |
| [setHeight(int value)](#setHeight-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza, in unità logiche, della cella del carattere o del carattere del font. |
| [getWidth()](#getWidth--) | Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza media, in unità logiche, dei caratteri nel font. |
| [setWidth(int value)](#setWidth-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza media, in unità logiche, dei caratteri nel font. |
| [getEscapement()](#getEscapement--) | Ottiene o imposta un intero con segno a 32 bit che specifica l'angolo, in decimi di grado, tra il vettore di escapement e l'asse x del dispositivo. |
| [setEscapement(int value)](#setEscapement-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica l'angolo, in decimi di grado, tra il vettore di escapement e l'asse x del dispositivo. |
| [getOrientation()](#getOrientation--) | Ottiene o imposta un intero con segno a 32 bit che specifica l'angolo, in decimi di grado, tra la linea di base di ogni carattere e l'asse x del dispositivo. |
| [setOrientation(int value)](#setOrientation-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica l'angolo, in decimi di grado, tra la linea di base di ogni carattere e l'asse x del dispositivo. |
| [getWeight()](#getWeight--) | Ottiene o imposta un intero con segno a 32 bit che specifica il peso del font nell'intervallo da zero a 1000. |
| [setWeight(int value)](#setWeight-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica il peso del font nell'intervallo da zero a 1000. |
| [getItalic()](#getItalic--) | Ottiene o imposta un intero senza segno a 8 bit che specifica un font corsivo se impostato a 0x01; altrimenti, DEVE essere impostato a 0x00. |
| [setItalic(byte value)](#setItalic-byte-) | Ottiene o imposta un intero senza segno a 8 bit che specifica un font corsivo se impostato a 0x01; altrimenti, DEVE essere impostato a 0x00. |
| [getUnderline()](#getUnderline--) | Ottiene o imposta un intero senza segno a 8 bit che specifica un font sottolineato se impostato a 0x01; altrimenti, DEVE essere impostato a 0x00. |
| [setUnderline(byte value)](#setUnderline-byte-) | Ottiene o imposta un intero senza segno a 8 bit che specifica un font sottolineato se impostato a 0x01; altrimenti, DEVE essere impostato a 0x00. |
| [getStrikeout()](#getStrikeout--) | Ottiene o imposta un intero senza segno a 8 bit che specifica un font barrato se impostato a 0x01; altrimenti, DEVE essere impostato a 0x00. |
| [setStrikeout(byte value)](#setStrikeout-byte-) | Ottiene o imposta un intero senza segno a 8 bit che specifica un font barrato se impostato a 0x01; altrimenti, DEVE essere impostato a 0x00. |
| [getCharSet()](#getCharSet--) | Ottiene o imposta un intero senza segno a 8 bit che specifica il set di glifi dei caratteri. |
| [setCharSet(byte value)](#setCharSet-byte-) | Ottiene o imposta un intero senza segno a 8 bit che specifica il set di glifi dei caratteri. |
| [getOutPrecision()](#getOutPrecision--) | Ottiene o imposta un intero senza segno a 8 bit che specifica la precisione di output. |
| [setOutPrecision(byte value)](#setOutPrecision-byte-) | Ottiene o imposta un intero senza segno a 8 bit che specifica la precisione di output. |
| [getClipPrecision()](#getClipPrecision--) | Ottiene o imposta un intero senza segno a 8 bit che specifica la precisione di clipping. |
| [setClipPrecision(byte value)](#setClipPrecision-byte-) | Ottiene o imposta un intero senza segno a 8 bit che specifica la precisione di clipping. |
| [getQuality()](#getQuality--) | Ottiene o imposta un intero senza segno a 8 bit che specifica la qualità di output. |
| [setQuality(byte value)](#setQuality-byte-) | Ottiene o imposta un intero senza segno a 8 bit che specifica la qualità di output. |
| [getPitchAndFamily()](#getPitchAndFamily--) | Ottiene o imposta un oggetto WMF PitchAndFamily ([MS-WMF] sezione 2.2.2.14) che specifica il pitch e la famiglia del font. |
| [setPitchAndFamily(WmfPitchAndFamily value)](#setPitchAndFamily-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-) | Ottiene o imposta un oggetto WMF PitchAndFamily ([MS-WMF] sezione 2.2.2.14) che specifica il pitch e la famiglia del font. |
| [getFacename()](#getFacename--) | Ottiene o imposta un Facename (64 byte): una stringa di non più di 32 caratteri Unicode che specifica il nome del tipo di carattere del font. |
| [setFacename(String value)](#setFacename-java.lang.String-) | Ottiene o imposta un Facename (64 byte): una stringa di non più di 32 caratteri Unicode che specifica il nome del tipo di carattere del font. |
### EmfLogFont() {#EmfLogFont--}
```
public EmfLogFont()
```


### getHeight() {#getHeight--}
```
public int getHeight()
```


Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza, in unità logiche, della cella del carattere o del carattere del font. Il valore dell'altezza del carattere, noto anche come dimensione em, è il valore dell'altezza della cella del carattere meno il valore del leading interno. Il mapper del font DOVREBBE interpretare il valore specificato nel campo Height nel modo seguente.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza, in unità logiche, della cella del carattere o del carattere del font. Il valore dell'altezza del carattere, noto anche come dimensione em, è il valore dell'altezza della cella del carattere meno il valore del leading interno. Il mapper del font DOVREBBE interpretare il valore specificato nel campo Height nel modo seguente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza media, in unità logiche, dei caratteri nel font. Se il valore del campo Width è zero, un valore appropriato DOVREBBE essere calcolato da altri valori LogFont per trovare un font che abbia il rapporto d'aspetto previsto dal tipografo.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza media, in unità logiche, dei caratteri nel font. Se il valore del campo Width è zero, un valore appropriato DOVREBBE essere calcolato da altri valori LogFont per trovare un font che abbia il rapporto d'aspetto previsto dal tipografo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getEscapement() {#getEscapement--}
```
public int getEscapement()
```


Ottiene o imposta un intero con segno a 32 bit che specifica l'angolo, in decimi di grado, tra il vettore di escapement e l'asse x del dispositivo. Il vettore di escapement è parallelo alla linea di base di una riga di testo.

**Returns:**
int
### setEscapement(int value) {#setEscapement-int-}
```
public void setEscapement(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica l'angolo, in decimi di grado, tra il vettore di escapement e l'asse x del dispositivo. Il vettore di escapement è parallelo alla linea di base di una riga di testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


Ottiene o imposta un intero con segno a 32 bit che specifica l'angolo, in decimi di grado, tra la linea di base di ogni carattere e l'asse x del dispositivo.

**Returns:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica l'angolo, in decimi di grado, tra la linea di base di ogni carattere e l'asse x del dispositivo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getWeight() {#getWeight--}
```
public int getWeight()
```


Ottiene o imposta un intero con segno a 32 bit che specifica lo spessore del carattere nell'intervallo da zero a 1000. Ad esempio, 400 è normale e 700 è grassetto. Se questo valore è zero, può essere usato uno spessore predefinito.

**Returns:**
int
### setWeight(int value) {#setWeight-int-}
```
public void setWeight(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica lo spessore del carattere nell'intervallo da zero a 1000. Ad esempio, 400 è normale e 700 è grassetto. Se questo valore è zero, può essere usato uno spessore predefinito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getItalic() {#getItalic--}
```
public byte getItalic()
```


Ottiene o imposta un intero senza segno a 8 bit che specifica un font corsivo se impostato a 0x01; altrimenti, DEVE essere impostato a 0x00.

**Returns:**
byte
### setItalic(byte value) {#setItalic-byte-}
```
public void setItalic(byte value)
```


Ottiene o imposta un intero senza segno a 8 bit che specifica un font corsivo se impostato a 0x01; altrimenti, DEVE essere impostato a 0x00.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getUnderline() {#getUnderline--}
```
public byte getUnderline()
```


Ottiene o imposta un intero senza segno a 8 bit che specifica un font sottolineato se impostato a 0x01; altrimenti, DEVE essere impostato a 0x00.

**Returns:**
byte
### setUnderline(byte value) {#setUnderline-byte-}
```
public void setUnderline(byte value)
```


Ottiene o imposta un intero senza segno a 8 bit che specifica un font sottolineato se impostato a 0x01; altrimenti, DEVE essere impostato a 0x00.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getStrikeout() {#getStrikeout--}
```
public byte getStrikeout()
```


Ottiene o imposta un intero senza segno a 8 bit che specifica un font barrato se impostato a 0x01; altrimenti, DEVE essere impostato a 0x00.

**Returns:**
byte
### setStrikeout(byte value) {#setStrikeout-byte-}
```
public void setStrikeout(byte value)
```


Ottiene o imposta un intero senza segno a 8 bit che specifica un font barrato se impostato a 0x01; altrimenti, DEVE essere impostato a 0x00.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getCharSet() {#getCharSet--}
```
public byte getCharSet()
```


Ottiene o imposta un intero senza segno a 8 bit che specifica il set di glifi dei caratteri. Deve essere un valore nell'enumerazione WMF CharacterSet ([MS-WMF] sezione 2.1.1.5). Se il set di caratteri è sconosciuto, l'elaborazione del metafile NON DEVE tentare di tradurre o interpretare le stringhe renderizzate con quel carattere.

**Returns:**
byte
### setCharSet(byte value) {#setCharSet-byte-}
```
public void setCharSet(byte value)
```


Ottiene o imposta un intero senza segno a 8 bit che specifica il set di glifi dei caratteri. Deve essere un valore nell'enumerazione WMF CharacterSet ([MS-WMF] sezione 2.1.1.5). Se il set di caratteri è sconosciuto, l'elaborazione del metafile NON DEVE tentare di tradurre o interpretare le stringhe renderizzate con quel carattere.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getOutPrecision() {#getOutPrecision--}
```
public byte getOutPrecision()
```


Ottiene o imposta un intero senza segno a 8 bit che specifica la precisione di output. La precisione di output definisce quanto il carattere debba corrispondere strettamente all'altezza, larghezza, orientamento dei caratteri, escapement, passo e tipo di carattere richiesti. Deve essere un valore dell'enumerazione WMF OutPrecision.

**Returns:**
byte
### setOutPrecision(byte value) {#setOutPrecision-byte-}
```
public void setOutPrecision(byte value)
```


Ottiene o imposta un intero senza segno a 8 bit che specifica la precisione di output. La precisione di output definisce quanto il carattere debba corrispondere strettamente all'altezza, larghezza, orientamento dei caratteri, escapement, passo e tipo di carattere richiesti. Deve essere un valore dell'enumerazione WMF OutPrecision.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getClipPrecision() {#getClipPrecision--}
```
public byte getClipPrecision()
```


Ottiene o imposta un intero senza segno a 8 bit che specifica la precisione di ritaglio. La precisione di ritaglio definisce come ritagliare i caratteri che sono parzialmente fuori dalla regione di ritaglio. Può essere uno o più dei flag WMF ClipPrecision.

**Returns:**
byte
### setClipPrecision(byte value) {#setClipPrecision-byte-}
```
public void setClipPrecision(byte value)
```


Ottiene o imposta un intero senza segno a 8 bit che specifica la precisione di ritaglio. La precisione di ritaglio definisce come ritagliare i caratteri che sono parzialmente fuori dalla regione di ritaglio. Può essere uno o più dei flag WMF ClipPrecision.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getQuality() {#getQuality--}
```
public byte getQuality()
```


Ottiene o imposta un intero senza segno a 8 bit che specifica la qualità di output. La qualità di output definisce quanto cercare di far corrispondere gli attributi del font logico a quelli di un vero font fisico. Deve essere uno dei valori nell'enumerazione WMF FontQuality ([MS-WMF] sezione 2.1.1.10).

**Returns:**
byte
### setQuality(byte value) {#setQuality-byte-}
```
public void setQuality(byte value)
```


Ottiene o imposta un intero senza segno a 8 bit che specifica la qualità di output. La qualità di output definisce quanto cercare di far corrispondere gli attributi del font logico a quelli di un vero font fisico. Deve essere uno dei valori nell'enumerazione WMF FontQuality ([MS-WMF] sezione 2.1.1.10).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getPitchAndFamily() {#getPitchAndFamily--}
```
public WmfPitchAndFamily getPitchAndFamily()
```


Ottiene o imposta un oggetto WMF PitchAndFamily ([MS-WMF] sezione 2.2.2.14) che specifica il passo e la famiglia del carattere. Le famiglie di caratteri descrivono l'aspetto di un carattere in modo generale. Sono destinate a specificare un carattere quando il tipo di carattere specificato non è disponibile.

**Returns:**
[WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily)
### setPitchAndFamily(WmfPitchAndFamily value) {#setPitchAndFamily-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-}
```
public void setPitchAndFamily(WmfPitchAndFamily value)
```


Ottiene o imposta un oggetto WMF PitchAndFamily ([MS-WMF] sezione 2.2.2.14) che specifica il passo e la famiglia del carattere. Le famiglie di caratteri descrivono l'aspetto di un carattere in modo generale. Sono destinate a specificare un carattere quando il tipo di carattere specificato non è disponibile.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily) |  |

### getFacename() {#getFacename--}
```
public String getFacename()
```


Ottiene o imposta un Facename (64 byte): una stringa di non più di 32 caratteri Unicode che specifica il nome del tipo di carattere. Se la lunghezza di questa stringa è inferiore a 32 caratteri, deve essere presente un NULL terminatore, dopo il quale il resto di questo campo deve essere ignorato.

**Returns:**
java.lang.String
### setFacename(String value) {#setFacename-java.lang.String-}
```
public void setFacename(String value)
```


Ottiene o imposta un Facename (64 byte): una stringa di non più di 32 caratteri Unicode che specifica il nome del tipo di carattere. Se la lunghezza di questa stringa è inferiore a 32 caratteri, deve essere presente un NULL terminatore, dopo il quale il resto di questo campo deve essere ignorato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

