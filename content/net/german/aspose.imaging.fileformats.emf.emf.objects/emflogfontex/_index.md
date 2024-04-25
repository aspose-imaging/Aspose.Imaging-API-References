---
title: EmfLogFontEx
second_title: Aspose.Imaging für .NET-API-Referenz
description: Das LogFontEx-Objekt gibt die erweiterten Attribute einer logischen Schriftart an.
type: docs
weight: 3040
url: /de/aspose.imaging.fileformats.emf.emf.objects/emflogfontex/
---
## EmfLogFontEx class

Das LogFontEx-Objekt gibt die erweiterten Attribute einer logischen Schriftart an.

```csharp
public class EmfLogFontEx : EmfLogFont
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [EmfLogFontEx](emflogfontex)(EmfLogFont) | Initialisiert eine neue Instanz von[`EmfLogFontEx`](../emflogfontex) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CharSet](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/charset) { get; set; } | Ruft eine 8-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die den Satz von Zeichenglyphen angibt. Es MUSS ein Wert in der WMF-Zeichensatzaufzählung sein ([MS-WMF] Abschnitt 2.1.1.5). Wenn der -Zeichensatz unbekannt ist, SOLLTE die Metadateiverarbeitung NICHT versuchen, -Strings zu übersetzen oder zu interpretieren, die mit dieser Schriftart wiedergegeben werden. |
| [ClipPrecision](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/clipprecision) { get; set; } | Ruft eine 8-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die die Abschneidegenauigkeit angibt. Die Clipping-Präzision definiert, wie Zeichen abgeschnitten werden, die sich teilweise außerhalb des Clipping-Bereichs befinden. Dies kann eines oder mehrere der WMF ClipPrecision Flags sein |
| [Escapement](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/escapement) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt sie fest, die den Winkel in Zehntel Grad zwischen dem Escape-Vektor und der x-Achse des Geräts angibt. Der Hemmungsvektor ist parallel zur Grundlinie einer Textzeile. |
| [Facename](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/facename) { get; set; } | Ruft einen Gesichtsnamen (64 Bytes) ab oder legt ihn fest: Eine Zeichenfolge mit nicht mehr als 32 Unicode-Zeichen, die den -Schriftartnamen der Schriftart angibt. Wenn die Länge dieser Zeichenfolge weniger als 32 Zeichen beträgt, MUSS eine abschließende NULL vorhanden sein, danach MUSS der Rest dieses Felds ignoriert werden. |
| [FullName](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontex/fullname) { get; set; } | Ruft eine Zeichenfolge mit 64 Unicode-Zeichen ab oder legt sie fest, die den vollständigen Namen der Schriftart enthält. Wenn die Länge dieser Zeichenfolge weniger als 64 Zeichen beträgt, MUSS eine abschließende NULL vorhanden sein, nach , die der Rest dieses Felds ignoriert werden MUSS. |
| [Height](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/height) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die Höhe der Zeichenzelle oder des Zeichens der Schriftart in logischen Einheiten angibt. Der Zeichenhöhenwert, auch als em-Größe bezeichnet, ist der -Zeichenzellenhöhenwert abzüglich des internen Zeilenabstandswerts. Der Font-Mapper SOLLTE den im Feld Höhe angegebenen Wert folgendermaßen interpretieren. |
| [Italic](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/italic) { get; set; } | Ruft eine 8-Bit-Ganzzahl ohne Vorzeichen ab oder legt sie fest, die eine kursive Schriftart angibt, wenn sie auf 0x01 gesetzt ist; andernfalls MUSS es auf 0x00 gesetzt werden. |
| [Orientation](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/orientation) { get; set; } | Ruft eine vorzeichenbehaftete 32-Bit-Ganzzahl ab oder legt diese fest, die den Winkel in Zehntel Grad zwischen der Grundlinie jedes Zeichens und der x-Achse des Geräts angibt. |
| [OutPrecision](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/outprecision) { get; set; } | Ruft eine 8-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die die Ausgabegenauigkeit angibt. Die -Ausgabepräzision definiert, wie genau die Schriftart erforderlich ist, um der angeforderten Höhe, Breite, -Zeichenausrichtung, dem Escapezeichen, der Teilung und dem Schriftarttyp zu entsprechen. Es MUSS ein Wert aus der WMF OutPrecision Enumeration sein |
| [PitchAndFamily](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/pitchandfamily) { get; set; } | Ruft ein WMF PitchAndFamily-Objekt ab oder legt es fest ([MS-WMF] Abschnitt 2.2.2.14), das die Tonhöhe und Familie der Schriftart angibt. Schriftfamilien beschreiben das Aussehen einer Schrift auf allgemeine -Weise. Sie sind zum Festlegen einer Schriftart vorgesehen, wenn die angegebene Schriftart nicht verfügbar ist. |
| [Quality](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/quality) { get; set; } | Ruft eine 8-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die die Ausgabequalität angibt. Die Ausgabequalität definiert, wie genau versucht werden soll, die logischen Schriftartattribute mit denen einer tatsächlichen physischen Schriftart abzugleichen. Es MUSS einer der Werte in der WMF FontQuality-Enumeration sein ([MS-WMF] Abschnitt 2.1.1.10). |
| [Script](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontex/script) { get; set; } | Ruft eine Zeichenfolge von 32 Unicode-Zeichen ab oder legt diese fest, die den Zeichensatz der Schriftart definiert. Wenn die Länge dieser Zeichenfolge weniger als 32 Zeichen beträgt, MUSS eine abschließende NULL vorhanden sein, danach MUSS der Rest dieses Felds ignoriert werden. |
| [Strikeout](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/strikeout) { get; set; } | Ruft eine 8-Bit-Ganzzahl ohne Vorzeichen ab oder legt sie fest, die eine durchgestrichene Schriftart angibt, wenn sie auf 0x01 festgelegt ist; andernfalls MUSS es auf 0x00 gesetzt werden. |
| [Style](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontex/style) { get; set; } | Ruft eine Zeichenfolge von 32 Unicode-Zeichen ab oder legt diese fest, die den Stil der Schriftart definiert. Wenn die Länge von dieser Zeichenfolge weniger als 32 Zeichen beträgt, MUSS eine abschließende NULL vorhanden sein, danach MUSS der Rest dieses Felds ignoriert werden. |
| [Underline](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/underline) { get; set; } | Ruft eine 8-Bit-Ganzzahl ohne Vorzeichen ab oder legt sie fest, die eine unterstrichene Schriftart angibt, wenn sie auf 0x01 gesetzt ist; andernfalls MUSS es auf 0x00 gesetzt werden. |
| [Weight](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/weight) { get; set; } | Ruft eine vorzeichenbehaftete 32-Bit-Ganzzahl ab oder legt diese fest, die die Breite der Schriftart im Bereich von null bis 1000 angibt. Beispielsweise ist 400 normal und 700 fett. Wenn dieser Wert Null ist, kann ein standardmäßiges -Gewicht verwendet werden. |
| [Width](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/width) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die durchschnittliche Breite von Zeichen in der Schriftart in logischen Einheiten angibt. Wenn der Wert des Breitenfelds Null ist, SOLLTE ein geeigneter Wert aus anderen LogFont-Werten berechnet werden, um eine Schriftart zu finden, die das vom Typografen beabsichtigte -Seitenverhältnis hat. |

### Siehe auch

* class [EmfLogFont](../emflogfont)
* namensraum [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
