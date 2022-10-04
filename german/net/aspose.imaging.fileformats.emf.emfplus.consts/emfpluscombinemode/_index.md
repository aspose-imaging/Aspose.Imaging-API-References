---
title: EmfPlusCombineMode
second_title: Aspose.Imaging für .NET-API-Referenz
description: Die CombineMode-Enumeration definiert Modi zum Kombinieren zweier Grafikbereiche. In den folgenden Beschreibungen werden die zu kombinierenden Regionen als bestehende und neue Regionen bezeichnet.
type: docs
weight: 4710
url: /de/net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscombinemode/
---
## EmfPlusCombineMode enumeration

Die CombineMode-Enumeration definiert Modi zum Kombinieren zweier Grafikbereiche. In den folgenden Beschreibungen werden die zu kombinierenden Regionen als "bestehende" und "neue" Regionen bezeichnet.

```csharp
public enum EmfPlusCombineMode : byte
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| CombineModeReplace | `0` | Ersetzt die vorhandene Region durch die neue Region. |
| CombineModeIntersect | `1` | Ersetzt die vorhandene Region durch die Schnittmenge der vorhandenen Region und der neuen Region. |
| CombineModeUnion | `2` | Ersetzt die vorhandene Region durch die Vereinigung der vorhandenen und neuen Regionen. |
| CombineModeXor | `3` | Ersetzt die vorhandene Region durch das XOR der vorhandenen und neuen Regionen. |
| CombineModeExclude | `4` | Ersetzt die vorhandene Region durch den Teil von sich selbst, der sich nicht in der neuen Region befindet. |
| CombineModeComplement | `5` | Ersetzt die vorhandene Region durch den Teil der neuen Region, der sich nicht in der vorhandenen Region befindet. |

### Siehe auch

* namensraum [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->