---
title: "Classe EmfPlusSetPixelOffsetMode"
type: docs
weight: 530
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetpixeloffsetmode/
---

**Summary:** The EmfPlusSetPixelOffsetMode record specifies how pixels are centered with respect to the<br/>            coordinates of the drawing surface.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetPixelOffsetMode

**Inheritance:** EmfPlusPropertyRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusSetPixelOffsetMode(source)](#EmfPlusSetPixelOffsetMode_source_1) | Initialise une nouvelle instance de la classe [EmfPlusSetPixelOffsetMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetpixeloffsetmode/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui DOIT définir le nombre aligné sur 32 bits de<br/>            octets de données dans le champ RecordData qui suit. Ce nombre n'inclut pas l'en-tête d'enregistrement de 12 octets. |
| flags | int | r/w | Obtient ou définit un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont<br/>            l'opération doit être effectuée et sur la structure de l'enregistrement. |
| pixel_offset_mode | [EmfPlusPixelOffsetMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixeloffsetmode/) | r/w | Obtient ou définit la valeur du mode de décalage de pixel, à partir de l'énumération PixelOffsetMode<br/>            (section 2.1.1.26). |
| size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre aligné sur 32 bits d'octets<br/>            dans l'enregistrement complet, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |


### Constructor: EmfPlusSetPixelOffsetMode(source) {#EmfPlusSetPixelOffsetMode_source_1}


```
 EmfPlusSetPixelOffsetMode(source) 
```

Initialise une nouvelle instance de la classe [EmfPlusSetPixelOffsetMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetpixeloffsetmode/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La source. |

