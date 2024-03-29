---
title: EmfPlusCombineMode
second_title: Aspose.Imaging för .NET API-referens
description: CombineMode-uppräkningen definierar lägen för att kombinera två grafikområden. I följande beskrivningar hänvisas till regionerna som ska kombineras som befintliga och nya regioner.
type: docs
weight: 4710
url: /sv/net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscombinemode/
---
## EmfPlusCombineMode enumeration

CombineMode-uppräkningen definierar lägen för att kombinera två grafikområden. I följande beskrivningar hänvisas till regionerna som ska kombineras som "befintliga" och "nya" regioner.

```csharp
public enum EmfPlusCombineMode : byte
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| CombineModeReplace | `0` | Ersätter den befintliga regionen med den nya regionen. |
| CombineModeIntersect | `1` | Ersätter den befintliga regionen med skärningspunkten mellan den befintliga regionen och den nya regionen. |
| CombineModeUnion | `2` | Ersätter den befintliga regionen med föreningen av befintliga och nya regioner. |
| CombineModeXor | `3` | Ersätter den befintliga regionen med XOR för de befintliga och nya regionerna. |
| CombineModeExclude | `4` | Ersätter den befintliga regionen med den del av sig själv som inte finns i den nya regionen. |
| CombineModeComplement | `5` | Ersätter den befintliga regionen med den del av den nya regionen som inte finns i den befintliga regionen. |

### Se även

* namnutrymme [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
