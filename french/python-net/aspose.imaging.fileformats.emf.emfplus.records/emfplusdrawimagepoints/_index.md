---
title: "Classe EmfPlusDrawImagePoints"
type: docs
weight: 140
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/
---

**Summary:** The EmfPlusDrawImagePoints record specifies drawing a scaled image inside a parallelogram.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawImagePoints

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusDrawImagePoints(source)](#EmfPlusDrawImagePoints_source_1) | Initialise une nouvelle instance de la classe [EmfPlusDrawImagePoints](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/) . |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| applying_an_effect | bool | r/w | Obtient ou définit une valeur indiquant si [applying an effect].<br/>            Ce bit indique que le rendu de l'image comprend l'application d'un effet.<br/>            Si défini, un objet de la classe Effect DOIT avoir été spécifié dans un enregistrement EmfPlusSerializableObject antérieur (section 2.3.5.2). |
| compressé | bool | r/w | Obtient ou définit une valeur indiquant si le PointData est compressé.<br/>            Ce bit indique si le champ PointData spécifie des données compressées.<br/>            Si défini, PointData spécifie des emplacements absolus dans l'espace de coordonnées avec des coordonnées entières de 16 bits.<br/>            Si non défini, PointData spécifie des emplacements absolus dans l'espace de coordonnées avec des coordonnées à virgule flottante de 32 bits.<br/>            Remarque : si le drapeau P (ci‑dessous) est défini, ce drapeau est indéfini et DOIT être ignoré. |
| data_size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui DOIT définir le nombre aligné sur 32 bits de<br/>            octets de données dans le champ RecordData qui suit. Ce nombre n'inclut pas l'en-tête d'enregistrement de 12 octets. |
| flags | int | r/w | Obtient ou définit un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont<br/>            l'opération doit être effectuée et sur la structure de l'enregistrement. |
| image_attributes_id | int | r/w | Obtient ou définit un entier non signé de 32 bits contenant l'index de l'objet optionnel EmfPlusImageAttributes (section 2.2.1.5) dans la table d'objets EMF+. |
| object_id | System.Byte | r/w | Obtient ou définit l'identifiant de l'objet.<br/>            L'index d'un objet EmfPlusImage (section 2.2.1.4) dans la table d'objets EMF+, qui spécifie l'image à rendre. La valeur DOIT être comprise entre 0 et 63, inclus. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Obtient ou définit un tableau de points Count qui spécifient trois points d'un parallélogramme.<br/>            Les trois points représentent les coins supérieur gauche, supérieur droit et inférieur gauche du parallélogramme.<br/>            Le quatrième point du parallélogramme est extrapolé à partir des trois premiers.<br/>            La partie de l'image spécifiée par le champ SrcRect DOIT subir des transformations d'échelle et de cisaillement si nécessaire pour s'adapter à l'intérieur du parallélogramme. |
| relative | bool | r/w | Obtient ou définit une valeur indiquant si ce [EmfPlusDrawImagePoints](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/) est relatif.<br/>            Ce bit indique si le champ PointData spécifie des emplacements relatifs ou absolus.<br/>            Si défini, chaque élément de PointData spécifie un emplacement dans l'espace de coordonnées qui est<br/>            relatif à l'emplacement spécifié par l'élément précédent du tableau. Dans le cas du<br/>            premier élément de PointData, on suppose un emplacement précédent aux coordonnées (0,0). Si non défini,<br/>            PointData spécifie des emplacements absolus selon le drapeau C.<br/>            Remarque : si ce drapeau est défini, le drapeau C (ci‑dessus) est indéfini et DOIT être ignoré. |
| size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre aligné sur 32 bits d'octets<br/>            dans l'enregistrement complet, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Obtient ou définit un objet EmfPlusRectF (section 2.2.2.39) qui définit une partie de l'image à rendre. |
| src_unit | [EmfPlusUnitType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusunittype/) | r/w | Obtient ou définit un entier signé de 32 bits qui définit les unités du champ SrcRect. Il DOIT être la valeur UnitPixel de l'énumération UnitType (section 2.1.1.33). |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |


### Constructor: EmfPlusDrawImagePoints(source) {#EmfPlusDrawImagePoints_source_1}


```
 EmfPlusDrawImagePoints(source) 
```

Initialise une nouvelle instance de la classe [EmfPlusDrawImagePoints](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/) .

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La source. |

