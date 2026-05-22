---
title: "Classe WmfLogColorSpace"
type: docs
weight: 380
url: /fr/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/
---

**Summary:** The LogColorSpace object specifies a logical color space for the<br/>                playback device context, which can be the name of a color profile in<br/>                ASCII characters.

**Module:** [aspose.imaging.fileformats.wmf.objects](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/)

**Full Name:** aspose.imaging.fileformats.wmf.objects.WmfLogColorSpace

**Inheritance:** MetaObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [WmfLogColorSpace()](#WmfLogColorSpace__1) | Initialise une nouvelle instance de la classe WmfLogColorSpace |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| color_space_type | [WmfLogicalColorSpaceEnum](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmflogicalcolorspaceenum/) | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie l'espace colorimétrique<br/>                type. Il DOIT être défini dans l'énumération LogicalColorSpace<br/>                (section 2.1.1.14). Si cette valeur est LCS_sRGB ou<br/>                LCS_WINDOWS_COLOR_SPACE, l'espace colorimétrique sRGB DOIT être utilisé. |
| endpoints | [WmfCieXyzTriple](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfciexyztriple/) | r/w | Obtient ou définit un objet CIEXYZTriple (section 2.2.2.7) qui définit<br/>                les coordonnées de chromaticité CIE x, y et z des trois couleurs<br/>                qui correspondent au RGB [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) pour l'espace colorimétrique logique<br/>                associé au bitmap. Si le champ<br/>                [WmfLogColorSpace.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) ne spécifie pas<br/>                LCS_CALIBRATED_RGB, ce champ DOIT être ignoré. |
| filename | string | r/w | Obtient ou définit une chaîne de caractères ASCII optionnelle qui spécifie le<br/>                nom d'un fichier contenant un profil colorimétrique. Si un nom de fichier est<br/>                spécifié, et que le champ [WmfLogColorSpace.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) est défini sur<br/>                LCS_CALIBRATED_RGB, les autres champs de cette structure DEVRAIENT être<br/>                ignorés. |
| gamma_blue | int | r/w | Obtient ou définit une valeur à point fixe de 32 bits qui définit la courbe de réponse tonifiée<br/>                pour le bleu. Si le champ [WmfLogColorSpace.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) ne spécifie pas LCS_CALIBRATED_RGB, ce champ DOIT être ignoré. |
| gamma_green | int | r/w | Obtient ou définit une valeur à point fixe de 32 bits qui définit la courbe de réponse tonifiée<br/>                pour le vert. Si le champ [WmfLogColorSpace.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) ne spécifie pas LCS_CALIBRATED_RGB, ce champ DOIT être ignoré. |
| gamma_red | int | r/w | Obtient ou définit une valeur à point fixe de 32 bits qui définit la courbe de réponse tonifiée<br/>                pour le rouge. Si le champ [WmfLogColorSpace.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) ne spécifie pas LCS_CALIBRATED_RGB, ce champ DOIT être ignoré. |
| intent | [WmfGamutMappingIntent](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfgamutmappingintent/) | r/w | Obtient ou définit un entier signé de 32 bits qui définit l'intention de mappage du gamut<br/>                . Il DOIT être défini dans l'énumération GamutMappingIntent<br/>                (section 2.1.1.11). |
| signature | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) des objets d'espace colorimétrique ; il DOIT être fixé à<br/>                la valeur 0x50534F43, qui est le codage ASCII de la chaîne<br/>                "PSOC". |
| size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui définit le<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) de cet objet, en octets. |
| version | int | r/w | Obtient ou définit un entier non signé de 32 bits qui définit un<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) nombre ; il DOIT être 0x00000400. |


### Constructor: WmfLogColorSpace() {#WmfLogColorSpace__1}


```
 WmfLogColorSpace() 
```

Initialise une nouvelle instance de la classe WmfLogColorSpace

