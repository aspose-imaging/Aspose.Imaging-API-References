---
title: EmfPlusPathPointFlags
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Un intero senza segno a 32 bit che specifica come interpretare i punti e i tipi di punti associati definiti da questo oggetto. C 1 bit se impostato larray PathPoints specifica le posizioni assolute nello spazio delle coordinate con un numero intero a 16 bit coordinates. Se azzerato larray PathPoints specifica posizioni assolute nello spazio delle coordinate con coordinate a virgola mobile a 32 bit. Nota Se il flag P sotto è impostato questo flag PUÒ essere deselezionato e DEVE essere ignorato. R  1 bit se impostato i tipi di punto nellarray PathPointTypes sono specificati da oggetti EmfPlusPathPointTypeRle sezione 2.2.2.32 che utilizzano la compressione RLE run-length encoding e/o oggetti EmfPlusPathPointType sezione 2.2.2.31. Vedere MS-WMF sezione 3.1.6 per ulteriori informazioni sulla compressione RLE. Se deselezionato i tipi di punto nellarray PathPointTypes sono specificati dagli oggetti EmfPlusPathPointType. P 1 bit se impostato ogni elemento nellarray PathPoints specifica una posizione nello spazio delle coordinate relativa alla posizione specificata dallelemento precedente nellarray. Nel caso del primo elemento in PathPoints viene presupposta una posizione precedente alle coordinate 00. Se deselezionata ogni elemento nellarray PathPoints specifica una posizione assoluta.
type: docs
weight: 4960
url: /it/net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspathpointflags/
---
## EmfPlusPathPointFlags enumeration

Un intero senza segno a 32 bit che specifica come interpretare i punti e i tipi di punti associati definiti da questo oggetto. C (1 bit): se impostato, l'array PathPoints specifica le posizioni assolute nello spazio delle coordinate con un numero intero a 16 bit coordinates. Se azzerato, l'array PathPoints specifica posizioni assolute nello spazio delle coordinate con coordinate a virgola mobile a 32 bit. Nota Se il flag P (sotto) è impostato, questo flag PUÒ essere deselezionato e DEVE essere ignorato. R ( 1 bit): se impostato, i tipi di punto nell'array PathPointTypes sono specificati da oggetti EmfPlusPathPointTypeRle (sezione 2.2.2.32), che utilizzano la compressione RLE (run-length encoding) e/o oggetti EmfPlusPathPointType (sezione 2.2.2.31). Vedere [MS-WMF] sezione 3.1.6 per ulteriori informazioni sulla compressione RLE. Se deselezionato, i tipi di punto nell'array PathPointTypes sono specificati dagli oggetti EmfPlusPathPointType. P (1 bit): se impostato, ogni elemento nell'array PathPoints specifica una posizione nello spazio delle coordinate relativa alla posizione specificata dall'elemento precedente nell'array. Nel caso del primo elemento in PathPoints, viene presupposta una posizione precedente alle coordinate (0,0). Se deselezionata, ogni elemento nell'array PathPoints specifica una posizione assoluta.

```csharp
[Flags]
public enum EmfPlusPathPointFlags : short
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| C | `4000` | Il flag c |
| R | `1000` | Il flag r |
| P | `800` | Il flag p |

### Guarda anche

* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
