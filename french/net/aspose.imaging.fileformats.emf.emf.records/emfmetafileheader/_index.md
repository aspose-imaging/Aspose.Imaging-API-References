---
title: EmfMetafileHeader
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Les types denregistrement EMR_HEADER définissent les points de départ des métafichiers EMF et spécifient les propriétés de lappareil sur lequel limage dans le métafichier a été créée. Les informations contenues dans lenregistrement den-tête permettent aux métafichiers EMF dêtre indépendants de tout périphérique de sortie spécifique. La valeur du champ Taille peut être utilisée pour distinguer les différents types denregistrement EMR_HEADER répertoriés plus haut dans cette section. Il existe trois possibilités headers  Len-tête de base qui est lenregistrement EmfMetafileHeader. La partie à taille fixe de cet en-tête est de 88 octets et contient un objet Header. Le premier en-tête dextension qui est lenregistrement EmfMetafileHeaderExtension1. La partie à taille fixe partie de cet en-tête est de 100 octets et contient un objet Header et un objet HeaderExtension1 section 2.2.10. Le deuxième en-tête dextension qui est lenregistrement EmfMetafileHeaderExtension2. La partie à taille fixe de cet en-tête est de 108 octets et il contient un objet Header un objet HeaderExtension1 et un objet HeaderExtension2 section 2.2.11.
type: docs
weight: 3810
url: /fr/net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/
---
## EmfMetafileHeader class

Les types d'enregistrement EMR_HEADER définissent les points de départ des métafichiers EMF et spécifient les propriétés de l'appareil sur lequel l'image dans le métafichier a été créée. Les informations contenues dans l'enregistrement d'en-tête permettent aux métafichiers EMF d'être indépendants de tout périphérique de sortie spécifique. La valeur du champ Taille peut être utilisée pour distinguer les différents types d'enregistrement EMR_HEADER répertoriés plus haut dans cette section. Il existe trois possibilités headers : L'en-tête de base, qui est l'enregistrement EmfMetafileHeader. La partie à taille fixe de cet en-tête est de 88 octets et contient un objet Header. Le premier en-tête d'extension, qui est l'enregistrement EmfMetafileHeaderExtension1. La partie à taille fixe partie de cet en-tête est de 100 octets et contient un objet Header et un objet HeaderExtension1 (section 2.2.10). Le deuxième en-tête d'extension, qui est l'enregistrement EmfMetafileHeaderExtension2. La partie à taille fixe de cet en-tête est de 108 octets, et il contient un objet Header, un objet HeaderExtension1 et un objet HeaderExtension2 (section 2.2.11).

```csharp
public class EmfMetafileHeader : EmfRecord
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EmfMetafileHeader](emfmetafileheader#constructor)() | Initialise une nouvelle instance du[`EmfMetafileHeader`](../emfmetafileheader) classe. |
| [EmfMetafileHeader](emfmetafileheader#constructor_1)(EmfMetafileHeader) | Initialise une nouvelle instance du[`EmfMetafileHeader`](../emfmetafileheader) classe. |
| [EmfMetafileHeader](emfmetafileheader#constructor_2)(EmfRecord) | Initialise une nouvelle instance du[`EmfMetafileHeader`](../emfmetafileheader) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [EmfDescription](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfdescription) { get; set; } | Obtient ou définit la description EMF Chaîne Unicode UTF16-LE facultative, terminée par un caractère nul, de longueur et de contenu arbitraires. Son emplacement dans l'enregistrement et le nombre de caractères sont spécifiés par les champs offDescription et nDescription, respectivement, dans EmfHeader. Si la valeur de l'un des champs est zéro, aucune chaîne de description n'est présente. |
| [EmfDescriptionBuffer](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfdescriptionbuffer) { get; set; } | Obtient ou définit le tampon de description EMF Un tableau facultatif d'octets qui contient la chaîne de description EMF, qui n'est pas obligée d'être contiguë à la partie fixe de l'enregistrement EmfMetafileHeader . En conséquence, le champ dans ce tampon qui est étiqueté "UndefinedSpace" est facultatif et DOIT être ignoré. |
| [EmfHeader](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfheader) { get; set; } | Obtient ou définit un objet Header (section 2.2.9), qui contient des informations sur le contenu et la structure du métafichier |
| [EmfHeaderRecordBuffer](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfheaderrecordbuffer) { get; set; } | Obtient ou définit un tableau facultatif d'octets qui contient le reste de l'enregistrement d'en-tête EMF. La taille de ce champ DOIT être un multiple de 4 octets |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Obtient ou définit la taille de l'enregistrement |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Obtient ou définit le type. |

### Voir également

* class [EmfRecord](../emfrecord)
* espace de noms [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
