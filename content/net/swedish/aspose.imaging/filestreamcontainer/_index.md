---
title: FileStreamContainer
second_title: Aspose.Imaging för .NET API-referens
description: Hjälpare för bearbetning av filström.
type: docs
weight: 9300
url: /sv/aspose.imaging/filestreamcontainer/
---
## FileStreamContainer class

Hjälpare för bearbetning av filström.

```csharp
public sealed class FileStreamContainer : StreamContainer
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| virtual [CanRead](../../aspose.imaging/streamcontainer/canread) { get; } | Får ett värde som anger om strömmen stöder läsning. |
| virtual [CanSeek](../../aspose.imaging/streamcontainer/canseek) { get; } | Får ett värde som indikerar om ström stöder sökning. |
| virtual [CanWrite](../../aspose.imaging/streamcontainer/canwrite) { get; } | Får ett värde som indikerar om ström stöder skrivning. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| [FilePath](../../aspose.imaging/filestreamcontainer/filepath) { get; } | Hämtar filsökvägen. |
| [IsCreated](../../aspose.imaging/filestreamcontainer/iscreated) { get; } | Får ett värde som anger om strömmen skapades explicit. |
| virtual [IsStreamDisposedOnClose](../../aspose.imaging/streamcontainer/isstreamdisposedonclose) { get; } | Får ett värde som indikerar om den här strömmen slängs vid stängning. |
| [IsTemporal](../../aspose.imaging/filestreamcontainer/istemporal) { get; set; } | Hämtar eller ställer in ett värde som anger om strömmen är temporär. |
| virtual [Length](../../aspose.imaging/streamcontainer/length) { get; set; } | Hämtar eller ställer in strömlängden i byte. Detta värde är mindre änLength av startströmpositionen som skickas i StreamContainer-konstruktorn. |
| virtual [Position](../../aspose.imaging/streamcontainer/position) { get; set; } | Hämtar eller ställer in den aktuella positionen i strömmen. Detta värde representerar offset från startströmpositionen som skickats i StreamContainer-konstruktorn. |
| virtual [Stream](../../aspose.imaging/streamcontainer/stream) { get; } | Hämtar dataströmmen. |
| [SyncRoot](../../aspose.imaging/streamcontainer/syncroot) { get; } | Hämtar ett objekt som kan användas för att synkronisera åtkomst till den synkroniserade resursen. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [CreateFileStream](../../aspose.imaging/filestreamcontainer/createfilestream)(string, bool) | Skapar en ny filström. |
| static [OpenFileStream](../../aspose.imaging/filestreamcontainer/openfilestream)(string) | Öppnar en befintlig filström. Om filströmmen inte finns skapas lämpligt undantag. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Tar bort den aktuella instansen. |
| virtual [Flush](../../aspose.imaging/streamcontainer/flush)() | Rensar alla buffertar för denna ström och gör att all buffrad data skrivs till den underliggande enheten. |
| virtual [Read](../../aspose.imaging/streamcontainer/read)(byte[]) | Läser bytes för att fylla den angivna bytebufferten. |
| virtual [Read](../../aspose.imaging/streamcontainer/read)(byte[], int, int) | Läser en sekvens av byte från den aktuella strömmen och flyttar fram positionen i strömmen med antalet lästa byte. |
| virtual [ReadByte](../../aspose.imaging/streamcontainer/readbyte)() | Läser en byte från strömmen och flyttar fram positionen i strömmen med en byte, eller returnerar -1 om i slutet av strömmen. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(Stream) | Sparar (kopierar) strömmens data till den angivna strömmen. Använder standardbuffertstorlek[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount) och strömma[`Length`](../streamcontainer/length) värde. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string) | Sparar (kopierar) strömmens data till den angivna strömmen. Använder standardbuffertstorlek[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount) och strömma[`Length`](../streamcontainer/length) värde. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(Stream, int) | Sparar (kopierar) all ströms data till den angivna strömmen. Använder stream[`Length`](../streamcontainer/length) värde. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string, int) | Sparar (kopierar) strömmens data till den angivna strömmen. Använder stream[`Length`](../streamcontainer/length) värde. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(Stream, int, long) | Sparar (kopierar) strömmens data till den angivna strömmen. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string, int, long) | Sparar (kopierar) strömmens data till den angivna strömmen. |
| virtual [Seek](../../aspose.imaging/streamcontainer/seek)(long, SeekOrigin) | Ställer in positionen inom den aktuella strömmen. |
| virtual [SeekBegin](../../aspose.imaging/streamcontainer/seekbegin)() | Ställer in strömningspositionen till början av strömmen. Detta värde representerar offset från startströmpositionen som skickats i StreamContainer-konstruktorn. |
| virtual [ToBytes](../../aspose.imaging/streamcontainer/tobytes)() | Konverterar strömdata tillByte array. |
| virtual [ToBytes](../../aspose.imaging/streamcontainer/tobytes)(long, long) | Konverterar strömdata tillByte array. |
| virtual [Write](../../aspose.imaging/streamcontainer/write)(byte[]) | Skriver alla angivna byte till strömmen. |
| virtual [Write](../../aspose.imaging/streamcontainer/write)(byte[], int, int) | Skriver en sekvens av byte till den aktuella strömmen och flyttar fram den aktuella positionen inom denna ström med antalet skrivna byte. |
| virtual [WriteByte](../../aspose.imaging/streamcontainer/writebyte)(byte) | Skriver en byte till den aktuella positionen i strömmen och flyttar fram positionen i strömmen med en byte. |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto)(StreamContainer) | Kopierar ingående data till en annan[`StreamContainer`](../streamcontainer) . |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto)(StreamContainer, long) | Kopierar ingående data till en annan[`StreamContainer`](../streamcontainer) . |
| [explicit operator](../../aspose.imaging/filestreamcontainer/op_explicit#op_explicit_1) | Utför en explicit konvertering från[`FileStreamContainer`](../filestreamcontainer) tillStream . (2 operators) |

### Se även

* class [StreamContainer](../streamcontainer)
* namnutrymme [Aspose.Imaging](../../aspose.imaging)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
