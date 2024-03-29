---
title: EmfPolygon16
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lenregistrement EMR_POLYGON16 spécifie un polygone composé de deux sommets ou plus reliés par lignes droites. Le polygone est délimité à laide du stylo actuel et rempli à laide du pinceau actuel et du mode de remplissage du polygone. Le polygone est fermé automatiquement en traçant une ligne du dernier sommet au premier.
type: docs
weight: 4090
url: /fr/net/aspose.imaging.fileformats.emf.emf.records/emfpolygon16/
---
## EmfPolygon16 class

L'enregistrement EMR_POLYGON16 spécifie un polygone composé de deux sommets ou plus reliés par lignes droites. Le polygone est délimité à l'aide du stylo actuel et rempli à l'aide du pinceau actuel et du mode de remplissage du polygone. Le polygone est fermé automatiquement en traçant une ligne du dernier sommet au premier.

```csharp
public sealed class EmfPolygon16 : EmfDrawingRecordType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EmfPolygon16](emfpolygon16#constructor)() | Initialise une nouvelle instance du[`EmfPolygon16`](../emfpolygon16) classe. |
| [EmfPolygon16](emfpolygon16#constructor_1)(EmfRecord) | Initialise une nouvelle instance du[`EmfPolygon16`](../emfpolygon16) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [APoints](../../aspose.imaging.fileformats.emf.emf.records/emfpolygon16/apoints) { get; set; } | Obtient ou définit un tableau de longueur de comptage d'objets WMF PointS, spécifié dans [MS-WMF] section 2.2.2.16, qui spécifie le tableau de points. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfpolygon16/bounds) { get; set; } | Obtient ou définit un objet WMF RectL 128 bits, spécifié dans [MS-WMF] section 2.2.2.19, qui spécifie le rectangle englobant, en unités de périphérique. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Obtient ou définit la taille de l'enregistrement |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Obtient ou définit le type. |

### Remarques

Le polygone DEVRAIT être délimité à l'aide du stylo actuel et rempli à l'aide du pinceau actuel et du mode de remplissage du polygone . Le polygone DEVRAIT être fermé automatiquement en traçant une ligne du dernier sommet au premier

### Voir également

* class [EmfDrawingRecordType](../emfdrawingrecordtype)
* espace de noms [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
