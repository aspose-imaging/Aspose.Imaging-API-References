---
title: "Classe EmfRop4"
type: docs
weight: 1010
url: /it/python-net/aspose.imaging.fileformats.emf.emf.records/emfrop4/
---

**Summary:** A quaternary raster operation, which specifies ternary raster operations for <br/>            the foreground and background colors of a bitmap. These values define how the color data of <br/>            the source rectangle is to be combined with the color data of the destination rectangle.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfRop4

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfRop4(dword_data)](#EmfRop4_dword_data_1) | Inizializza una nuova istanza della classe [EmfRop4](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrop4/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| background_rop3 | System.Byte | r | Ottiene il ROP3 di sfondo.<br/>            Gli 8 bit più significativi senza segno di un valore di operazione raster ternario a 24 bit dalla enumerazione WMF Ternary Raster Operation ([MS-WMF] sezione 2.1.1.31). Questo codice definisce come combinare i dati di colore di sfondo dei <br/>            bitmap sorgente e di destinazione e il modello di pennello. |
| foreground_rop3 | System.Byte | r | Ottiene il ROP3 di primo piano.<br/>            Gli 8 bit più significativi senza segno di un valore di operazione raster ternario a 24 bit dalla enumerazione WMF Ternary Raster Operation. Questo <br/>            codice definisce come combinare i dati di colore di primo piano dei bitmap sorgente e di destinazione <br/>            e il modello di pennello. |


### Constructor: EmfRop4(dword_data) {#EmfRop4_dword_data_1}


```
 EmfRop4(dword_data) 
```

Inizializza una nuova istanza della classe [EmfRop4](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrop4/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dword_data | int | I dati dword. |

