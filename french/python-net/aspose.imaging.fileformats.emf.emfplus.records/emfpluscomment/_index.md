---
title: "Classe EmfPlusComment"
type: docs
weight: 50
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfpluscomment/
---

**Summary:** The EmfPlusComment record specifies arbitrary private data.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusComment

**Inheritance:** EmfPlusRecord

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusComment(source)](#EmfPlusComment_source_1) | Initialise une nouvelle instance de la classe [EmfPlusComment](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfpluscomment/) |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui DOIT définir le nombre aligné sur 32 bits de<br/>            octets de données dans le champ RecordData qui suit. Ce nombre n'inclut pas l'en-tête d'enregistrement de 12 octets. |
| flags | int | r/w | Obtient ou définit un entier non signé de 16 bits qui n'est pas utilisé. Ce champ DOIT être mis à zéro<br/>            et DOIT être ignoré lors de la réception. |
| private_data | System.Byte | r/w | Obtient ou définit un tableau d'octets de longueur DataSize contenant des données privées.<br/> octets de données spécifiques à l'enregistrement qui suivent. |
| size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre aligné sur 32 bits d'octets<br/>            dans l'enregistrement complet, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |


### Constructor: EmfPlusComment(source) {#EmfPlusComment_source_1}


```
 EmfPlusComment(source) 
```

Initialise une nouvelle instance de la classe [EmfPlusComment](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfpluscomment/)

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La source. |

