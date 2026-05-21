---
title: "EmfUniversalFontId"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto UniversalFontId definisce un meccanismo per identificare i caratteri nei metafili EMF."
type: docs
weight: 37
url: /it/java/com.aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfUniversalFontId extends EmfObject
```

L'oggetto UniversalFontId definisce un meccanismo per identificare i caratteri nei metafili EMF.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfUniversalFontId()](#EmfUniversalFontId--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getChecksum()](#getChecksum--) | Ottiene o imposta un intero senza segno a 32 bit che è il checksum del carattere. |
| [setChecksum(int value)](#setChecksum-int-) | Ottiene o imposta un intero senza segno a 32 bit che è il checksum del carattere. |
| [getIndex()](#getIndex--) | Ottiene o imposta un intero senza segno a 32 bit che è un indice associato all'oggetto carattere. |
| [setIndex(int value)](#setIndex-int-) | Ottiene o imposta un intero senza segno a 32 bit che è un indice associato all'oggetto carattere. |
### EmfUniversalFontId() {#EmfUniversalFontId--}
```
public EmfUniversalFontId()
```


### getChecksum() {#getChecksum--}
```
public int getChecksum()
```


Ottiene o imposta un intero senza segno a 32 bit che è il checksum del carattere. Il valore del checksum ha i seguenti significati. 0x00000000 L'oggetto è un carattere di dispositivo. 0x00000001 L'oggetto è un carattere Type 1 installato sulla macchina client e enumerato dal driver della stampante PostScript come carattere di dispositivo. 0x00000002 L'oggetto non è un carattere ma è un rasterizzatore Type 1. 3 \\u2264 valore L'oggetto è un bitmap, vettoriale o TrueType, o un carattere rasterizzato Type 1 creato da un rasterizzatore Type 1.

**Returns:**
int
### setChecksum(int value) {#setChecksum-int-}
```
public void setChecksum(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che è il checksum del carattere. Il valore del checksum ha i seguenti significati. 0x00000000 L'oggetto è un carattere di dispositivo. 0x00000001 L'oggetto è un carattere Type 1 installato sulla macchina client e enumerato dal driver della stampante PostScript come carattere di dispositivo. 0x00000002 L'oggetto non è un carattere ma è un rasterizzatore Type 1. 3 \\u2264 valore L'oggetto è un bitmap, vettoriale o TrueType, o un carattere rasterizzato Type 1 creato da un rasterizzatore Type 1.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getIndex() {#getIndex--}
```
public int getIndex()
```


Ottiene o imposta un intero senza segno a 32 bit che è un indice associato all'oggetto carattere. Il significato di questo campo è determinato dal tipo di carattere.

**Returns:**
int
### setIndex(int value) {#setIndex-int-}
```
public void setIndex(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che è un indice associato all'oggetto carattere. Il significato di questo campo è determinato dal tipo di carattere.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

