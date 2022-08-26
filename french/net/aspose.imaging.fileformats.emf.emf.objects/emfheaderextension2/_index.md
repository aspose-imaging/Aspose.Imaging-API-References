---
title: EmfHeaderExtension2
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lobjet HeaderExtension2 définit la deuxième extension de len-tête du métafichier EMF. Il ajoute la capacité à mesurer les surfaces des appareils en micromètres ce qui améliore la résolution et lévolutivité des métafichiers EMF.
type: docs
weight: 3000
url: /fr/net/aspose.imaging.fileformats.emf.emf.objects/emfheaderextension2/
---
## EmfHeaderExtension2 class

L'objet HeaderExtension2 définit la deuxième extension de l'en-tête du métafichier EMF. Il ajoute la capacité à mesurer les surfaces des appareils en micromètres, ce qui améliore la résolution et l'évolutivité des métafichiers EMF.

```csharp
public sealed class EmfHeaderExtension2 : EmfHeaderObject
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EmfHeaderExtension2](emfheaderextension2)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/bounds) { get; set; } | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui spécifie les limites rectangulaires inclusives-inclusives en unités de périphérique du plus petit rectangle pouvant être dessiné autour de l'image stockée dans le métafichier |
| [Bytes](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/bytes) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie la taille du métafichier, en octets. |
| [Device](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/device) { get; set; } | Obtient ou définit un objet WMF SizeL ([MS-WMF] section 2.2.2.22) qui spécifie la taille du périphérique de référence, en pixels |
| [Frame](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/frame) { get; set; } | Obtient ou définit un objet WMF RectL qui spécifie les dimensions rectangulaires inclusives-inclusives, en unités de 0,01 millimètre, d'un rectangle qui entoure l'image stockée dans le métafichier |
| [Handles](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/handles) { get; set; } | Obtient ou définit un entier non signé 16 bits qui spécifie le nombre d'objets graphiques qui seront utilisés lors du traitement du métafichier |
| [MicrometersX](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderextension2/micrometersx) { get; set; } | Obtient ou définit la taille horizontale 32 bits du périphérique d'affichage pour lequel l'image de métafichier a été générée, en micromètres |
| [MicrometersY](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderextension2/micrometersy) { get; set; } | Obtient ou définit la taille verticale 32 bits du périphérique d'affichage pour lequel l'image de métafichier a été générée, en micromètres. |
| [Millimeters](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/millimeters) { get; set; } | Obtient ou définit un objet WMF SizeL qui spécifie la taille de l'appareil de référence, en millimètres |
| [NDesription](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/ndesription) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie le nombre de caractères dans le tableau qui contient la description du contenu du métafichier. C'est zéro s'il n'y a pas de chaîne de description. |
| [NPalEntries](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/npalentries) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie le nombre d'entrées dans la palette de métafichier . La palette est située dans la fiche EMR_EOF |
| [OffDescription](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/offdescription) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie le décalage entre le début de cet enregistrement et le tableau contenant la description du contenu du métafichier |
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
