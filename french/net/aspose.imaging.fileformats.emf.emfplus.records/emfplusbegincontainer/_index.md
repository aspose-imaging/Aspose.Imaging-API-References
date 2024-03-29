---
title: EmfPlusBeginContainer
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lenregistrement EmfPlusBeginContainer ouvre un nouveau conteneur détat graphique et spécifie une transformation pour celui-ci.
type: docs
weight: 5840
url: /fr/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/
---
## EmfPlusBeginContainer class

L'enregistrement EmfPlusBeginContainer ouvre un nouveau conteneur d'état graphique et spécifie une transformation pour celui-ci.

```csharp
public sealed class EmfPlusBeginContainer : EmfPlusStateRecordType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EmfPlusBeginContainer](emfplusbegincontainer)(EmfPlusRecord) | Initialise une nouvelle instance du[`EmfPlusBeginContainer`](../emfplusbegincontainer) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Obtient ou définit un entier non signé 32 bits qui DOIT définir le nombre aligné sur 32 bits de octets de données dans le champ RecordData qui suit. Ce numéro n'inclut pas l'en-tête d'enregistrement de 12 octets. |
| [DestRect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/destrect) { get; set; } | Obtient ou définit un objet EmfPlusRectF (section 2.2.2.39) qui, avec SrcRect, spécifie une transformation pour le conteneur. Cette transformation donne SrcRect lorsqu'elle est appliquée à DestRect. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Obtient ou définit un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont l'opération doit être effectuée et sur la structure de l'enregistrement. |
| [PageUnit](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/pageunit) { get; } | Obtient l'unité de page. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie le nombre d'octets alignés sur 32 bits dans l'enregistrement entier, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| [SrcRect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/srcrect) { get; set; } | Obtient ou définit un rectangle EmfPlusRectF qui, avec DestRect, spécifie une transformation pour le conteneur. Cette transformation donne SrcRect lorsqu'elle est appliquée à DestRect. |
| [StackIndex](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/stackindex) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie un index à associer au conteneur d'état graphique . L'index DOIT être référencé par un enregistrement subséquent EmfPlusEndContainer (section 2.3.7.3) pour fermer le conteneur d'état graphique. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |

### Voir également

* class [EmfPlusStateRecordType](../emfplusstaterecordtype)
* espace de noms [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
