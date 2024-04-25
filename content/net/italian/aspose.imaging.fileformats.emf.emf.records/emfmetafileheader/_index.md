---
title: EmfMetafileHeader
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: I tipi di record EMR_HEADER definiscono i punti di partenza dei metafile EMF e specificano le proprietà del dispositivo su cui è stata creata limmagine nel metafile . Le informazioni nel record di intestazione consentono a metafile EMF di essere indipendenti da qualsiasi dispositivo di output specifico. Il valore del campo Dimensione può essere utilizzato per distinguere tra i diversi tipi di record EMR_HEADER elencati in precedenza in questa sezione. Sono possibili tre headers Lintestazione di base che è il record EmfMetafileHeader. La parte a dimensione fissa di questa intestazione è 88 byte e contiene un oggetto Header. La prima intestazione di estensione che è il record EmfMetafileHeaderExtension1. La dimensione fissa parte di questa intestazione è di 100 byte e contiene un oggetto Header e un oggetto HeaderExtension1 sezione 2.2.10. La seconda intestazione di estensione che è il record EmfMetafileHeaderExtension2. La parte a dimensione fissa di questa intestazione è 108 byte e contiene un oggetto Header un oggetto HeaderExtension1 e un oggetto HeaderExtension2 sezione 2.2.11.
type: docs
weight: 3810
url: /it/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/
---
## EmfMetafileHeader class

I tipi di record EMR_HEADER definiscono i punti di partenza dei metafile EMF e specificano le proprietà del dispositivo su cui è stata creata l'immagine nel metafile . Le informazioni nel record di intestazione consentono a metafile EMF di essere indipendenti da qualsiasi dispositivo di output specifico. Il valore del campo Dimensione può essere utilizzato per distinguere tra i diversi tipi di record EMR_HEADER elencati in precedenza in questa sezione. Sono possibili tre headers: L'intestazione di base, che è il record EmfMetafileHeader. La parte a dimensione fissa di questa intestazione è 88 byte e contiene un oggetto Header. La prima intestazione di estensione, che è il record EmfMetafileHeaderExtension1. La dimensione fissa parte di questa intestazione è di 100 byte e contiene un oggetto Header e un oggetto HeaderExtension1 (sezione 2.2.10). La seconda intestazione di estensione, che è il record EmfMetafileHeaderExtension2. La parte a dimensione fissa di questa intestazione è 108 byte, e contiene un oggetto Header, un oggetto HeaderExtension1 e un oggetto HeaderExtension2 (sezione 2.2.11).

```csharp
public class EmfMetafileHeader : EmfRecord
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmfMetafileHeader](emfmetafileheader#constructor)() | Inizializza una nuova istanza di[`EmfMetafileHeader`](../emfmetafileheader) classe. |
| [EmfMetafileHeader](emfmetafileheader#constructor_1)(EmfMetafileHeader) | Inizializza una nuova istanza di[`EmfMetafileHeader`](../emfmetafileheader) classe. |
| [EmfMetafileHeader](emfmetafileheader#constructor_2)(EmfRecord) | Inizializza una nuova istanza di[`EmfMetafileHeader`](../emfmetafileheader) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [EmfDescription](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfdescription) { get; set; } | Ottiene o imposta la descrizione EMF Una stringa Unicode UTF16-LE opzionale con terminazione null di lunghezza e contenuto arbitrari. La sua posizione nel record e il numero di caratteri sono specificati rispettivamente dai campi offDescription e nDescription in EmfHeader. Se il valore di uno dei campi è zero, non è presente alcuna stringa di descrizione. |
| [EmfDescriptionBuffer](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfdescriptionbuffer) { get; set; } | Ottiene o imposta il buffer di descrizione EMF Una matrice facoltativa di byte che contiene la stringa di descrizione EMF, che non deve essere contigua alla parte fissa del record EmfMetafileHeader . Di conseguenza, il campo in questo buffer che è etichettato "UndefinedSpace" è facoltativo e DEVE essere ignorato. |
| [EmfHeader](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfheader) { get; set; } | Ottiene o imposta un oggetto Header (sezione 2.2.9), che contiene informazioni sul contenuto e sulla struttura del metafile |
| [EmfHeaderRecordBuffer](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfheaderrecordbuffer) { get; set; } | Ottiene o imposta una matrice facoltativa di byte che contiene il resto del record di intestazione EMF. La dimensione di questo campo DEVE essere un multiplo di 4 byte |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Ottiene o imposta la dimensione del record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Ottiene o imposta il tipo. |

### Guarda anche

* class [EmfRecord](../emfrecord)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
