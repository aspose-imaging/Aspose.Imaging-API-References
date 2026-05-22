---
title: "EmfPlusTranslateWorldTransform Classe"
type: docs
weight: 630
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplustranslateworldtransform/
---

**Summary:** The EmfPlusTranslateWorldTransform record performs a translation on the current world space transform.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTranslateWorldTransform

**Inheritance:** EmfPlusTerminalServerRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusTranslateWorldTransform(source)](#EmfPlusTranslateWorldTransform_source_1) | Initialise une nouvelle instance de la classe [EmfPlusTranslateWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplustranslateworldtransform/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui DOIT définir le nombre aligné sur 32 bits de<br/>            octets de données dans le champ RecordData qui suit. Ce nombre n'inclut pas l'en-tête d'enregistrement de 12 octets. |
| dx | float | r/w | Obtient ou définit une valeur flottante de 32 bits qui définit la distance horizontale. La translation<br/>            est effectuée en construisant une nouvelle matrice de transformation du monde à partir des champs dx et dy. |
| dy | float | r/w | Obtient ou définit une valeur flottante de 32 bits qui définit la valeur de la distance verticale. |
| flags | int | r/w | Obtient ou définit un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont<br/>            l'opération doit être effectuée et sur la structure de l'enregistrement. |
| post_multiplied_matrix | bool | r | Obtient une valeur indiquant si [post multiplied matrix].<br/>            Si le bit est défini, la matrice de transformation doit être post‑multipliée. Si le bit est effacé, elle doit être pré‑multipliée. |
| size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre aligné sur 32 bits d'octets<br/>            dans l'enregistrement complet, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |


### Constructor: EmfPlusTranslateWorldTransform(source) {#EmfPlusTranslateWorldTransform_source_1}


```
 EmfPlusTranslateWorldTransform(source) 
```

Initialise une nouvelle instance de la classe [EmfPlusTranslateWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplustranslateworldtransform/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La source. |

