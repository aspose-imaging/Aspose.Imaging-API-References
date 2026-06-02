---
title: "Classe EmfPlusScaleWorldTransform"
type: docs
weight: 430
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/
---

**Summary:** The EmfPlusScaleWorldTransform record performs a scaling on the current world space transform.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusScaleWorldTransform

**Inheritance:** EmfPlusTerminalServerRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusScaleWorldTransform(source)](#EmfPlusScaleWorldTransform_source_1) | Initialise une nouvelle instance de la classe [EmfPlusScaleWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/) |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui DOIT définir le nombre aligné sur 32 bits de<br/>            octets de données dans le champ RecordData qui suit. Ce nombre n'inclut pas l'en-tête d'enregistrement de 12 octets. |
| flags | int | r/w | Obtient ou définit un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont<br/>            l'opération doit être effectuée et sur la structure de l'enregistrement. |
| post_multiplied_matrix | bool | r | Obtient une valeur indiquant si [post multiplied matrix].<br/>            Si définie, la matrice de transformation doit être post-multipliée. Si non définie, elle doit être pré-multipliée. |
| size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre aligné sur 32 bits d'octets<br/>            dans l'enregistrement complet, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| sx | float | r/w | Obtient ou définit une valeur à virgule flottante 32 bits qui définit le facteur d'échelle horizontal. Le redimensionnement<br/>            est effectué en construisant une nouvelle matrice de transformation à partir des valeurs des champs Sx et Sy, comme<br/>            indiqué dans le tableau suivant.<br/>            -----------------<br/> | Sx | 0 | 0 | <br/> | 0 | Sx | 0 | <br/>            -----------------<br/>            Figure 3 : Matrice de transformation d'échelle |
| sy | float | r/w | Obtient ou définit une valeur à virgule flottante 32 bits qui définit le facteur d'échelle vertical. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |


### Constructor: EmfPlusScaleWorldTransform(source) {#EmfPlusScaleWorldTransform_source_1}


```
 EmfPlusScaleWorldTransform(source) 
```

Initialise une nouvelle instance de la classe [EmfPlusScaleWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/)

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La source. |

