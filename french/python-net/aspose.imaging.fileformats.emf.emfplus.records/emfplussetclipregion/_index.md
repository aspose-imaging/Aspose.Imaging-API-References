---
title: "Classe EmfPlusSetClipRegion"
type: docs
weight: 480
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetclipregion/
---

**Summary:** The EmfPlusSetClipRegion record combines the current clipping region with another graphics region.<br/>            The new current clipping region is set to the result of performing the CombineMode operation on<br/>            the previous current clipping region and the specified EmfPlusRegion object.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetClipRegion

**Inheritance:** EmfPlusClippingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusSetClipRegion(source)](#EmfPlusSetClipRegion_source_1) | Initialise une nouvelle instance de la classe [EmfPlusSetClipRegion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetclipregion/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| cm | [EmfPlusCombineMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscombinemode/) | r/w | Obtient ou définit le CM (4 bits) : spécifie l'opération logique pour combiner deux régions. Voir l'énumération<br/>            CombineMode (section 2.1.1.4) pour la signification des valeurs. |
| data_size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui DOIT définir le nombre aligné sur 32 bits de<br/>            octets de données dans le champ RecordData qui suit. Ce nombre n'inclut pas l'en-tête d'enregistrement de 12 octets. |
| flags | int | r/w | Obtient ou définit un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont<br/>            l'opération doit être effectuée et sur la structure de l'enregistrement. |
| object_id | System.Byte | r/w | Obtient ou définit l'index d'un objet EmfPlusRegion (section 2.2.1.8) dans la table d'objets EMF+<br/>            La valeur DOIT être comprise entre 0 et 63, inclusivement. |
| size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre aligné sur 32 bits d'octets<br/>            dans l'enregistrement complet, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |


### Constructor: EmfPlusSetClipRegion(source) {#EmfPlusSetClipRegion_source_1}


```
 EmfPlusSetClipRegion(source) 
```

Initialise une nouvelle instance de la classe [EmfPlusSetClipRegion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetclipregion/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La source. |

