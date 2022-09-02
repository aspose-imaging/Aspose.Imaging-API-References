---
title: SplitStreamContainer
second_title: Aspose.Imaging för .NET API-referens
description: Representerar delad strömbehållare som innehåller strömmen och tillhandahåller strömbehandlingsrutiner.
type: docs
weight: 11120
url: /sv/net/aspose.imaging/splitstreamcontainer/
---
## SplitStreamContainer class

Representerar delad strömbehållare som innehåller strömmen och tillhandahåller strömbehandlingsrutiner.

```csharp
public class SplitStreamContainer : StreamContainer
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [SplitStreamContainer](splitstreamcontainer#constructor_1)(Stream) | Initierar en ny instans av[`SplitStreamContainer`](../splitstreamcontainer) class. |
| [SplitStreamContainer](splitstreamcontainer#constructor_2)(Stream, bool) | Initierar en ny instans av[`SplitStreamContainer`](../splitstreamcontainer) class. |
| [SplitStreamContainer](splitstreamcontainer#constructor)(StreamContainer, bool) | Initierar en ny instans av[`SplitStreamContainer`](../splitstreamcontainer) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| override [CanRead](../../aspose.imaging/splitstreamcontainer/canread) { get; } | Får ett värde som anger om strömmen stöder läsning. |
| override [CanSeek](../../aspose.imaging/splitstreamcontainer/canseek) { get; } | Får ett värde som indikerar om ström stöder sökning. |
| override [CanWrite](../../aspose.imaging/splitstreamcontainer/canwrite) { get; } | Får ett värde som indikerar om ström stöder skrivning. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| virtual [IsStreamDisposedOnClose](../../aspose.imaging/streamcontainer/isstreamdisposedonclose) { get; } | Får ett värde som indikerar om den här strömmen slängs vid stängning. |
| override [Length](../../aspose.imaging/splitstreamcontainer/length) { get; set; } | Hämtar eller ställer in strömlängden i byte. Detta värde är mindre änLength av startströmpositionen som skickas i StreamContainer-konstruktorn. |
| override [Position](../../aspose.imaging/splitstreamcontainer/position) { get; set; } | Hämtar eller ställer in den aktuella positionen i strömmen. Detta värde representerar offset från startströmpositionen som skickats i StreamContainer-konstruktorn. |
| override [Stream](../../aspose.imaging/splitstreamcontainer/stream) { get; } | Hämtar dataströmmen. |
| [SyncRoot](../../aspose.imaging/splitstreamcontainer/syncroot) { get; } | Hämtar ett objekt som kan användas för att synkronisera åtkomst till den synkroniserade resursen. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Tar bort den aktuella instansen. |
| override [Flush](../../aspose.imaging/splitstreamcontainer/flush)() | Rensar alla buffertar för denna ström och gör att all buffrad data skrivs till den underliggande enheten. |
| [Insert](../../aspose.imaging/splitstreamcontainer/insert)(int, StreamContainer, bool) | Infogar strömbehållaren i angiven position. |
| override [Read](../../aspose.imaging/splitstreamcontainer/read#read)(byte[]) | Läser bytes för att fylla den angivna bytebufferten. |
| override [Read](../../aspose.imaging/splitstreamcontainer/read#read_1)(byte[], int, int) | Läser en sekvens av byte från den aktuella strömmen och flyttar fram positionen i strömmen med antalet lästa byte. |
| override [ReadByte](../../aspose.imaging/splitstreamcontainer/readbyte)() | Läser en byte från strömmen och flyttar fram positionen i strömmen med en byte, eller returnerar -1 om i slutet av strömmen. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(Stream) | Sparar (kopierar) strömmens data till den angivna strömmen. Använder standardbuffertstorlek[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount) och strömma[`Length`](../streamcontainer/length) värde. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string) | Sparar (kopierar) strömmens data till den angivna strömmen. Använder standardbuffertstorlek[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount) och strömma[`Length`](../streamcontainer/length) värde. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(Stream, int) | Sparar (kopierar) all ströms data till den angivna strömmen. Använder stream[`Length`](../streamcontainer/length) värde. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string, int) | Sparar (kopierar) strömmens data till den angivna strömmen. Använder stream[`Length`](../streamcontainer/length) värde. |
| override [Save](../../aspose.imaging/splitstreamcontainer/save#save_2)(Stream, int, long) | Sparar (kopierar) strömmens data till den angivna strömmen. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string, int, long) | Sparar (kopierar) strömmens data till den angivna strömmen. |
| override [Seek](../../aspose.imaging/splitstreamcontainer/seek)(long, SeekOrigin) | Ställer in positionen inom den aktuella strömmen. |
| override [SeekBegin](../../aspose.imaging/splitstreamcontainer/seekbegin)() | Ställer in strömningspositionen till början av strömmen. Detta värde representerar offset från startströmpositionen som skickats i StreamContainer-konstruktorn. |
| override [ToBytes](../../aspose.imaging/splitstreamcontainer/tobytes#tobytes)() | Konverterar strömdata tillByte array. |
| override [ToBytes](../../aspose.imaging/splitstreamcontainer/tobytes#tobytes_1)(long, long) | Konverterar strömdata tillByte array. |
| override [Write](../../aspose.imaging/splitstreamcontainer/write#write)(byte[]) | Skriver alla angivna byte till strömmen. |
| override [Write](../../aspose.imaging/splitstreamcontainer/write#write_1)(byte[], int, int) | Skriver en sekvens av byte till den aktuella strömmen och flyttar fram den aktuella positionen inom denna ström med antalet skrivna byte. |
| override [WriteByte](../../aspose.imaging/splitstreamcontainer/writebyte)(byte) | Skriver en byte till den aktuella positionen i strömmen och flyttar fram positionen i strömmen med en byte. |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto)(StreamContainer) | Kopierar ingående data till en annan[`StreamContainer`](../streamcontainer) . |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto)(StreamContainer, long) | Kopierar ingående data till en annan[`StreamContainer`](../streamcontainer) . |

### Se även

* class [StreamContainer](../streamcontainer)
* namnutrymme [Aspose.Imaging](../../aspose.imaging)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
