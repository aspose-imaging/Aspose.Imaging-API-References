---
title: "Classe EmfPlusDrawImage"
type: docs
weight: 130
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/
---

**Summary:** The EmfPlusDrawImage record specifies drawing a scaled image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawImage

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusDrawImage(source)](#EmfPlusDrawImage_source_1) | Initialise une nouvelle instance de la classe [EmfPlusDrawImage](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/) |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| compressé | bool | r/w | Obtient ou définit une valeur indiquant si le PointData est compressé.<br/>            Si définie, RectData contient un objet EmfPlusRect (section 2.2.2.38).<br/>            Si non définie, RectData contient un objet EmfPlusRectF (section 2.2.2.39). |
| data_size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui DOIT définir le nombre aligné sur 32 bits de<br/>            octets de données dans le champ RecordData qui suit. Ce nombre n'inclut pas l'en-tête d'enregistrement de 12 octets. |
| flags | int | r/w | Obtient ou définit un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont<br/>            l'opération doit être effectuée et sur la structure de l'enregistrement. |
| image_attributes_id | int | r/w | Obtient ou définit l'identifiant des attributs d'image<br/> Un entier non signé de 32 bits qui spécifie l'index d'un objet EmfPlusImageAttributes optionnel (section 2.2.1.5) dans la table d'objets EMF+. |
| object_id | System.Byte | r/w | Obtient ou définit l'identifiant de l'objet.<br/>            L'index d'un objet EmfPlusImage (section 2.2.1.4) dans la table d'objets EMF+, qui spécifie l'image à rendre. La valeur DOIT être comprise entre 0 et 63, inclus. |
| rect_data | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Obtient ou définit les données du rectangle<br/> Un objet EmfPlusRect ou EmfPlusRectF qui définit la boîte englobante de l'image.<br/> La partie de l'image spécifiée par le champ SrcRect est mise à l'échelle pour s'adapter à ce rectangle. |
| size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre aligné sur 32 bits d'octets<br/>            dans l'enregistrement complet, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Obtient ou définit le rectangle source<br/> Un objet EmfPlusRectF qui spécifie une partie de l'image à rendre.<br/> La partie de l'image spécifiée par ce rectangle est mise à l'échelle pour s'adapter au rectangle de destination<br/> spécifié par le champ RectData. |
| src_unit | [EmfPlusUnitType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusunittype/) | r/w | Obtient ou définit l'unité source<br/> Un entier signé de 32 bits qui spécifie les unités du champ SrcRect.<br/> Il DOIT être le membre UnitTypePixel de l'énumération UnitType (section 2.1.1.33). |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |


### Constructor: EmfPlusDrawImage(source) {#EmfPlusDrawImage_source_1}


```
 EmfPlusDrawImage(source) 
```

Initialise une nouvelle instance de la classe [EmfPlusDrawImage](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/)

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La source. |

