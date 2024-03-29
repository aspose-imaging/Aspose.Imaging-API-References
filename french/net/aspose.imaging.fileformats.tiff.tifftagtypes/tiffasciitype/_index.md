---
title: TiffASCIIType
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Le type tiff ascii.
type: docs
weight: 7910
url: /fr/net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffasciitype/
---
## TiffASCIIType class

Le type tiff ascii.

```csharp
public sealed class TiffASCIIType : TiffDataType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [TiffASCIIType](tiffasciitype#constructor)(TiffTags) | Initialise une nouvelle instance du[`TiffASCIIType`](../tiffasciitype) classe. |
| [TiffASCIIType](tiffasciitype#constructor_1)(ushort) | Initialise une nouvelle instance du[`TiffASCIIType`](../tiffasciitype) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [AlignedDataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/aligneddatasize) { get; } | Obtient la taille des données supplémentaires en octets (au cas où les 12 octets ne suffisent pas pour contenir les données de balise). |
| override [Count](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffasciitype/count) { get; } | Obtient le nombre d'éléments. |
| override [DataSize](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffasciitype/datasize) { get; } | Obtient la taille des données supplémentaires en octets (au cas où les 12 octets ne suffisent pas pour contenir les données de balise). |
| [Id](../../aspose.imaging.fileformats.tiff/tiffdatatype/id) { get; } | Obtient la représentation entière de l'ID de balise. |
| [IsValid](../../aspose.imaging.fileformats.tiff/tiffdatatype/isvalid) { get; } | Obtient une valeur indiquant si les données de balise sont valides. La balise valide contient des données qui peuvent être conservées. La balise invalide ne peut pas être stockée. |
| [TagId](../../aspose.imaging.fileformats.tiff/tiffdatatype/tagid) { get; } | Obtient l'identifiant de la balise. |
| override [TagType](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffasciitype/tagtype) { get; } | Obtient le type de balise. |
| [Text](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffasciitype/text) { get; set; } | Obtient ou définit le texte. |
| override [Value](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffasciitype/value) { get; set; } | Obtient ou définit la valeur que ce type de données contient. |

## Méthodes

| Nom | La description |
| --- | --- |
| [CompareTo](../../aspose.imaging.fileformats.tiff/tiffdatatype/compareto)(object) | Compare l'instance actuelle avec un autre objet du même type et renvoie un entier qui indique si l'instance actuelle précède, suit ou apparaît à la même position dans l'ordre de tri que l'autre objet. |
| virtual [DeepClone](../../aspose.imaging.fileformats.tiff/tiffdatatype/deepclone)() | Effectue un clone profond de cette instance. |
| override [ToString](../../aspose.imaging.fileformats.tiff/tiffdatatype/tostring)() | Renvoie unString qui représente cette instance. |
| override [WriteAdditionalData](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffasciitype/writeadditionaldata)(TiffStreamWriter) | Écrit les données de variable supplémentaires. |
| [WriteTag](../../aspose.imaging.fileformats.tiff/tiffdatatype/writetag)(TiffStreamWriter, long) | Écrit les données de variable. |

### Voir également

* class [TiffDataType](../../aspose.imaging.fileformats.tiff/tiffdatatype)
* espace de noms [Aspose.Imaging.FileFormats.Tiff.TiffTagTypes](../../aspose.imaging.fileformats.tiff.tifftagtypes)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
