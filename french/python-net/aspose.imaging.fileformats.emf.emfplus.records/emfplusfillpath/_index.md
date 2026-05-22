---
title: "EmfPlusFillPath Classe"
type: docs
weight: 250
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpath/
---

**Summary:** Fill path record<br/>            FLAGS:<br/>            16-bit unsigned integer that provides information about how the operation is to be performed,<br/>            and about the structure of the record.<br/>            0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1<br/>            S X X X X X X X |   ObjectId    |<br/>            S (1 bit): This bit indicates the type of data in the BrushId field.<br/>            If set, BrushId specifies a color as an EmfPlusARGB object (section 2.2.2.1). If clear, BrushId contains the index of an EmfPlusBrush object (section 2.2.1.1) in the EMF+ Object Table.<br/>            X (1 bit): Reserved and MUST be ignored.<br/>            ObjectId (1 byte): The index of the EmfPlusPath object (section 2.2.1.6) to fill, in the EMF+ Object Table. The value MUST be zero to 63, inclusive.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillPath

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusFillPath(source)](#EmfPlusFillPath_source_1) | Initialise une nouvelle instance de la classe [EmfPlusFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpath/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Obtient ou définit l'ID du pinceau<br/>            Un entier non signé de 32 bits qui définit le pinceau, le contenu dont la détermination dépend du bit S dans le champ Flags. |
| data_size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui DOIT définir le nombre aligné sur 32 bits de<br/>            octets de données dans le champ RecordData qui suit. Ce nombre n'inclut pas l'en-tête d'enregistrement de 12 octets. |
| flags | int | r/w | Obtient ou définit un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont<br/>            l'opération doit être effectuée et sur la structure de l'enregistrement. |
| is_color | bool | r/w | Obtient ou définit une valeur indiquant si cette instance est une couleur.<br/>            Si définie, BrushId spécifie une couleur sous forme d'un objet EmfPlusARGB (section 2.2.2.1). Si non définie,<br/>            BrushId contient l'index d'un objet EmfPlusBrush (section 2.2.1.1) dans la table d'objets EMF+. |
| object_id | System.Byte | r/w | Obtient ou définit l'identifiant de l'objet.<br/>            L'index de l'objet EmfPlusPath (section 2.2.1.6) à remplir, dans la<br/>            table d'objets EMF+. La valeur DOIT être comprise entre 0 et 63, inclus. |
| size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre aligné sur 32 bits d'octets<br/>            dans l'enregistrement complet, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |


### Constructor: EmfPlusFillPath(source) {#EmfPlusFillPath_source_1}


```
 EmfPlusFillPath(source) 
```

Initialise une nouvelle instance de la classe [EmfPlusFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpath/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La source. |

