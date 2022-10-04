---
title: EmfColorMatchToTargetW
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lenregistrement EMR_COLORMATCHTOTargetW spécifie sil faut effectuer la correspondance des couleurs avec un profil color spécifié dans un fichier dont le nom est composé de caractères Unicode.
type: docs
weight: 3330
url: /fr/net/aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/
---
## EmfColorMatchToTargetW class

L'enregistrement EMR_COLORMATCHTOTargetW spécifie s'il faut effectuer la correspondance des couleurs avec un profil color spécifié dans un fichier dont le nom est composé de caractères Unicode.

```csharp
public sealed class EmfColorMatchToTargetW : EmfStateRecordType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EmfColorMatchToTargetW](emfcolormatchtotargetw)(EmfRecord) | Initialise une nouvelle instance du[`EmfColorMatchToTargetW`](../emfcolormatchtotargetw) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [CbData](../../aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/cbdata) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie la taille des données brutes du profil de couleur target , s'il est contenu dans le champ Data. |
| [CbName](../../aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/cbname) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie le nombre d'octets dans le nom Unicode UTF16-LE du profil de couleur souhaité. |
| [Data](../../aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/data) { get; set; } | Obtient ou définit un tableau de taille (cbName + cbData) en octets, qui spécifie le nom UTF16-LE et les données brutes du profil de couleur souhaité. |
| [DwAction](../../aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/dwaction) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie une valeur de l'énumération ColorSpace (section 2.1.7). |
| [DwFlags](../../aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/dwflags) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie une valeur de l'énumération ColorMatchToTarget (section 2.1.6). |
| [Name](../../aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/name) { get; } | Obtient le nom |
| [RawData](../../aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/rawdata) { get; } | Obtient les données brutes |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Obtient ou définit la taille de l'enregistrement |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Obtient ou définit le type. |

### Remarques

Un enregistrement EMR_COLORMATCHTOTargetW peut être utilisé pour contrôler s'il faut appliquer la transformation de couleur current dans le contexte du périphérique de lecture. Si la valeur dwAction est CS_ENABLE, le mappage color est activé et la transformation de couleur actuelle DEVRAIT être appliquée aux opérations graphics suivantes. Si dwAction est défini sur CS_DISABLE, la transformation de couleur NE DEVRAIT PAS être appliquée. Alors que le mappage des couleurs vers la cible est activé par une valeur dwAction de CS_ENABLE, les modifications apportées à l'espace colorimétrique ou au mappage de la gamme de couleurs ne sont pas appliquées. Cependant, ces modifications DOIVENT prendre effet lorsque le mappage des couleurs sur la cible est désactivé. Le champ dwAction NE DOIT PAS être défini sur CS_DELETE_TRANSFORM sauf si la gestion des couleurs a déjà été activée avec un enregistrement EMR_SETICMMODE (section 2.3.11.14).

### Voir également

* class [EmfStateRecordType](../emfstaterecordtype)
* espace de noms [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->