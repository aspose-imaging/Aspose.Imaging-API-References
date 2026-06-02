---
title: "Classe EmfFormat"
type: docs
weight: 60
url: /it/python-net/aspose.imaging.fileformats.emf.emf.objects/emfformat/
---

**Summary:** The EmrFormat object contains information that identifies the format of image data in an<br/>            EMR_COMMENT_MULTIFORMATS record(section 2.3.3.4.3).

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfFormat

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfFormat()](#EmfFormat__1) | Inizializza una nuova istanza della classe EmfFormat |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| off_data | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica l'offset dei dati dal <br/>            inizio del campo identificatore in un record EMR_COMMENT_PUBLIC (sezione 2.3.3.4). <br/>            L'offset DEVE essere allineato a 32 bit. |
| signature | [EmfFormatSignature](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfformatsignature/) | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il formato dei dati immagine. <br/>            Questo valore DEVE appartenere all'enumerazione FormatSignature (sezione 2.1.14). |
| size_data | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione dei dati in byte |
| versione | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di versione del formato. <br/>            Se il campo Signature specifica PostScript incapsulato (EPS), <br/>            questo valore DEVE essere 0x00000001; altrimenti, questo valore DEVE essere ignorato |


### Constructor: EmfFormat() {#EmfFormat__1}


```
 EmfFormat() 
```

Inizializza una nuova istanza della classe EmfFormat

