---
title: "EmfLogFontEx Klasse"
type: docs
weight: 140
url: /de/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfontex/
---

**Summary:** The LogFontEx object specifies the extended attributes of a logical font.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfLogFontEx

**Inheritance:** EmfLogFont

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfLogFontEx(emf_log_font)](#EmfLogFontEx_emf_log_font_1) | Initialisiert eine neue Instanz der [EmfLogFontEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfontex/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| char_set | [WmfCharacterSet](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfcharacterset/) | r/w | Ruft ab oder legt ein 8‑Bit vorzeichenloses Integer fest, das den Satz von Zeichen‑Glyphen angibt. Es MUSS <br/>            ein Wert aus der WMF CharacterSet‑Aufzählung ([MS-WMF] Abschnitt 2.1.1.5) sein. Wenn der <br/>            Zeichensatz unbekannt ist, Metadateiverarbeitung SHOULD NOT versuchen, Zeichenketten, die mit dieser Schriftart gerendert werden, zu übersetzen oder zu interpretieren. |
| clip_precision | [WmfClipPrecisionFlags](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfclipprecisionflags/) | r/w | Ruft ab oder legt ein 8‑Bit vorzeichenloses Integer fest, das die Clipping‑Präzision angibt. Die <br/>            Clipping‑Präzision definiert, wie Zeichen, die teilweise außerhalb der Clipping‑Region liegen, abgeschnitten werden. <br/>            Sie kann einer oder mehreren der WMF ClipPrecision‑Flags entsprechen. |
| escapement | int | r/w | Ruft ab oder legt eine 32‑Bit vorzeichenbehaftete Ganzzahl fest, die den Winkel in Zehntelgrad <br/>            zwischen dem Escapement‑Vektor und der x‑Achse des Geräts angibt. Der Escapement‑Vektor ist <br/>            parallel zur Grundlinie einer Textzeile. |
| Schriftname | string | r/w | Ruft ab oder legt einen Facename (64 Bytes) fest:  Eine Zeichenkette von höchstens 32 Unicode‑Zeichen, die den <br/>            Schriftartnamen der Schriftart angibt. Wenn die Länge dieser Zeichenkette weniger als 32 Zeichen beträgt, ein abschließendes NULL MUST vorhanden sein, nach dem der Rest dieses Feldes MUST ignoriert werden. |
| full_name | string | r/w | Ruft ab oder legt eine Zeichenkette von 64 Unicode‑Zeichen fest, die den vollständigen Namen der Schriftart enthält. Wenn <br/>            die Länge dieser Zeichenkette weniger als 64 Zeichen beträgt, ein abschließendes NULL MUST vorhanden sein, nach dem der Rest dieses Feldes MUST ignoriert werden. |
| height | int | r/w | Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die Höhe, in logischen Einheiten, der Zeichenzelle oder des Zeichens der Schriftart angibt. <br/>            Der Zeichenhöhenwert, auch als Em‑Größe bekannt, ist der Wert der Zeichenzellenhöhe minus dem internen Führungswert. <br/>            Der Schriftarten‑Mapper SOLLTE den im Feld Height angegebenen Wert wie folgt interpretieren. |
| kursiv | System.Byte | r/w | Liest oder setzt eine 8‑Bit vorzeichenlose Ganzzahl, die eine kursive Schriftart angibt, wenn sie auf 0x01 gesetzt ist; andernfalls <br/>            MUSS sie auf 0x00 gesetzt werden. |
| Ausrichtung | int | r/w | Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die den Winkel in Zehntelgrad <br/>            zwischen der Grundlinie jedes Zeichens und der x‑Achse des Geräts angibt. |
| out_precision | [WmfOutPrecision](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfoutprecision/) | r/w | Liest oder setzt eine 8‑Bit vorzeichenlose Ganzzahl, die die Ausgabegenauigkeit angibt. Die <br/>            Ausgabegenauigkeit definiert, wie genau die Schriftart an die angeforderte Höhe, Breite, <br/>            Zeichenorientierung, Flucht, Pitch und Schriftarttyp angepasst werden muss. Sie MUSS ein Wert aus der WMF <br/>            OutPrecision‑Aufzählung sein. |
| pitch_and_family | [WmfPitchAndFamily](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/) | r/w | Liest oder setzt ein WMF PitchAndFamily‑Objekt ([MS-WMF] Abschnitt 2.2.2.14), das <br/>            den Pitch und die Familie der Schriftart angibt. Schriftfamilien beschreiben das Aussehen einer Schriftart allgemein. Sie dienen dazu, eine Schriftart anzugeben, wenn die angegebene Schriftart nicht verfügbar ist. |
| quality | [WmfFontQuality](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmffontquality/) | r/w | Liest oder setzt eine 8‑Bit vorzeichenlose Ganzzahl, die die Ausgabequalität angibt. Die Ausgabequalität <br/>            definiert, wie genau versucht werden soll, die logischen Schriftattributwerte an die einer tatsächlichen <br/>            physischen Schriftart anzupassen. Sie MUSS einer der Werte in der WMF FontQuality‑Aufzählung ([MS-WMF] <br/>            Abschnitt 2.1.1.10) sein. |
| Skript | string | r/w | Liest oder setzt eine Zeichenkette aus 32 Unicode‑Zeichen, die den Zeichensatz der Schriftart definiert. <br/>            Ist die Länge dieser Zeichenkette weniger als 32 Zeichen, MUSS ein abschließendes NULL vorhanden sein, <br/>            danach MUSS der Rest dieses Feldes ignoriert werden. |
| Durchgestrichen | System.Byte | r/w | Liest oder setzt eine 8‑Bit vorzeichenlose Ganzzahl, die eine durchgestrichene Schriftart angibt, wenn sie auf 0x01 gesetzt ist; <br/>            andernfalls MUSS sie auf 0x00 gesetzt werden. |
| Stil | string | r/w | Liest oder setzt eine Zeichenkette aus 32 Unicode‑Zeichen, die den Stil der Schriftart definiert. Ist die Länge dieser <br/>            Zeichenkette weniger als 32 Zeichen, MUSS ein abschließendes NULL vorhanden sein, danach <br/>            MUSS der Rest dieses Feldes ignoriert werden. |
| Unterstrichen | System.Byte | r/w | Liest oder setzt eine 8‑Bit vorzeichenlose Ganzzahl, die eine unterstrichene Schriftart angibt, wenn sie auf 0x01 gesetzt ist; <br/>            andernfalls MUSS sie auf 0x00 gesetzt werden. |
| weight | [EmfLogFontWeight](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emflogfontweight/) | r/w | Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die das Gewicht der Schriftart im Bereich <br/>            null bis 1000 angibt. Zum Beispiel ist 400 normal und 700 fett. Ist dieser Wert null, kann ein Standard‑<br/>            gewicht verwendet werden. |
| width | int | r/w | Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die durchschnittliche Breite in logischen Einheiten von <br/>            Zeichen in der Schriftart angibt. Ist der Wert des Feldes Width null, SOLLTE ein geeigneter Wert aus anderen LogFont‑Werten <br/>            berechnet werden, um eine Schriftart zu finden, die das vom Typografen beabsichtigte Seitenverhältnis hat. |


### Constructor: EmfLogFontEx(emf_log_font) {#EmfLogFontEx_emf_log_font_1}


```
 EmfLogFontEx(emf_log_font) 
```

Initialisiert eine neue Instanz der [EmfLogFontEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfontex/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| emf_log_font | [EmfLogFont](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfont/) | Die EMF-Logschriftart. |

