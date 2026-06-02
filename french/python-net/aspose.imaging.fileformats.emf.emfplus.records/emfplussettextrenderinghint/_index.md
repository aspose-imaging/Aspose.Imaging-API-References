---
title: "Classe EmfPlusSetTextRenderingHint"
type: docs
weight: 560
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettextrenderinghint/
---

**Summary:** The EmfPlusSetTextRenderingHint record specifies the quality of text rendering, including the type of anti-aliasing.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetTextRenderingHint

**Inheritance:** EmfPlusPropertyRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusSetTextRenderingHint(source)](#EmfPlusSetTextRenderingHint_source_1) | Initialise une nouvelle instance de la classe [EmfPlusSetTextRenderingHint](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettextrenderinghint/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui DOIT définir le nombre aligné sur 32 bits de<br/>            octets de données dans le champ RecordData qui suit. Ce nombre n'inclut pas l'en-tête d'enregistrement de 12 octets. |
| flags | int | r/w | Obtient ou définit un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont<br/>            l'opération doit être effectuée et sur la structure de l'enregistrement. |
| size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre aligné sur 32 bits d'octets<br/>            dans l'enregistrement complet, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| text_rendering_hint | [EmfPlusTextRenderingHint](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplustextrenderinghint/) | r/w | Obtient ou définit la valeur du conseil de rendu du texte, à partir de l'énumération <br/>            TextRenderingHint (section 2.1.1.32), qui spécifie la qualité à<br/>            utiliser lors du rendu du texte ultérieur. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |


### Constructor: EmfPlusSetTextRenderingHint(source) {#EmfPlusSetTextRenderingHint_source_1}


```
 EmfPlusSetTextRenderingHint(source) 
```

Initialise une nouvelle instance de la classe [EmfPlusSetTextRenderingHint](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettextrenderinghint/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La source. |

