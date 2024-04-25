---
title: SplitStreamContainer
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Rappresenta il contenitore del flusso diviso che contiene il flusso e fornisce le routine di elaborazione del flusso.
type: docs
weight: 11120
url: /it/aspose.imaging/splitstreamcontainer/
---
## SplitStreamContainer class

Rappresenta il contenitore del flusso diviso che contiene il flusso e fornisce le routine di elaborazione del flusso.

```csharp
public class SplitStreamContainer : StreamContainer
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SplitStreamContainer](splitstreamcontainer#constructor_1)(Stream) | Inizializza una nuova istanza di[`SplitStreamContainer`](../splitstreamcontainer) classe. |
| [SplitStreamContainer](splitstreamcontainer#constructor_2)(Stream, bool) | Inizializza una nuova istanza di[`SplitStreamContainer`](../splitstreamcontainer) classe. |
| [SplitStreamContainer](splitstreamcontainer#constructor)(StreamContainer, bool) | Inizializza una nuova istanza di[`SplitStreamContainer`](../splitstreamcontainer) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| override [CanRead](../../aspose.imaging/splitstreamcontainer/canread) { get; } | Ottiene un valore che indica se il flusso supporta la lettura. |
| override [CanSeek](../../aspose.imaging/splitstreamcontainer/canseek) { get; } | Ottiene un valore che indica se il flusso supporta la ricerca. |
| override [CanWrite](../../aspose.imaging/splitstreamcontainer/canwrite) { get; } | Ottiene un valore che indica se il flusso supporta la scrittura. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| virtual [IsStreamDisposedOnClose](../../aspose.imaging/streamcontainer/isstreamdisposedonclose) { get; } | Ottiene un valore che indica se questo flusso viene eliminato alla chiusura. |
| override [Length](../../aspose.imaging/splitstreamcontainer/length) { get; set; } | Ottiene o imposta la lunghezza del flusso in byte. Questo valore è inferiore aLength dalla posizione del flusso iniziale passata nel costruttore StreamContainer. |
| override [Position](../../aspose.imaging/splitstreamcontainer/position) { get; set; } | Ottiene o imposta la posizione corrente all'interno del flusso. Questo valore rappresenta l'offset dalla posizione del flusso iniziale passata nel costruttore StreamContainer. |
| override [Stream](../../aspose.imaging/splitstreamcontainer/stream) { get; } | Ottiene il flusso di dati. |
| [SyncRoot](../../aspose.imaging/splitstreamcontainer/syncroot) { get; } | Ottiene un oggetto che può essere utilizzato per sincronizzare l'accesso alla risorsa sincronizzata. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Elimina l'istanza corrente. |
| override [Flush](../../aspose.imaging/splitstreamcontainer/flush)() | Cancella tutti i buffer per questo flusso e fa in modo che tutti i dati memorizzati nel buffer vengano scritti sul dispositivo sottostante. |
| [Insert](../../aspose.imaging/splitstreamcontainer/insert)(int, StreamContainer, bool) | Inserisce il contenitore del flusso nella posizione specificata. |
| override [Read](../../aspose.imaging/splitstreamcontainer/read#read)(byte[]) | Legge i byte per riempire il buffer di byte specificato. |
| override [Read](../../aspose.imaging/splitstreamcontainer/read#read_1)(byte[], int, int) | Legge una sequenza di byte dal flusso corrente e fa avanzare la posizione all'interno del flusso del numero di byte letti. |
| override [ReadByte](../../aspose.imaging/splitstreamcontainer/readbyte)() | Legge un byte dal flusso e fa avanzare la posizione all'interno del flusso di un byte, oppure restituisce -1 se alla fine del flusso. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(Stream) | Salva (copia) i dati del flusso nel flusso specificato. Utilizza la dimensione del buffer predefinita[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount) e streaming[`Length`](../streamcontainer/length) valore. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string) | Salva (copia) i dati del flusso nel flusso specificato. Utilizza la dimensione del buffer predefinita[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount) e streaming[`Length`](../streamcontainer/length) valore. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(Stream, int) | Salva (copia) tutti i dati del flusso nel flusso specificato. Utilizza il flusso[`Length`](../streamcontainer/length) valore. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string, int) | Salva (copia) i dati del flusso nel flusso specificato. Utilizza il flusso[`Length`](../streamcontainer/length) valore. |
| override [Save](../../aspose.imaging/splitstreamcontainer/save#save_2)(Stream, int, long) | Salva (copia) i dati del flusso nel flusso specificato. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string, int, long) | Salva (copia) i dati del flusso nel flusso specificato. |
| override [Seek](../../aspose.imaging/splitstreamcontainer/seek)(long, SeekOrigin) | Imposta la posizione all'interno del flusso corrente. |
| override [SeekBegin](../../aspose.imaging/splitstreamcontainer/seekbegin)() | Imposta la posizione del flusso all'inizio del flusso. Questo valore rappresenta l'offset dalla posizione del flusso iniziale passata nel costruttore StreamContainer. |
| override [ToBytes](../../aspose.imaging/splitstreamcontainer/tobytes#tobytes)() | Converte i dati del flusso in fileByte matrice. |
| override [ToBytes](../../aspose.imaging/splitstreamcontainer/tobytes#tobytes_1)(long, long) | Converte i dati del flusso in fileByte matrice. |
| override [Write](../../aspose.imaging/splitstreamcontainer/write#write)(byte[]) | Scrive tutti i byte specificati nel flusso. |
| override [Write](../../aspose.imaging/splitstreamcontainer/write#write_1)(byte[], int, int) | Scrive una sequenza di byte nel flusso corrente e fa avanzare la posizione corrente all'interno di questo flusso del numero di byte scritti. |
| override [WriteByte](../../aspose.imaging/splitstreamcontainer/writebyte)(byte) | Scrive un byte nella posizione corrente nello stream e fa avanzare la posizione all'interno dello stream di un byte. |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto)(StreamContainer) | Copia i dati contenuti in un altro[`StreamContainer`](../streamcontainer) . |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto)(StreamContainer, long) | Copia i dati contenuti in un altro[`StreamContainer`](../streamcontainer) . |

### Guarda anche

* class [StreamContainer](../streamcontainer)
* spazio dei nomi [Aspose.Imaging](../../aspose.imaging)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
