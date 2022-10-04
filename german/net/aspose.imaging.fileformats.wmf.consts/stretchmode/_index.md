---
title: StretchMode
second_title: Aspose.Imaging für .NET-API-Referenz
description: DieStretchMode./stretchmodeDie Aufzählung gibt den Bitmap -Stretching-Modus an der definiert wie das System Zeilen oder Spalten einer Bitmap mit vorhandenen Pixeln kombiniert.
type: docs
weight: 8090
url: /de/net/aspose.imaging.fileformats.wmf.consts/stretchmode/
---
## StretchMode enumeration

Die[`StretchMode`](../stretchmode)Die Aufzählung gibt den Bitmap -Stretching-Modus an, der definiert, wie das System Zeilen oder Spalten einer Bitmap mit vorhandenen Pixeln kombiniert.

```csharp
public enum StretchMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| BlackOnWhite | `1` | Führt eine boolesche UND-Operation durch, indem die Farbwerte für die eliminierten und vorhandenen Pixel verwendet werden. Wenn die Bitmap eine monochrome Bitmap ist, behält dieser Modus schwarze Pixel auf Kosten von white Pixel bei. |
| WhiteOnBlack | `2` | Führt eine boolesche ODER-Operation durch, indem die Farbwerte für die eliminierten und vorhandenen Pixel verwendet werden. Wenn die Bitmap eine monochrome Bitmap ist, behält dieser Modus weiße Pixel auf Kosten von black Pixel bei. |
| ColorOnColor | `3` | Löscht die Pixel. Dieser Modus löscht alle eliminierten Pixelzeilen , ohne zu versuchen, ihre Informationen zu erhalten. |
| HalfTone | `4` | Ordnet Pixel aus dem Quellrechteck Pixelblöcken im Zielrechteck zu. Die durchschnittliche Farbe über den Zielblock von Pixeln entspricht in etwa der Farbe der Quellpixel. |

### Siehe auch

* namensraum [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->