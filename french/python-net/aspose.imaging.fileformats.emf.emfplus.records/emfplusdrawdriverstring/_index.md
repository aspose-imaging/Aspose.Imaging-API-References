---
title: "Classe EmfPlusDrawDriverString"
type: docs
weight: 110
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/
---

**Summary:** The EmfPlusDrawDriverString record specifies text output with character positions.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawDriverString

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusDrawDriverString(source)](#EmfPlusDrawDriverString_source_1) | Initialise une nouvelle instance de la classe [EmfPlusDrawDriverString](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/) |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Obtient ou définit l'identifiant du pinceau<br/>            Un entier non signé de 32 bits qui spécifie soit la couleur de premier plan du texte, soit un pinceau graphique,<br/>            selon la valeur du drapeau S dans le champ Flags. |
| data_size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui DOIT définir le nombre aligné sur 32 bits de<br/>            octets de données dans le champ RecordData qui suit. Ce nombre n'inclut pas l'en-tête d'enregistrement de 12 octets. |
| driver_string_options_flags | [EmfPlusDriverStringOptionsFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusdriverstringoptionsflags/) | r/w | Obtient ou définit les indicateurs d'options de chaîne de pilote<br/>            Un entier non signé de 32 bits qui spécifie l'espacement, l'orientation et la qualité de rendu de la chaîne. |
| flags | int | r/w | Obtient ou définit un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont<br/>            l'opération doit être effectuée et sur la structure de l'enregistrement. |
| glyph_count | int | r/w | Obtient ou définit le nombre de glyphes<br/>            Un entier non signé de 32 bits qui spécifie le nombre de glyphes dans la chaîne. |
| glyph_pos | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Obtient ou définit le tableau des positions des glyphes<br/>            Un tableau d'objets EmfPlusPointF (section 2.2.2.36) qui spécifient la position de sortie de chaque glyphe de caractère.<br/>            Il DOIT y avoir GlyphCount éléments, qui ont une correspondance un à un avec les éléments du tableau Glyphs.<br/>            Les positions des glyphes sont calculées à partir de la position du premier glyphe si le drapeau DriverStringOptionsRealizedAdvance<br/>            dans les indicateurs DriverStringOptions est activé. Dans ce cas, GlyphPos spécifie uniquement la position du premier glyphe. |
| glyphs | int[] | r/w | Obtient ou définit le tableau des glyphes<br/>            Un tableau de valeurs 16 bits qui définissent la chaîne de texte à dessiner.<br/>            Si le drapeau DriverStringOptionsCmapLookup dans le champ DriverStringOptionsFlags est activé, chaque valeur de ce<br/>            tableau spécifie un caractère Unicode. Sinon, chaque valeur spécifie un indice vers un<br/>            glyphe de caractère dans l'objet EmfPlusFont spécifié par la valeur ObjectId dans le champ Flags. |
| is_color | bool | r/w | Obtient ou définit une valeur indiquant si cette instance est une couleur.<br/>            Ce bit indique le type de données dans le champ BrushId.<br/>            S'il est défini, BrushId spécifie la valeur de couleur dans un objet EmfPlusARGB<br/>            (section 2.2.2.1). S'il est effacé, BrushId contient l'index de la Table des Objets EMF+ d'un objet EmfPlusBrush (section 2.1.1). |
| matrix_present | int | r/w | Obtient ou définit si le drapeau de matrice présente<br/>            Un entier non signé de 32 bits qui spécifie si une matrice de transformation est présente dans le champ TransformMatrix<br/>            0 - aucune matrice présente. 1 - la matrice de transformation est dans le champ TransformMatrix |
| object_id | System.Byte | r/w | Obtient ou définit l'identifiant de l'objet.<br/>            L'index de la Table des Objets EMF+ d'un ***EmfPlusFont*** (section<br/>            2.2.1.3) pour rendre le texte. La valeur DOIT être comprise entre 0 et 63, inclus. |
| size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre aligné sur 32 bits d'octets<br/>            dans l'enregistrement complet, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Obtient ou définit la matrice de transformation<br/>            Un objet optionnel EmfPlusTransformMatrix (section 2.2.2.47) qui spécifie la transformation à appliquer à<br/>            chaque valeur du tableau de texte. La présence de ces données est déterminée à partir du champ MatrixPresent. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |


### Constructor: EmfPlusDrawDriverString(source) {#EmfPlusDrawDriverString_source_1}


```
 EmfPlusDrawDriverString(source) 
```

Initialise une nouvelle instance de la classe [EmfPlusDrawDriverString](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/)

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La source. |

