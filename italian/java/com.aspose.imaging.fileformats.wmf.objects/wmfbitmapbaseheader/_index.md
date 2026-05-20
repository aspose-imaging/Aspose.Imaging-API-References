---
title: "WmfBitmapBaseHeader"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "La classe base dell'intestazione bitmap."
type: docs
weight: 14
url: /it/java/com.aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public abstract class WmfBitmapBaseHeader extends MetaObject
```

La classe base dell'intestazione bitmap.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [WmfBitmapBaseHeader()](#WmfBitmapBaseHeader--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getHeaderSize()](#getHeaderSize--) | Ottiene o imposta un intero senza segno a 32 bit che definisce la dimensione di questo oggetto, in byte. |
| [setHeaderSize(int value)](#setHeaderSize-int-) | Ottiene o imposta un intero senza segno a 32 bit che definisce la dimensione di questo oggetto, in byte. |
| [getPlanes()](#getPlanes--) | Ottiene o imposta un intero senza segno a 16 bit che definisce il numero di `planes` per il dispositivo di destinazione. |
| [setPlanes(short value)](#setPlanes-short-) | Ottiene o imposta un intero senza segno a 16 bit che definisce il numero di `planes` per il dispositivo di destinazione. |
| [getBitCount()](#getBitCount--) | Ottiene o imposta un intero senza segno a 16 bit che definisce il formato di ogni pixel e il numero massimo di colori nel DIB. |
| [setBitCount(short value)](#setBitCount-short-) | Ottiene o imposta un intero senza segno a 16 bit che definisce il formato di ogni pixel e il numero massimo di colori nel DIB. |
### WmfBitmapBaseHeader() {#WmfBitmapBaseHeader--}
```
public WmfBitmapBaseHeader()
```


### getHeaderSize() {#getHeaderSize--}
```
public int getHeaderSize()
```


Ottiene o imposta un intero senza segno a 32 bit che definisce la dimensione di questo oggetto, in byte.

**Returns:**
int
### setHeaderSize(int value) {#setHeaderSize-int-}
```
public void setHeaderSize(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che definisce la dimensione di questo oggetto, in byte.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | un intero senza segno a 16 bit che definisce il numero di `planes` per il dispositivo di destinazione. Questo valore DEVE essere 0x0001. |

### getPlanes() {#getPlanes--}
```
public short getPlanes()
```


Ottiene o imposta un intero senza segno a 16 bit che definisce il numero di `planes` per il dispositivo di destinazione. Questo valore DEVE essere 0x0001.

**Returns:**
short - un intero senza segno a 16 bit che definisce il numero di `planes` per il dispositivo di destinazione.
### setPlanes(short value) {#setPlanes-short-}
```
public void setPlanes(short value)
```


Ottiene o imposta un intero senza segno a 16 bit che definisce il numero di `planes` per il dispositivo di destinazione. Questo valore DEVE essere 0x0001.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short | un intero senza segno a 16 bit che definisce il numero di `planes` per il dispositivo di destinazione. Questo valore DEVE essere \* 0x0001. |

### getBitCount() {#getBitCount--}
```
public short getBitCount()
```


Ottiene o imposta un intero senza segno a 16 bit che definisce il formato di ogni pixel e il numero massimo di colori nel DIB. Questo valore DEVE essere nell'enumerazione `BitCount` (sezione 2.1.1.3).

**Returns:**
short - un intero senza segno a 16 bit che definisce il formato di ogni pixel e il numero massimo di colori nel DIB.
### setBitCount(short value) {#setBitCount-short-}
```
public void setBitCount(short value)
```


Ottiene o imposta un intero senza segno a 16 bit che definisce il formato di ogni pixel e il numero massimo di colori nel DIB. Questo valore DEVE essere nell'enumerazione `BitCount` (sezione 2.1.1.3).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short | un intero senza segno a 16 bit che definisce il formato di ogni pixel e il numero massimo di colori nel DIB. |

