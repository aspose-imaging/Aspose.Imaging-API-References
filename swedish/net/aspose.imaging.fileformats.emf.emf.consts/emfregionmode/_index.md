---
title: EmfRegionMode
second_title: Aspose.Imaging för .NET API-referens
description: RegionMode-uppräkningen definierar värden som används med EMR_SELECTCLIPPATH och EMR_EXTSELECTCLIPRGN anger den aktuella sökvägen eller en ny region som kombineras med den aktuella klippregionen.
type: docs
weight: 2830
url: /sv/net/aspose.imaging.fileformats.emf.emf.consts/emfregionmode/
---
## EmfRegionMode enumeration

RegionMode-uppräkningen definierar värden som används med EMR_SELECTCLIPPATH och EMR_EXTSELECTCLIPRGN, anger den aktuella sökvägen eller en ny region som kombineras med den aktuella klippregionen.

```csharp
public enum EmfRegionMode
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| RGN_AND | `1` | Det nya klippområdet inkluderar skärningspunkten (överlappande områden) för det aktuella klippområdet och den aktuella banan (eller nya regionen). |
| RGN_OR | `2` | Den nya klippningsregionen inkluderar föreningen (kombinerade områden) av den aktuella klippningsregionen och den aktuella sökvägen (eller nya regionen). |
| RGN_XOR | `3` | Den nya klippningsregionen inkluderar föreningen av den aktuella klippningsregionen och den aktuella banan (eller nya regionen) men utan de överlappande områdena |
| RGN_DIFF | `4` | Den nya klippningsregionen inkluderar områdena i den aktuella klippningsregionen med de för den aktuella banan (eller nya regionen) uteslutna. |
| RGN_COPY | `5` | Den nya urklippsregionen är den aktuella sökvägen (eller den nya regionen). |

### Se även

* namnutrymme [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->