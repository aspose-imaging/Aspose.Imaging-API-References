---
title: "StreamContainer"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar en strömbehållare som innehåller strömmen och tillhandahåller rutiner för strömbehandling."
type: docs
weight: 109
url: /sv/java/com.aspose.imaging/streamcontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)

**All Implemented Interfaces:**
com.aspose.internal.interfaces.ISynchronizable
```
public class StreamContainer extends DisposableObject implements ISynchronizable
```

Representerar en strömbehållare som innehåller strömmen och tillhandahåller rutiner för strömbehandling.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [StreamContainer(InputStream stream)](#StreamContainer-java.io.InputStream-) | Initierar en ny instans av klassen `StreamContainer`. |
| [StreamContainer(System.IO.Stream stream)](#StreamContainer-com.aspose.ms.System.IO.Stream-) | Initierar en ny instans av klassen `StreamContainer`. |
| [StreamContainer(InputStream stream, boolean disposeStream)](#StreamContainer-java.io.InputStream-boolean-) | Initierar en ny instans av klassen `StreamContainer`. |
| [StreamContainer(System.IO.Stream stream, boolean disposeStream)](#StreamContainer-com.aspose.ms.System.IO.Stream-boolean-) | Initierar en ny instans av klassen `StreamContainer`. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [READ_WRITE_BYTES_COUNT](#READ-WRITE-BYTES-COUNT) | Anger antalet läs- och skrivbyte vid sekventiell läsning. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [to_Stream(StreamContainer streamContainer)](#to-Stream-com.aspose.imaging.StreamContainer-) | Utför en explicit konvertering från `com.aspose.imaging.StreamContainer` till `System.IO.Stream`. |
| [getSyncRoot()](#getSyncRoot--) | Hämtar ett objekt som kan användas för att synkronisera åtkomst till den synkroniserade resursen. |
| [getPosition()](#getPosition--) | Hämtar eller anger den aktuella positionen i strömmen. |
| [setPosition(long value)](#setPosition-long-) | Hämtar eller anger den aktuella positionen i strömmen. |
| [getStream()](#getStream--) | Hämtar datastreamen. |
| [isStreamDisposedOnClose()](#isStreamDisposedOnClose--) | Hämtar ett värde som indikerar om denna ström avyttras vid stängning. |
| [getLength()](#getLength--) | Hämtar eller anger strömlängden i byte. |
| [setLength(long value)](#setLength-long-) | Hämtar eller anger strömlängden i byte. |
| [canRead()](#canRead--) | Hämtar ett värde som indikerar om strömmen stödjer läsning. |
| [canSeek()](#canSeek--) | Hämtar ett värde som indikerar om strömmen stödjer sökning. |
| [canWrite()](#canWrite--) | Hämtar ett värde som indikerar om strömmen stödjer skrivning. |
| [flush()](#flush--) | Rensar alla buffertar för denna ström och får all buffrad data att skrivas till den underliggande enheten. |
| [write(byte[] bytes)](#write-byte---) | Skriver alla angivna byte till strömmen. |
| [writeByte(byte value)](#writeByte-byte-) | Skriver en byte till den aktuella positionen i strömmen och flyttar positionen i strömmen fram ett byte. |
| [read(byte[] bytes)](#read-byte---) | Läser byte för att fylla den angivna bytebufferten. |
| [toBytes()](#toBytes--) | Konverterar strömdatan till `byte`-arrayen. |
| [toBytes(long position, long bytesCount)](#toBytes-long-long-) | Konverterar strömdatan till `byte`-arrayen. |
| [read(byte[] buffer, int offset, int count)](#read-byte---int-int-) | Läser en sekvens av byte från den aktuella strömmen och avancerar positionen i strömmen med antalet lästa byte. |
| [readByte()](#readByte--) | Läser en byte från strömmen och avancerar positionen i strömmen med en byte, eller returnerar -1 om det är slut på strömmen. |
| [seek(long offset, int origin)](#seek-long-int-) | Ställer in positionen i den aktuella strömmen. |
| [seekBegin()](#seekBegin--) | Ställer in strömmens position till början av strömmen. |
| [write(byte[] buffer, int offset, int count)](#write-byte---int-int-) | Skriver en sekvens av byte till den aktuella strömmen och avancerar den aktuella positionen i denna ström med antalet skrivna byte. |
| [save(OutputStream destinationStream)](#save-java.io.OutputStream-) | Sparar (kopierar) strömmens data till den angivna strömmen. |
| [save(OutputStream destinationStream, int bufferSize)](#save-java.io.OutputStream-int-) | Sparar (kopierar) all data i strömmen till den angivna strömmen. |
| [save(OutputStream destinationStream, int bufferSize, long length)](#save-java.io.OutputStream-int-long-) | Sparar (kopierar) strömmens data till den angivna strömmen. |
| [save(String filePath)](#save-java.lang.String-) | Sparar (kopierar) strömmens data till den angivna strömmen. |
| [save(String filePath, int bufferSize)](#save-java.lang.String-int-) | Sparar (kopierar) strömmens data till den angivna strömmen. |
| [save(String filePath, int bufferSize, long length)](#save-java.lang.String-int-long-) | Sparar (kopierar) strömmens data till den angivna strömmen. |
| [writeTo(StreamContainer streamContainer)](#writeTo-com.aspose.imaging.StreamContainer-) | Kopierar det innehållande data till en annan `StreamContainer`. |
| [writeTo(StreamContainer streamContainer, long length)](#writeTo-com.aspose.imaging.StreamContainer-long-) | Kopierar det innehållande data till en annan `StreamContainer`. |
### StreamContainer(InputStream stream) {#StreamContainer-java.io.InputStream-}
```
public StreamContainer(InputStream stream)
```


Initierar en ny instans av klassen `StreamContainer`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Strömmen. |

### StreamContainer(System.IO.Stream stream) {#StreamContainer-com.aspose.ms.System.IO.Stream-}
```
public StreamContainer(System.IO.Stream stream)
```


Initierar en ny instans av klassen `StreamContainer`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | com.aspose.ms.System.IO.Stream | Strömmen. |

### StreamContainer(InputStream stream, boolean disposeStream) {#StreamContainer-java.io.InputStream-boolean-}
```
public StreamContainer(InputStream stream, boolean disposeStream)
```


Initierar en ny instans av klassen `StreamContainer`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Datastreamen. |
| disposeStream | boolean | om den sätts till `true` kommer strömmen att avyttras när behållaren avyttras. |

### StreamContainer(System.IO.Stream stream, boolean disposeStream) {#StreamContainer-com.aspose.ms.System.IO.Stream-boolean-}
```
public StreamContainer(System.IO.Stream stream, boolean disposeStream)
```


Initierar en ny instans av klassen `StreamContainer`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | com.aspose.ms.System.IO.Stream | Datastreamen. |
| disposeStream | boolean | om den sätts till `true` kommer strömmen att avyttras när behållaren avyttras. |

### READ_WRITE_BYTES_COUNT {#READ-WRITE-BYTES-COUNT}
```
public static final int READ_WRITE_BYTES_COUNT
```


Anger antalet läs- och skrivbyte vid sekventiell läsning.

### to_Stream(StreamContainer streamContainer) {#to-Stream-com.aspose.imaging.StreamContainer-}
```
public static System.IO.Stream to_Stream(StreamContainer streamContainer)
```


Utför en explicit konvertering från `com.aspose.imaging.StreamContainer` till `System.IO.Stream`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Strömbehållaren. |

**Returns:**
com.aspose.ms.System.IO.Stream - Resultatet av konverteringen.
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Hämtar ett objekt som kan användas för att synkronisera åtkomst till den synkroniserade resursen.

Värde: Objektet som kan användas för att synkronisera åtkomst till den synkroniserade resursen.

**Returns:**
java.lang.Object
### getPosition() {#getPosition--}
```
public long getPosition()
```


Hämtar eller anger den aktuella positionen i strömmen. Detta värde representerar offset från startpositionen i strömmen som skickas in i StreamContainer‑konstruktorn.

Värde: Den aktuella strömpositionen.

**Returns:**
long
### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


Hämtar eller anger den aktuella positionen i strömmen. Detta värde representerar offset från startpositionen i strömmen som skickas in i StreamContainer‑konstruktorn.

Värde: Den aktuella strömpositionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### getStream() {#getStream--}
```
public InputStream getStream()
```


Hämtar datastreamen.

Värde: Datastreamen.

**Returns:**
java.io.InputStream
### isStreamDisposedOnClose() {#isStreamDisposedOnClose--}
```
public boolean isStreamDisposedOnClose()
```


Hämtar ett värde som indikerar om denna ström avyttras vid stängning.

Värde: `true` om strömmen avyttras vid stängning; annars `false`.

**Returns:**
boolean
### getLength() {#getLength--}
```
public long getLength()
```


Hämtar eller anger strömlängden i byte. Detta värde är mindre än Stream\#getLength().getLength() med startpositionen i strömmen som skickas in i StreamContainer‑konstruktorn.

Värde: Strömlängden.

**Returns:**
long
### setLength(long value) {#setLength-long-}
```
public void setLength(long value)
```


Hämtar eller anger strömlängden i byte. Detta värde är mindre än Stream\#getLength().getLength() med startpositionen i strömmen som skickas in i StreamContainer‑konstruktorn.

Värde: Strömlängden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### canRead() {#canRead--}
```
public boolean canRead()
```


Hämtar ett värde som indikerar om strömmen stödjer läsning.

Värde: `true` om strömmen stöder läsning; annars `false`.

**Returns:**
boolean
### canSeek() {#canSeek--}
```
public boolean canSeek()
```


Hämtar ett värde som indikerar om strömmen stödjer sökning.

Värde: `true` om strömmen stöder sökning; annars `false`.

**Returns:**
boolean
### canWrite() {#canWrite--}
```
public boolean canWrite()
```


Hämtar ett värde som indikerar om strömmen stödjer skrivning.

Värde: `true` om strömmen stöder skrivning; annars `false`.

**Returns:**
boolean
### flush() {#flush--}
```
public void flush()
```


Rensar alla buffertar för denna ström och får all buffrad data att skrivas till den underliggande enheten.

### write(byte[] bytes) {#write-byte---}
```
public void write(byte[] bytes)
```


Skriver alla angivna byte till strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | byte[] | Byte att skriva. |

### writeByte(byte value) {#writeByte-byte-}
```
public void writeByte(byte value)
```


Skriver en byte till den aktuella positionen i strömmen och flyttar positionen i strömmen fram ett byte.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte | Byte att skriva till strömmen. |

### read(byte[] bytes) {#read-byte---}
```
public int read(byte[] bytes)
```


Läser byte för att fylla den angivna bytebufferten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | byte[] | Byte att fylla. |

**Returns:**
int - Antalet lästa byte. Detta värde kan vara mindre än antalet byte i bufferten om det inte finns tillräckligt med byte i strömmen.
### toBytes() {#toBytes--}
```
public byte[] toBytes()
```


Konverterar strömdatan till `byte`-arrayen.

**Returns:**
byte[] - Strömdatan konverterad till `byte`-arrayen.
### toBytes(long position, long bytesCount) {#toBytes-long-long-}
```
public byte[] toBytes(long position, long bytesCount)
```


Konverterar strömdatan till `byte`-arrayen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att börja läsa byte från. |
| bytesCount | long | Antalet byte att läsa. |

**Returns:**
byte[] - Strömdatan konverterad till `byte`-arrayen.
### read(byte[] buffer, int offset, int count) {#read-byte---int-int-}
```
public int read(byte[] buffer, int offset, int count)
```


Läser en sekvens av byte från den aktuella strömmen och avancerar positionen i strömmen med antalet lästa byte.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | byte[] | En array av byte. När den här metoden returnerar innehåller bufferten den specificerade byte-arrayen med värdena mellan `offset` och (`offset` + `count` - 1) ersatta av de byte som lästs från den aktuella källan. |
| offset | int | Den nollbaserade byte-offseten i `buffer` där lagringen av data som lästs från den aktuella strömmen ska börja. |
| antal | int | Det maximala antalet byte som ska läsas från den aktuella strömmen. |

**Returns:**
int - Det totala antalet byte som lästs in i bufferten. Detta kan vara mindre än det begärda antalet byte om så många byte för närvarande inte är tillgängliga, eller noll (0) om slutet på strömmen har nåtts.
### readByte() {#readByte--}
```
public int readByte()
```


Läser en byte från strömmen och avancerar positionen i strömmen med en byte, eller returnerar -1 om det är slut på strömmen.

**Returns:**
int - Den osignerade byte konverterad till en Int32, eller -1 om slutet på strömmen har nåtts.
### seek(long offset, int origin) {#seek-long-int-}
```
public long seek(long offset, int origin)
```


Ställer in positionen i den aktuella strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| offset | long | En byte-offset relativt `origin`-parametern. Detta värde representerar offset från startpositionen för strömmen som angavs i StreamContainer-konstruktorn. |
| origin | int | Ett värde av typen `System.IO.SeekOrigin` som anger referenspunkten som används för att erhålla den nya positionen. |

**Returns:**
long - Den nya positionen inom den aktuella strömmen.
### seekBegin() {#seekBegin--}
```
public void seekBegin()
```


Sätter strömmens position till början av strömmen. Detta värde representerar offset från startpositionen för strömmen som angavs i StreamContainer-konstruktorn.

### write(byte[] buffer, int offset, int count) {#write-byte---int-int-}
```
public void write(byte[] buffer, int offset, int count)
```


Skriver en sekvens av byte till den aktuella strömmen och avancerar den aktuella positionen i denna ström med antalet skrivna byte.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | byte[] | En array av byte. Denna metod kopierar `count` byte från `buffer` till den aktuella strömmen. |
| offset | int | Den nollbaserade byte-offseten i `buffer` där kopieringen av byte till den aktuella strömmen ska börja. |
| antal | int | Antalet byte som ska skrivas till den aktuella strömmen. |

### save(OutputStream destinationStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destinationStream)
```


Sparar (kopierar) strömmens data till den angivna strömmen. Använder standardbuffertstorlek `ReadWriteBytesCount` och strömmens värde `Length`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | Strömmen att spara data till. |

### save(OutputStream destinationStream, int bufferSize) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream destinationStream, int bufferSize)
```


Sparar (kopierar) all strömmens data till den angivna strömmen. Använder strömmens värde `Length`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | Strömmen att spara data till. |
| bufferSize | int | Bufferten. |

### save(OutputStream destinationStream, int bufferSize, long length) {#save-java.io.OutputStream-int-long-}
```
public void save(OutputStream destinationStream, int bufferSize, long length)
```


Sparar (kopierar) strömmens data till den angivna strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | Strömmen att spara data till. |
| bufferSize | int | Buffertstorleken. Som standard används värdet `ReadWriteBytesCount`. |
| längd | long | Strömmens datalängd att kopiera. Som standard sätts längden till värdet `Length`. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Sparar (kopierar) strömmens data till den angivna strömmen. Använder standardbuffertstorlek `ReadWriteBytesCount` och strömmens värde `Length`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filsökvägen att spara strömmens data till. |

### save(String filePath, int bufferSize) {#save-java.lang.String-int-}
```
public void save(String filePath, int bufferSize)
```


Sparar (kopierar) strömmens data till den angivna strömmen. Använder strömmens värde `Length`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filsökvägen att spara strömmens data till. |
| bufferSize | int | Buffertstorleken. Som standard används värdet `ReadWriteBytesCount`. |

### save(String filePath, int bufferSize, long length) {#save-java.lang.String-int-long-}
```
public void save(String filePath, int bufferSize, long length)
```


Sparar (kopierar) strömmens data till den angivna strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filsökvägen att spara strömmens data till. |
| bufferSize | int | Buffertstorleken. Som standard används värdet `ReadWriteBytesCount`. |
| längd | long | Strömmens datalängd att kopiera. Som standard sätts längden till värdet `Length`. |

### writeTo(StreamContainer streamContainer) {#writeTo-com.aspose.imaging.StreamContainer-}
```
public void writeTo(StreamContainer streamContainer)
```


Kopierar det innehållande data till en annan `StreamContainer`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Strömbehållaren att kopiera till. |

### writeTo(StreamContainer streamContainer, long length) {#writeTo-com.aspose.imaging.StreamContainer-long-}
```
public void writeTo(StreamContainer streamContainer, long length)
```


Kopierar det innehållande data till en annan `StreamContainer`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Strömbehållaren att kopiera till. |
| längd | long | Antalet byte att skriva. |

