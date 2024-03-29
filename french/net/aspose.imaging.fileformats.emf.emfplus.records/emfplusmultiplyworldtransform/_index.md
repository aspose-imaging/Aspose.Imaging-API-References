---
title: EmfPlusMultiplyWorldTransform
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lenregistrement EmfPlusMultiplyWorldTransform multiplie la transformation de lespace univers actuel par une matrice de transformation spécifiée.
type: docs
weight: 6150
url: /fr/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusmultiplyworldtransform/
---
## EmfPlusMultiplyWorldTransform class

L'enregistrement EmfPlusMultiplyWorldTransform multiplie la transformation de l'espace univers actuel par une matrice de transformation spécifiée.

```csharp
public sealed class EmfPlusMultiplyWorldTransform : EmfPlusTerminalServerRecordType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EmfPlusMultiplyWorldTransform](emfplusmultiplyworldtransform)(EmfPlusRecord) | Initialise une nouvelle instance du[`EmfPlusMultiplyWorldTransform`](../emfplusmultiplyworldtransform) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Obtient ou définit un entier non signé 32 bits qui DOIT définir le nombre aligné sur 32 bits de octets de données dans le champ RecordData qui suit. Ce numéro n'inclut pas l'en-tête d'enregistrement de 12 octets. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Obtient ou définit un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont l'opération doit être effectuée et sur la structure de l'enregistrement. |
| [MatrixData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusmultiplyworldtransform/matrixdata) { get; set; } | Obtient ou définit un objet EmfPlusTransformMatrix (section 2.2.2.47) qui définit la matrice de multiplication. |
| [PostMultipliedMatrix](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusmultiplyworldtransform/postmultipliedmatrix) { get; } | Obtient une valeur indiquant si [matrice post-multipliée]. Si elle est définie, la matrice de transformation doit être post-multipliée. S'il est clair, il doit être prémultiplié. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie le nombre d'octets alignés sur 32 bits dans l'enregistrement entier, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |

### Voir également

* class [EmfPlusTerminalServerRecordType](../emfplusterminalserverrecordtype)
* espace de noms [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
