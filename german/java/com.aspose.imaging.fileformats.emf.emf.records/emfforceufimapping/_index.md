---
title: "EmfForceUfiMapping"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_FORCEUFIMAPPING‑Record zwingt den Font‑Mapper, Schriftarten anhand ihrer UniversalFontId vorzugsweise gegenüber den Informationen aus LogFont (Abschnitt 2.2.13) abzugleichen."
type: docs
weight: 61
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfforceufimapping/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfForceUfiMapping extends EmfStateRecordType
```

Der EMR\_FORCEUFIMAPPING-Datensatz zwingt den Schriftartenzuordner, Schriftarten anhand ihrer UniversalFontId anstelle ihrer LogFont (Abschnitt 2.2.13)-Informationen abzugleichen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfForceUfiMapping(EmfRecord source)](#EmfForceUfiMapping-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfForceUfiMapping`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getUfi()](#getUfi--) | Liest oder setzt die zu verwendende Schriftarten‑ID, angegeben als UniversalFontId (Abschnitt 2.2.27). |
| [setUfi(EmfUniversalFontId value)](#setUfi-com.aspose.imaging.fileformats.emf.emf.objects.EmfUniversalFontId-) | Liest oder setzt die zu verwendende Schriftarten‑ID, angegeben als UniversalFontId (Abschnitt 2.2.27). |
### EmfForceUfiMapping(EmfRecord source) {#EmfForceUfiMapping-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfForceUfiMapping(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfForceUfiMapping`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### getUfi() {#getUfi--}
```
public EmfUniversalFontId getUfi()
```


Liest oder setzt die zu verwendende Schriftarten‑ID, angegeben als UniversalFontId (Abschnitt 2.2.27).

**Returns:**
[EmfUniversalFontId](../../com.aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid)
### setUfi(EmfUniversalFontId value) {#setUfi-com.aspose.imaging.fileformats.emf.emf.objects.EmfUniversalFontId-}
```
public void setUfi(EmfUniversalFontId value)
```


Liest oder setzt die zu verwendende Schriftarten‑ID, angegeben als UniversalFontId (Abschnitt 2.2.27).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfUniversalFontId](../../com.aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid) |  |

