---
title: "EmfPlusFillPolygon Classe"
type: docs
weight: 270
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/
---

**Summary:** The EmfPlusFillPolygon record specifies filling the interior of a polygon.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillPolygon

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusFillPolygon(source)](#EmfPlusFillPolygon_source_1) | Initialise une nouvelle instance de la classe [EmfPlusFillPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Obtient ou définit l'identifiant du pinceau<br/>            Un entier non signé de 32 bits qui définit le pinceau, le contenu <br/>            dont la détermination dépend du bit S dans le champ Flags. |
| data_size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui DOIT définir le nombre aligné sur 32 bits de<br/>            octets de données dans le champ RecordData qui suit. Ce nombre n'inclut pas l'en-tête d'enregistrement de 12 octets. |
| flags | int | r/w | Obtient ou définit un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont<br/>            l'opération doit être effectuée et sur la structure de l'enregistrement. |
| is_color | bool | r/w | Obtient ou définit une valeur indiquant si cette instance est une couleur.<br/>            Si définie, BrushId spécifie une couleur sous forme d'un objet EmfPlusARGB (section 2.2.2.1). <br/>            Si non définie, BrushId contient l'index d'un objet EmfPlusBrush (section 2.2.1.1) dans la table d'objets EMF+. |
| is_compressed | bool | r/w | Obtient ou définit une valeur indiquant si cette instance est compressée.<br/>            Si définie, PointData spécifie des emplacements absolus dans l'espace de coordonnées avec des coordonnées entières de 16 bits. Si non définie, PointData spécifie des emplacements absolus dans l'espace de coordonnées avec des coordonnées à virgule flottante de 32 bits. |
| is_relative | bool | r/w | Obtient ou définit une valeur indiquant si cette instance est relative.<br/>            Si définie, chaque élément de PointData spécifie un emplacement dans l'espace de coordonnées qui est relatif à l'emplacement spécifié par l'élément précédent <br/>            du tableau. Dans le cas du premier élément de PointData, on suppose un emplacement précédent aux coordonnées (0,0). Si non définie, PointData spécifie <br/>            des emplacements absolus selon le C flag. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Obtient ou définit les données de point<br/>            Un tableau de Count points qui définissent les sommets du polygone. <br/>            Les deux premiers points du tableau spécifient le premier côté du polygone. <br/>            Chaque point supplémentaire spécifie un nouveau côté, dont les sommets <br/>            comprennent le point et le point précédent. Si le dernier point et le <br/>            premier point ne coïncident pas, ils spécifient le dernier côté du polygone. |
| size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre aligné sur 32 bits d'octets<br/>            dans l'enregistrement complet, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |


### Constructor: EmfPlusFillPolygon(source) {#EmfPlusFillPolygon_source_1}


```
 EmfPlusFillPolygon(source) 
```

Initialise une nouvelle instance de la classe [EmfPlusFillPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La source. |

