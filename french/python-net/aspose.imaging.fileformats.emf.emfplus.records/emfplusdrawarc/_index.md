---
title: "EmfPlusDrawArc Classe"
type: docs
weight: 70
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/
---

**Summary:** The EmfPlusDrawArc record specifies drawing the arc of an ellipse.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawArc

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusDrawArc(source)](#EmfPlusDrawArc_source_1) | Initialise une nouvelle instance de la classe [EmfPlusDrawArc](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/) . |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Obtient ou définit la taille des données.<br/>            Un entier non signé de 32 bits qui spécifie le nombre d'octets alignés sur 32 bits des<br/>            données spécifiques à l'enregistrement qui suivent.<br/>            Pour ce type d'enregistrement, la valeur DOIT être l'une des suivantes :<br/>            0x00000010 si le bit C est activé dans le champ Flags.<br/>            0x00000018 si le bit C est désactivé dans le champ Flags. |
| flags | int | r/w | Obtient ou définit un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont<br/>            l'opération doit être effectuée et sur la structure de l'enregistrement. |
| object_id | System.Byte | r/w | Obtient ou définit l'identifiant de l'objet.<br/>            L'index d'un objet EmfPlusPen (section 2.2.1.7) dans la<br/>            table d'objets EMF+ pour dessiner l'arc. La valeur DOIT être comprise entre 0 et 63, inclusivement. |
| rect_float | bool | r/w | Obtient ou définit une valeur indiquant si les données contiennent <br/>            des enregistrements EmfPlusRectF ou EmfPlusRect<br/>            Ce bit indique si les données du champ RectData sont compressées.<br/>            Si le bit est activé, RectData contient un objet EmfPlusRect (section 2.2.2.38).<br/>            Si le bit est désactivé, RectData contient un objet EmfPlusRectF (section 2.2.2.39). |
| rectangle_data | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Obtient ou définit les données du rectangle<br/>            Soit un objet EmfPlusRect ou EmfPlusRectF qui définit la boîte englobante<br/>            de l'ellipse colinéaire avec l'arc. Ce rectangle définit la<br/>            position, la taille et la forme de l'arc. Le type d'objet dans ce champ est<br/>            spécifié par la valeur du champ Flags. |
| size | int | r/w | Obtient ou définit la taille.<br/>            Un entier non signé de 32 bits qui spécifie le nombre d'octets alignés sur 32 bits de<br/>            l'enregistrement complet, y compris l'en-tête d'enregistrement de 12 octets et<br/>            les données spécifiques à l'enregistrement. Pour ce type d'enregistrement, la valeur DOIT être l'une des suivantes :<br/>            0x0000001C si le bit C est activé dans le champ Flags.<br/>            0x00000024 si le bit C est désactivé dans le champ Flags |
| start_angle | float | r/w | Obtient ou définit l'angle de départ<br/>            Une valeur flottante non négative de 32 bits qui spécifie l'angle entre<br/>            l'axe des x et le point de départ de l'arc. Toute valeur est acceptable,<br/>            mais elle DOIT être interprétée modulo 360, le résultat utilisé étant<br/>            dans l'intervalle de 0,0 inclus à 360,0 exclus. |
| sweep_angle | float | r/w | Obtient ou définit l'angle d'extension<br/>            Une valeur flottante de 32 bits qui spécifie l'étendue de l'arc à tracer,<br/>            en tant qu'angle en degrés mesuré depuis le point de départ défini par la<br/>            valeur StartAngle. Toute valeur est acceptable, mais elle DOIT être limitée à -360,0<br/>            à 360,0 inclus. Une valeur positive indique que le balayage est défini dans<br/>            le sens horaire, et une valeur négative indique que le balayage est<br/>            défini dans le sens antihoraire. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |


### Constructor: EmfPlusDrawArc(source) {#EmfPlusDrawArc_source_1}


```
 EmfPlusDrawArc(source) 
```

Initialise une nouvelle instance de la classe [EmfPlusDrawArc](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/) .

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La source. |

