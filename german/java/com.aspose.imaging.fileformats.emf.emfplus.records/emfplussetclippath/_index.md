---
title: "EmfPlusSetClipPath"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EmfPlusSetClipPath-Datensatz kombiniert die aktuelle Clipping‑Region mit einem Grafikpfad."
type: docs
weight: 55
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetclippath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusClippingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusclippingrecordtype)
```
public final class EmfPlusSetClipPath extends EmfPlusClippingRecordType
```

Der EmfPlusSetClipPath‑Datensatz kombiniert die aktuelle Clipping‑Region mit einem Grafikpfad. Die neue aktuelle Clipping‑Region wird auf das Ergebnis der CombineMode‑Operation gesetzt.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusSetClipPath(EmfPlusRecord source)](#EmfPlusSetClipPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialisiert eine neue Instanz der `EmfPlusSetClipPath`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCm()](#getCm--) | Liest oder setzt das CM (4 Bits): Gibt die logische Operation zum Kombinieren zweier Regionen an. |
| [setCm(byte value)](#setCm-byte-) | Liest oder setzt das CM (4 Bits): Gibt die logische Operation zum Kombinieren zweier Regionen an. |
| [getObjectId()](#getObjectId--) | Liest oder setzt den Index eines EmfPlusPath‑Objekts (Abschnitt 2.2.1.6) in der EMF+ Object Table. |
| [setObjectId(byte value)](#setObjectId-byte-) | Liest oder setzt den Index eines EmfPlusPath‑Objekts (Abschnitt 2.2.1.6) in der EMF+ Object Table. |
### EmfPlusSetClipPath(EmfPlusRecord source) {#EmfPlusSetClipPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetClipPath(EmfPlusRecord source)
```


Initialisiert eine neue Instanz der `EmfPlusSetClipPath`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Die Quelle. |

### getCm() {#getCm--}
```
public byte getCm()
```


Liest oder setzt das CM (4 Bits): Gibt die logische Operation zum Kombinieren zweier Regionen an. Siehe die CombineMode‑Aufzählung (Abschnitt 2.1.1.4) für die Bedeutungen der Werte.

Wert: Das cm.

**Returns:**
byte
### setCm(byte value) {#setCm-byte-}
```
public void setCm(byte value)
```


Liest oder setzt das CM (4 Bits): Gibt die logische Operation zum Kombinieren zweier Regionen an. Siehe die CombineMode‑Aufzählung (Abschnitt 2.1.1.4) für die Bedeutungen der Werte.

Wert: Das cm.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Liest oder setzt den Index eines EmfPlusPath‑Objekts (Abschnitt 2.2.1.6) in der EMF+ Object Table. Der Wert MUSS zwischen 0 und 63 liegen, einschließlich.

Wert: Die Objektkennung.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Liest oder setzt den Index eines EmfPlusPath‑Objekts (Abschnitt 2.2.1.6) in der EMF+ Object Table. Der Wert MUSS zwischen 0 und 63 liegen, einschließlich.

Wert: Die Objektkennung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

