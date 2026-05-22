---
title: "Classe WmfLogColorSpaceW"
type: docs
weight: 390
url: /fr/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/
---

**Summary:** The LogColorSpaceW object specifies a logical color space, which can be<br/>                defined by a color profile file with a name consisting of Unicode 16-bit<br/>                characters.

**Module:** [aspose.imaging.fileformats.wmf.objects](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/)

**Full Name:** aspose.imaging.fileformats.wmf.objects.WmfLogColorSpaceW

**Inheritance:** MetaObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [WmfLogColorSpaceW()](#WmfLogColorSpaceW__1) | Initialise une nouvelle instance de la classe WmfLogColorSpaceW |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| color_space_type | [WmfLogicalColorSpaceEnum](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmflogicalcolorspaceenum/) | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie l'espace colorimétrique<br/>                type. Il DOIT être défini dans l'énumération LogicalColorSpace<br/>                (section 2.1.1.14). Si cette valeur est LCS_sRGB ou<br/>                LCS_WINDOWS_COLOR_SPACE, l'espace colorimétrique sRGB DOIT être utilisé. |
| endpoints | [WmfCieXyzTriple](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfciexyztriple/) | r/w | Obtient ou définit un objet CIEXYZTriple (section 2.2.2.7) qui définit<br/>                les coordonnées de chromaticité CIE x, y et z des trois couleurs<br/>                qui correspondent au RGB [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) pour l'espace colorimétrique logique<br/>                associé au bitmap. Si le champ<br/>                [WmfLogColorSpaceW.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) ne spécifie pas<br/>                LCS_CALIBRATED_RGB, ce champ DOIT être ignoré. |
| filename | string | r/w | Obtient ou définit une chaîne de caractères Unicode UTF16-LE optionnelle, terminée par un caractère nul<br/>                qui spécifie le nom d'un fichier contenant un profil colorimétrique. Si un nom de fichier est spécifié, et que le champ<br/>                [WmfLogColorSpaceW.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) est défini sur LCS_CALIBRATED_RGB, les<br/>                autres champs de cette structure DEVRAIENT être ignorés. |
| gamma_blue | int | r/w | Obtient ou définit une valeur à point fixe de 32 bits qui définit la courbe de réponse tonifiée<br/>                pour le bleu. Si le champ [WmfLogColorSpaceW.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) ne spécifie pas LCS_CALIBRATED_RGB, ce champ DOIT être ignoré. |
| gamma_green | int | r/w | Obtient ou définit une valeur à point fixe de 32 bits qui définit la courbe de réponse tonifiée<br/>                pour le vert. Si le champ [WmfLogColorSpaceW.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) ne spécifie pas LCS_CALIBRATED_RGB, ce champ DOIT être ignoré. |
| gamma_red | int | r/w | Obtient ou définit une valeur à point fixe de 32 bits qui définit la courbe de réponse tonifiée<br/>                pour le rouge. Si le champ [WmfLogColorSpaceW.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) ne spécifie pas LCS_CALIBRATED_RGB, ce champ DOIT être ignoré. |
| intent | [WmfGamutMappingIntent](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfgamutmappingintent/) | r/w | Obtient ou définit un entier signé de 32 bits qui définit l'intention de mappage du gamut<br/>                . Il DOIT être défini dans l'énumération GamutMappingIntent<br/>                (section 2.1.1.11). |
| signature | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) des objets d'espace colorimétrique ; il DOIT être fixé à<br/>                la valeur 0x50534F43, qui est le codage ASCII de la chaîne<br/>                "PSOC". |
| size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui définit le<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) de cet objet, en octets. |
| version | int | r/w | Obtient ou définit un entier non signé de 32 bits qui définit un<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) nombre ; il DOIT être 0x00000400. |


### Constructor: WmfLogColorSpaceW() {#WmfLogColorSpaceW__1}


```
 WmfLogColorSpaceW() 
```

Initialise une nouvelle instance de la classe WmfLogColorSpaceW

