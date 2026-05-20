---
title: "EmfSetTextAlign"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_SETTEXTALIGN-Datensatz legt die Textausrichtung fest."
type: docs
weight: 139
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfsettextalign/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetTextAlign extends EmfStateRecordType
```

Der EMR\_SETTEXTALIGN-Datensatz gibt die Textausrichtung an.

Die EMR\_SMALLTEXTOUT-, EMR\_EXTTEXTOUTA- und EMR\_EXTTEXTOUTW-Datensätze verwenden Textausrichtungswerte, um eine Textzeichenkette im Ausgabemedium zu positionieren. Die Werte geben das Verhältnis zwischen einem Referenzpunkt und einem Rechteck an, das den Text begrenzt. Der Referenzpunkt ist entweder die aktuelle Position oder ein an einen Textausgabedatensatz übergebener Punkt. Das den Text begrenzende Rechteck wird durch die Zeichenzellen in der Textzeichenkette gebildet.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfSetTextAlign(EmfRecord source)](#EmfSetTextAlign-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfSetTextAlign`‑Klasse. |
| [EmfSetTextAlign()](#EmfSetTextAlign--) | Initialisiert eine neue Instanz der `EmfSetTextAlign`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getTextAlignmentMode()](#getTextAlignmentMode--) | Ruft ab oder legt eine 32‑Bit‑vorzeichenlose Ganzzahl fest, die die Textausrichtung mittels einer Maske von Textausrichtungs‑Flags angibt. |
| [setTextAlignmentMode(int value)](#setTextAlignmentMode-int-) | Ruft ab oder legt eine 32‑Bit‑vorzeichenlose Ganzzahl fest, die die Textausrichtung mittels einer Maske von Textausrichtungs‑Flags angibt. |
### EmfSetTextAlign(EmfRecord source) {#EmfSetTextAlign-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetTextAlign(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfSetTextAlign`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### EmfSetTextAlign() {#EmfSetTextAlign--}
```
public EmfSetTextAlign()
```


Initialisiert eine neue Instanz der `EmfSetTextAlign`‑Klasse.

### getTextAlignmentMode() {#getTextAlignmentMode--}
```
public int getTextAlignmentMode()
```


Ruft ab oder legt eine 32‑Bit‑vorzeichenlose Ganzzahl fest, die die Textausrichtung mittels einer Maske von Textausrichtungs‑Flags angibt. Diese sind entweder `Wmf.Consts.WmfTextAlignmentModeFlags` ([MS-WMF] Abschnitt 2.1.2.3) für Text mit einer horizontalen Grundlinie oder `Wmf.Consts.WmfVerticalTextAlignmentModeFlags` ([MS-WMF] Abschnitt 2.1.2.4) für Text mit einer vertikalen Grundlinie. Es kann nur ein Wert aus denen gewählt werden, die die horizontale bzw. vertikale Ausrichtung beeinflussen.

**Returns:**
int
### setTextAlignmentMode(int value) {#setTextAlignmentMode-int-}
```
public void setTextAlignmentMode(int value)
```


Ruft ab oder legt eine 32‑Bit‑vorzeichenlose Ganzzahl fest, die die Textausrichtung mittels einer Maske von Textausrichtungs‑Flags angibt. Diese sind entweder `Wmf.Consts.WmfTextAlignmentModeFlags` ([MS-WMF] Abschnitt 2.1.2.3) für Text mit einer horizontalen Grundlinie oder `Wmf.Consts.WmfVerticalTextAlignmentModeFlags` ([MS-WMF] Abschnitt 2.1.2.4) für Text mit einer vertikalen Grundlinie. Es kann nur ein Wert aus denen gewählt werden, die die horizontale bzw. vertikale Ausrichtung beeinflussen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

