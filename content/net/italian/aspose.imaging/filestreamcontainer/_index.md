---
title: FileStreamContainer
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Helper per lelaborazione del flusso di file.
type: docs
weight: 9300
url: /it/aspose.imaging/filestreamcontainer/
---
## FileStreamContainer class

Helper per l'elaborazione del flusso di file.

```csharp
public sealed class FileStreamContainer : StreamContainer
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| virtual [CanRead](../../aspose.imaging/streamcontainer/canread) { get; } | Ottiene un valore che indica se il flusso supporta la lettura. |
| virtual [CanSeek](../../aspose.imaging/streamcontainer/canseek) { get; } | Ottiene un valore che indica se il flusso supporta la ricerca. |
| virtual [CanWrite](../../aspose.imaging/streamcontainer/canwrite) { get; } | Ottiene un valore che indica se il flusso supporta la scrittura. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| [FilePath](../../aspose.imaging/filestreamcontainer/filepath) { get; } | Ottiene il percorso del file. |
| [IsCreated](../../aspose.imaging/filestreamcontainer/iscreated) { get; } | Ottiene un valore che indica se il flusso è stato creato in modo esplicito. |
| virtual [IsStreamDisposedOnClose](../../aspose.imaging/streamcontainer/isstreamdisposedonclose) { get; } | Ottiene un valore che indica se questo flusso viene eliminato alla chiusura. |
| [IsTemporal](../../aspose.imaging/filestreamcontainer/istemporal) { get; set; } | Ottiene o imposta un valore che indica se il flusso è temporale. |
| virtual [Length](../../aspose.imaging/streamcontainer/length) { get; set; } | Ottiene o imposta la lunghezza del flusso in byte. Questo valore è inferiore aLength dalla posizione del flusso iniziale passata nel costruttore StreamContainer. |
| virtual [Position](../../aspose.imaging/streamcontainer/position) { get; set; } | Ottiene o imposta la posizione corrente all'interno del flusso. Questo valore rappresenta l'offset dalla posizione del flusso iniziale passata nel costruttore StreamContainer. |
| virtual [Stream](../../aspose.imaging/streamcontainer/stream) { get; } | Ottiene il flusso di dati. |
| [SyncRoot](../../aspose.imaging/streamcontainer/syncroot) { get; } | Ottiene un oggetto che può essere utilizzato per sincronizzare l'accesso alla risorsa sincronizzata. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [CreateFileStream](../../aspose.imaging/filestreamcontainer/createfilestream)(string, bool) | Crea un nuovo flusso di file. |
| static [OpenFileStream](../../aspose.imaging/filestreamcontainer/openfilestream)(string) | Apre un flusso di file esistente. Se il flusso di file non esiste, viene generata l'eccezione appropriata. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Elimina l'istanza corrente. |
| virtual [Flush](../../aspose.imaging/streamcontainer/flush)() | Cancella tutti i buffer per questo flusso e fa in modo che tutti i dati memorizzati nel buffer vengano scritti sul dispositivo sottostante. |
| virtual [Read](../../aspose.imaging/streamcontainer/read)(byte[]) | Legge i byte per riempire il buffer di byte specificato. |
| virtual [Read](../../aspose.imaging/streamcontainer/read)(byte[], int, int) | Legge una sequenza di byte dal flusso corrente e fa avanzare la posizione all'interno del flusso del numero di byte letti. |
| virtual [ReadByte](../../aspose.imaging/streamcontainer/readbyte)() | Legge un byte dal flusso e fa avanzare la posizione all'interno del flusso di un byte, oppure restituisce -1 se alla fine del flusso. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(Stream) | Salva (copia) i dati del flusso nel flusso specificato. Utilizza la dimensione del buffer predefinita[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount) e streaming[`Length`](../streamcontainer/length) valore. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string) | Salva (copia) i dati del flusso nel flusso specificato. Utilizza la dimensione del buffer predefinita[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount) e streaming[`Length`](../streamcontainer/length) valore. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(Stream, int) | Salva (copia) tutti i dati del flusso nel flusso specificato. Utilizza il flusso[`Length`](../streamcontainer/length) valore. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string, int) | Salva (copia) i dati del flusso nel flusso specificato. Utilizza il flusso[`Length`](../streamcontainer/length) valore. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(Stream, int, long) | Salva (copia) i dati del flusso nel flusso specificato. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string, int, long) | Salva (copia) i dati del flusso nel flusso specificato. |
| virtual [Seek](../../aspose.imaging/streamcontainer/seek)(long, SeekOrigin) | Imposta la posizione all'interno del flusso corrente. |
| virtual [SeekBegin](../../aspose.imaging/streamcontainer/seekbegin)() | Imposta la posizione del flusso all'inizio del flusso. Questo valore rappresenta l'offset dalla posizione del flusso iniziale passata nel costruttore StreamContainer. |
| virtual [ToBytes](../../aspose.imaging/streamcontainer/tobytes)() | Converte i dati del flusso in fileByte matrice. |
| virtual [ToBytes](../../aspose.imaging/streamcontainer/tobytes)(long, long) | Converte i dati del flusso in fileByte matrice. |
| virtual [Write](../../aspose.imaging/streamcontainer/write)(byte[]) | Scrive tutti i byte specificati nel flusso. |
| virtual [Write](../../aspose.imaging/streamcontainer/write)(byte[], int, int) | Scrive una sequenza di byte nel flusso corrente e fa avanzare la posizione corrente all'interno di questo flusso del numero di byte scritti. |
| virtual [WriteByte](../../aspose.imaging/streamcontainer/writebyte)(byte) | Scrive un byte nella posizione corrente nello stream e fa avanzare la posizione all'interno dello stream di un byte. |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto)(StreamContainer) | Copia i dati contenuti in un altro[`StreamContainer`](../streamcontainer) . |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto)(StreamContainer, long) | Copia i dati contenuti in un altro[`StreamContainer`](../streamcontainer) . |
| [explicit operator](../../aspose.imaging/filestreamcontainer/op_explicit#op_explicit_1) | Esegue una conversione esplicita da[`FileStreamContainer`](../filestreamcontainer) aStream . (2 operators) |

### Guarda anche

* class [StreamContainer](../streamcontainer)
* spazio dei nomi [Aspose.Imaging](../../aspose.imaging)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
