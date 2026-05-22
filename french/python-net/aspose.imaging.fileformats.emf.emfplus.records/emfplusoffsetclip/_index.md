---
title: "Classe EmfPlusOffsetClip"
type: docs
weight: 350
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusoffsetclip/
---

**Summary:** The EmfPlusOffsetClip record applies a translation transform on the current clipping region for the world space.<br/>            The new current clipping region is set to the result of the translation transform.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusOffsetClip

**Inheritance:** EmfPlusClippingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusOffsetClip(source)](#EmfPlusOffsetClip_source_1) | Initialise une nouvelle instance de la classe [EmfPlusOffsetClip](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusoffsetclip/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui DOIT définir le nombre aligné sur 32 bits de<br/>            octets de données dans le champ RecordData qui suit. Ce nombre n'inclut pas l'en-tête d'enregistrement de 12 octets. |
| dx | float | r/w | Obtient ou définit une valeur à virgule flottante de 32 bits qui spécifie le décalage horizontal pour la translation. |
| dy | float | r/w | Obtient ou définit une valeur à virgule flottante de 32 bits qui spécifie le décalage vertical pour la translation. |
| flags | int | r/w | Obtient ou définit un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont<br/>            l'opération doit être effectuée et sur la structure de l'enregistrement. |
| size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre aligné sur 32 bits d'octets<br/>            dans l'enregistrement complet, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |


### Constructor: EmfPlusOffsetClip(source) {#EmfPlusOffsetClip_source_1}


```
 EmfPlusOffsetClip(source) 
```

Initialise une nouvelle instance de la classe [EmfPlusOffsetClip](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusoffsetclip/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La source. |

