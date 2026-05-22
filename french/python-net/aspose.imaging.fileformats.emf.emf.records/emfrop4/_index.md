---
title: "Classe EmfRop4"
type: docs
weight: 1010
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfrop4/
---

**Summary:** A quaternary raster operation, which specifies ternary raster operations for <br/>            the foreground and background colors of a bitmap. These values define how the color data of <br/>            the source rectangle is to be combined with the color data of the destination rectangle.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfRop4

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfRop4(dword_data)](#EmfRop4_dword_data_1) | Initialise une nouvelle instance de la classe [EmfRop4](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrop4/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| background_rop3 | System.Byte | r | Obtient le ROP3 d'arrière-plan.<br/>            Les 8 bits les plus significatifs non signés d'une valeur d'opération raster ternaire de 24 bits provenant de l'énumération WMF Ternary Raster Operation ([MS-WMF] section 2.1.1.31). Ce code définit comment combiner les données de couleur d'arrière-plan des images source et destination ainsi que le motif de brosse. |
| foreground_rop3 | System.Byte | r | Obtient le ROP3 de premier plan.<br/>            Les 8 bits les plus significatifs non signés d'une valeur d'opération raster ternaire de 24 bits provenant de l'énumération WMF Ternary Raster Operation. Ce <br/>            code définit comment combiner les données de couleur de premier plan des images source et destination ainsi que le motif de brosse. |


### Constructor: EmfRop4(dword_data) {#EmfRop4_dword_data_1}


```
 EmfRop4(dword_data) 
```

Initialise une nouvelle instance de la classe [EmfRop4](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrop4/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dword_data | int | Les données dword. |

