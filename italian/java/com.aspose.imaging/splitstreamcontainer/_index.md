---
title: "SplitStreamContainer"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta un contenitore di flusso diviso che contiene il flusso e fornisce routine di elaborazione del flusso."
type: docs
weight: 108
url: /it/java/com.aspose.imaging/splitstreamcontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.StreamContainer](../../com.aspose.imaging/streamcontainer)
```
public class SplitStreamContainer extends StreamContainer
```

Rappresenta un contenitore di flusso diviso che contiene il flusso e fornisce routine di elaborazione del flusso.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SplitStreamContainer(InputStream stream)](#SplitStreamContainer-java.io.InputStream-) | Inizializza una nuova istanza della classe `SplitStreamContainer`. |
| [SplitStreamContainer(InputStream stream, boolean disposeStream)](#SplitStreamContainer-java.io.InputStream-boolean-) | Inizializza una nuova istanza della classe `SplitStreamContainer`. |
| [SplitStreamContainer(StreamContainer stream, boolean disposeStream)](#SplitStreamContainer-com.aspose.imaging.StreamContainer-boolean-) | Inizializza una nuova istanza della classe `SplitStreamContainer`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSyncRoot()](#getSyncRoot--) | Restituisce un oggetto che può essere usato per sincronizzare l'accesso alla risorsa sincronizzata. |
| [getPosition()](#getPosition--) | Restituisce la posizione corrente all'interno del flusso. |
| [setPosition(long value)](#setPosition-long-) | Imposta la posizione corrente all'interno del flusso. |
| [getLength()](#getLength--) | Restituisce la lunghezza del flusso in byte. |
| [setLength(long value)](#setLength-long-) | Imposta la lunghezza del flusso in byte. |
| [canRead()](#canRead--) | Restituisce un valore che indica se il flusso supporta la lettura. |
| [canSeek()](#canSeek--) | Restituisce un valore che indica se il flusso supporta lo spostamento. |
| [canWrite()](#canWrite--) | Restituisce un valore che indica se il flusso supporta la scrittura. |
| [insert(int position, StreamContainer stream, boolean disposeStream)](#insert-int-com.aspose.imaging.StreamContainer-boolean-) | Inserisce il contenitore del flusso nella posizione specificata. |
| [flush()](#flush--) | Cancella tutti i buffer per questo flusso e provoca la scrittura di tutti i dati bufferizzati sul dispositivo sottostante. |
| [write(byte[] bytes)](#write-byte---) | Scrive tutti i byte specificati nel flusso. |
| [writeByte(byte value)](#writeByte-byte-) | Scrive un byte nella posizione corrente del flusso e avanza la posizione nel flusso di un byte. |
| [read(byte[] bytes)](#read-byte---) | Legge byte per riempire il buffer di byte specificato. |
| [toBytes()](#toBytes--) | Converte i dati del flusso in un array di `byte`. |
| [toBytes(long position, long bytesCount)](#toBytes-long-long-) | Converte i dati del flusso in un array di `byte`. |
| [read(byte[] buffer, int offset, int count)](#read-byte---int-int-) | Legge una sequenza di byte dal flusso corrente e avanza la posizione all'interno del flusso del numero di byte letti. |
| [readByte()](#readByte--) | Legge un byte dal flusso e avanza la posizione all'interno del flusso di un byte, oppure restituisce -1 se è alla fine del flusso. |
| [seek(long offset, int origin)](#seek-long-int-) | Imposta la posizione all'interno del flusso corrente. |
| [seekBegin()](#seekBegin--) | Imposta la posizione del flusso all'inizio del flusso. |
| [write(byte[] buffer, int offset, int count)](#write-byte---int-int-) | Scrive una sequenza di byte nel flusso corrente e avanza la posizione corrente all'interno di questo flusso del numero di byte scritti. |
### SplitStreamContainer(InputStream stream) {#SplitStreamContainer-java.io.InputStream-}
```
public SplitStreamContainer(InputStream stream)
```


Inizializza una nuova istanza della classe `SplitStreamContainer`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Il flusso. |

### SplitStreamContainer(InputStream stream, boolean disposeStream) {#SplitStreamContainer-java.io.InputStream-boolean-}
```
public SplitStreamContainer(InputStream stream, boolean disposeStream)
```


Inizializza una nuova istanza della classe `SplitStreamContainer`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Il flusso di dati. |
| disposeStream | boolean | se impostato su `true` il flusso verrà eliminato quando il contenitore viene eliminato. |

### SplitStreamContainer(StreamContainer stream, boolean disposeStream) {#SplitStreamContainer-com.aspose.imaging.StreamContainer-boolean-}
```
public SplitStreamContainer(StreamContainer stream, boolean disposeStream)
```


Inizializza una nuova istanza della classe `SplitStreamContainer`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Il contenitore dello stream. |
| disposeStream | boolean | se impostato su `true` elimina il flusso. |

### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Restituisce un oggetto che può essere usato per sincronizzare l'accesso alla risorsa sincronizzata.

**Returns:**
java.lang.Object - L'oggetto che può essere usato per sincronizzare l'accesso alla risorsa sincronizzata.
### getPosition() {#getPosition--}
```
public long getPosition()
```


Ottiene la posizione corrente all'interno del flusso. Questo valore rappresenta l'offset dalla posizione iniziale del flusso passata nel costruttore di StreamContainer.

**Returns:**
long - La posizione corrente del flusso.
### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


Imposta la posizione corrente all'interno del flusso. Questo valore rappresenta l'offset dalla posizione iniziale del flusso passata nel costruttore di StreamContainer.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long | La posizione corrente del flusso. |

### getLength() {#getLength--}
```
public long getLength()
```


Ottiene la lunghezza del flusso in byte. Questo valore è inferiore a `System.IO.Stream.Length` della posizione iniziale del flusso passata nel costruttore di StreamContainer.

**Returns:**
long - La lunghezza del flusso.
### setLength(long value) {#setLength-long-}
```
public void setLength(long value)
```


Imposta la lunghezza del flusso in byte. Questo valore è inferiore a `System.IO.Stream.Length` della posizione iniziale del flusso passata nel costruttore di StreamContainer.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long | La lunghezza del flusso. |

### canRead() {#canRead--}
```
public boolean canRead()
```


Restituisce un valore che indica se il flusso supporta la lettura.

**Returns:**
boolean - `true` se il flusso supporta la lettura; altrimenti, `false`.
### canSeek() {#canSeek--}
```
public boolean canSeek()
```


Restituisce un valore che indica se il flusso supporta lo spostamento.

**Returns:**
boolean - `true` se il flusso supporta la ricerca; altrimenti, `false`.
### canWrite() {#canWrite--}
```
public boolean canWrite()
```


Restituisce un valore che indica se il flusso supporta la scrittura.

**Returns:**
boolean - `true` se il flusso supporta la scrittura; altrimenti, `false`.
### insert(int position, StreamContainer stream, boolean disposeStream) {#insert-int-com.aspose.imaging.StreamContainer-boolean-}
```
public void insert(int position, StreamContainer stream, boolean disposeStream)
```


Inserisce il contenitore del flusso nella posizione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | int | La posizione in cui inserire. |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Il contenitore del flusso da inserire. |
| disposeStream | boolean | se impostato su `true` elimina il flusso. |

### flush() {#flush--}
```
public void flush()
```


Cancella tutti i buffer per questo flusso e provoca la scrittura di tutti i dati bufferizzati sul dispositivo sottostante.

### write(byte[] bytes) {#write-byte---}
```
public void write(byte[] bytes)
```


Scrive tutti i byte specificati nel flusso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| byte | byte[] | I byte da scrivere. |

### writeByte(byte value) {#writeByte-byte-}
```
public void writeByte(byte value)
```


Scrive un byte nella posizione corrente del flusso e avanza la posizione nel flusso di un byte.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte | Il byte da scrivere nel flusso. |

### read(byte[] bytes) {#read-byte---}
```
public int read(byte[] bytes)
```


Legge byte per riempire il buffer di byte specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| byte | byte[] | I byte da riempire. |

**Returns:**
int - Il numero di byte letti. Questo valore può essere inferiore al numero di byte nel buffer se non ci sono abbastanza byte nello stream.
### toBytes() {#toBytes--}
```
public byte[] toBytes()
```


Converte i dati del flusso in un array di `byte`.

**Returns:**
byte[] - I dati dello stream convertiti nell'array `byte`.
### toBytes(long position, long bytesCount) {#toBytes-long-long-}
```
public byte[] toBytes(long position, long bytesCount)
```


Converte i dati del flusso in un array di `byte`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui iniziare a leggere i byte. |
| bytesCount | long | Il conteggio dei byte da leggere. |

**Returns:**
byte[] - I dati dello stream convertiti nell'array `byte`.
### read(byte[] buffer, int offset, int count) {#read-byte---int-int-}
```
public int read(byte[] buffer, int offset, int count)
```


Legge una sequenza di byte dal flusso corrente e avanza la posizione all'interno del flusso del numero di byte letti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | byte[] | Un array di byte. Quando questo metodo restituisce, il buffer contiene l'array di byte specificato con i valori compresi tra `offset` e (`offset` + `count` - 1) sostituiti dai byte letti dalla sorgente corrente. |
| offset | int | L'offset di byte basato su zero in `buffer` al quale iniziare a memorizzare i dati letti dallo stream corrente. |
| count | int | Il numero massimo di byte da leggere dallo stream corrente. |

**Returns:**
int - Il numero totale di byte letti nel buffer. Questo può essere inferiore al numero di byte richiesti se tali byte non sono attualmente disponibili, o zero (0) se è stato raggiunto la fine dello stream.
### readByte() {#readByte--}
```
public int readByte()
```


Legge un byte dal flusso e avanza la posizione all'interno del flusso di un byte, oppure restituisce -1 se è alla fine del flusso.

**Returns:**
int - Il byte senza segno convertito in Int32, o -1 se si è alla fine dello stream.
### seek(long offset, int origin) {#seek-long-int-}
```
public long seek(long offset, int origin)
```


Imposta la posizione all'interno del flusso corrente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| offset | long | Un offset di byte relativo al parametro `origin`. Questo valore rappresenta l'offset dalla posizione iniziale dello stream passata nel costruttore di StreamContainer. |
| origin | int | Un valore di tipo `System.IO.SeekOrigin` che indica il punto di riferimento usato per ottenere la nuova posizione. |

**Returns:**
long - La nuova posizione all'interno dello stream corrente.
### seekBegin() {#seekBegin--}
```
public void seekBegin()
```


Imposta la posizione dello stream all'inizio dello stream. Questo valore rappresenta l'offset dalla posizione iniziale dello stream passata nel costruttore di StreamContainer.

### write(byte[] buffer, int offset, int count) {#write-byte---int-int-}
```
public void write(byte[] buffer, int offset, int count)
```


Scrive una sequenza di byte nel flusso corrente e avanza la posizione corrente all'interno di questo flusso del numero di byte scritti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | byte[] | Un array di byte. Questo metodo copia `count` byte da `buffer` allo stream corrente. |
| offset | int | L'offset di byte basato su zero in `buffer` al quale iniziare a copiare i byte nello stream corrente. |
| count | int | Il numero di byte da scrivere nello stream corrente. |

