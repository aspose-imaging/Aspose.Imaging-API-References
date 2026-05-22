---
title: "Classe EmfPlusFillRegion"
type: docs
weight: 290
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillregion/
---

**Summary:** The EmfPlusFillRegion record specifies filling the interior of a graphics region

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillRegion

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusFillRegion(source)](#EmfPlusFillRegion_source_1) | Initialise une nouvelle instance de la classe [EmfPlusFillRegion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillregion/) |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Obtient ou définit l'identifiant du pinceau<br/>            Un entier non signé de 32 bits qui définit le pinceau, dont le contenu est déterminé par le bit S dans le champ Flags. |
| data_size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui DOIT définir le nombre aligné sur 32 bits de<br/>            octets de données dans le champ RecordData qui suit. Ce nombre n'inclut pas l'en-tête d'enregistrement de 12 octets. |
| flags | int | r/w | Obtient ou définit un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont<br/>            l'opération doit être effectuée et sur la structure de l'enregistrement. |
| is_color | bool | r/w | Obtient ou définit une valeur indiquant si cette instance est une couleur.<br/>            Si définie, BrushId spécifie une couleur sous forme d'un objet EmfPlusARGB (section 2.2.2.1). <br/>            Si non définie, BrushId contient l'index d'un objet EmfPlusBrush (section 2.2.1.1) dans la table d'objets EMF+. |
| object_id | System.Byte | r/w | Obtient ou définit l'identifiant de l'objet.<br/> L'index de l'objet EmfPlusRegion (section 2.2.1.8) à remplir, dans la<br/> table d'objets EMF+. La valeur DOIT être comprise entre 0 et 63, inclus. |
| size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre aligné sur 32 bits d'octets<br/>            dans l'enregistrement complet, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |


### Constructor: EmfPlusFillRegion(source) {#EmfPlusFillRegion_source_1}


```
 EmfPlusFillRegion(source) 
```

Initialise une nouvelle instance de la classe [EmfPlusFillRegion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillregion/)

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La source. |

