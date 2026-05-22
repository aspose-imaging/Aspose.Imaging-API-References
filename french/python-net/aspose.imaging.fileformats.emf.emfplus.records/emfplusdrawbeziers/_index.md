---
title: "Classe EmfPlusDrawBeziers"
type: docs
weight: 80
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/
---

**Summary:** The EmfPlusDrawBeziers record specifies drawing a sequence of connected Bezier curves. <br/>            The order for Bezier data points is the start point, control point 1, <br/>            control point 2 and end point. For more information see [MSDN-DrawBeziers].

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawBeziers

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusDrawBeziers(source)](#EmfPlusDrawBeziers_source_1) | Initialise une nouvelle instance de la classe [EmfPlusDrawBeziers](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/) . |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| compressé | bool | r/w | Obtient ou définit une valeur indiquant si le PointData est compressé. <br/>            Si défini, PointData spécifie des emplacements absolus dans l'espace de coordonnées avec <br/>            des coordonnées entières de 16 bits. Si non défini, PointData spécifie des emplacements <br/>            absolus dans l'espace de coordonnées avec des coordonnées à virgule flottante de 32 bits.<br/>            Remarque : si le drapeau Relative (ci‑dessous) est défini, ce drapeau est indéfini et DOIT être ignoré. |
| data_size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui DOIT définir le nombre aligné sur 32 bits de<br/>            octets de données dans le champ RecordData qui suit. Ce nombre n'inclut pas l'en-tête d'enregistrement de 12 octets. |
| flags | int | r/w | Obtient ou définit un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont<br/>            l'opération doit être effectuée et sur la structure de l'enregistrement. |
| object_id | System.Byte | r/w | Obtient ou définit l'identifiant de l'objet.<br/>            L'index d'un objet EmfPlusPen (section 2.2.1.7) dans la table d'objets EMF+<br/>            pour dessiner les courbes de Bézier. La valeur DOIT être comprise entre 0 et 63, inclus. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Obtient ou définit les données de points<br/>            Un tableau de points Count qui spécifient les points de départ, d'arrivée et de contrôle des courbes de Bézier. La coordonnée d'arrivée d'une courbe de Bézier est la coordonnée de départ de la suivante. Les points de contrôle sont utilisés pour produire l'effet Bézier.<br/>            Le type de données dans ce tableau est spécifié par le champ Flags, comme suit : Type de données Signification<br/>            Objet EmfPlusPointR (section 2.2.2.37)<br/>            Si le drapeau P est défini dans Flags, les points spécifient des emplacements relatifs.<br/>            Objet EmfPlusPointF (section 2.2.2.36)<br/>            Si les bits P et C sont non définis dans le champ Flags, les points spécifient des emplacements absolus.<br/>            Objet EmfPlusPoint (section 2.2.2.35)<br/>            Si le bit P est non défini et le bit C est défini dans le champ Flags, les points spécifient des emplacements relatifs.<br/>            Une courbe de Bézier ne passe pas par ses points de contrôle. Les points de contrôle agissent comme |
| relative | bool | r/w | Obtient ou définit une valeur indiquant si le PointData est relatif.<br/>            Si défini, chaque élément du PointData spécifie un emplacement dans l'espace de coordonnées <br/>            qui est relatif à l'emplacement spécifié par l'élément précédent du tableau. <br/>            Dans le cas du premier élément du PointData, un emplacement précédent aux coordonnées <br/>            (0,0) est supposé. Si non défini, le PointData spécifie des emplacements absolus selon le drapeau C.<br/>            Remarque : Si ce drapeau est défini, le drapeau C (ci‑dessus) est indéfini et DOIT être ignoré. |
| size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre aligné sur 32 bits d'octets<br/>            dans l'enregistrement complet, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |


### Constructor: EmfPlusDrawBeziers(source) {#EmfPlusDrawBeziers_source_1}


```
 EmfPlusDrawBeziers(source) 
```

Initialise une nouvelle instance de la classe [EmfPlusDrawBeziers](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/) .

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La source. |

