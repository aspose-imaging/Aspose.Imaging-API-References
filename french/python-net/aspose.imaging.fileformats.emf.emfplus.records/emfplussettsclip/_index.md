---
title: "EmfPlusSetTsClip Class"
type: docs
weight: 570
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/
---

**Summary:** The EmfPlusSetTSClip record specifies clipping areas in the graphics device context for a terminal server.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetTsClip

**Inheritance:** EmfPlusTerminalServerRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusSetTsClip(source)](#EmfPlusSetTsClip_source_1) | Initialise une nouvelle instance de la classe [EmfPlusSetTsClip](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| compressed | bool | r | Obtient une valeur indiquant si ce [EmfPlusSetTsClip](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/) est compressé.<br/> Ce bit spécifie le format des données de rectangle dans le champ rects. Si le bit est défini, chaque<br/> rectangle est défini sur 4 octets. Si le bit n'est pas défini, chaque rectangle est défini sur 8 octets. |
| data_size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui DOIT définir le nombre aligné sur 32 bits de<br/>            octets de données dans le champ RecordData qui suit. Ce nombre n'inclut pas l'en-tête d'enregistrement de 12 octets. |
| flags | int | r/w | Obtient ou définit un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont<br/>            l'opération doit être effectuée et sur la structure de l'enregistrement. |
| num_rects | int | r | Obtient le nombre de rectangles.<br/> Ce champ spécifie le nombre de rectangles définis dans le champ rect. |
| rects | [Rectangle[]](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtient ou définit un tableau de rectangles NumRects qui définissent les zones de découpage. Le format de<br/> ces données est déterminé par le bit C dans le champ Flags. |
| size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre aligné sur 32 bits d'octets<br/>            dans l'enregistrement complet, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |


### Constructor: EmfPlusSetTsClip(source) {#EmfPlusSetTsClip_source_1}


```
 EmfPlusSetTsClip(source) 
```

Initialise une nouvelle instance de la classe [EmfPlusSetTsClip](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La source. |

