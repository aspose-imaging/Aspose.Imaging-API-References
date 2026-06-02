---
title: "Classe EmfPlusDrawString"
type: docs
weight: 190
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/
---

**Summary:** The EmfPlusDrawString record specifies text output with string formatting

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawString

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusDrawString(source)](#EmfPlusDrawString_source_1) | Initialise une nouvelle instance de la classe [EmfPlusDrawString](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Obtient ou définit l'identifiant du pinceau<br/> Un entier non signé de 32 bits qui spécifie le pinceau, dont le contenu <br/> est déterminé par le bit S dans le champ Flags. Cette définition est utilisée <br/> pour peindre la couleur du texte au premier plan ; c’est‑à‑dire, uniquement les glyphes eux‑mêmes. |
| data_size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui DOIT définir le nombre aligné sur 32 bits de<br/>            octets de données dans le champ RecordData qui suit. Ce nombre n'inclut pas l'en-tête d'enregistrement de 12 octets. |
| flags | int | r/w | Obtient ou définit un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont<br/>            l'opération doit être effectuée et sur la structure de l'enregistrement. |
| format_id | int | r/w | Obtient ou définit l'identifiant du format<br/> Un entier non signé de 32 bits qui spécifie l'index d'un objet optionnel <br/> EmfPlusStringFormat (section 2.2.1.9) dans la table d'objets EMF+. <br/> Cet objet spécifie les informations de mise en page du texte et les manipulations d'affichage <br/> à appliquer à une chaîne. |
| is_color | bool | r/w | Obtient ou définit une valeur indiquant si cette instance est en couleur.<br/> Si elle est définie, BrushId spécifie une couleur sous forme d'objet EmfPlusARGB (section 2.2.2.1).<br/> Si elle n'est pas définie, BrushId contient l'index d'un objet EmfPlusBrush <br/> (section 2.2.1.1) dans la table d'objets EMF+. |
| layout_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Obtient ou définit le rectangle de mise en page<br/> Un objet EmfPlusRectF (section 2.2.2.39) qui définit la zone de délimitation <br/> de la destination qui recevra la chaîne. |
| length | int | r/w | Obtient ou définit la longueur<br/> Un entier non signé de 32 bits qui spécifie le nombre de caractères dans la chaîne. |
| object_id | System.Byte | r/w | Obtient ou définit l'identifiant de l'objet.<br/> L'index d'un objet EmfPlusFont (section 2.2.1.3) dans la table d'objets EMF+<br/> pour rendre le texte. La valeur DOIT être comprise entre 0 et 63, inclusivement. |
| size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre aligné sur 32 bits d'octets<br/>            dans l'enregistrement complet, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| string_data | string | r/w | Obtient ou définit les données de la chaîne<br/> Un tableau de caractères Unicode de 16 bits qui spécifie la chaîne à dessiner |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |


### Constructor: EmfPlusDrawString(source) {#EmfPlusDrawString_source_1}


```
 EmfPlusDrawString(source) 
```

Initialise une nouvelle instance de la classe [EmfPlusDrawString](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La source. |

