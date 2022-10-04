---
title: WmfClipPrecisionFlags
second_title: Aspose.Imaging für .NET-API-Referenz
description: ClipPrecision-Flags geben die Clipping-Präzision an die definiert wie Zeichen abgeschnitten werden die teilweise außerhalb eines Clipping-Bereichs liegen. Diese Flags können kombiniert werden um mehrere Optionen anzugeben.
type: docs
weight: 8130
url: /de/net/aspose.imaging.fileformats.wmf.consts/wmfclipprecisionflags/
---
## WmfClipPrecisionFlags enumeration

ClipPrecision-Flags geben die Clipping-Präzision an, die definiert, wie Zeichen abgeschnitten werden, die teilweise außerhalb eines Clipping-Bereichs liegen. Diese Flags können kombiniert werden, um mehrere Optionen anzugeben.

```csharp
[Flags]
public enum WmfClipPrecisionFlags : byte
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Default | `0` | Gibt an, dass Standard-Clipping verwendet werden MUSS. |
| Character | `1` | Dieser Wert SOLLTE NICHT verwendet werden. |
| Stroke | `2` | Dieser Wert KANN zurückgegeben werden, wenn gerasterte, TrueType- und Vektorschriftarten aufgelistet werden. [33] (Windows NT 3.1, Windows NT 3.5, Windows NT 3.51, Windows NT 4.0, Windows 2000 und Windows XP: Dieser Wert wird immer zurückgegeben, wenn Schriftarten aufzählen.) |
| LhAngles | `10` | Dieser Wert wird verwendet, um die Drehung der Schriftart wie folgt zu steuern: - Wenn festgelegt, SOLLTE die Drehung für alle Schriftarten durch die Ausrichtung des Koordinatensystems bestimmt werden; das heißt, ob die Ausrichtung linkshändig oder rechtshändig ist. - Wenn klar, SOLLTEN Geräteschriftarten gegen den Uhrzeigersinn rotieren, aber die Drehung von anderen Schriftarten SOLLTE durch die Ausrichtung des Koordinatensystems bestimmt werden. |
| TtAlways | `20` | Dieser Wert SOLLTE NICHT [34] verwendet werden. [34] Dieser Wert wird in den folgenden Windows-Versionen ignoriert: - Windows Vista - Windows Server 2008 - Windows 7 - Windows Server 2008 R2 - Windows 8 - Windows Server 2012_x00d - Windows.x00d_ 8.1 - Windows Server 2012 R2 |
| DfaDisable | `40` | Dieser Wert gibt an, dass die Schriftzuordnung deaktiviert werden SOLLTE [35]. [35] Dieser Wert wird nicht unterstützt. in Windows 95, Windows 98 und Windows Millennium Edition. und Windows Server 2003. Dieser Wert wird in diesen Windows-Versionen ignoriert: - Windows Vista - Windows Server 2008 - Windows 7 - Windows Server 2008 R2 - Windows 8 - Windows Server 2012 - Windows 8.1 - Windows 8.1 - Windows Server 202 |
| Embedded | `80` | Dieser Wert gibt an, dass die Schriftarteinbettung verwendet werden MUSS, um den Inhalt von document wiederzugeben; Eingebettete Schriftarten sind schreibgeschützt. |

### Siehe auch

* namensraum [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->