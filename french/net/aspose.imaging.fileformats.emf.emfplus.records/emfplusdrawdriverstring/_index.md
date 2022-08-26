---
title: EmfPlusDrawDriverString
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lenregistrement EmfPlusDrawDriverString spécifie une sortie de texte avec des positions de caractères.
type: docs
weight: 5940
url: /fr/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/
---
## EmfPlusDrawDriverString class

L'enregistrement EmfPlusDrawDriverString spécifie une sortie de texte avec des positions de caractères.

```csharp
public sealed class EmfPlusDrawDriverString : EmfPlusDrawingRecordType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EmfPlusDrawDriverString](emfplusdrawdriverstring)(EmfPlusRecord) | Initialise une nouvelle instance du[`EmfPlusDrawDriverString`](../emfplusdrawdriverstring) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/brushid) { get; set; } | Obtient ou définit l'identifiant du pinceau Un entier non signé 32 bits qui spécifie soit la couleur de premier plan du texte, soit un pinceau graphique, selon la valeur de l'indicateur S dans Flags |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Obtient ou définit un entier non signé 32 bits qui DOIT définir le nombre aligné sur 32 bits de octets de données dans le champ RecordData qui suit. Ce numéro n'inclut pas l'en-tête d'enregistrement de 12 octets. |
| [DriverStringOptionsFlags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/driverstringoptionsflags) { get; set; } | Obtient ou définit les options de chaîne du pilote flags Un entier non signé 32 bits qui spécifie l'espacement, l'orientation et la qualité de rendu de la chaîne. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Obtient ou définit un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont l'opération doit être effectuée et sur la structure de l'enregistrement. |
| [GlyphCount](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/glyphcount) { get; set; } | Obtient ou définit le nombre de glyphes Un entier non signé 32 bits qui spécifie le nombre de glyphes dans la chaîne |
| [GlyphPos](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/glyphpos) { get; set; } | Obtient ou définit les positions des glyphes array Un tableau d'objets EmfPlusPointF (section 2.2.2.36) qui spécifient la position de sortie de chaque glyphe de caractère. Il DOIT y avoir des éléments GlyphCount, qui ont une correspondance un à un avec les éléments du Tableau de glyphes. Les positions des glyphes sont calculées à partir de la position du premier glyphe si l'indicateur DriverStringOptionsRealizedAdvance dans les indicateurs DriverStringOptions est défini. Dans ce cas, GlyphPos spécifie la position du premier glyphe uniquement. |
| [Glyphs](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/glyphs) { get; set; } | Obtient ou définit les glyphes array Un tableau de valeurs 16 bits qui définissent la chaîne de texte à dessiner. Si l'indicateur DriverStringOptionsCmapLookup dans le champ DriverStringOptionsFlags est défini, chaque valeur dans this array spécifie un caractère Unicode. Sinon, chaque valeur spécifie un index vers un glyphe de caractère a dans l'objet EmfPlusFont spécifié par la valeur ObjectId dans le champ Flags. |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/iscolor) { get; set; } | Obtient ou définit une valeur indiquant si cette instance est de couleur. Ce bit indique le type de données dans le champ BrushId. S'il est défini, BrushId spécifie la valeur de couleur dans un objet EmfPlusARGB (section 2.2.2.1). Si clair, BrushId contient l'index EMF+ Object Table d'un objet EmfPlusBrush (section 2.2.1.1). |
| [MatrixPresent](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/matrixpresent) { get; set; } | Obtient ou définit si la matrice est présente flag Un entier non signé de 32 bits qui spécifie si une matrice de transformation est présente dans le champ TransformMatrix 0 - aucune matrice présente. 1 - la matrice de transformation est dans TransformMatrix field |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/objectid) { get; set; } | Obtient ou définit l'identifiant de l'objet. L'index de la table d'objets EMF+ d'un[EmfPlusFont](EmfPlusFont) objet (section 2.2.1.3) pour rendre le texte. La valeur DOIT être de zéro à 63, inclus. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie le nombre d'octets alignés sur 32 bits dans l'enregistrement entier, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| [TransformMatrix](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/transformmatrix) { get; set; } | Obtient ou définit la matrice de transformation Un objet EmfPlusTransformMatrix facultatif (section 2.2.2.47) qui spécifie la transformation à appliquer à chaque valeur du tableau de texte. La présence de ces données est déterminée à partir du champ MatrixPresent. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |

### Voir également

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* espace de noms [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
