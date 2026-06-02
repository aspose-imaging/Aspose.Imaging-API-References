---
title: "Classe EmfPlusDrawClosedCurve"
type: docs
weight: 90
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/
---

**Summary:** The EmfPlusDrawClosedCurve record specifies drawing a closed cardinal spline

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawClosedCurve

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusDrawClosedCurve(source)](#EmfPlusDrawClosedCurve_source_1) | Initialise une nouvelle instance de la classe [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/).<br/>            RecordType - Un entier non signé de 16 bits qui identifie ce type d'enregistrement comme EmfPlusDrawClosedCurve<br/>            provenant de l'énumération RecordType (section 2.1.1.1). La valeur DOIT être 0x4017. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| compressed | bool | r/w | Obtient ou définit une valeur indiquant si cet [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) est compressé.<br/>            Ce bit indique si le champ PointData spécifie des données compressées.<br/>            Si le bit est défini, PointData spécifie des emplacements absolus dans l'espace de coordonnées avec des coordonnées entières de 16 bits. <br/>            Si le bit est effacé, PointData spécifie des emplacements absolus dans l'espace de coordonnées avec des coordonnées à virgule flottante de 32 bits<br/>            Remarque : si le drapeau Relative (ci‑dessus) est défini, ce drapeau est indéfini et DOIT être ignoré |
| data_size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui DOIT définir le nombre aligné sur 32 bits de<br/>            octets de données dans le champ RecordData qui suit. Ce nombre n'inclut pas l'en-tête d'enregistrement de 12 octets. |
| flags | int | r/w | Obtient ou définit un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont<br/>            l'opération doit être effectuée et sur la structure de l'enregistrement. |
| object_id | System.Byte | r/w | Obtient ou définit l'identifiant de l'objet.<br/>            L'index d'un objet EmfPlusPen (section 2.2.1.7) dans la table d'objets EMF+<br/>            pour tracer la courbe fermée. La valeur DOIT être comprise entre 0 et 63, inclus. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Obtient ou définit les données de points<br/>            Un tableau de Count points qui spécifient les extrémités des lignes définissant la spline. Dans une spline cardinal fermée, <br/>            la courbe continue à travers le dernier point du tableau PointData et se connecte au premier point du tableau.<br/>            Le type de données dans ce tableau est indiqué par le champ Flags, comme suit : Type de données Signification<br/>            objet EmfPlusPointR (section 2.2.2.37)<br/>            Si le drapeau P est activé dans Flags, les points spécifient des positions relatives.<br/>            objet EmfPlusPointF (section 2.2.2.36)<br/>            Si les bits P et C sont activés dans le champ Flags, les points spécifient des positions absolues.<br/>            objet EmfPlusPoint (section 2.2.2.35)<br/>            Si le bit P est désactivé et le bit C activé dans le champ Flags, les points spécifient des positions relatives. |
| relative | bool | r/w | Obtient ou définit une valeur indiquant si cet [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) est relatif.<br/>            Ce bit indique si le champ PointData spécifie des emplacements relatifs ou absolus.<br/>            Si le bit est défini, chaque élément de PointData spécifie un emplacement dans l'espace de coordonnées qui est relatif <br/>            à l'emplacement spécifié par l'élément précédent du tableau. Dans le cas du premier <br/>            élément de PointData, un emplacement précédent aux coordonnées (0,0) est supposé. Si le bit est effacé, <br/>            PointData spécifie des emplacements absolus selon le drapeau C.<br/>            Remarque : si ce drapeau est défini, le drapeau Compressed (ci‑dessus) est indéfini et DOIT être ignoré |
| size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre aligné sur 32 bits d'octets<br/>            dans l'enregistrement complet, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| tension | float | r/w | Obtient ou définit la tension<br/>            Un nombre à virgule flottante de 32 bits qui indique à quel point la spline <br/>            se plie lorsqu'elle passe par les points. Une valeur de 0 indique que <br/>            la spline est une séquence de lignes droites. À mesure que la valeur augmente, <br/>            la courbe devient plus arrondie. Pour plus d'informations, voir [SPLINE77] et [PETZOLD]. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |


### Constructor: EmfPlusDrawClosedCurve(source) {#EmfPlusDrawClosedCurve_source_1}


```
 EmfPlusDrawClosedCurve(source) 
```

Initialise une nouvelle instance de la classe [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/).<br/>            RecordType - Un entier non signé de 16 bits qui identifie ce type d'enregistrement comme EmfPlusDrawClosedCurve<br/>            provenant de l'énumération RecordType (section 2.1.1.1). La valeur DOIT être 0x4017.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La source. |

