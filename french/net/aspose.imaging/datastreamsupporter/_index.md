---
title: DataStreamSupporter
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Le conteneur de flux de données.
type: docs
weight: 810
url: /fr/net/aspose.imaging/datastreamsupporter/
---
## DataStreamSupporter class

Le conteneur de flux de données.

```csharp
public abstract class DataStreamSupporter : DisposableObject
```

## Propriétés

| Nom | La description |
| --- | --- |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Obtient le flux de données de l'objet. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtient une valeur indiquant si cette instance est supprimée. |
| abstract [IsCached](../../aspose.imaging/datastreamsupporter/iscached) { get; } | Obtient une valeur indiquant si les données de l'objet sont actuellement mises en cache et qu'aucune lecture de données n'est requise. |

## Méthodes

| Nom | La description |
| --- | --- |
| abstract [CacheData](../../aspose.imaging/datastreamsupporter/cachedata)() | Met en cache les données et garantit qu'aucun chargement de données supplémentaire ne sera effectué à partir du sous-jacent[`DataStreamContainer`](./datastreamcontainer) . |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Supprime l'instance actuelle. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save#save)() | Enregistre les données de l'objet dans la[`DataStreamSupporter`](../datastreamsupporter) . |
| [Save](../../aspose.imaging/datastreamsupporter/save#save_1)(Stream) | Enregistre les données de l'objet dans le flux spécifié. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save#save_2)(string) | Enregistre les données de l'objet à l'emplacement de fichier spécifié. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save#save_3)(string, bool) | Enregistre les données de l'objet à l'emplacement de fichier spécifié. |

### Voir également

* class [DisposableObject](../disposableobject)
* espace de noms [Aspose.Imaging](../../aspose.imaging)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
