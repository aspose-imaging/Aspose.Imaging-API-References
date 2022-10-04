---
title: EmfPlusDriverStringOptionsFlags
second_title: Aspose.Imaging für .NET-API-Referenz
description: Die DriverStringOptions-Flags geben Eigenschaften der Grafiktextpositionierung und -wiedergabe an. Diese Flags können kombiniert werden um mehrere Optionen anzugeben.
type: docs
weight: 4790
url: /de/net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusdriverstringoptionsflags/
---
## EmfPlusDriverStringOptionsFlags enumeration

Die DriverStringOptions-Flags geben Eigenschaften der Grafiktextpositionierung und -wiedergabe an. Diese Flags können kombiniert werden, um mehrere Optionen anzugeben.

```csharp
[Flags]
public enum EmfPlusDriverStringOptionsFlags
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| DriverStringOptionsCmapLookup | `1` | Wenn gesetzt, SOLLTEN die Positionen von Zeichenglyphen in einer Zeichentabellen-Nachschlagetabelle angegeben werden. Wenn klar, SOLLTEN die Glyphenpositionen aus einem Array von Koordinaten abgerufen werden. |
| DriverStringOptionsVertical | `2` | Wenn gesetzt, SOLLTE der String vertikal gerendert werden. Wenn frei, SOLLTE der String horizontal gerendert werden. |
| DriverStringOptionsRealizedAdvance | `4` | Wenn gesetzt, SOLLTEN die Zeichen-Glyphenpositionen relativ zur Position der ersten Glyphe berechnet werden. Wenn frei, SOLLTEN die Glyphenpositionen aus einem Array von Koordinaten bezogen werden. |
| DriverStringOptionsLimitSubpixel | `8` | Wenn festgelegt, SOLLTE weniger Speicher verwendet werden, um Anti-Aliasing-Glyphen zwischenzuspeichern, was zu einer Textwiedergabe mit geringerer Qualität führt. Wenn klar, SOLLTE mehr Speicher verwendet werden, was zu einer Textwiedergabe mit höherer Qualität führt. |

### Bemerkungen

Grafiktextausgabe ist spezifiziert in[`EmfPlusDrawDriverString`](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring) Datensätze

### Siehe auch

* namensraum [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->