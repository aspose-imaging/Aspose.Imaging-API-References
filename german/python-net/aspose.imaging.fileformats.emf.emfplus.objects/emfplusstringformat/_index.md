---
title: "EmfPlusStringFormat Class"
type: docs
weight: 650
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/
---

**Summary:** The EmfPlusStringFormat object specifies text layout,<br/>            display manipulations, and language identification

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStringFormat

**Inheritance:** EmfPlusGraphicsObjectType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusStringFormat()](#EmfPlusStringFormat__1) | Initialisiert eine neue Instanz der EmfPlusStringFormat‑Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| digit_language | [EmfPlusLanguageIdentifierType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslanguageidentifiertype/) | r/w | Liest oder setzt ein EmfPlusLanguageIdentifier‑Objekt, das die<br/>            Sprache angibt, die für numerische Ziffern im String verwendet werden soll.<br/>            Zum Beispiel, wenn dieser String arabische Ziffern enthält,<br/>            muss dieses Feld einen Sprachidentifikator enthalten, der<br/>            eine arabische Sprache angibt. |
| digit_substitution | [EmfPlusStringDigitSubstitution](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringdigitsubstitution/) | r/w | Liest oder setzt eine vorzeichenlose 32‑Bit‑Ganzzahl, die angibt, wie numerische Ziffern im String gemäß einer Gebietsschema‑ oder Sprachdefinition ersetzt werden sollen.<br/>            Dieser Wert MUSS in der StringDigitSubstitution‑Aufzählung (Abschnitt 2.1.1.30) definiert sein. |
| first_tab_offset | float | r/w | Ruft einen 32‑Bit‑Gleitkommawert ab oder legt ihn fest, der die Anzahl\n            von Leerzeichen zwischen dem Beginn einer Textzeile und\n            dem ersten Tabulatorstopp angibt |
| hotkey_prefix | [EmfPlusHotkeyPrefix](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplushotkeyprefix/) | r/w | Ruft einen 32‑Bit‑vorzeichenbehafteten Integer ab oder legt ihn fest, der den Typ der\n            Verarbeitung angibt, die an einem String durchgeführt wird, wenn ein Tastenkombinationspräfix (also ein Und‑Zeichen) gefunden wird.\n            Im Wesentlichen legt dieses Feld fest, ob Tastenkombinationspräfixe, die sich auf Text beziehen, angezeigt werden.\n            Der Wert MUSS in der HotkeyPrefix‑Aufzählung definiert sein\n            (Abschnitt 2.1.1.14). |
| language | [EmfPlusLanguageIdentifierType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslanguageidentifiertype/) | r/w | Ruft ein EmfPlusLanguageIdentifier‑Objekt ab oder legt es fest (Abschnitt 2.2.2.23)\n            das die für den String zu verwendende Sprache angibt |
| leading_margin | float | r/w | Ruft einen 32‑Bit‑Gleitkommawert ab oder legt ihn fest, der die Länge\n            des Abstandes angibt, der zur Ausgangsposition eines Strings hinzugefügt wird.\n            Der Standardwert ist 1/6 Zoll; für typografische Schriftarten beträgt der\n            Standardwert 0. |
| line_align | [EmfPlusStringAlignment](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringalignment/) | r/w | Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der angibt, wie der String vertikal im Layout‑Rechteck ausgerichtet wird.\n            Dieser Wert MUSS in der StringAlignment‑Aufzählung definiert sein. |
| range_count | int | r/w | Ruft einen 32‑Bit‑vorzeichenbehafteten Integer ab oder legt ihn fest, der die Anzahl der EmfPlusCharacterRange‑Objekte\n            (Abschnitt 2.2.2.8) im Feld StringFormatData angibt. |
| string_alignment | [EmfPlusStringAlignment](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringalignment/) | r/w | Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der angibt, wie der String horizontal im Layout‑Rechteck ausgerichtet wird.\n            Dieser Wert MUSS in der StringAlignment‑Aufzählung\n            (Abschnitt 2.1.1.29) definiert sein. |
| string_format_data | [EmfPlusStringFormatData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata/) | r/w | Ruft ein EmfPlusStringFormatData‑Objekt ab oder legt es fest (Abschnitt 2.2.2.44)\n            das optionale Textlayout‑Daten angibt. |
| string_format_flags | [EmfPlusStringFormatFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringformatflags/) | r/w | Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der Textlayout‑Optionen für Formatierung, Beschneidung und Schriftartenverwaltung angibt.\n            Dieser Wert MUSS aus StringFormat‑Flags bestehen\n            (Abschnitt 2.1.2.8). |
| tabstop_count | int | r/w | Ruft einen 32‑Bit‑vorzeichenbehafteten Integer ab oder legt ihn fest, der die Anzahl der Tabstopps\n            im Feld StringFormatData definiert. |
| tracking | float | r/w | Ruft einen 32‑Bit‑Gleitkommawert ab oder legt ihn fest, der das Verhältnis\n            des horizontalen Raums, der jedem Zeichen in einem angegebenen String zugewiesen wird, zur schriftdefinierten Breite des\n            Zeichens angibt. Hohe Werte für diese Eigenschaft bedeuten großzügigen\n            Abstand zwischen den Zeichen; Werte kleiner als 1 können zu\n            Zeichenüberlappungen führen. Der Standardwert ist 1,03; für typografische\n            Schriftarten beträgt der Standardwert 1,00. |
| trailing_margin | float | r/w | Ruft einen 32‑Bit‑Gleitkommawert ab oder legt ihn fest, der die Länge\n            des Abstandes angibt, der nach einem String freigelassen wird. Der Standardwert\n            ist 1/6 Zoll; für typografische Schriftarten beträgt der Standardwert 0. |
| trimming | [EmfPlusStringTrimming](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringtrimming/) | r/w | Ruft ab oder legt fest, wie Zeichen aus einem String abgeschnitten werden, der zu groß ist, um in ein Layout‑Rechteck zu passen. Dieser Wert MUSS in der StringTrimming‑Aufzählung definiert sein (Abschnitt 2.1.1.31). |
| version | [EmfPlusGraphicsVersion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/) | r/w | Liest oder setzt die Version. |


### Constructor: EmfPlusStringFormat() {#EmfPlusStringFormat__1}


```
 EmfPlusStringFormat() 
```

Initialisiert eine neue Instanz der EmfPlusStringFormat‑Klasse

