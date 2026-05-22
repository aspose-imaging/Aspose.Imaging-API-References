---
title: "Classe EmfPlusFillClosedCurve"
type: docs
weight: 230
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/
---

**Summary:** The EmfPlusFillClosedCurve record specifies filling the interior of a closed cardinal spline

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillClosedCurve

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusFillClosedCurve(source)](#EmfPlusFillClosedCurve_source_1) | Initialise une nouvelle instance de la classe [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Obtient ou définit l'identifiant du pinceau<br/>            Un entier non signé de 32 bits qui spécifie l'EmfPlusBrush, dont le contenu est <br/>            déterminé par le bit S dans le champ Flags. Ce pinceau est utilisé pour remplir l'intérieur <br/>            du spline cardinal fermé. |
| compressed | bool | r/w | Obtient ou définit une valeur indiquant si ce [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/) est compressé.<br/>            Ce bit indique si le champ PointData spécifie des données compressées.<br/>            Si défini, PointData spécifie des emplacements absolus dans l'espace de coordonnées avec des coordonnées entières de 16 bits. Si non défini, PointData spécifie des emplacements absolus dans l'espace de coordonnées avec des coordonnées à virgule flottante de 32 bits.<br/>            ----------------------<br/>            Une opération de remplissage "winding" remplit les zones selon la règle de la "parité pair‑impair".<br/>            Selon cette règle, un point de test peut être déterminé comme étant à l'intérieur ou à l'extérieur d'une courbe fermée comme suit : tracer une ligne du point de test vers un point distant de la courbe. Si cette ligne traverse la courbe un nombre impair de fois, le point de test est à l'intérieur de la courbe ; sinon, le point de test est à l'extérieur de la courbe.<br/>            ---------------------<br/>            Une opération de remplissage "alternate" remplit les zones selon la règle du "non‑zéro".<br/>            Selon cette règle, un point de test peut être déterminé comme étant à l'intérieur ou à l'extérieur d'une courbe fermée comme suit : tracer une ligne d'un point de test vers un point distant de la courbe. Compter le nombre de fois où la courbe traverse la ligne de test de gauche à droite, et le nombre de fois où la courbe traverse la ligne de test de droite à gauche. Si ces deux nombres sont identiques, le point de test est à l'extérieur de la courbe ; sinon, le point de test est à l'intérieur de la courbe. |
| data_size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui DOIT définir le nombre aligné sur 32 bits de<br/>            octets de données dans le champ RecordData qui suit. Ce nombre n'inclut pas l'en-tête d'enregistrement de 12 octets. |
| flags | int | r/w | Obtient ou définit un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont<br/>            l'opération doit être effectuée et sur la structure de l'enregistrement. |
| is_color | bool | r/w | Obtient ou définit une valeur indiquant si cette instance est en couleur.<br/> Si elle est définie, BrushId spécifie une couleur sous forme d'objet EmfPlusARGB (section 2.2.2.1).<br/> Si elle n'est pas définie, BrushId contient l'index d'un objet EmfPlusBrush <br/> (section 2.2.1.1) dans la table d'objets EMF+. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Obtient ou définit les données de points<br/>            Un tableau de points Count qui spécifient les extrémités des lignes définissant le spline. <br/>            Dans un spline cardinal fermé, la courbe continue à travers le dernier point du tableau PointData <br/>            et se connecte au premier point du tableau. |
| relative | bool | r/w | Obtient ou définit une valeur indiquant si ce [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/) est relatif.<br/>            Ce bit indique si le champ PointData spécifie des emplacements relatifs ou absolus.<br/>            Si défini, chaque élément du PointData spécifie un emplacement dans l'espace de coordonnées qui est<br/>            relatif à l'emplacement spécifié par l'élément précédent du tableau. Dans le cas <br/>            du premier élément du PointData, un emplacement précédent aux coordonnées (0,0) est supposé. <br/>            Si non défini, le PointData spécifie des emplacements absolus selon le drapeau C.<br/>            Remarque : Si ce drapeau est défini, le drapeau C (ci‑dessus) est indéfini et DOIT être ignoré. |
| size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre aligné sur 32 bits d'octets<br/>            dans l'enregistrement complet, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| tension | float | r/w | Obtient ou définit la tension<br/>            Une valeur à virgule flottante de 32 bits qui spécifie à quel point le spline se courbe lorsqu'il passe <br/>            à travers les points. Une valeur de 0,0 indique que le spline est une séquence de lignes droites. Au fur et à mesure que la valeur augmente, la courbe devient plus arrondie. Pour plus d'informations, <br/>            voir [SPLINE77] et [PETZOLD]. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |
| winding | bool | r/w | Obtient ou définit une valeur indiquant si ce [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/) utilise le mode "winding".<br/>            Ce bit indique comment effectuer l'opération de remplissage.<br/>            Si défini, le remplissage est de type "winding". Si non défini, le remplissage est de type "alternate". |


### Constructor: EmfPlusFillClosedCurve(source) {#EmfPlusFillClosedCurve_source_1}


```
 EmfPlusFillClosedCurve(source) 
```

Initialise une nouvelle instance de la classe [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La source. |

