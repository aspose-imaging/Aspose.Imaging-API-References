---
title: EmfSetPolyFillMode
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lenregistrement EMR_SETPOLYFILLMODE définit le mode de remplissage du polygone.
type: docs
weight: 4460
url: /fr/net/aspose.imaging.fileformats.emf.emf.records/emfsetpolyfillmode/
---
## EmfSetPolyFillMode class

L'enregistrement EMR_SETPOLYFILLMODE définit le mode de remplissage du polygone.

```csharp
public sealed class EmfSetPolyFillMode : EmfStateRecordType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EmfSetPolyFillMode](emfsetpolyfillmode#constructor)() | Initialise une nouvelle instance du[`EmfSetPolyFillMode`](../emfsetpolyfillmode) classe. |
| [EmfSetPolyFillMode](emfsetpolyfillmode#constructor_1)(EmfRecord) | Initialise une nouvelle instance du[`EmfSetPolyFillMode`](../emfsetpolyfillmode) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [PolygonFillMode](../../aspose.imaging.fileformats.emf.emf.records/emfsetpolyfillmode/polygonfillmode) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie le mode de remplissage du polygone et DOIT être dans l'énumération PolygonFillMode (section 2.1.27). |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Obtient ou définit la taille de l'enregistrement |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Obtient ou définit le type. |

### Remarques

En général, les modes ne diffèrent que dans les cas où un polygone complexe qui se chevauche DOIT être rempli ; for exemple, un polygone à cinq côtés qui forme une étoile à cinq branches avec un pentagone au centre. Dans de tels cas, le mode ALTERNÉ DEVRAIT remplir toutes les autres régions fermées du polygone (les points de l'étoile), mais le mode ENROULEMENT DEVRAIT remplir toutes les régions (les points de l'étoile et du pentagone). Lorsque le mode de remplissage est ALTERNÉ, le la zone entre les côtés polygon impairs et pairs sur chaque ligne de balayage DEVRAIT être remplie. Autrement dit, la zone entre le premier et le deuxième côté DEVRAIT être remplie, et entre le troisième et le quatrième côté, et ainsi de suite. Lorsque le mode de remplissage est ENROULEMENT, toute région qui a une valeur d'enroulement non nulle DEVRAIT être remplie. L'enroulement value est le nombre de fois qu'un stylo utilisé pour dessiner le polygone ferait le tour de la région . La direction de chaque arête du polygone est significative.

### Voir également

* class [EmfStateRecordType](../emfstaterecordtype)
* espace de noms [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->