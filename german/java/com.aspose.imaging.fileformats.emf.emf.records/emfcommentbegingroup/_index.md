---
title: "EmfCommentBeginGroup"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_COMMENT_BEGINGROUP-Datensatz gibt den Beginn einer Gruppe von Zeichen‑Datensätzen an."
type: docs
weight: 26
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentbegingroup/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentPublicRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype)
```
public final class EmfCommentBeginGroup extends EmfCommentPublicRecordType
```

Der EMR\_COMMENT\_BEGINGROUP-Datensatz gibt den Beginn einer Gruppe von Zeichen‑Datensätzen an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfCommentBeginGroup(EmfRecord source)](#EmfCommentBeginGroup-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfCommentBeginGroup`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRectangle()](#getRectangle--) | Liest oder setzt ein WMF RectL-Objekt ([MS-WMF] Abschnitt 2.2.2.19), das das Ausgaberechteck in logischen Koordinaten angibt. |
| [setRectangle(Rectangle value)](#setRectangle-com.aspose.imaging.Rectangle-) | Liest oder setzt ein WMF RectL-Objekt ([MS-WMF] Abschnitt 2.2.2.19), das das Ausgaberechteck in logischen Koordinaten angibt. |
| [getNDescription()](#getNDescription--) | Liest oder setzt die Anzahl der Unicode‑Zeichen in der nachfolgenden optionalen Beschreibungszeichenkette. |
| [setNDescription(int value)](#setNDescription-int-) | Liest oder setzt die Anzahl der Unicode‑Zeichen in der nachfolgenden optionalen Beschreibungszeichenkette. |
| [getDescription()](#getDescription--) | Liest oder setzt eine optionale, nullterminierte Unicode‑Zeichenkette, die diese Gruppe von Datensätzen beschreibt. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Liest oder setzt eine optionale, nullterminierte Unicode‑Zeichenkette, die diese Gruppe von Datensätzen beschreibt. |
### EmfCommentBeginGroup(EmfRecord source) {#EmfCommentBeginGroup-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentBeginGroup(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfCommentBeginGroup`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Liest oder setzt ein WMF RectL-Objekt ([MS-WMF] Abschnitt 2.2.2.19), das das Ausgaberechteck in logischen Koordinaten angibt.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setRectangle(Rectangle value) {#setRectangle-com.aspose.imaging.Rectangle-}
```
public void setRectangle(Rectangle value)
```


Liest oder setzt ein WMF RectL-Objekt ([MS-WMF] Abschnitt 2.2.2.19), das das Ausgaberechteck in logischen Koordinaten angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getNDescription() {#getNDescription--}
```
public int getNDescription()
```


Liest oder setzt die Anzahl der Unicode‑Zeichen in der nachfolgenden optionalen Beschreibungszeichenkette.

**Returns:**
int
### setNDescription(int value) {#setNDescription-int-}
```
public void setNDescription(int value)
```


Liest oder setzt die Anzahl der Unicode‑Zeichen in der nachfolgenden optionalen Beschreibungszeichenkette.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getDescription() {#getDescription--}
```
public String getDescription()
```


Liest oder setzt eine optionale, nullterminierte Unicode‑Zeichenkette, die diese Gruppe von Datensätzen beschreibt.

**Returns:**
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


Liest oder setzt eine optionale, nullterminierte Unicode‑Zeichenkette, die diese Gruppe von Datensätzen beschreibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

