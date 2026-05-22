---
title: "EmfPlusDrawPie Classe"
type: docs
weight: 170
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpie/
---

**Summary:** The EmfPlusDrawPie record specifies drawing a section of the interior of an ellipse.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawPie

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusDrawPie(source)](#EmfPlusDrawPie_source_1) | Initialise une nouvelle instance de la classe [EmfPlusDrawPie](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpie/) . |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| compressé | bool | r/w | Obtient ou définit une valeur indiquant si le PointData est compressé.<br/>            Si définie, RectData contient un objet EmfPlusRect (section 2.2.2.38).<br/>            Si non définie, RectData contient un objet EmfPlusRectF (section 2.2.2.39). |
| data_size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui DOIT définir le nombre aligné sur 32 bits de<br/>            octets de données dans le champ RecordData qui suit. Ce nombre n'inclut pas l'en-tête d'enregistrement de 12 octets. |
| flags | int | r/w | Obtient ou définit un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont<br/>            l'opération doit être effectuée et sur la structure de l'enregistrement. |
| object_id | System.Byte | r/w | Obtient ou définit l'identifiant de l'objet.<br/>            L'index d'un objet EmfPlusPen (section 2.2.1.7) dans la table d'objets EMF+<br/>            pour dessiner le secteur. La valeur DOIT être comprise entre 0 et 63, inclusivement. |
| rect_data | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Obtient ou définit les données du rectangle<br/>            Soit un objet EmfPlusRect ou EmfPlusRectF qui définit la boîte englobante de l'<br/>            ellipse contenant le secteur de tarte. Ce rectangle définit la position, la taille, <br/>            et la forme de la tarte. Le type d'objet dans ce champ est spécifié par la valeur <br/>            du champ Flags. |
| size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre aligné sur 32 bits d'octets<br/>            dans l'enregistrement complet, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| start_angle | float | r/w | Obtient ou définit l'angle de départ<br/>            Une valeur flottante 32 bits, non négative qui spécifie l'angle entre l'<br/>            axe des x et le point de départ du secteur de tarte. Toute valeur est acceptable, mais elle <br/>            DOIT être interprétée modulo 360, le résultat utilisé devant être dans l'intervalle <br/>            de 0,0 inclus à 360,0 exclus. |
| sweep_angle | float | r/w | Obtient ou définit l'angle d'arc<br/>            Une valeur flottante 32 bits qui spécifie l'étendue de l'arc qui définit <br/>            le secteur de tarte à dessiner, en tant qu'angle en degrés mesuré depuis le point de départ <br/>            défini par la valeur StartAngle. Toute valeur est acceptable, mais elle DOIT être limitée <br/>            à -360,0 à 360,0 inclus. Une valeur positive indique que l'arc est défini <br/>            dans le sens horaire, et une valeur négative indique qu'il est défini <br/>            dans le sens anti-horaire. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |


### Constructor: EmfPlusDrawPie(source) {#EmfPlusDrawPie_source_1}


```
 EmfPlusDrawPie(source) 
```

Initialise une nouvelle instance de la classe [EmfPlusDrawPie](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpie/) .

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La source. |

