---
title: StreamContainer
second_title: Aspose.Imaging för .NET API-referens
description: Representerar strömbehållare som innehåller strömmen och tillhandahåller strömbehandlingsrutiner.
type: docs
weight: 11130
url: /sv/aspose.imaging/streamcontainer/
---
## StreamContainer class

Representerar strömbehållare som innehåller strömmen och tillhandahåller strömbehandlingsrutiner.

```csharp
public class StreamContainer : DisposableObject
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [StreamContainer](streamcontainer#constructor)(Stream) | Initierar en ny instans av[`StreamContainer`](../streamcontainer) class. |
| [StreamContainer](streamcontainer#constructor_1)(Stream, bool) | Initierar en ny instans av[`StreamContainer`](../streamcontainer) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| virtual [CanRead](../../aspose.imaging/streamcontainer/canread) { get; } | Får ett värde som anger om strömmen stöder läsning. |
| virtual [CanSeek](../../aspose.imaging/streamcontainer/canseek) { get; } | Får ett värde som indikerar om ström stöder sökning. |
| virtual [CanWrite](../../aspose.imaging/streamcontainer/canwrite) { get; } | Får ett värde som indikerar om ström stöder skrivning. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| virtual [IsStreamDisposedOnClose](../../aspose.imaging/streamcontainer/isstreamdisposedonclose) { get; } | Får ett värde som indikerar om den här strömmen slängs vid stängning. |
| virtual [Length](../../aspose.imaging/streamcontainer/length) { get; set; } | Hämtar eller ställer in strömlängden i byte. Detta värde är mindre änLength av startströmpositionen som skickas i StreamContainer-konstruktorn. |
| virtual [Position](../../aspose.imaging/streamcontainer/position) { get; set; } | Hämtar eller ställer in den aktuella positionen i strömmen. Detta värde representerar offset från startströmpositionen som skickats i StreamContainer-konstruktorn. |
| virtual [Stream](../../aspose.imaging/streamcontainer/stream) { get; } | Hämtar dataströmmen. |
| [SyncRoot](../../aspose.imaging/streamcontainer/syncroot) { get; } | Hämtar ett objekt som kan användas för att synkronisera åtkomst till den synkroniserade resursen. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Tar bort den aktuella instansen. |
| virtual [Flush](../../aspose.imaging/streamcontainer/flush)() | Rensar alla buffertar för denna ström och gör att all buffrad data skrivs till den underliggande enheten. |
| virtual [Read](../../aspose.imaging/streamcontainer/read#read)(byte[]) | Läser bytes för att fylla den angivna bytebufferten. |
| virtual [Read](../../aspose.imaging/streamcontainer/read#read_1)(byte[], int, int) | Läser en sekvens av byte från den aktuella strömmen och flyttar fram positionen i strömmen med antalet lästa byte. |
| virtual [ReadByte](../../aspose.imaging/streamcontainer/readbyte)() | Läser en byte från strömmen och flyttar fram positionen i strömmen med en byte, eller returnerar -1 om i slutet av strömmen. |
| virtual [Save](../../aspose.imaging/streamcontainer/save#save)(Stream) | Sparar (kopierar) strömmens data till den angivna strömmen. Använder standardbuffertstorlek[`ReadWriteBytesCount`](./readwritebytescount) och strömma[`Length`](./length) värde. |
| virtual [Save](../../aspose.imaging/streamcontainer/save#save_3)(string) | Sparar (kopierar) strömmens data till den angivna strömmen. Använder standardbuffertstorlek[`ReadWriteBytesCount`](./readwritebytescount) och strömma[`Length`](./length) värde. |
| virtual [Save](../../aspose.imaging/streamcontainer/save#save_1)(Stream, int) | Sparar (kopierar) all ströms data till den angivna strömmen. Använder stream[`Length`](./length) värde. |
| virtual [Save](../../aspose.imaging/streamcontainer/save#save_4)(string, int) | Sparar (kopierar) strömmens data till den angivna strömmen. Använder stream[`Length`](./length) värde. |
| virtual [Save](../../aspose.imaging/streamcontainer/save#save_2)(Stream, int, long) | Sparar (kopierar) strömmens data till den angivna strömmen. |
| virtual [Save](../../aspose.imaging/streamcontainer/save#save_5)(string, int, long) | Sparar (kopierar) strömmens data till den angivna strömmen. |
| virtual [Seek](../../aspose.imaging/streamcontainer/seek)(long, SeekOrigin) | Ställer in positionen inom den aktuella strömmen. |
| virtual [SeekBegin](../../aspose.imaging/streamcontainer/seekbegin)() | Ställer in strömningspositionen till början av strömmen. Detta värde representerar offset från startströmpositionen som skickats i StreamContainer-konstruktorn. |
| virtual [ToBytes](../../aspose.imaging/streamcontainer/tobytes#tobytes)() | Konverterar strömdata tillByte array. |
| virtual [ToBytes](../../aspose.imaging/streamcontainer/tobytes#tobytes_1)(long, long) | Konverterar strömdata tillByte array. |
| virtual [Write](../../aspose.imaging/streamcontainer/write#write)(byte[]) | Skriver alla angivna byte till strömmen. |
| virtual [Write](../../aspose.imaging/streamcontainer/write#write_1)(byte[], int, int) | Skriver en sekvens av byte till den aktuella strömmen och flyttar fram den aktuella positionen inom denna ström med antalet skrivna byte. |
| virtual [WriteByte](../../aspose.imaging/streamcontainer/writebyte)(byte) | Skriver en byte till den aktuella positionen i strömmen och flyttar fram positionen i strömmen med en byte. |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto#writeto)(StreamContainer) | Kopierar ingående data till en annan[`StreamContainer`](../streamcontainer) . |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto#writeto_1)(StreamContainer, long) | Kopierar ingående data till en annan[`StreamContainer`](../streamcontainer) . |
| [explicit operator](../../aspose.imaging/streamcontainer/op_explicit) | Utför en explicit konvertering från[`StreamContainer`](../streamcontainer) tillStream . |

## Fält

| namn | Beskrivning |
| --- | --- |
| const [ReadWriteBytesCount](../../aspose.imaging/streamcontainer/readwritebytescount) | Anger antal läs- och skrivbytes vid sekventiell läsning. |

### Se även

* class [DisposableObject](../disposableobject)
* namnutrymme [Aspose.Imaging](../../aspose.imaging)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
