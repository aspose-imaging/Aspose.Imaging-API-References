---
title: EmfPlusBeginContainerNoParams
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lenregistrement EmfPlusBeginContainerNoParams ouvre un nouveau conteneur détat graphique.
type: docs
weight: 5850
url: /fr/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainernoparams/
---
## EmfPlusBeginContainerNoParams class

L'enregistrement EmfPlusBeginContainerNoParams ouvre un nouveau conteneur d'état graphique.

```csharp
public sealed class EmfPlusBeginContainerNoParams : EmfPlusStateRecordType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EmfPlusBeginContainerNoParams](emfplusbegincontainernoparams)(EmfPlusRecord) | Initialise une nouvelle instance du[`EmfPlusBeginContainerNoParams`](../emfplusbegincontainernoparams) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Obtient ou définit un entier non signé 32 bits qui DOIT définir le nombre aligné sur 32 bits de octets de données dans le champ RecordData qui suit. Ce numéro n'inclut pas l'en-tête d'enregistrement de 12 octets. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Obtient ou définit un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont l'opération doit être effectuée et sur la structure de l'enregistrement. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie le nombre d'octets alignés sur 32 bits dans l'enregistrement entier, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| [StackIndex](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainernoparams/stackindex) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie un index à associer au conteneur d'état graphique . L'index DOIT être référencé par un enregistrement subséquent EmfPlusEndContainer (section 2.3.7.3) pour fermer le conteneur d'état graphique. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |

### Voir également

* class [EmfPlusStateRecordType](../emfplusstaterecordtype)
* espace de noms [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
