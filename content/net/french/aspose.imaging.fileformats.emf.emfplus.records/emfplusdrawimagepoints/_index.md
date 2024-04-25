---
title: EmfPlusDrawImagePoints
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lenregistrement EmfPlusDrawImagePoints spécifie le dessin dune image à léchelle à lintérieur dun parallélogramme.
type: docs
weight: 5970
url: /fr/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/
---
## EmfPlusDrawImagePoints class

L'enregistrement EmfPlusDrawImagePoints spécifie le dessin d'une image à l'échelle à l'intérieur d'un parallélogramme.

```csharp
public sealed class EmfPlusDrawImagePoints : EmfPlusDrawingRecordType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EmfPlusDrawImagePoints](emfplusdrawimagepoints)(EmfPlusRecord) | Initialise une nouvelle instance du[`EmfPlusDrawImagePoints`](../emfplusdrawimagepoints) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [ApplyingAnEffect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/applyinganeffect) { get; set; } | Obtient ou définit une valeur indiquant si [appliquer un effet]. Ce bit indique que le rendu de l'image inclut l'application d'un effet. S'il est défini, un objet de la classe Effect DOIT avoir été spécifié dans un enregistrement EmfPlusSerializableObject antérieur (section 2.3.5.2). |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/compressed) { get; set; } | Obtient ou définit une valeur indiquant si PointData est compressé. Ce bit indique si le champ PointData spécifie des données compressées. S'il est défini, PointData spécifie des emplacements absolus dans l'espace de coordonnées avec des coordonnées integer 16 bits. S'il est clair, PointData spécifie des emplacements absolus dans l'espace de coordonnées avec coordonnées à virgule flottante 32 bits. Remarque Si l'indicateur P (ci-dessous) est défini, cet indicateur est indéfini et DOIT être ignoré. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Obtient ou définit un entier non signé 32 bits qui DOIT définir le nombre aligné sur 32 bits de octets de données dans le champ RecordData qui suit. Ce numéro n'inclut pas l'en-tête d'enregistrement de 12 octets. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Obtient ou définit un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont l'opération doit être effectuée et sur la structure de l'enregistrement. |
| [ImageAttributesId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/imageattributesid) { get; set; } | Obtient ou définit un entier non signé 32 bits qui contient l'index de l'objet facultatif EmfPlusImageAttributes (section 2.2.1.5) dans la table d'objets EMF+. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/objectid) { get; set; } | Obtient ou définit l'identifiant de l'objet. L'index d'un objet EmfPlusImage (section 2.2.1.4) dans la table d'objets EMF+ , qui spécifie l'image à afficher. La valeur DOIT être de zéro à 63, inclus. |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/pointdata) { get; set; } | Obtient ou définit un tableau de points de comptage qui spécifient trois points d'un parallélogramme. Les trois points représentent les coins supérieur gauche, supérieur droit et inférieur gauche du parallélogramme . Le quatrième point du parallélogramme est extrapolé des trois premiers. La partie de l'image spécifiée par le champ SrcRect DEVRAIT avoir des transformations de mise à l'échelle et de cisaillement appliquées si nécessaire pour s'adapter à l'intérieur du parallélogramme. |
| [Relative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/relative) { get; set; } | Obtient ou définit une valeur indiquant si cette[`EmfPlusDrawImagePoints`](../emfplusdrawimagepoints)est relatif. Ce bit indique si le champ PointData spécifie des emplacements relatifs ou absolus. S'il est défini, chaque élément de PointData spécifie un emplacement dans l'espace de coordonnées qui est par rapport à l'emplacement spécifié par l'élément précédent dans le tableau. Dans le cas du premier élément the dans PointData, un emplacement précédent aux coordonnées (0,0) est supposé. S'il est clair, PointData spécifie les emplacements absolus en fonction de l'indicateur C. Remarque Si cet indicateur est défini, l'indicateur C (ci-dessus) est indéfini et DOIT être ignoré. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie le nombre d'octets alignés sur 32 bits dans l'enregistrement entier, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| [SrcRect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/srcrect) { get; set; } | Obtient ou définit un objet EmfPlusRectF (section 2.2.2.39) qui définit une partie de l'image à rendre. |
| [SrcUnit](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/srcunit) { get; set; } | Obtient ou définit un entier signé 32 bits qui définit les unités du champ SrcRect. Il DOIT être la valeur UnitPixel de l'énumération UnitType (section 2.1.1.33). |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |

### Remarques

Un EmfPlusImage peut spécifier un bitmap ou un métafichier. Les couleurs d'une image peuvent être manipulées pendant le rendu. Ils peuvent être corrigés, assombris, éclaircis et supprimés.

### Voir également

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* espace de noms [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
