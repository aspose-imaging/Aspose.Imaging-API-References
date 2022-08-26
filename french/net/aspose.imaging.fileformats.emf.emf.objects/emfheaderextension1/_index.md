---
title: EmfHeaderExtension1
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lobjet HeaderExtension1 définit la première extension de len-tête du métafichier EMF. Il ajoute la prise en charge dun objet PixelFormatDescriptor section 2.2.22 et des enregistrements OpenGL OPENGL section 2.3.9.
type: docs
weight: 2990
url: /fr/net/aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/
---
## EmfHeaderExtension1 class

L'objet HeaderExtension1 définit la première extension de l'en-tête du métafichier EMF. Il ajoute la prise en charge d'un objet PixelFormatDescriptor (section 2.2.22) et des enregistrements OpenGL [OPENGL] (section 2.3.9).

```csharp
public sealed class EmfHeaderExtension1 : EmfHeaderObject
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EmfHeaderExtension1](emfheaderextension1)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [BOpenGl](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/bopengl) { get; set; } | Obtient ou définit un entier non signé 32 bits qui indique si les commandes OpenGL sont présentes dans le métafichier. 0x00000000 Les enregistrements OpenGL ne sont pas présents dans le métafichier. 0x00000001 Les enregistrements OpenGL sont présents dans le métafichier. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/bounds) { get; set; } | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui spécifie les limites rectangulaires inclusives-inclusives en unités de périphérique du plus petit rectangle pouvant être dessiné autour de l'image stockée dans le métafichier |
| [Bytes](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/bytes) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie la taille du métafichier, en octets. |
| [CbPixelFormat](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/cbpixelformat) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie la taille de l'objet PixelFormatDescriptor. Cela DOIT être 0x00000000 si aucun format de pixel n'est défini |
| [Device](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/device) { get; set; } | Obtient ou définit un objet WMF SizeL ([MS-WMF] section 2.2.2.22) qui spécifie la taille du périphérique de référence, en pixels |
| [Frame](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/frame) { get; set; } | Obtient ou définit un objet WMF RectL qui spécifie les dimensions rectangulaires inclusives-inclusives, en unités de 0,01 millimètre, d'un rectangle qui entoure l'image stockée dans le métafichier |
| [Handles](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/handles) { get; set; } | Obtient ou définit un entier non signé 16 bits qui spécifie le nombre d'objets graphiques qui seront utilisés lors du traitement du métafichier |
| [Millimeters](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/millimeters) { get; set; } | Obtient ou définit un objet WMF SizeL qui spécifie la taille de l'appareil de référence, en millimètres |
| [NDesription](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/ndesription) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie le nombre de caractères dans le tableau qui contient la description du contenu du métafichier. C'est zéro s'il n'y a pas de chaîne de description. |
| [NPalEntries](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/npalentries) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie le nombre d'entrées dans la palette de métafichier . La palette est située dans la fiche EMR_EOF |
| [OffDescription](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/offdescription) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie le décalage entre le début de cet enregistrement et le tableau contenant la description du contenu du métafichier |
| [OffPixelFormat](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/offpixelformat) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie le décalage de l'objet PixelFormatDescriptor. Cela DOIT être 0x00000000 si aucun format de pixel n'est défini. |
| [Records](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/records) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie le nombre d'enregistrements dans le métafichier |
| [RecordSignature](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/recordsignature) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie la signature de l'enregistrement. Cela DOIT être ENHMETA_SIGNATURE, de l'énumération FormatSignature (section 2.1.14). |
| [Reserved](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/reserved) { get; set; } | Obtient ou définit un entier non signé 16 bits qui DOIT être 0x0000 et DOIT être ignoré |
| [Valid](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/valid) { get; } | Obtient une valeur indiquant si cela[`EmfHeaderObject`](../emfheaderobject)est valide. |
| [Version](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/version) { get; set; } | Obtient ou définit la version (4 octets) : entier non signé 32 bits qui spécifie l'interopérabilité du métafichier EMF. Cela DEVRAIT être 0x00010000 |

### Voir également

* class [EmfHeaderObject](../emfheaderobject)
* espace de noms [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
