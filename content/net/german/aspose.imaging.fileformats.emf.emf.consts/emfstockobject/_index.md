---
title: EmfStockObject
second_title: Aspose.Imaging für .NET-API-Referenz
description: Die StockObject-Enumeration spezifiziert die Indizes von vordefinierten logischen Grafikobjekten  die in Grafikoperationen verwendet werden können. Die spezifischen Strukturen von Stock-Objekten sind implementierungsabhängig Die Eigenschaften von Bestandsobjekten SOLLTEN jedoch den Eigenschaften von explizit erstellten Objekten desselben Typs entsprechen. Diese Eigenschaften werden nach Möglichkeit für die in dieser Aufzählung definierten Bestandsobjekte angegeben.
type: docs
weight: 2860
url: /de/aspose.imaging.fileformats.emf.emf.consts/emfstockobject/
---
## EmfStockObject enumeration

Die StockObject-Enumeration spezifiziert die Indizes von vordefinierten logischen Grafikobjekten , die in Grafikoperationen verwendet werden können. Die spezifischen Strukturen von Stock-Objekten sind implementierungsabhängig; Die Eigenschaften von Bestandsobjekten SOLLTEN jedoch den Eigenschaften von explizit erstellten Objekten desselben Typs entsprechen. Diese Eigenschaften werden nach Möglichkeit für die in dieser Aufzählung definierten Bestandsobjekte angegeben.

```csharp
public enum EmfStockObject
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| WHITE_BRUSH | `-2147483648` | Ein weißer, einfarbiger Pinsel, der einem logischen Pinsel (LogBrushEx-Objekt, Abschnitt 2.2.12) mit den folgenden Eigenschaften entspricht: BrushStyle: BS_SOLID (WMF BrushStyle-Enumeration, [MS-WMF] Abschnitt 2.1.1.4) Farbe: 0x00FFFFFF (WMF ColorRef-Objekt, [MS-WMF] Abschnitt 2.2.2.8) |
| LTGRAY_BRUSH | `-2147483647` | Ein hellgrauer Volltonpinsel, der einem logischen Pinsel mit den folgenden Eigenschaften entspricht: Pinselstil: BS_SOLID Farbe: 0x00C0C0C0 |
| GRAY_BRUSH | `-2147483646` | Ein grauer Volltonpinsel, der einem logischen Pinsel mit den folgenden Eigenschaften entspricht: Pinselstil: BS_SOLID Farbe: 0x00808080 |
| DKGRAY_BRUSH | `-2147483645` | Ein dunkelgrauer Volltonpinsel, der einem logischen Pinsel mit den folgenden Eigenschaften entspricht: Pinselstil: BS_SOLID Farbe: 0x00404040 |
| BLACK_BRUSH | `-2147483644` | Ein schwarzer Volltonpinsel, der einem logischen Pinsel mit den folgenden Eigenschaften entspricht: Pinselstil: BS_SOLID Farbe: 0x00000000 |
| NULL_BRUSH | `-2147483643` | Ein Nullpinsel, der einem logischen Pinsel mit den folgenden Eigenschaften entspricht: BrushStyle: BS_NULL |
| WHITE_PEN | `-2147483642` | Ein weißer Volltonstift, der einem logischen Stift entspricht (LogPen-Objekt, Abschnitt 2.2.19) mit den folgenden Eigenschaften: PenStyle: PS_COSMETIC + PS_SOLID (PenStyle-Enumeration, Abschnitt 2.1.25) ColorRef: 0x00FFFFFF ( WMF ColorRef-Objekt). |
| BLACK_PEN | `-2147483641` | Ein schwarzer Volltonstift, der einem logischen Stift entspricht, mit den folgenden Eigenschaften: PenStyle: PS_COSMETIC + PS_SOLID ColorRef: 0x00000000 |
| NULL_PEN | `-2147483640` | Ein Nullstift, der einem logischen Stift mit den folgenden Eigenschaften entspricht: PenStyle: PS_NULL |
| OEM_FIXED_FONT | `-2147483638` | Eine OEM-Zeichensatzschriftart mit fester Breite, die einer logischen Schriftart (LogFont-Objekt, Abschnitt 2.2.13) mit den folgenden Eigenschaften entspricht: Charset: OEM_CHARSET (WMF CharacterSet-Enumeration, [MS-WMF] Abschnitt 2.1.1.5 ) PitchAndFamily: FF_DONTCARE (WMF FamilyFont-Aufzählung, [MS-WMF] Abschnitt 2.1.1.8) + FIXED_PITCH (WMF PitchFont-Aufzählung, [MS-WMF] Abschnitt 2.1.1.24) |
| ANSI_FIXED_FONT | `-2147483637` | Eine Schriftart mit fester Breite, die einer logischen Schriftart mit den folgenden Eigenschaften entspricht: Charset: ANSI_CHARSET PitchAndFamily: FF_DONTCARE + FIXED_PITCH |
| ANSI_VAR_FONT | `-2147483636` | Eine Schriftart mit variabler Breite, die einer logischen Schriftart mit den folgenden Eigenschaften entspricht: Charset: ANSI_CHARSET PitchAndFamily: FF_DONTCARE + VARIABLE_PITCH |
| SYSTEM_FONT | `-2147483635` | Eine Schriftart, die garantiert im Betriebssystem verfügbar ist. Die tatsächliche Schriftart, die durch diesen Wert angegeben wird, ist implementierungsabhängig |
| DEVICE_DEFAULT_FONT | `-2147483634` | Die Standardschriftart, die vom Grafikgerätetreiber für das aktuelle Ausgabegerät bereitgestellt wird. Die tatsächliche Schriftart, die durch diesen Wert angegeben wird, ist implementierungsabhängig |
| DEFAULT_PALETTE | `-2147483633` | Die Standardpalette, die für das aktuelle Ausgabegerät definiert ist. Die tatsächliche Palette, die durch diesen Wert angegeben wird, ist implementierungsabhängig |
| SYSTEM_FIXED_FONT | `-2147483632` | Eine Schriftart mit fester Breite, die garantiert im Betriebssystem verfügbar ist. Die tatsächliche Schriftart, die durch diesen Wert angegeben wird, ist implementierungsabhängig |
| DEFAULT_GUI_FONT | `-2147483631` | Eine Schriftart mit fester Breite, die garantiert im Betriebssystem verfügbar ist. Die tatsächliche Schriftart, die durch diesen Wert angegeben wird, ist implementierungsabhängig |
| DC_BRUSH | `-2147483630` | Der Volltonpinsel, der derzeit im Kontext des Wiedergabegeräts ausgewählt ist |
| DC_PEN | `-2147483629` | Der Farbstift, der derzeit im Kontext des Wiedergabegeräts ausgewählt ist |

### Siehe auch

* namensraum [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
