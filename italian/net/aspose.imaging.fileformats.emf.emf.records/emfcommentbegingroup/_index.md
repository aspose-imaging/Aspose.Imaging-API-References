---
title: EmfCommentBeginGroup
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Il record EMR_COMMENT_BEGINGROUP specifica linizio di un gruppo di record di disegno.
type: docs
weight: 3350
url: /it/net/aspose.imaging.fileformats.emf.emf.records/emfcommentbegingroup/
---
## EmfCommentBeginGroup class

Il record EMR_COMMENT_BEGINGROUP specifica l'inizio di un gruppo di record di disegno.

```csharp
public sealed class EmfCommentBeginGroup : EmfCommentPublicRecordType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmfCommentBeginGroup](emfcommentbegingroup)(EmfRecord) | Inizializza una nuova istanza di[`EmfCommentBeginGroup`](../emfcommentbegingroup) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| override [CommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/commentidentifier) { get; set; } | Ottiene o imposta un numero intero senza segno a 32 bit che identifica questo record di commento come specifica di dati pubblici. Il valore 0x43494447, che è la stringa ASCII "CIDG", identifica questo come record EMR_COMMENT_PUBLIC. |
| [DataSize](../../aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/datasize) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione, in byte, dei campi CommentIdentifier e CommentRecordParm nel campo RecordBuffer che segue . NON DEVE includere la dimensione di se stesso o la dimensione del campo AlignmentPadding, se present |
| [Description](../../aspose.imaging.fileformats.emf.emf.records/emfcommentbegingroup/description) { get; set; } | Ottiene o imposta una stringa Unicode facoltativa con terminazione null che descrive questo gruppo di record. |
| [NDescription](../../aspose.imaging.fileformats.emf.emf.records/emfcommentbegingroup/ndescription) { get; set; } | Ottiene o imposta il numero di caratteri Unicode nella stringa di descrizione facoltativa che segue. |
| [PublicCommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/publiccommentidentifier) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che identifica il tipo di record di commento pubblico . Questo DOVREBBE essere uno dei valori elencati nella tabella precedente, che sono specificati nell'enumerazione EmrComment (sezione 2.1.10), a meno che non siano stati implementati ulteriori tipi di record di commento pubblico sul server di stampa. |
| [Rectangle](../../aspose.imaging.fileformats.emf.emf.records/emfcommentbegingroup/rectangle) { get; set; } | Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che specifica il rettangolo di output in coordinate logiche. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Ottiene o imposta la dimensione del record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Ottiene o imposta il tipo. |

### Guarda anche

* class [EmfCommentPublicRecordType](../emfcommentpublicrecordtype)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
