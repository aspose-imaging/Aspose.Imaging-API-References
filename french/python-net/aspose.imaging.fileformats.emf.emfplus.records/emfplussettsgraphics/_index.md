---
title: "Classe EmfPlusSetTsGraphics"
type: docs
weight: 580
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/
---

**Summary:** The EmfPlusSetTSGraphics record specifies the state of a graphics device context for a terminal server.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetTsGraphics

**Inheritance:** EmfPlusTerminalServerRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusSetTsGraphics(source)](#EmfPlusSetTsGraphics_source_1) | Initialise une nouvelle instance de la classe [EmfPlusSetTsGraphics](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| anti_alias_mode | [EmfPlusSmoothingMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplussmoothingmode/) | r/w | Obtient ou définit un entier non signé de 8 bits qui spécifie la qualité du rendu des lignes,<br/>            y compris le type d'anticrénelage des lignes. Il DOIT être défini dans l'énumération SmoothingMode<br/>            (section 2.1.1.28). |
| basic_vga_colors | bool | r | Obtient une valeur indiquant si [basic vga colors].<br/>            Si elle est définie, la palette ne contient que les couleurs VGA de base. |
| compositing_mode | [EmfPlusCompositingMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscompositingmode/) | r/w | Obtient ou définit un entier non signé de 8 bits qui spécifie comment les couleurs source sont<br/>            combinées avec les couleurs d'arrière-plan. Il DOIT être une valeur de l'énumération CompositingMode<br/>            (section 2.1.1.5). |
| compositing_quality | [EmfPlusCompositingQuality](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscompositingquality/) | r/w | Obtient ou définit un entier non signé de 8 bits qui spécifie le degré de<br/>            lissage à appliquer aux lignes, courbes et aux bords des zones remplies afin qu'ils apparaissent plus<br/>            continus ou nettement définis. Il DOIT être une valeur de l'énumération CompositingQuality (section 2.1.1.6). |
| data_size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui DOIT définir le nombre aligné sur 32 bits de<br/>            octets de données dans le champ RecordData qui suit. Ce nombre n'inclut pas l'en-tête d'enregistrement de 12 octets. |
| filter_type | [EmfPlusFilterType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusfiltertype/) | r/w | Obtient ou définit un entier non signé de 8 bits qui spécifie comment le redimensionnement, y compris l'étirement<br/>            et la réduction, est effectué. Il DOIT être une valeur de l'énumération FilterType (section 2.1.1.11). |
| flags | int | r/w | Obtient ou définit un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont<br/>            l'opération doit être effectuée et sur la structure de l'enregistrement. |
| have_palette | bool | r | Obtient une valeur indiquant si [have palette].<br/>            Si elle est définie, cet enregistrement contient un objet EmfPlusPalette (section 2.2.2.28) dans le<br/>            champ Palette suivant les données d'état graphique. |
| palette | [EmfPlusPalette](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette/) | r/w | Obtient ou définit un objet EmfPlusPalette optionnel. |
| pixel_offset | [EmfPlusPixelOffsetMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixeloffsetmode/) | r/w | Obtient ou définit un entier non signé de 8 bits qui spécifie la qualité globale de l'image<br/>            et du processus de rendu du texte. Il DOIT être une valeur de l'énumération PixelOffsetMode (section 2.1.1.26). |
| render_origin_x | int | r/w | Obtient ou définit un entier signé de 16 bits, qui est la coordonnée horizontale de<br/>            l'origine pour le rendu du tramage et des matrices de dithering. |
| render_origin_y | int | r/w | Obtient ou définit un entier signé de 16 bits, qui est la coordonnée verticale de l'origine<br/>            pour le rendu du tramage et des matrices de dithering. |
| size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre aligné sur 32 bits d'octets<br/>            dans l'enregistrement complet, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| text_contrast | int | r/w | Obtient ou définit un entier non signé de 16 bits qui spécifie la valeur de correction gamma<br/>            utilisée pour le rendu du texte anti-aliasé et ClearType. Cette valeur DOIT être dans la plage de 0 à 12, inclusive. |
| text_render_hint | [EmfPlusTextRenderingHint](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplustextrenderinghint/) | r/w | Obtient ou définit un entier non signé de 8 bits qui spécifie la qualité du rendu du texte<br/>            , y compris le type d'anticrénelage du texte. Il DOIT être défini dans l'énumération<br/>            TextRenderingHint (section 2.1.1.32). |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |
| world_to_device | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Obtient ou définit un objet EmfPlusTransformMatrix de 192 bits (section 2.2.2.47) qui<br/>            spécifie les transformations de l'espace mondial vers l'espace dispositif. |


### Constructor: EmfPlusSetTsGraphics(source) {#EmfPlusSetTsGraphics_source_1}


```
 EmfPlusSetTsGraphics(source) 
```

Initialise une nouvelle instance de la classe [EmfPlusSetTsGraphics](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La source. |

