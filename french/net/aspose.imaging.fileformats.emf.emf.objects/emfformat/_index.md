---
title: EmfFormat
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lobjet EmrFormat contient des informations qui identifient le format des données dimage dans un enregistrement EMR_COMMENT_MULTIFORMATS section 2.3.3.4.3.
type: docs
weight: 2960
url: /fr/net/aspose.imaging.fileformats.emf.emf.objects/emfformat/
---
## EmfFormat class

L'objet EmrFormat contient des informations qui identifient le format des données d'image dans un enregistrement EMR_COMMENT_MULTIFORMATS (section 2.3.3.4.3).

```csharp
public sealed class EmfFormat : EmfObject
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EmfFormat](emfformat)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [OffData](../../aspose.imaging.fileformats.emf.emf.objects/emfformat/offdata) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie le décalage des données à partir du début du champ d'identifiant dans un enregistrement EMR_COMMENT_PUBLIC (section 2.3.3.4). Le décalage DOIT être aligné sur 32 bits. |
| [Signature](../../aspose.imaging.fileformats.emf.emf.objects/emfformat/signature) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie le format des données d'image. Cette valeur DOIT être dans l'énumération FormatSignature (section 2.1.14). |
| [SizeData](../../aspose.imaging.fileformats.emf.emf.objects/emfformat/sizedata) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie la taille des données en octets |
| [Version](../../aspose.imaging.fileformats.emf.emf.objects/emfformat/version) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie le numéro de version du format. Si le champ Signature spécifie du PostScript encapsulé (EPS), cette valeur DOIT être 0x00000001 ; sinon, cette valeur DOIT être ignorée |

### Voir également

* class [EmfObject](../emfobject)
* espace de noms [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->