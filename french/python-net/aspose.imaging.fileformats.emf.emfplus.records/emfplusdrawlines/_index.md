---
title: "Classe EmfPlusDrawLines"
type: docs
weight: 150
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/
---

**Summary:** The EmfPlusDrawlLines record specifies drawing a series of connected lines

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawLines

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusDrawLines(source)](#EmfPlusDrawLines_source_1) | Initialise une nouvelle instance de la classe [EmfPlusDrawLines](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| closed_shape | bool | r/w | Obtient ou définit une valeur indiquant si [closed shape]. |
| compressed | bool | r/w | Obtient ou définit une valeur indiquant si cet [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) est compressé.<br/>            Ce bit indique si le champ PointData spécifie des données compressées.<br/>            Si le bit est défini, PointData spécifie des emplacements absolus dans l'espace de coordonnées avec des coordonnées entières de 16 bits. <br/>            Si le bit est effacé, PointData spécifie des emplacements absolus dans l'espace de coordonnées avec des coordonnées à virgule flottante de 32 bits<br/>            Remarque : si le drapeau Relative (ci‑dessus) est défini, ce drapeau est indéfini et DOIT être ignoré |
| data_size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui DOIT définir le nombre aligné sur 32 bits de<br/>            octets de données dans le champ RecordData qui suit. Ce nombre n'inclut pas l'en-tête d'enregistrement de 12 octets. |
| flags | int | r/w | Obtient ou définit un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont<br/>            l'opération doit être effectuée et sur la structure de l'enregistrement. |
| object_id | System.Byte | r/w | Obtient ou définit l'identifiant de l'objet.<br/>            L'index d'un objet EmfPlusPen (section 2.2.1.7) dans la table d'objets EMF+<br/>            pour tracer les lignes. La valeur DOIT être comprise entre 0 et 63, inclus. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Obtient ou définit les données de points<br/>            Un tableau de points Count qui spécifient les points de départ et d'arrivée des lignes à tracer. |
| relative | bool | r/w | Obtient ou définit une valeur indiquant si cet [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) est relatif.<br/>            Ce bit indique si le champ PointData spécifie des emplacements relatifs ou absolus.<br/>            Si le bit est défini, chaque élément de PointData spécifie un emplacement dans l'espace de coordonnées qui est relatif <br/>            à l'emplacement spécifié par l'élément précédent du tableau. Dans le cas du premier <br/>            élément de PointData, un emplacement précédent aux coordonnées (0,0) est supposé. Si le bit est effacé, <br/>            PointData spécifie des emplacements absolus selon le drapeau C.<br/>            Remarque : si ce drapeau est défini, le drapeau Compressed (ci‑dessus) est indéfini et DOIT être ignoré |
| size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre aligné sur 32 bits d'octets<br/>            dans l'enregistrement complet, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |


### Constructor: EmfPlusDrawLines(source) {#EmfPlusDrawLines_source_1}


```
 EmfPlusDrawLines(source) 
```

Initialise une nouvelle instance de la classe [EmfPlusDrawLines](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La source. |

