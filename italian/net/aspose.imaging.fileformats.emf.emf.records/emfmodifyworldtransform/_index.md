---
title: EmfModifyWorldTransform
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Il record EMR_MODIFYWORLDTRANSFORM modifica lo spazio mondiale corrente in page-space trasforma nel contesto del dispositivo di riproduzione.
type: docs
weight: 3840
url: /it/net/aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/
---
## EmfModifyWorldTransform class

Il record EMR_MODIFYWORLDTRANSFORM modifica lo spazio mondiale corrente in page-space trasforma nel contesto del dispositivo di riproduzione.

```csharp
public sealed class EmfModifyWorldTransform : EmfTransformRecordType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmfModifyWorldTransform](emfmodifyworldtransform#constructor)() | Inizializza una nuova istanza di[`EmfModifyWorldTransform`](../emfmodifyworldtransform) classe. |
| [EmfModifyWorldTransform](emfmodifyworldtransform#constructor_1)(EmfRecord) | Inizializza una nuova istanza di[`EmfModifyWorldTransform`](../emfmodifyworldtransform) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ModifyWorldTransformMode](../../aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/modifyworldtransformmode) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che specifica come viene utilizzata la trasformazione specificata in Xform. Questo valore DEVE essere nell'enumerazione ModifyWorldTransformMode (sezione 2.1.24). |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Ottiene o imposta la dimensione del record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Ottiene o imposta il tipo. |
| [Xform](../../aspose.imaging.fileformats.emf.emf.records/emftransformrecordtype/xform) { get; set; } | Ottiene o imposta un oggetto XForm (sezione 2.2.28), che definisce una trasformazione da spazio mondiale a spazio pagina. |

### Osservazioni

Per ulteriori informazioni sulle trasformazioni e gli spazi delle coordinate, vedere [MSDN-WRLDPGSPC]. Vedere sezione 2.3.12 per la specifica di altri tipi di record di trasformazione.

### Guarda anche

* class [EmfTransformRecordType](../emftransformrecordtype)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->