---
title: EmfPlusDrawString
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lenregistrement EmfPlusDrawString spécifie la sortie de texte avec le formatage de chaîne
type: docs
weight: 6020
url: /fr/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/
---
## EmfPlusDrawString class

L'enregistrement EmfPlusDrawString spécifie la sortie de texte avec le formatage de chaîne

```csharp
public sealed class EmfPlusDrawString : EmfPlusDrawingRecordType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EmfPlusDrawString](emfplusdrawstring)(EmfPlusRecord) | Initialise une nouvelle instance du[`EmfPlusDrawString`](../emfplusdrawstring) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/brushid) { get; set; } | Obtient ou définit l'identifiant du pinceau Un entier non signé 32 bits qui spécifie le pinceau, dont le contenu est déterminé par le bit S dans le champ Flags. Cette définition est utilisée pour peindre la couleur du texte de premier plan ; c'est-à-dire, juste les glyphes eux-mêmes. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Obtient ou définit un entier non signé 32 bits qui DOIT définir le nombre aligné sur 32 bits de octets de données dans le champ RecordData qui suit. Ce numéro n'inclut pas l'en-tête d'enregistrement de 12 octets. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Obtient ou définit un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont l'opération doit être effectuée et sur la structure de l'enregistrement. |
| [FormatId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/formatid) { get; set; } | Obtient ou définit l'identificateur de format Un entier non signé 32 bits qui spécifie l'index d'un objet facultatif EmfPlusStringFormat (section 2.2.1.9) dans la table d'objets EMF+. Cet objet spécifie les informations de mise en page du texte et les manipulations d'affichage à appliquer à une chaîne |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/iscolor) { get; set; } | Obtient ou définit une valeur indiquant si cette instance est de couleur. Si défini, BrushId spécifie une couleur en tant qu'objet EmfPlusARGB (section 2.2.2.1). S'il est clair, BrushId contient l'index d'un objet EmfPlusBrush (section 2.2.1.1 ) dans la table d'objets EMF+. |
| [LayoutRect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/layoutrect) { get; set; } | Obtient ou définit la disposition rect Un objet EmfPlusRectF (section 2.2.2.39) qui définit la zone de délimitation de la destination qui recevra le string |
| [Length](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/length) { get; set; } | Obtient ou définit la longueur entier non signé 32 bits qui spécifie le nombre de caractères dans la chaîne. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/objectid) { get; set; } | Obtient ou définit l'identifiant de l'objet. L'index d'un objet EmfPlusFont (section 2.2.1.3) dans la table d'objets EMF+ pour restituer le texte. La valeur DOIT être de zéro à 63, inclus. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie le nombre d'octets alignés sur 32 bits dans l'enregistrement entier, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| [StringData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/stringdata) { get; set; } | Obtient ou définit la chaîne data Un tableau de caractères Unicode 16 bits qui spécifie la chaîne à dessiner |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |

### Voir également

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* espace de noms [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
