---
title: "EmfLogFontPanose"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto LogFontPanose specifica le caratteristiche PANOSE di un font logico."
type: docs
weight: 25
url: /it/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont)
```
public final class EmfLogFontPanose extends EmfLogFont
```

L'oggetto LogFontPanose specifica le caratteristiche PANOSE di un font logico.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfLogFontPanose(EmfLogFont emfLogFont)](#EmfLogFontPanose-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-) | Inizializza una nuova istanza della classe `EmfLogFontPanose`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFullName()](#getFullName--) | Ottiene o imposta una stringa di 64 caratteri Unicode che definisce il nome completo del carattere. |
| [setFullName(String value)](#setFullName-java.lang.String-) | Ottiene o imposta una stringa di 64 caratteri Unicode che definisce il nome completo del carattere. |
| [getStyle()](#getStyle--) | Ottiene o imposta una stringa di 32 caratteri Unicode che definisce lo stile del carattere. |
| [setStyle(String value)](#setStyle-java.lang.String-) | Ottiene o imposta una stringa di 32 caratteri Unicode che definisce lo stile del carattere. |
| [getVersion()](#getVersion--) | Ottiene o imposta Questo campo MUST essere ignorato. |
| [setVersion(int value)](#setVersion-int-) | Ottiene o imposta Questo campo MUST essere ignorato. |
| [getStyleSize()](#getStyleSize--) | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione in punti in cui viene eseguito il hinting del carattere. |
| [setStyleSize(int value)](#setStyleSize-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione in punti in cui viene eseguito il hinting del carattere. |
| [getMatch()](#getMatch--) | Ottiene o imposta Questo campo MUST essere ignorato. |
| [setMatch(int value)](#setMatch-int-) | Ottiene o imposta Questo campo MUST essere ignorato. |
| [getVendorId()](#getVendorId--) | Ottiene o imposta Questo campo MUST essere ignorato. |
| [setVendorId(int value)](#setVendorId-int-) | Ottiene o imposta Questo campo MUST essere ignorato. |
| [getCulture()](#getCulture--) | Ottiene o imposta un intero senza segno a 32 bit che MUST essere impostato a zero e MUST essere ignorato. |
| [setCulture(int value)](#setCulture-int-) | Ottiene o imposta un intero senza segno a 32 bit che MUST essere impostato a zero e MUST essere ignorato. |
| [getPanose()](#getPanose--) | Ottiene o imposta un oggetto Panose (sezione 2.2.21) che specifica le caratteristiche PANOSE del carattere logico. |
| [setPanose(EmfPanose value)](#setPanose-com.aspose.imaging.fileformats.emf.emf.objects.EmfPanose-) | Ottiene o imposta un oggetto Panose (sezione 2.2.21) che specifica le caratteristiche PANOSE del carattere logico. |
| [getPadding()](#getPadding--) | Ottiene o imposta un campo che esiste solo per garantire l'allineamento a 32 bit di questa struttura. |
| [setPadding(short value)](#setPadding-short-) | Ottiene o imposta un campo che esiste solo per garantire l'allineamento a 32 bit di questa struttura. |
### EmfLogFontPanose(EmfLogFont emfLogFont) {#EmfLogFontPanose-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-}
```
public EmfLogFontPanose(EmfLogFont emfLogFont)
```


Inizializza una nuova istanza della classe `EmfLogFontPanose`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| emfLogFont | [EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont) | Il carattere log di base. |

### getFullName() {#getFullName--}
```
public String getFullName()
```


Ottiene o imposta una stringa di 64 caratteri Unicode che definisce il nome completo del carattere. Se la lunghezza di questa stringa è inferiore a 64 caratteri, deve essere presente un NULL terminatore, dopo il quale il resto di questo campo MUST essere ignorato.

**Returns:**
java.lang.String
### setFullName(String value) {#setFullName-java.lang.String-}
```
public void setFullName(String value)
```


Ottiene o imposta una stringa di 64 caratteri Unicode che definisce il nome completo del carattere. Se la lunghezza di questa stringa è inferiore a 64 caratteri, deve essere presente un NULL terminatore, dopo il quale il resto di questo campo MUST essere ignorato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getStyle() {#getStyle--}
```
public String getStyle()
```


Ottiene o imposta una stringa di 32 caratteri Unicode che definisce lo stile del carattere. Se la lunghezza di questa stringa è inferiore a 32 caratteri, un NULL terminatore DEVE essere presente, dopo il quale il resto di questo campo DEVE essere ignorato.

**Returns:**
java.lang.String
### setStyle(String value) {#setStyle-java.lang.String-}
```
public void setStyle(String value)
```


Ottiene o imposta una stringa di 32 caratteri Unicode che definisce lo stile del carattere. Se la lunghezza di questa stringa è inferiore a 32 caratteri, un NULL terminatore DEVE essere presente, dopo il quale il resto di questo campo DEVE essere ignorato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Ottiene o imposta Questo campo MUST essere ignorato.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Ottiene o imposta Questo campo MUST essere ignorato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getStyleSize() {#getStyleSize--}
```
public int getStyleSize()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione in punti in cui viene eseguito il hinting del carattere. Se impostato a zero, il hinting del carattere viene eseguito alla dimensione in punti corrispondente al campo Height nell'oggetto LogFont nel campo LogFont.

**Returns:**
int
### setStyleSize(int value) {#setStyleSize-int-}
```
public void setStyleSize(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione in punti in cui viene eseguito il hinting del carattere. Se impostato a zero, il hinting del carattere viene eseguito alla dimensione in punti corrispondente al campo Height nell'oggetto LogFont nel campo LogFont.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getMatch() {#getMatch--}
```
public int getMatch()
```


Ottiene o imposta Questo campo MUST essere ignorato.

**Returns:**
int
### setMatch(int value) {#setMatch-int-}
```
public void setMatch(int value)
```


Ottiene o imposta Questo campo MUST essere ignorato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getVendorId() {#getVendorId--}
```
public int getVendorId()
```


Ottiene o imposta Questo campo MUST essere ignorato.

**Returns:**
int
### setVendorId(int value) {#setVendorId-int-}
```
public void setVendorId(int value)
```


Ottiene o imposta Questo campo MUST essere ignorato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getCulture() {#getCulture--}
```
public int getCulture()
```


Ottiene o imposta un intero senza segno a 32 bit che MUST essere impostato a zero e MUST essere ignorato.

**Returns:**
int
### setCulture(int value) {#setCulture-int-}
```
public void setCulture(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che MUST essere impostato a zero e MUST essere ignorato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getPanose() {#getPanose--}
```
public EmfPanose getPanose()
```


Ottiene o imposta un oggetto Panose (sezione 2.2.21) che specifica le caratteristiche PANOSE del carattere logico. Se tutti i campi di questo oggetto sono zero, esso MUST essere ignorato.

**Returns:**
[EmfPanose](../../com.aspose.imaging.fileformats.emf.emf.objects/emfpanose)
### setPanose(EmfPanose value) {#setPanose-com.aspose.imaging.fileformats.emf.emf.objects.EmfPanose-}
```
public void setPanose(EmfPanose value)
```


Ottiene o imposta un oggetto Panose (sezione 2.2.21) che specifica le caratteristiche PANOSE del carattere logico. Se tutti i campi di questo oggetto sono zero, esso MUST essere ignorato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfPanose](../../com.aspose.imaging.fileformats.emf.emf.objects/emfpanose) |  |

### getPadding() {#getPadding--}
```
public short getPadding()
```


Ottiene o imposta un campo che esiste solo per garantire l'allineamento a 32 bit di questa struttura. Esso MUST essere ignorato

**Returns:**
short
### setPadding(short value) {#setPadding-short-}
```
public void setPadding(short value)
```


Ottiene o imposta un campo che esiste solo per garantire l'allineamento a 32 bit di questa struttura. Esso MUST essere ignorato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

