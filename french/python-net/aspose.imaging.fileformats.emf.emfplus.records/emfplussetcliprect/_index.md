---
title: "Classe EmfPlusSetClipRect"
type: docs
weight: 470
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetcliprect/
---

**Summary:** The EmfPlusSetClipRect record combines the current clipping region with a rectangle.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetClipRect

**Inheritance:** EmfPlusClippingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusSetClipRect(source)](#EmfPlusSetClipRect_source_1) | Initialise une nouvelle instance de la classe [EmfPlusSetClipRect](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetcliprect/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| clip_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Obtient ou définit un objet EmfPlusRectF (section 2.2.2.39) qui définit le rectangle à<br/>            utiliser dans l'opération CombineMode. |
| cm | [EmfPlusCombineMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscombinemode/) | r/w | Obtient ou définit le CM (4 bits) : spécifie l'opération logique pour combiner deux régions. Voir l'énumération<br/>            CombineMode (section 2.1.1.4) pour la signification des valeurs. |
| data_size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui DOIT définir le nombre aligné sur 32 bits de<br/>            octets de données dans le champ RecordData qui suit. Ce nombre n'inclut pas l'en-tête d'enregistrement de 12 octets. |
| flags | int | r/w | Obtient ou définit un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont<br/>            l'opération doit être effectuée et sur la structure de l'enregistrement. |
| size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre aligné sur 32 bits d'octets<br/>            dans l'enregistrement complet, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |


### Constructor: EmfPlusSetClipRect(source) {#EmfPlusSetClipRect_source_1}


```
 EmfPlusSetClipRect(source) 
```

Initialise une nouvelle instance de la classe [EmfPlusSetClipRect](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetcliprect/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La source. |

