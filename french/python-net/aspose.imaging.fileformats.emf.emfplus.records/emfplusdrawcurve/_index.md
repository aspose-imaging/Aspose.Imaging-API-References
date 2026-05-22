---
title: "Classe EmfPlusDrawCurve"
type: docs
weight: 100
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/
---

**Summary:** The EmfPlusDrawCurve record specifies drawing a cardinal spline<br/>            NOTE: ObjectID (1 byte): The index of an EmfPlusPen object (section 2.2.1.7)<br/>             in the EMF+ Object Table to draw the curve. The value MUST be zero to 63, inclusive.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawCurve

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusDrawCurve(source)](#EmfPlusDrawCurve_source_1) | Initialise une nouvelle instance de la classe [EmfPlusDrawCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/) |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| compressed | bool | r/w | Obtient ou définit une valeur indiquant si cet [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) est compressé.<br/>            Ce bit indique si le champ PointData spécifie des données compressées.<br/>            Si le bit est défini, PointData spécifie des emplacements absolus dans l'espace de coordonnées avec des coordonnées entières de 16 bits. <br/>            Si le bit est effacé, PointData spécifie des emplacements absolus dans l'espace de coordonnées avec des coordonnées à virgule flottante de 32 bits<br/>            Remarque : si le drapeau Relative (ci‑dessus) est défini, ce drapeau est indéfini et DOIT être ignoré |
| data_size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui DOIT définir le nombre aligné sur 32 bits de<br/>            octets de données dans le champ RecordData qui suit. Ce nombre n'inclut pas l'en-tête d'enregistrement de 12 octets. |
| flags | int | r/w | Obtient ou définit un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont<br/>            l'opération doit être effectuée et sur la structure de l'enregistrement. |
| num_segments | int | r/w | Obtient ou définit le nombre de segments <br/> Un entier non signé de 32 bits qui spécifie le nombre de segments de ligne composant la spline. |
| object_id | System.Byte | r/w | Obtient ou définit l'identifiant de l'objet.<br/> L'index d'un objet EmfPlusPen (section 2.2.1.7) dans la table d'objets EMF+<br/> pour dessiner la courbe. La valeur DOIT être comprise entre 0 et 63, inclus. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Obtient ou définit un tableau d'entiers signés de 32 bits ou de nombres à virgule flottante de 32 bits de longueur <br/> Count qui définit les valeurs de coordonnées des points d'extrémité des lignes à tracer. |
| size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre aligné sur 32 bits d'octets<br/>            dans l'enregistrement complet, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| tension | float | r/w | Obtient ou définit la tension<br/>            Un nombre à virgule flottante de 32 bits qui indique à quel point la spline <br/>            se plie lorsqu'elle passe par les points. Une valeur de 0 indique que <br/>            la spline est une séquence de lignes droites. À mesure que la valeur augmente, <br/>            la courbe devient plus arrondie. Pour plus d'informations, voir [SPLINE77] et [PETZOLD]. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |


### Constructor: EmfPlusDrawCurve(source) {#EmfPlusDrawCurve_source_1}


```
 EmfPlusDrawCurve(source) 
```

Initialise une nouvelle instance de la classe [EmfPlusDrawCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/)

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La source. |

