---
title: "EmfSetArcDirection"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_SETARCDIRECTION‑Datensatz gibt die Zeichenrichtung an, die für Bogen‑ und Rechteckausgaben verwendet wird."
type: docs
weight: 118
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetArcDirection extends EmfStateRecordType
```

Der EMR\_SETARCDIRECTION-Datensatz spezifiziert die Zeichenrichtung, die für Bogen‑ und Rechteckausgaben verwendet werden soll.

Der EMR\_SETARCDIRECTION‑Datensatz beeinflusst die Richtung, in der die folgenden Datensätze zeichnen: - EMR\_ARC (Abschnitt 2.3.5.2) - EMR\_ARCTO (Abschnitt 2.3.5.3) - EMR\_CHORD (Abschnitt 2.3.5.4) - EMR\_ELLIPSE (Abschnitt 2.3.5.5) - EMR\_PIE (Abschnitt 2.3.5.15) - EMR\_RECTANGLE (Abschnitt 2.3.5.34) - EMR\_ROUNDRECT (Abschnitt 2.3.5.35)
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfSetArcDirection(EmfRecord source)](#EmfSetArcDirection-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfSetArcDirection`-Klasse. |
| [EmfSetArcDirection()](#EmfSetArcDirection--) | Initialisiert eine neue Instanz der `EmfSetArcDirection`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getArcDirection()](#getArcDirection--) | Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die die Bogenrichtung angibt. |
| [setArcDirection(int value)](#setArcDirection-int-) | Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die die Bogenrichtung angibt. |
### EmfSetArcDirection(EmfRecord source) {#EmfSetArcDirection-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetArcDirection(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfSetArcDirection`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### EmfSetArcDirection() {#EmfSetArcDirection--}
```
public EmfSetArcDirection()
```


Initialisiert eine neue Instanz der `EmfSetArcDirection`-Klasse.

### getArcDirection() {#getArcDirection--}
```
public int getArcDirection()
```


Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die die Bogenrichtung angibt. Der Wert MUSS in der ArcDirection‑Aufzählung (Abschnitt 2.1.2) enthalten sein. Die Standardrichtung ist gegen den Uhrzeigersinn.

**Returns:**
int
### setArcDirection(int value) {#setArcDirection-int-}
```
public void setArcDirection(int value)
```


Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die die Bogenrichtung angibt. Der Wert MUSS in der ArcDirection‑Aufzählung (Abschnitt 2.1.2) enthalten sein. Die Standardrichtung ist gegen den Uhrzeigersinn.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

