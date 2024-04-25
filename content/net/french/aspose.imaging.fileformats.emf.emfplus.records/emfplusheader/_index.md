---
title: EmfPlusHeader
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lenregistrement EmfPlusHeader spécifie le début des données EMF dans le métafichier. Lenregistrement EmfPlusHeader DOIT être intégré dans un enregistrement EMF EMR_COMMENT_EMFPLUS qui DOIT être lenregistrement suivant immédiatement len-tête EMF dans le métafichier. Lenregistrement EMR_COMMENT_EMFPLUS est spécifié dans MS-EMF section 2.3.3.2.
type: docs
weight: 6140
url: /fr/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/
---
## EmfPlusHeader class

L'enregistrement EmfPlusHeader spécifie le début des données EMF+ dans le métafichier. L'enregistrement EmfPlusHeader DOIT être intégré dans un enregistrement EMF EMR_COMMENT_EMFPLUS, qui DOIT être l'enregistrement suivant immédiatement l'en-tête EMF dans le métafichier. L'enregistrement EMR_COMMENT_EMFPLUS est spécifié dans [MS-EMF] section 2.3.3.2.

```csharp
public sealed class EmfPlusHeader : EmfPlusControlRecordType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EmfPlusHeader](emfplusheader)(EmfPlusRecord) | Initialise une nouvelle instance du[`EmfPlusHeader`](../emfplusheader) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Obtient ou définit un entier non signé 32 bits qui DOIT définir le nombre aligné sur 32 bits de octets de données dans le champ RecordData qui suit. Ce numéro n'inclut pas l'en-tête d'enregistrement de 12 octets. |
| [DualMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/dualmode) { get; set; } | Obtient ou définit une valeur indiquant si [dual mode]. S'il est défini, cet indicateur indique que ce métafichier est "dual-mode", ce qui signifie qu'il contient deux ensembles d'enregistrements, chacun spécifiant complètement le contenu graphique. S'il n'est pas défini, le contenu graphique est spécifié par des enregistrements EMF+ et éventuellement des enregistrements EMF précédés d'un enregistrement EmfPlusGetDC. Si cet indicateur est défini, les enregistrements EMF seuls DEVRAIENT suffire à définir le contenu graphique . Notez que, que l'indicateur "double mode" soit défini ou non, certains enregistrements EMF sont toujours présents, à savoir les enregistrements de contrôle EMF et les enregistrements EMF qui contiennent des enregistrements EMF+. Les enregistrements de contrôle EMF sont spécifiés dans [MS-EMF] section 2.3.4. |
| [EmfPlusFlags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/emfplusflags) { get; set; } | Obtient ou définit les indicateurs EMF plus. Un entier non signé de 32 bits qui contient des informations sur la façon dont ce métafichier a été enregistré. si le 31e bit du champ est défini, cet indicateur indique que le métafichier a été enregistré avec une référence contexte de périphérique pour un affichage vidéo. S'il est clair, le métafichier a été enregistré avec un contexte de périphérique de référence pour une imprimante. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Obtient ou définit un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont l'opération doit être effectuée et sur la structure de l'enregistrement. |
| [IsValid](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/isvalid) { get; } | Obtient une valeur indiquant si cette instance est valide. |
| [LogicalDpiX](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/logicaldpix) { get; set; } | Obtient ou définit le dpi logique x. Un entier non signé 32 bits qui spécifie la résolution horizontale pour laquelle le métafichier a été enregistré, en unités de pixels par pouce. |
| [LogicalDpiY](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/logicaldpiy) { get; set; } | Obtient ou définit le ppp logique y. Un entier non signé 32 bits qui spécifie la résolution verticale pour laquelle le métafichier a été enregistré, en unités de lignes par pouce |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie le nombre d'octets alignés sur 32 bits dans l'enregistrement entier, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |
| [Version](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/version) { get; set; } | Obtient ou définit la version. Un objet EmfPlusGraphicsVersion (section 2.2.2.19) qui spécifie la version des graphiques du système d'exploitation qui a été utilisée pour créer ce métafichier. |
| [VideoDisplay](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/videodisplay) { get; set; } | Obtient ou définit une valeur indiquant si la vidéo s'affiche. s'il est défini, cet indicateur indique que le métafichier a été enregistré avec un contexte de référence device pour un affichage vidéo. S'il est clair, le métafichier a été enregistré avec un contexte de référence device pour une imprimante. |

### Voir également

* class [EmfPlusControlRecordType](../emfpluscontrolrecordtype)
* espace de noms [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
