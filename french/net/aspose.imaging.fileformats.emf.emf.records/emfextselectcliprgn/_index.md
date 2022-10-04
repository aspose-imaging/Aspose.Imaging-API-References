---
title: EmfExtSelectClipRgn
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lenregistrement EMR_EXTSELECTCLIPRGN combine la région spécifiée avec la région de clip actuelle en utilisant le mode spécifié. Remarque Les champs qui ne sont pas décrits dans cette section sont spécifiés dans la section 2.3.2.
type: docs
weight: 3660
url: /fr/net/aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/
---
## EmfExtSelectClipRgn class

L'enregistrement EMR_EXTSELECTCLIPRGN combine la région spécifiée avec la région de clip actuelle en utilisant le mode spécifié. Remarque Les champs qui ne sont pas décrits dans cette section sont spécifiés dans la section 2.3.2.

```csharp
public sealed class EmfExtSelectClipRgn : EmfClippingRecordType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EmfExtSelectClipRgn](emfextselectcliprgn#constructor)() | Initialise une nouvelle instance du[`EmfExtSelectClipRgn`](../emfextselectcliprgn) classe. |
| [EmfExtSelectClipRgn](emfextselectcliprgn#constructor_1)(EmfRecord) | Initialise une nouvelle instance du[`EmfExtSelectClipRgn`](../emfextselectcliprgn) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [RegionMode](../../aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/regionmode) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie la manière d'utiliser la région. La valeur DOIT être dans l'énumération RegionMode (section 2.1.29). |
| [RgnData](../../aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/rgndata) { get; set; } | Obtient ou définit un tableau de longueur RgnDataSize d'octets qui spécifie un objet RegionData en unités logiques. Si RegionMode est RGN_COPY, ces données peuvent être omises et la région de clip DEVRAIT être définie sur la région de clip par défaut (NULL). |
| [RgnDataSize](../../aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/rgndatasize) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie la taille des données de région en octets. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Obtient ou définit la taille de l'enregistrement |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Obtient ou définit le type. |

### Voir également

* class [EmfClippingRecordType](../emfclippingrecordtype)
* espace de noms [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->