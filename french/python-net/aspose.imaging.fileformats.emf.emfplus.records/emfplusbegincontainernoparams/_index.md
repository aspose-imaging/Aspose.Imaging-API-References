---
title: "Classe EmfPlusBeginContainerNoParams"
type: docs
weight: 20
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainernoparams/
---

**Summary:** The EmfPlusBeginContainerNoParams record opens a new graphics state container.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusBeginContainerNoParams

**Inheritance:** EmfPlusStateRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusBeginContainerNoParams(source)](#EmfPlusBeginContainerNoParams_source_1) | Initialise une nouvelle instance de la classe [EmfPlusBeginContainerNoParams](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainernoparams/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui DOIT définir le nombre aligné sur 32 bits de<br/>            octets de données dans le champ RecordData qui suit. Ce nombre n'inclut pas l'en-tête d'enregistrement de 12 octets. |
| flags | int | r/w | Obtient ou définit un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont<br/>            l'opération doit être effectuée et sur la structure de l'enregistrement. |
| size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre aligné sur 32 bits d'octets<br/>            dans l'enregistrement complet, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| stack_index | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie un indice à associer au<br/> conteneur d'état graphique. L'indice DOIT être référencé par un enregistrement EmfPlusEndContainer subséquent (section 2.3.7.3) pour fermer le conteneur d'état graphique. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |


### Constructor: EmfPlusBeginContainerNoParams(source) {#EmfPlusBeginContainerNoParams_source_1}


```
 EmfPlusBeginContainerNoParams(source) 
```

Initialise une nouvelle instance de la classe [EmfPlusBeginContainerNoParams](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainernoparams/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La source. |

