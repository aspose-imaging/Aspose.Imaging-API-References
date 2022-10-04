---
title: EmfCommentPublicRecordType
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: I tipi di record EMR_COMMENT_PUBLIC specificano le estensioni allelaborazione EMF.
type: docs
weight: 3410
url: /it/net/aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/
---
## EmfCommentPublicRecordType class

I tipi di record EMR_COMMENT_PUBLIC specificano le estensioni all'elaborazione EMF.

```csharp
public abstract class EmfCommentPublicRecordType : EmfCommentRecordType
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| override [CommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/commentidentifier) { get; set; } | Ottiene o imposta un numero intero senza segno a 32 bit che identifica questo record di commento come specifica di dati pubblici. Il valore 0x43494447, che è la stringa ASCII "CIDG", identifica questo come record EMR_COMMENT_PUBLIC. |
| [DataSize](../../aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/datasize) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione, in byte, dei campi CommentIdentifier e CommentRecordParm nel campo RecordBuffer che segue . NON DEVE includere la dimensione di se stesso o la dimensione del campo AlignmentPadding, se present |
| [PublicCommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/publiccommentidentifier) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che identifica il tipo di record di commento pubblico . Questo DOVREBBE essere uno dei valori elencati nella tabella precedente, che sono specificati nell'enumerazione EmrComment (sezione 2.1.10), a meno che non siano stati implementati ulteriori tipi di record di commento pubblico sul server di stampa. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Ottiene o imposta la dimensione del record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Ottiene o imposta il tipo. |

### Guarda anche

* class [EmfCommentRecordType](../emfcommentrecordtype)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->