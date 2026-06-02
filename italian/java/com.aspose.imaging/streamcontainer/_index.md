---
title: "StreamContainer"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta un contenitore di flusso che contiene il flusso e fornisce routine di elaborazione del flusso."
type: docs
weight: 109
url: /it/java/com.aspose.imaging/streamcontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)

**All Implemented Interfaces:**
com.aspose.internal.interfaces.ISynchronizable
```
public class StreamContainer extends DisposableObject implements ISynchronizable
```

Rappresenta un contenitore di flusso che contiene il flusso e fornisce routine di elaborazione del flusso.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [StreamContainer(InputStream stream)](#StreamContainer-java.io.InputStream-) | Inizializza una nuova istanza della classe `StreamContainer`. |
| [StreamContainer(System.IO.Stream stream)](#StreamContainer-com.aspose.ms.System.IO.Stream-) | Inizializza una nuova istanza della classe `StreamContainer`. |
| [StreamContainer(InputStream stream, boolean disposeStream)](#StreamContainer-java.io.InputStream-boolean-) | Inizializza una nuova istanza della classe `StreamContainer`. |
| [StreamContainer(System.IO.Stream stream, boolean disposeStream)](#StreamContainer-com.aspose.ms.System.IO.Stream-boolean-) | Inizializza una nuova istanza della classe `StreamContainer`. |
## Campi

| Campo | Descrizione |
| --- | --- |
| [READ_WRITE_BYTES_COUNT](#READ-WRITE-BYTES-COUNT) | Specifica il conteggio dei byte di lettura e scrittura durante la lettura sequenziale. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [to_Stream(StreamContainer streamContainer)](#to-Stream-com.aspose.imaging.StreamContainer-) | Esegue una conversione esplicita da `com.aspose.imaging.StreamContainer` a `System.IO.Stream`. |
| [getSyncRoot()](#getSyncRoot--) | Restituisce un oggetto che può essere usato per sincronizzare l'accesso alla risorsa sincronizzata. |
| [getPosition()](#getPosition--) | Ottiene o imposta la posizione corrente all'interno del flusso. |
| [setPosition(long value)](#setPosition-long-) | Ottiene o imposta la posizione corrente all'interno del flusso. |
| [getStream()](#getStream--) | Ottiene il flusso di dati. |
| [isStreamDisposedOnClose()](#isStreamDisposedOnClose--) | Ottiene un valore che indica se questo flusso viene eliminato alla chiusura. |
| [getLength()](#getLength--) | Ottiene o imposta la lunghezza del flusso in byte. |
| [setLength(long value)](#setLength-long-) | Ottiene o imposta la lunghezza del flusso in byte. |
| [canRead()](#canRead--) | Restituisce un valore che indica se il flusso supporta la lettura. |
| [canSeek()](#canSeek--) | Restituisce un valore che indica se il flusso supporta lo spostamento. |
| [canWrite()](#canWrite--) | Restituisce un valore che indica se il flusso supporta la scrittura. |
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
| [save(OutputStream destinationStream)](#save-java.io.OutputStream-) | Salva (copia) i dati del flusso nello stream specificato. |
| [save(OutputStream destinationStream, int bufferSize)](#save-java.io.OutputStream-int-) | Salva (copia) tutti i dati del flusso nello stream specificato. |
| [save(OutputStream destinationStream, int bufferSize, long length)](#save-java.io.OutputStream-int-long-) | Salva (copia) i dati del flusso nello stream specificato. |
| [save(String filePath)](#save-java.lang.String-) | Salva (copia) i dati del flusso nello stream specificato. |
| [save(String filePath, int bufferSize)](#save-java.lang.String-int-) | Salva (copia) i dati del flusso nello stream specificato. |
| [save(String filePath, int bufferSize, long length)](#save-java.lang.String-int-long-) | Salva (copia) i dati del flusso nello stream specificato. |
| [writeTo(StreamContainer streamContainer)](#writeTo-com.aspose.imaging.StreamContainer-) | Copia i dati contenuti in un altro `StreamContainer`. |
| [writeTo(StreamContainer streamContainer, long length)](#writeTo-com.aspose.imaging.StreamContainer-long-) | Copia i dati contenuti in un altro `StreamContainer`. |
### StreamContainer(InputStream stream) {#StreamContainer-java.io.InputStream-}
```
public StreamContainer(InputStream stream)
```


Inizializza una nuova istanza della classe `StreamContainer`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Il flusso. |

### StreamContainer(System.IO.Stream stream) {#StreamContainer-com.aspose.ms.System.IO.Stream-}
```
public StreamContainer(System.IO.Stream stream)
```


Inizializza una nuova istanza della classe `StreamContainer`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | com.aspose.ms.System.IO.Stream | Il flusso. |

### StreamContainer(InputStream stream, boolean disposeStream) {#StreamContainer-java.io.InputStream-boolean-}
```
public StreamContainer(InputStream stream, boolean disposeStream)
```


Inizializza una nuova istanza della classe `StreamContainer`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Il flusso di dati. |
| disposeStream | boolean | se impostato su `true` il flusso verrà eliminato quando il contenitore viene eliminato. |

### StreamContainer(System.IO.Stream stream, boolean disposeStream) {#StreamContainer-com.aspose.ms.System.IO.Stream-boolean-}
```
public StreamContainer(System.IO.Stream stream, boolean disposeStream)
```


Inizializza una nuova istanza della classe `StreamContainer`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | com.aspose.ms.System.IO.Stream | Il flusso di dati. |
| disposeStream | boolean | se impostato su `true` il flusso verrà eliminato quando il contenitore viene eliminato. |

### READ_WRITE_BYTES_COUNT {#READ-WRITE-BYTES-COUNT}
```
public static final int READ_WRITE_BYTES_COUNT
```


Specifica il conteggio dei byte di lettura e scrittura durante la lettura sequenziale.

### to_Stream(StreamContainer streamContainer) {#to-Stream-com.aspose.imaging.StreamContainer-}
```
public static System.IO.Stream to_Stream(StreamContainer streamContainer)
```


Esegue una conversione esplicita da `com.aspose.imaging.StreamContainer` a `System.IO.Stream`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Il contenitore dello stream. |

**Returns:**
com.aspose.ms.System.IO.Stream - Il risultato della conversione.
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Restituisce un oggetto che può essere usato per sincronizzare l'accesso alla risorsa sincronizzata.

Valore: L'oggetto che può essere usato per sincronizzare l'accesso alla risorsa sincronizzata.

**Returns:**
java.lang.Object
### getPosition() {#getPosition--}
```
public long getPosition()
```


Ottiene o imposta la posizione corrente all'interno del flusso. Questo valore rappresenta lo scostamento dalla posizione iniziale del flusso passata nel costruttore di StreamContainer.

Valore: La posizione corrente del flusso.

**Returns:**
long
### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


Ottiene o imposta la posizione corrente all'interno del flusso. Questo valore rappresenta lo scostamento dalla posizione iniziale del flusso passata nel costruttore di StreamContainer.

Valore: La posizione corrente del flusso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### getStream() {#getStream--}
```
public InputStream getStream()
```


Ottiene il flusso di dati.

Valore: Il flusso di dati.

**Returns:**
java.io.InputStream
### isStreamDisposedOnClose() {#isStreamDisposedOnClose--}
```
public boolean isStreamDisposedOnClose()
```


Ottiene un valore che indica se questo flusso viene eliminato alla chiusura.

Valore: `true` se il flusso viene eliminato alla chiusura; altrimenti, `false`.

**Returns:**
boolean
### getLength() {#getLength--}
```
public long getLength()
```


Ottiene o imposta la lunghezza del flusso in byte. Questo valore è inferiore a Stream\#getLength().getLength() della posizione iniziale del flusso passata nel costruttore di StreamContainer.

Valore: La lunghezza del flusso.

**Returns:**
long
### setLength(long value) {#setLength-long-}
```
public void setLength(long value)
```


Ottiene o imposta la lunghezza del flusso in byte. Questo valore è inferiore a Stream\#getLength().getLength() della posizione iniziale del flusso passata nel costruttore di StreamContainer.

Valore: La lunghezza del flusso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### canRead() {#canRead--}
```
public boolean canRead()
```


Restituisce un valore che indica se il flusso supporta la lettura.

Valore: `true` se il flusso supporta la lettura; altrimenti, `false`.

**Returns:**
boolean
### canSeek() {#canSeek--}
```
public boolean canSeek()
```


Restituisce un valore che indica se il flusso supporta lo spostamento.

Valore: `true` se il flusso supporta lo spostamento; altrimenti, `false`.

**Returns:**
boolean
### canWrite() {#canWrite--}
```
public boolean canWrite()
```


Restituisce un valore che indica se il flusso supporta la scrittura.

Valore: `true` se lo stream supporta la scrittura; altrimenti, `false`.

**Returns:**
boolean
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

### save(OutputStream destinationStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destinationStream)
```


Salva (copia) i dati dello stream nello stream specificato. Usa la dimensione predefinita del buffer `ReadWriteBytesCount` e il valore `Length` dello stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | Lo stream in cui salvare i dati. |

### save(OutputStream destinationStream, int bufferSize) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream destinationStream, int bufferSize)
```


Salva (copia) tutti i dati dello stream nello stream specificato. Usa il valore `Length` dello stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | Lo stream in cui salvare i dati. |
| bufferSize | int | Il buffer. |

### save(OutputStream destinationStream, int bufferSize, long length) {#save-java.io.OutputStream-int-long-}
```
public void save(OutputStream destinationStream, int bufferSize, long length)
```


Salva (copia) i dati del flusso nello stream specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | Lo stream in cui salvare i dati. |
| bufferSize | int | La dimensione del buffer. Per impostazione predefinita viene usato il valore `ReadWriteBytesCount`. |
| length | long | La lunghezza dei dati dello stream da copiare. Per impostazione predefinita, la lunghezza è impostata al valore `Length`. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Salva (copia) i dati dello stream nello stream specificato. Usa la dimensione predefinita del buffer `ReadWriteBytesCount` e il valore `Length` dello stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso del file in cui salvare i dati dello stream. |

### save(String filePath, int bufferSize) {#save-java.lang.String-int-}
```
public void save(String filePath, int bufferSize)
```


Salva (copia) i dati dello stream nello stream specificato. Usa il valore `Length` dello stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso del file in cui salvare i dati dello stream. |
| bufferSize | int | La dimensione del buffer. Per impostazione predefinita viene usato il valore `ReadWriteBytesCount`. |

### save(String filePath, int bufferSize, long length) {#save-java.lang.String-int-long-}
```
public void save(String filePath, int bufferSize, long length)
```


Salva (copia) i dati del flusso nello stream specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso del file in cui salvare i dati dello stream. |
| bufferSize | int | La dimensione del buffer. Per impostazione predefinita viene usato il valore `ReadWriteBytesCount`. |
| length | long | La lunghezza dei dati dello stream da copiare. Per impostazione predefinita, la lunghezza è impostata al valore `Length`. |

### writeTo(StreamContainer streamContainer) {#writeTo-com.aspose.imaging.StreamContainer-}
```
public void writeTo(StreamContainer streamContainer)
```


Copia i dati contenuti in un altro `StreamContainer`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Il contenitore di stream in cui copiare. |

### writeTo(StreamContainer streamContainer, long length) {#writeTo-com.aspose.imaging.StreamContainer-long-}
```
public void writeTo(StreamContainer streamContainer, long length)
```


Copia i dati contenuti in un altro `StreamContainer`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Il contenitore di stream in cui copiare. |
| length | long | Il conteggio dei byte da scrivere. |

