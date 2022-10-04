---
title: DataStreamSupporter
second_title: Aspose.Imaging för .NET API-referens
description: Dataströmsbehållaren.
type: docs
weight: 810
url: /sv/net/aspose.imaging/datastreamsupporter/
---
## DataStreamSupporter class

Dataströmsbehållaren.

```csharp
public abstract class DataStreamSupporter : DisposableObject
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Hämtar objektets dataström. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| abstract [IsCached](../../aspose.imaging/datastreamsupporter/iscached) { get; } | Får ett värde som indikerar om objektets data är cachad för närvarande och ingen dataläsning krävs. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| abstract [CacheData](../../aspose.imaging/datastreamsupporter/cachedata)() | Cachelagrar data och säkerställer att ingen ytterligare dataladdning kommer att utföras från det underliggande[`DataStreamContainer`](./datastreamcontainer) . |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Tar bort den aktuella instansen. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save#save)() | Sparar objektets data till den aktuella[`DataStreamSupporter`](../datastreamsupporter) . |
| [Save](../../aspose.imaging/datastreamsupporter/save#save_1)(Stream) | Sparar objektets data till den angivna strömmen. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save#save_2)(string) | Sparar objektets data till den angivna filplatsen. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save#save_3)(string, bool) | Sparar objektets data till den angivna filplatsen. |

### Se även

* class [DisposableObject](../disposableobject)
* namnutrymme [Aspose.Imaging](../../aspose.imaging)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->