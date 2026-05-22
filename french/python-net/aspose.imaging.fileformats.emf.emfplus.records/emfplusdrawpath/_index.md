---
title: "Classe EmfPlusDrawPath"
type: docs
weight: 160
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpath/
---

**Summary:** The EmfPlusDrawPath record specifies drawing a graphics path.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawPath

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusDrawPath(source)](#EmfPlusDrawPath_source_1) | Initialise une nouvelle instance de la classe [EmfPlusDrawPath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpath/) |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui DOIT définir le nombre aligné sur 32 bits de<br/>            octets de données dans le champ RecordData qui suit. Ce nombre n'inclut pas l'en-tête d'enregistrement de 12 octets. |
| flags | int | r/w | Obtient ou définit un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont<br/>            l'opération doit être effectuée et sur la structure de l'enregistrement. |
| object_id | System.Byte | r/w | Obtient ou définit l'identifiant de l'objet.<br/> L'index de l'objet EmfPlusPath (section 2.2.1.6) à dessiner, dans la<br/> table d'objets EMF+. La valeur DOIT être comprise entre 0 et 63, inclus. |
| pen_id | int | r/w | Obtient ou définit l'identifiant du stylo<br/> Un entier non signé de 32 bits qui spécifie un index dans la table d'objets EMF+<br/> pour un objet EmfPlusPen (section 2.2.1.7) à utiliser pour dessiner le EmfPlusPath.<br/> La valeur DOIT être comprise entre 0 et 63, inclus. |
| size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre aligné sur 32 bits d'octets<br/>            dans l'enregistrement complet, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |


### Constructor: EmfPlusDrawPath(source) {#EmfPlusDrawPath_source_1}


```
 EmfPlusDrawPath(source) 
```

Initialise une nouvelle instance de la classe [EmfPlusDrawPath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpath/)

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La source. |

