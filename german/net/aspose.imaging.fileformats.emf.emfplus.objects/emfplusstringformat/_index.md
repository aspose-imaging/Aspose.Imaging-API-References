---
title: EmfPlusStringFormat
second_title: Aspose.Imaging für .NET-API-Referenz
description: Das EmfPlusStringFormat-Objekt gibt das Textlayout Anzeigemanipulationen und die Sprachidentifikation an
type: docs
weight: 5780
url: /de/net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/
---
## EmfPlusStringFormat class

Das EmfPlusStringFormat-Objekt gibt das Textlayout, Anzeigemanipulationen und die Sprachidentifikation an

```csharp
public sealed class EmfPlusStringFormat : EmfPlusGraphicsObjectType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [EmfPlusStringFormat](emfplusstringformat)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [DigitLanguage](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/digitlanguage) { get; set; } | Ruft ein EmfPlusLanguageIdentifier-Objekt ab oder legt es fest, das die Sprache angibt, die für numerische Ziffern in der Zeichenfolge verwendet werden soll. Wenn diese Zeichenfolge beispielsweise arabische Ziffern enthält, MUSS dieses Feld eine Sprachkennung enthalten, die eine arabische Sprache angibt |
| [DigitSubstitution](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/digitsubstitution) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt sie fest, die angibt, wie numerische Ziffern in der Zeichenfolge gemäß einem Gebietsschema oder einer Sprache ersetzt werden. Dieser Wert MUSS in der StringDigitSubstitution -Enumeration (Abschnitt 2.1.1.30) definiert werden. |
| [FirstTabOffset](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/firsttaboffset) { get; set; } | Liest oder setzt einen 32-Bit-Gleitkommawert, der die Anzahl von Leerzeichen zwischen dem Anfang einer Textzeile und dem ersten Tabstopp angibt |
| [HotkeyPrefix](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/hotkeyprefix) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt sie fest, die die Art der -Verarbeitung angibt, die an einer Zeichenfolge ausgeführt wird, wenn ein Tastaturkürzel-Präfix (d. h. ein kaufmännisches Und) gefunden wird. Im Grunde gibt dieses Feld an, ob das Tastaturkürzel-Präfix angezeigt werden soll beziehen sich auf Text. Der Wert MUSS in der HotkeyPrefix Enumeration (Abschnitt 2.1.1.14) definiert werden. |
| [Language](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/language) { get; set; } | Ruft ein EmfPlusLanguageIdentifier-Objekt ab oder legt es fest (Abschnitt 2.2.2.23) , das die für die Zeichenfolge zu verwendende Sprache angibt |
| [LeadingMargin](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/leadingmargin) { get; set; } | Ruft einen 32-Bit-Gleitkommawert ab oder legt ihn fest, der die Länge des Leerzeichens angibt, das an der Anfangsposition einer Zeichenfolge hinzugefügt werden soll. Der Standardwert ist 1/6 Zoll; für typografische Schriftarten ist der Standardwert 0. |
| [LineAlign](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/linealign) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt sie fest, die angibt, wie die Zeichenfolge vertikal im Layoutrechteck ausgerichtet wird. Dieser Wert MUSS in der StringAlignment-Enumeration definiert werden. |
| [RangeCount](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/rangecount) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt sie fest, die die Anzahl der EmfPlusCharacterRange -Objekte (Abschnitt 2.2.2.8) angibt, die im Feld „StringFormatData“ definiert sind. |
| [StringAlignment](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/stringalignment) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt sie fest, die angibt, wie die Zeichenfolge horizontal im Layoutrechteck ausgerichtet wird. Dieser Wert MUSS in der StringAlignment -Enumeration (Abschnitt 2.1.1.29) definiert werden. |
| [StringFormatData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/stringformatdata) { get; set; } | Ruft ein EmfPlusStringFormatData-Objekt ab oder legt es fest (Abschnitt 2.2.2.44) , das optionale Textlayoutdaten angibt. |
| [StringFormatFlags](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/stringformatflags) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt sie fest, die Optionen für das Textlayout für Formatierung, Beschneidung und Schriftbehandlung angibt. Dieser Wert MUSS aus StringFormat-Flags (Abschnitt 2.1.2.8) bestehen. |
| [TabstopCount](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/tabstopcount) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die Anzahl der Tabstopps angibt, die im Feld „StringFormatData“ definiert sind. |
| [Tracking](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/tracking) { get; set; } | Ruft einen 32-Bit-Gleitkommawert ab oder legt ihn fest, der das Verhältnis des horizontalen Abstands, der jedem Zeichen in einer angegebenen Zeichenfolge zugewiesen ist, zur schriftartdefinierten Breite des -Zeichens angibt. Große Werte für diese Eigenschaft geben reichlich Platz zwischen den Zeichen an; Werte kleiner als 1 können zu einer Überlappung von Zeichen führen. Der Standardwert ist 1,03; für typografische -Schriftarten ist der Standardwert 1,00. |
| [TrailingMargin](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/trailingmargin) { get; set; } | Ruft einen 32-Bit-Gleitkommawert ab oder legt ihn fest, der die Länge des Leerzeichens angibt, das nach einer Zeichenfolge gelassen werden soll. Der default ist 1/6 Zoll; für typografische Schriftarten ist der Standardwert 0. |
| [Trimming](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/trimming) { get; set; } | Ruft ab oder legt fest, wie Zeichen aus einer Zeichenfolge abgeschnitten werden, die zu groß ist, um in ein Layoutrechteck zu passen. Dieser Wert MUSS in der StringTrimming-Aufzählung (Abschnitt 2.1.1.31) definiert werden. |
| [Version](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype/version) { get; set; } | Ruft die Version ab oder legt sie fest. |

### Siehe auch

* class [EmfPlusGraphicsObjectType](../emfplusgraphicsobjecttype)
* namensraum [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
