---
title: "SplitStreamContainer"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar en delad strömbehållare som innehåller strömmen och tillhandahåller rutiner för strömbehandling."
type: docs
weight: 108
url: /sv/java/com.aspose.imaging/splitstreamcontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.StreamContainer](../../com.aspose.imaging/streamcontainer)
```
public class SplitStreamContainer extends StreamContainer
```

Representerar en delad strömbehållare som innehåller strömmen och tillhandahåller rutiner för strömbehandling.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [SplitStreamContainer(InputStream stream)](#SplitStreamContainer-java.io.InputStream-) | Initierar en ny instans av klassen `SplitStreamContainer`. |
| [SplitStreamContainer(InputStream stream, boolean disposeStream)](#SplitStreamContainer-java.io.InputStream-boolean-) | Initierar en ny instans av klassen `SplitStreamContainer`. |
| [SplitStreamContainer(StreamContainer stream, boolean disposeStream)](#SplitStreamContainer-com.aspose.imaging.StreamContainer-boolean-) | Initierar en ny instans av klassen `SplitStreamContainer`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSyncRoot()](#getSyncRoot--) | Hämtar ett objekt som kan användas för att synkronisera åtkomst till den synkroniserade resursen. |
| [getPosition()](#getPosition--) | Hämtar den aktuella positionen i strömmen. |
| [setPosition(long value)](#setPosition-long-) | Ställer in den aktuella positionen i strömmen. |
| [getLength()](#getLength--) | Hämtar strömlängden i byte. |
| [setLength(long value)](#setLength-long-) | Ställer in strömlängden i byte. |
| [canRead()](#canRead--) | Hämtar ett värde som indikerar om strömmen stödjer läsning. |
| [canSeek()](#canSeek--) | Hämtar ett värde som indikerar om strömmen stödjer sökning. |
| [canWrite()](#canWrite--) | Hämtar ett värde som indikerar om strömmen stödjer skrivning. |
| [insert(int position, StreamContainer stream, boolean disposeStream)](#insert-int-com.aspose.imaging.StreamContainer-boolean-) | Infogar strömbehållaren på angiven position. |
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
### SplitStreamContainer(InputStream stream) {#SplitStreamContainer-java.io.InputStream-}
```
public SplitStreamContainer(InputStream stream)
```


Initierar en ny instans av klassen `SplitStreamContainer`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Strömmen. |

### SplitStreamContainer(InputStream stream, boolean disposeStream) {#SplitStreamContainer-java.io.InputStream-boolean-}
```
public SplitStreamContainer(InputStream stream, boolean disposeStream)
```


Initierar en ny instans av klassen `SplitStreamContainer`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Datastreamen. |
| disposeStream | boolean | om den sätts till `true` kommer strömmen att avyttras när behållaren avyttras. |

### SplitStreamContainer(StreamContainer stream, boolean disposeStream) {#SplitStreamContainer-com.aspose.imaging.StreamContainer-boolean-}
```
public SplitStreamContainer(StreamContainer stream, boolean disposeStream)
```


Initierar en ny instans av klassen `SplitStreamContainer`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Strömbehållaren. |
| disposeStream | boolean | om den sätts till `true` avyttras strömmen. |

### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Hämtar ett objekt som kan användas för att synkronisera åtkomst till den synkroniserade resursen.

**Returns:**
java.lang.Object - Objektet som kan användas för att synkronisera åtkomst till den synkroniserade resursen.
### getPosition() {#getPosition--}
```
public long getPosition()
```


Hämtar den aktuella positionen i strömmen. Detta värde representerar förskjutning från startpositionen för strömmen som angavs i StreamContainer-konstruktorn.

**Returns:**
long - Den aktuella strömpositionen.
### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


Ställer in den aktuella positionen i strömmen. Detta värde representerar förskjutning från startpositionen för strömmen som angavs i StreamContainer-konstruktorn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long | Den aktuella strömpositionen. |

### getLength() {#getLength--}
```
public long getLength()
```


Hämtar strömmens längd i byte. Detta värde är mindre än `System.IO.Stream.Length` med startpositionen för strömmen som angavs i StreamContainer-konstruktorn.

**Returns:**
long - Strömlängden.
### setLength(long value) {#setLength-long-}
```
public void setLength(long value)
```


Ställer in strömlängden i byte. Detta värde är mindre än `System.IO.Stream.Length` med startpositionen för strömmen som angavs i StreamContainer-konstruktorn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long | Strömlängden. |

### canRead() {#canRead--}
```
public boolean canRead()
```


Hämtar ett värde som indikerar om strömmen stödjer läsning.

**Returns:**
boolean - `true` om strömmen stödjer läsning; annars `false`.
### canSeek() {#canSeek--}
```
public boolean canSeek()
```


Hämtar ett värde som indikerar om strömmen stödjer sökning.

**Returns:**
boolean - `true` om strömmen stödjer sökning; annars `false`.
### canWrite() {#canWrite--}
```
public boolean canWrite()
```


Hämtar ett värde som indikerar om strömmen stödjer skrivning.

**Returns:**
boolean - `true` om strömmen stödjer skrivning; annars `false`.
### insert(int position, StreamContainer stream, boolean disposeStream) {#insert-int-com.aspose.imaging.StreamContainer-boolean-}
```
public void insert(int position, StreamContainer stream, boolean disposeStream)
```


Infogar strömbehållaren på angiven position.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | int | Positionen att infoga till. |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Strömbehållaren att infoga. |
| disposeStream | boolean | om den sätts till `true` avyttras strömmen. |

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

