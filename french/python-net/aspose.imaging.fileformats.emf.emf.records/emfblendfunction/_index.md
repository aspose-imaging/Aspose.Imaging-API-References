---
title: "Classe EmfBlendFunction"
type: docs
weight: 90
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction/
---

**Summary:** A structure that specifies the blending operations for source and destination bitmaps.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfBlendFunction()](#EmfBlendFunction__1) | Initialise une nouvelle instance de la classe EmfBlendFunction |
| [EmfBlendFunction(dword_data)](#EmfBlendFunction_dword_data_2) | Initialise une nouvelle instance de la classe [EmfBlendFunction](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| alpha_format | [EmfBlendFunction+AlphaFormatEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction+alphaformatenum/) | r | Obtient une structure qui spécifie comment les pixels source et destination sont <br/>            interprétés par rapport à la transparence alpha. |
| blend_flags | System.Byte | r | Obtient les indicateurs de fusion.<br/>            Cette valeur DOIT être 0x00 et DOIT être ignorée. |
| blend_operation | System.Byte | r | Obtient le code d'opération de fusion. <br/>            La seule opération de fusion source et destination <br/>            qui a été définie est 0x00, ce qui indique que le bitmap source <br/>            DOIT être combiné avec le bitmap destination en fonction des valeurs de transparence alpha <br/>            des pixels source. Voir les équations suivantes pour plus de détails. |
| src_constant_alpha | System.Byte | r | Obtient un entier non signé de 8 bits qui spécifie la transparence alpha, <br/>            qui détermine la fusion des bitmaps source et destination. Cette valeur DOIT être <br/>            utilisée sur l'ensemble du bitmap source. La valeur minimale de transparence alpha, zéro, <br/>            correspond à complètement transparent, la valeur maximale, 0xFF, correspond à <br/>            complètement opaque. En pratique, une valeur de 0xFF indique que les valeurs alpha par pixel <br/>            déterminent la fusion des bitmaps source et destination. Voir les équations plus loin dans <br/>            cette section pour plus de détails. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [to_int()](#to_int__1) | Convertit la représentation sous forme de chaîne d'un nombre en entier. |


### Constructor: EmfBlendFunction() {#EmfBlendFunction__1}


```
 EmfBlendFunction() 
```

Initialise une nouvelle instance de la classe EmfBlendFunction

### Constructor: EmfBlendFunction(dword_data) {#EmfBlendFunction_dword_data_2}


```
 EmfBlendFunction(dword_data) 
```

Initialise une nouvelle instance de la classe [EmfBlendFunction](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dword_data | int | Les données dword. |

### Method: to_int() {#to_int__1}


```
 to_int() 
```

Convertit la représentation sous forme de chaîne d'un nombre en entier.

**Returns**

| Type | Description |
| :- | :- |
| int | La valeur DWORD de la structure. |


