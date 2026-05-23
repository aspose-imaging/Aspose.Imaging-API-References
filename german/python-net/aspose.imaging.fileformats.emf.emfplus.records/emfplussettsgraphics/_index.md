---
title: "EmfPlusSetTsGraphics Klasse"
type: docs
weight: 580
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/
---

**Summary:** The EmfPlusSetTSGraphics record specifies the state of a graphics device context for a terminal server.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetTsGraphics

**Inheritance:** EmfPlusTerminalServerRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusSetTsGraphics(source)](#EmfPlusSetTsGraphics_source_1) | Initialisiert eine neue Instanz der Klasse [EmfPlusSetTsGraphics](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| anti_alias_mode | [EmfPlusSmoothingMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplussmoothingmode/) | r/w | Liest oder setzt ein 8‑Bit‑vorzeichenloses Integer, das die Qualität der Liniendarstellung angibt,<br/>            einschließlich des Typs der Linien‑Anti‑Aliasing. Es MUSS in der SmoothingMode<br/>            Aufzählung (Abschnitt 2.1.1.28) definiert sein. |
| basic_vga_colors | bool | r | Liest einen Wert, der angibt, ob [basic vga colors].<br/>            Wenn gesetzt, enthält die Palette nur die grundlegenden VGA‑Farben. |
| compositing_mode | [EmfPlusCompositingMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscompositingmode/) | r/w | Liest oder setzt ein 8‑Bit‑vorzeichenloses Integer, das angibt, wie Quellfarben<br/>            mit Hintergrundfarben kombiniert werden. Es MUSS ein Wert der CompositingMode<br/>            Aufzählung (Abschnitt 2.1.1.5) sein. |
| compositing_quality | [EmfPlusCompositingQuality](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscompositingquality/) | r/w | Liest oder setzt ein 8‑Bit‑vorzeichenloses Integer, das den Grad der<br/>            Glättung von Linien, Kurven und den Kanten gefüllter Flächen angibt, um sie kontinuierlicher oder schärfer definiert erscheinen zu lassen. Es MUSS ein Wert der CompositingQuality Aufzählung (Abschnitt 2.1.1.6) sein. |
| data_size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die DIE 32‑Bit‑ausgerichtete Anzahl von<br/>            Bytes an Daten im nachfolgenden RecordData‑Feld DEFINIEREN MUSS. Diese Zahl beinhaltet nicht den 12‑Byte‑Datensatz‑Header. |
| filter_type | [EmfPlusFilterType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusfiltertype/) | r/w | Liest oder setzt ein 8‑Bit‑vorzeichenloses Integer, das angibt, wie Skalierung, einschließlich Dehnung<br/>            und Verkleinerung, durchgeführt wird. Es MUSS ein Wert der FilterType Aufzählung (Abschnitt 2.1.1.11) sein. |
| flags | int | r/w | Liest oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die Informationen für einige Datensätze darüber enthält, wie<br/>            die Operation auszuführen ist und wie die Struktur des Datensatzes beschaffen ist. |
| have_palette | bool | r | Liest einen Wert, der angibt, ob [have palette].<br/>            Wenn gesetzt, enthält dieser Datensatz ein EmfPlusPalette‑Objekt (Abschnitt 2.2.2.28) im<br/>            Palette‑Feld nach den Grafik‑Zustandsdaten. |
| palette | [EmfPlusPalette](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette/) | r/w | Liest oder setzt ein optionales EmfPlusPalette‑Objekt. |
| pixel_offset | [EmfPlusPixelOffsetMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixeloffsetmode/) | r/w | Liest oder setzt ein 8‑Bit‑vorzeichenloses Integer, das die Gesamtqualität des Bildes<br/>            und des Textdarstellungsprozesses angibt. Es MUSS ein Wert der PixelOffsetMode Aufzählung (Abschnitt 2.1.1.26) sein. |
| render_origin_x | int | r/w | Liest oder setzt ein 16‑Bit‑vorzeichenbehaftetes Integer, das die horizontale Koordinate des<br/>            Ursprungs für die Darstellung von Halftoning‑ und Dithering‑Matrizen ist. |
| render_origin_y | int | r/w | Liest oder setzt ein 16‑Bit‑vorzeichenbehaftetes Integer, das die vertikale Koordinate des Ursprungs<br/>            für die Darstellung von Halftoning‑ und Dithering‑Matrizen ist. |
| size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die 32‑Bit‑ausgerichtete Anzahl von Bytes<br/>            im gesamten Datensatz angibt, einschließlich des 12‑Byte‑Datensatz‑Headers und der datensatzspezifischen Daten. |
| text_contrast | int | r/w | Liest oder setzt ein 16‑Bit‑vorzeichenloses Integer, das den Gamma‑Korrekturwert<br/>            für die Darstellung von anti‑aliasiertem und ClearType‑Text angibt. Dieser Wert MUSS im Bereich von 0 bis 12 liegen, einschließlich. |
| text_render_hint | [EmfPlusTextRenderingHint](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplustextrenderinghint/) | r/w | Liest oder setzt ein 8‑Bit‑vorzeichenloses Integer, das die Qualität der Text<br/>            Darstellung angibt, einschließlich des Typs des Text‑Anti‑Aliasing. Es MUSS in der<br/>            TextRenderingHint Aufzählung (Abschnitt 2.1.1.32) definiert sein. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Liest eine 16‑Bit‑vorzeichenlose Ganzzahl, die den Datensatztyp identifiziert. |
| world_to_device | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Liest oder setzt ein 192‑Bit EmfPlusTransformMatrix‑Objekt (Abschnitt 2.2.2.47), das<br/>            die Transformationen vom Weltraum zum Geräteraum angibt. |


### Constructor: EmfPlusSetTsGraphics(source) {#EmfPlusSetTsGraphics_source_1}


```
 EmfPlusSetTsGraphics(source) 
```

Initialisiert eine neue Instanz der Klasse [EmfPlusSetTsGraphics](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Die Quelle. |

