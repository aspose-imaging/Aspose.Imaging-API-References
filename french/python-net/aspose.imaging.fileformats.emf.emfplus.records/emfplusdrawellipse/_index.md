---
title: "Classe EmfPlusDrawEllipse"
type: docs
weight: 120
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawellipse/
---

**Summary:** The EmfPlusDrawEllipse record specifies drawing an ellipse.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawEllipse

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusDrawEllipse(source)](#EmfPlusDrawEllipse_source_1) | Initialise une nouvelle instance de la classe [EmfPlusDrawEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawellipse/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| compressé | bool | r/w | Obtient ou définit une valeur indiquant si le PointData est compressé. <br/>            Si défini, RectData contient un objet EmfPlusRect (section 2.2.2.38). <br/>            Si non défini, RectData contient un objet EmfPlusRectF (section 2.2.2.39). |
| data_size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui DOIT définir le nombre aligné sur 32 bits de<br/>            octets de données dans le champ RecordData qui suit. Ce nombre n'inclut pas l'en-tête d'enregistrement de 12 octets. |
| flags | int | r/w | Obtient ou définit un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont<br/>            l'opération doit être effectuée et sur la structure de l'enregistrement. |
| object_id | System.Byte | r/w | Obtient ou définit l'identifiant de l'objet.<br/>            L'index d'un objet EmfPlusPen (section 2.2.1.7) dans la table d'objets EMF+<br/>            pour dessiner l'ellipse. La valeur DOIT être comprise entre 0 et 63, inclus. |
| rect_data | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Obtient ou définit les données du rectangle<br/>            Soit un objet EmfPlusRect, soit un objet EmfPlusRectF qui définit la boîte englobante de l'ellipse. |
| size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre aligné sur 32 bits d'octets<br/>            dans l'enregistrement complet, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |


### Constructor: EmfPlusDrawEllipse(source) {#EmfPlusDrawEllipse_source_1}


```
 EmfPlusDrawEllipse(source) 
```

Initialise une nouvelle instance de la classe [EmfPlusDrawEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawellipse/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La source. |

