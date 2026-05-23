---
title: "Classe EmfRegionDataHeader"
type: docs
weight: 250
url: /it/python-net/aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader/
---

**Summary:** The RegionDataHeader object describes the properties of a RegionData object.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfRegionDataHeader

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfRegionDataHeader()](#EmfRegionDataHeader__1) | Inizializza una nuova istanza della classe EmfRegionDataHeader |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Ottiene o imposta un oggetto WMF RectL a 128 bit ([MS-WMF] sezione 2.2.2.19), che specifica <br/>            i limiti della regione. |
| count_rects | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di rettangoli in questa regione. |
| rgn_size | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione del buffer di rettangoli in byte. |
| dimensione | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione di questo oggetto in byte. Questo DEVE essere 0x00000020. |
| type | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il tipo di regione. Questo DOVREBBE essere <br/>            RDH_RECTANGLES (0x00000001). |


### Constructor: EmfRegionDataHeader() {#EmfRegionDataHeader__1}


```
 EmfRegionDataHeader() 
```

Inizializza una nuova istanza della classe EmfRegionDataHeader

