---
title: "Classe EmfPlusBeginContainer"
type: docs
weight: 10
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/
---

**Summary:** The EmfPlusBeginContainer record opens a new graphics state container and specifies a transform for it.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusBeginContainer

**Inheritance:** EmfPlusStateRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusBeginContainer(source)](#EmfPlusBeginContainer_source_1) | Initialise une nouvelle instance de la classe [EmfPlusBeginContainer](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/) |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui DOIT définir le nombre aligné sur 32 bits de<br/>            octets de données dans le champ RecordData qui suit. Ce nombre n'inclut pas l'en-tête d'enregistrement de 12 octets. |
| dest_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Obtient ou définit un objet EmfPlusRectF (section 2.2.2.39) qui, avec SrcRect, spécifie<br/>            une transformation pour le conteneur. Cette transformation donne SrcRect lorsqu'elle est appliquée à DestRect. |
| flags | int | r/w | Obtient ou définit un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont<br/>            l'opération doit être effectuée et sur la structure de l'enregistrement. |
| page_unit | [EmfPlusUnitType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusunittype/) | r | Obtient l'unité de page. |
| size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre aligné sur 32 bits d'octets<br/>            dans l'enregistrement complet, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Obtient ou définit un rectangle EmfPlusRectF qui, avec DestRect, spécifie une transformation<br/>            pour le conteneur. Cette transformation donne SrcRect lorsqu'elle est appliquée à DestRect. |
| stack_index | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie un indice à associer au<br/> conteneur d'état graphique. L'indice DOIT être référencé par un enregistrement EmfPlusEndContainer subséquent (section 2.3.7.3) pour fermer le conteneur d'état graphique. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |


### Constructor: EmfPlusBeginContainer(source) {#EmfPlusBeginContainer_source_1}


```
 EmfPlusBeginContainer(source) 
```

Initialise une nouvelle instance de la classe [EmfPlusBeginContainer](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/)

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La source. |

