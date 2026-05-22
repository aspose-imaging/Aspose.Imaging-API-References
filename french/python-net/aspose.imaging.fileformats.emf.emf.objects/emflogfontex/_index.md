---
title: "Classe EmfLogFontEx"
type: docs
weight: 140
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfontex/
---

**Summary:** The LogFontEx object specifies the extended attributes of a logical font.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfLogFontEx

**Inheritance:** EmfLogFont

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfLogFontEx(emf_log_font)](#EmfLogFontEx_emf_log_font_1) | Initialise une nouvelle instance de la classe [EmfLogFontEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfontex/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| char_set | [WmfCharacterSet](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfcharacterset/) | r/w | Obtient ou définit un entier non signé de 8 bits qui spécifie l'ensemble des glyphes de caractères. Il DOIT <br/>            être une valeur de l'énumération WMF CharacterSet ([MS-WMF] section 2.1.1.5). Si le <br/>            jeu de caractères est inconnu, le traitement du métafichier NE DEVRAIT PAS tenter de traduire ou d'interpréter <br/>            les chaînes rendues avec cette police. |
| clip_precision | [WmfClipPrecisionFlags](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfclipprecisionflags/) | r/w | Obtient ou définit un entier non signé de 8 bits qui spécifie la précision de découpage. La <br/>            précision de découpage définit comment découper les caractères qui sont partiellement en dehors de la région de découpage. <br/>            Elle peut être une ou plusieurs des indicateurs WMF ClipPrecision. |
| escapement | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie l'angle, en dixièmes de degré, <br/>            entre le vecteur d'échappement et l'axe x du dispositif. Le vecteur d'échappement est <br/>            parallèle à la ligne de base d'une rangée de texte. |
| nom de police | string | r/w | Obtient ou définit un Facename (64 octets) : une chaîne de maximum 32 caractères Unicode qui spécifie le <br/>            nom de la police. Si la longueur de cette chaîne est inférieure à 32 caractères, un NULL terminateur DOIT être présent, après quoi le reste de ce champ DOIT être ignoré. |
| full_name | string | r/w | Obtient ou définit une chaîne de 64 caractères Unicode contenant le nom complet de la police. Si <br/>            la longueur de cette chaîne est inférieure à 64 caractères, un NULL terminateur DOIT être présent, après <br/>            quoi le reste de ce champ DOIT être ignoré. |
| height | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie la hauteur, en unités logiques, de la cellule de caractère ou du caractère de la police.<br/>            La valeur de la hauteur du caractère, également appelée taille em, est la valeur de la hauteur de la cellule de caractère moins la valeur de l’interligne interne.<br/>            Le mappeur de police DOIT interpréter la valeur spécifiée dans le champ Height de la manière suivante. |
| italique | System.Byte | r/w | Obtient ou définit un entier non signé de 8 bits qui spécifie une police italique si la valeur est 0x01 ; sinon,<br/>            il DOIT être réglé à 0x00. |
| orientation | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie l’angle, en dixièmes de degré, <br/>            entre la ligne de base de chaque caractère et l’axe x du dispositif. |
| out_precision | [WmfOutPrecision](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfoutprecision/) | r/w | Obtient ou définit un entier non signé de 8 bits qui spécifie la précision de sortie. La <br/>            précision de sortie définit à quel point la police doit correspondre étroitement à la hauteur, la largeur, <br/>            l’orientation du caractère, l’échappement, le pas et le type de police demandés. Elle DOIT être une valeur de l’énumération WMF <br/>            OutPrecision. |
| pitch_and_family | [WmfPitchAndFamily](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/) | r/w | Obtient ou définit un objet WMF PitchAndFamily ([MS-WMF] section 2.2.2.14) qui <br/>            spécifie le pas et la famille de la police. Les familles de police décrivent l’apparence d’une police de manière générale. Elles sont destinées à spécifier une police lorsque le type de caractère spécifié n’est pas disponible. |
| quality | [WmfFontQuality](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmffontquality/) | r/w | Obtient ou définit un entier non signé de 8 bits qui spécifie la qualité de sortie. La qualité de sortie <br/>            définit à quel point il faut tenter de faire correspondre les attributs de police logique à ceux d’une police physique réelle. Elle DOIT être l’une des valeurs de l’énumération WMF FontQuality ([MS-WMF] <br/>            section 2.1.1.10). |
| script | string | r/w | Obtient ou définit une chaîne de 32 caractères Unicode qui définit le jeu de caractères de la police.<br/>            Si la longueur de cette chaîne est inférieure à 32 caractères, un NULL terminateur DOIT être présent, <br/>            après quoi le reste de ce champ DOIT être ignoré. |
| barré | System.Byte | r/w | Obtient ou définit un entier non signé de 8 bits qui spécifie une police barrée si la valeur est 0x01 ; <br/>            sinon, il DOIT être réglé à 0x00. |
| style | string | r/w | Obtient ou définit une chaîne de 32 caractères Unicode qui définit le style de la police. Si la longueur de <br/>            cette chaîne est inférieure à 32 caractères, un NULL terminateur DOIT être présent, après quoi le <br/>            reste de ce champ DOIT être ignoré. |
| souligné | System.Byte | r/w | Obtient ou définit un entier non signé de 8 bits qui spécifie une police soulignée si la valeur est 0x01 ; <br/>            sinon, il DOIT être réglé à 0x00. |
| weight | [EmfLogFontWeight](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emflogfontweight/) | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie le poids de la police dans la plage <br/>            de zéro à 1000. Par exemple, 400 est normal et 700 est gras. Si cette valeur est zéro, un poids par défaut peut être utilisé. |
| width | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie la largeur moyenne, en unités logiques, des <br/>            caractères de la police. Si la valeur du champ Width est zéro, une valeur appropriée DOIT être <br/>            calculée à partir d’autres valeurs LogFont pour trouver une police correspondant au ratio d’aspect prévu par le typographe. |


### Constructor: EmfLogFontEx(emf_log_font) {#EmfLogFontEx_emf_log_font_1}


```
 EmfLogFontEx(emf_log_font) 
```

Initialise une nouvelle instance de la classe [EmfLogFontEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfontex/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| emf_log_font | [EmfLogFont](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfont/) | La police de journal EMF. |

