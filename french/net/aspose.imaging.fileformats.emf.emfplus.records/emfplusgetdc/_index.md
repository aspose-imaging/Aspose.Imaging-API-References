---
title: EmfPlusGetDc
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lenregistrement EmfPlusGetDC spécifie que les enregistrements EMF suivants rencontrés dans le métafichier DEVRAIENT être traités.
type: docs
weight: 6130
url: /fr/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusgetdc/
---
## EmfPlusGetDc class

L'enregistrement EmfPlusGetDC spécifie que les enregistrements EMF suivants rencontrés dans le métafichier DEVRAIENT être traités.

```csharp
public sealed class EmfPlusGetDc : EmfPlusControlRecordType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EmfPlusGetDc](emfplusgetdc)(EmfPlusRecord) | Initialise une nouvelle instance du[`EmfPlusGetDc`](../emfplusgetdc) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Obtient ou définit un entier non signé 32 bits qui DOIT définir le nombre aligné sur 32 bits de octets de données dans le champ RecordData qui suit. Ce numéro n'inclut pas l'en-tête d'enregistrement de 12 octets. |
| override [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusgetdc/flags) { get; set; } | Obtient ou définit un entier non signé 16 bits qui n'est pas utilisé. Ce champ DEVRAIT être défini sur zéro et DOIT être ignoré lors de la réception |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie le nombre d'octets alignés sur 32 bits dans l'enregistrement entier, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |

### Voir également

* class [EmfPlusControlRecordType](../emfpluscontrolrecordtype)
* espace de noms [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
