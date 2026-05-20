---
title: "BitmapV5Header"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "La struttura BitmapV5Header è il file di intestazione delle informazioni bitmap."
type: docs
weight: 14
url: /it/java/com.aspose.imaging.fileformats.bmp/bitmapv5header/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.bmp.BitmapCoreHeader](../../com.aspose.imaging.fileformats.bmp/bitmapcoreheader), [com.aspose.imaging.fileformats.bmp.BitmapInfoHeader](../../com.aspose.imaging.fileformats.bmp/bitmapinfoheader), [com.aspose.imaging.fileformats.bmp.BitmapV4Header](../../com.aspose.imaging.fileformats.bmp/bitmapv4header)
```
public class BitmapV5Header extends BitmapV4Header
```

La struttura BitmapV5Header è il file di intestazione delle informazioni bitmap. È una versione estesa della struttura BITMAPINFOHEADER.

Se bV5Height è negativo, indicando un DIB top-down, bV5Compression deve essere o BI\\_RGB o BI\\_BITFIELDS. I DIB top-down non possono essere compressi. L'interfaccia Independent Color Management (ICM) 2.0 consente ai profili colore International Color Consortium (ICC) di essere collegati o incorporati nei DIB (DIB). Vedi Using Structures per ulteriori informazioni. Quando un DIB viene caricato in memoria, i dati del profilo (se presenti) dovrebbero seguire la tavola dei colori, e bV5ProfileData dovrebbe fornire l'offset dei dati del profilo dall'inizio della struttura BITMAPV5HEADER. Il valore memorizzato in bV5ProfileData sarà diverso dal valore restituito dall'operatore sizeof dato l'argomento BITMAPV5HEADER, perché bV5ProfileData è l'offset in byte dall'inizio della struttura BITMAPV5HEADER all'inizio dei dati del profilo. (I bit del bitmap non seguono la tavola dei colori in memoria). Le applicazioni dovrebbero modificare il membro bV5ProfileData dopo aver caricato il DIB in memoria. Per i DIB compressi, i dati del profilo dovrebbero seguire i bit del bitmap in modo simile al formato file. Il membro bV5ProfileData dovrebbe comunque fornire l'offset dei dati del profilo dall'inizio della BITMAPV5HEADER. Le applicazioni dovrebbero accedere ai dati del profilo solo quando bV5Size è uguale alla dimensione della BITMAPV5HEADER e bV5CSType è uguale a PROFILE\\_EMBEDDED o PROFILE\\_LINKED.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [BitmapV5Header()](#BitmapV5Header--) | Inizializza una nuova istanza della classe `BitmapV5Header`. |
| [BitmapV5Header(byte[] bytes)](#BitmapV5Header-byte---) | Inizializza una nuova istanza della classe `BitmapV5Header`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getIntent()](#getIntent--) | Ottiene l'intento di rendering per il bitmap. |
| [setIntent(long value)](#setIntent-long-) | Imposta l'intento di rendering per il bitmap. |
| [getProfileData()](#getProfileData--) | Ottiene i dati del profilo. |
| [setProfileData(long value)](#setProfileData-long-) | Imposta i dati del profilo. |
| [getProfileSize()](#getProfileSize--) | Ottiene la dimensione del profilo. |
| [setProfileSize(long value)](#setProfileSize-long-) | Imposta la dimensione del profilo. |
| [getReserved()](#getReserved--) | Ottiene il membro riservato. |
| [setReserved(long value)](#setReserved-long-) | Imposta il membro riservato. |
### BitmapV5Header() {#BitmapV5Header--}
```
public BitmapV5Header()
```


Inizializza una nuova istanza della classe `BitmapV5Header`.

### BitmapV5Header(byte[] bytes) {#BitmapV5Header-byte---}
```
public BitmapV5Header(byte[] bytes)
```


Inizializza una nuova istanza della classe `BitmapV5Header`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| byte | byte[] | I byte. |

### getIntent() {#getIntent--}
```
public long getIntent()
```


Ottiene l'intento di rendering per il bitmap.

**Returns:**
long - L'intento.
### setIntent(long value) {#setIntent-long-}
```
public void setIntent(long value)
```


Imposta l'intento di rendering per il bitmap.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long | L'intento. |

### getProfileData() {#getProfileData--}
```
public long getProfileData()
```


Ottiene i dati del profilo.

**Returns:**
long - I dati del profilo.
### setProfileData(long value) {#setProfileData-long-}
```
public void setProfileData(long value)
```


Imposta i dati del profilo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long | I dati del profilo. |

### getProfileSize() {#getProfileSize--}
```
public long getProfileSize()
```


Ottiene la dimensione del profilo.

**Returns:**
long - La dimensione del profilo.
### setProfileSize(long value) {#setProfileSize-long-}
```
public void setProfileSize(long value)
```


Imposta la dimensione del profilo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long | La dimensione del profilo. |

### getReserved() {#getReserved--}
```
public long getReserved()
```


Ottiene il membro riservato.

**Returns:**
long - Il valore riservato.
### setReserved(long value) {#setReserved-long-}
```
public void setReserved(long value)
```


Imposta il membro riservato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long | Il valore riservato. |

