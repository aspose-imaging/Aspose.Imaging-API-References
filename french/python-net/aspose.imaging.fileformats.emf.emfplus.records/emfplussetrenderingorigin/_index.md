---
title: "EmfPlusSetRenderingOrigin Classe"
type: docs
weight: 540
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetrenderingorigin/
---

**Summary:** The EmfPlusSetRenderingOrigin record specifies the rendering origin for graphics output.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetRenderingOrigin

**Inheritance:** EmfPlusPropertyRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusSetRenderingOrigin(source)](#EmfPlusSetRenderingOrigin_source_1) | Initialise une nouvelle instance de la classe [EmfPlusSetRenderingOrigin](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetrenderingorigin/) . |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui DOIT définir le nombre aligné sur 32 bits de<br/>            octets de données dans le champ RecordData qui suit. Ce nombre n'inclut pas l'en-tête d'enregistrement de 12 octets. |
| flags | int | r/w | Obtient ou définit un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont<br/>            l'opération doit être effectuée et sur la structure de l'enregistrement. |
| size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre aligné sur 32 bits d'octets<br/>            dans l'enregistrement complet, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |
| x | int | r/w | Obtient ou définit un entier non signé de 32 bits qui définit la valeur de la coordonnée horizontale de l'origine de rendu. |
| y | int | r/w | Obtient ou définit un entier non signé de 32 bits qui définit la valeur de la coordonnée verticale de l'origine de rendu. |


### Constructor: EmfPlusSetRenderingOrigin(source) {#EmfPlusSetRenderingOrigin_source_1}


```
 EmfPlusSetRenderingOrigin(source) 
```

Initialise une nouvelle instance de la classe [EmfPlusSetRenderingOrigin](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetrenderingorigin/) .

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La source. |

