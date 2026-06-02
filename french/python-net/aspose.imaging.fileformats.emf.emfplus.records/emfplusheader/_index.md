---
title: "Classe EmfPlusHeader"
type: docs
weight: 310
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/
---

**Summary:** The EmfPlusHeader record specifies the start of EMF+ data in the metafile.<br/>            The EmfPlusHeader record MUST be embedded in an EMF EMR_COMMENT_EMFPLUS record,<br/>             which MUST be the record immediately following the EMF header in the metafile. <br/>            The EMR_COMMENT_EMFPLUS record is specified in [MS-EMF] section 2.3.3.2.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusHeader

**Inheritance:** EmfPlusControlRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusHeader(source)](#EmfPlusHeader_source_1) | Initialise une nouvelle instance de la classe [EmfPlusHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui DOIT définir le nombre aligné sur 32 bits de<br/>            octets de données dans le champ RecordData qui suit. Ce nombre n'inclut pas l'en-tête d'enregistrement de 12 octets. |
| dual_mode | bool | r/w | Obtient ou définit une valeur indiquant si [dual mode].<br/> Si elle est définie, ce drapeau indique que ce métafichier est "dual-mode", ce qui signifie<br/> qu'il contient deux ensembles d'enregistrements, chacun spécifiant complètement <br/> le contenu graphique. Si elle est désactivée, le contenu graphique est spécifié par des enregistrements EMF+ <br/> et éventuellement des enregistrements EMF précédés d'un enregistrement EmfPlusGetDC. <br/> Si ce drapeau est défini, les enregistrements EMF seuls DEVRAIENT suffire à définir le <br/> contenu graphique. Notez que que le drapeau "dual-mode" soit activé ou non, certains <br/> enregistrements EMF sont toujours présents, à savoir les enregistrements de contrôle EMF et les enregistrements EMF <br/> qui contiennent des enregistrements EMF+. Les enregistrements de contrôle EMF sont spécifiés dans [MS-EMF] <br/> section 2.3.4. |
| emf_plus_flags | int | r/w | Obtient ou définit les indicateurs EMF plus.<br/> Un entier non signé de 32 bits qui contient des informations sur la façon dont ce métafichier a été enregistré.<br/> si le 31ᵉ bit du champ est défini, ce drapeau indique que le métafichier a été enregistré avec <br/> un contexte de périphérique de référence pour un affichage vidéo. Si désactivé, le métafichier a été enregistré avec<br/> un contexte de périphérique de référence pour une imprimante. |
| flags | int | r/w | Obtient ou définit un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont<br/>            l'opération doit être effectuée et sur la structure de l'enregistrement. |
| is_valid | bool | r | Obtient une valeur indiquant si cette instance est valide. |
| logical_dpi_x | int | r/w | Obtient ou définit le DPI logique x.<br/> Un entier non signé de 32 bits qui spécifie la résolution horizontale pour laquelle le métafichier <br/> a été enregistré, en unités de pixels par pouce. |
| logical_dpi_y | int | r/w | Obtient ou définit le DPI logique y.<br/> Un entier non signé de 32 bits qui spécifie la résolution verticale pour laquelle le métafichier <br/> a été enregistré, en unités de lignes par pouce. |
| size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre aligné sur 32 bits d'octets<br/>            dans l'enregistrement complet, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |
| version | [EmfPlusGraphicsVersion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/) | r/w | Obtient ou définit la version.<br/> Un objet EmfPlusGraphicsVersion (section 2.2.2.19) qui spécifie la version des graphiques du système d'exploitation<br/> utilisée pour créer ce métafichier. |
| video_display | bool | r/w | Obtient ou définit une valeur indiquant si affichage vidéo.<br/> si défini, ce drapeau indique que le métafichier a été enregistré avec un contexte de périphérique de référence<br/> pour un affichage vidéo. Si désactivé, le métafichier a été enregistré avec un contexte de périphérique de référence<br/> pour une imprimante. |


### Constructor: EmfPlusHeader(source) {#EmfPlusHeader_source_1}


```
 EmfPlusHeader(source) 
```

Initialise une nouvelle instance de la classe [EmfPlusHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La source. |

