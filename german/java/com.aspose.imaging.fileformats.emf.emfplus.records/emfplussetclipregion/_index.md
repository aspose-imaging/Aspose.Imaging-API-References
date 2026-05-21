---
title: "EmfPlusSetClipRegion"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EmfPlusSetClipRegion-Datensatz kombiniert die aktuelle Clipping‑Region mit einer anderen Grafikregion."
type: docs
weight: 57
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetclipregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusClippingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusclippingrecordtype)
```
public final class EmfPlusSetClipRegion extends EmfPlusClippingRecordType
```

Der EmfPlusSetClipRegion‑Datensatz kombiniert die aktuelle Beschneidungsregion mit einer anderen Grafikregion. Die neue aktuelle Beschneidungsregion wird auf das Ergebnis der CombineMode‑Operation zwischen der vorherigen aktuellen Beschneidungsregion und dem angegebenen EmfPlusRegion‑Objekt gesetzt.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusSetClipRegion(EmfPlusRecord source)](#EmfPlusSetClipRegion-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialisiert eine neue Instanz der `EmfPlusSetClipRegion`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCm()](#getCm--) | Liest oder setzt das CM (4 Bits): Gibt die logische Operation zum Kombinieren zweier Regionen an. |
| [setCm(byte value)](#setCm-byte-) | Liest oder setzt das CM (4 Bits): Gibt die logische Operation zum Kombinieren zweier Regionen an. |
| [getObjectId()](#getObjectId--) | Liest oder setzt den Index eines EmfPlusRegion‑Objekts (Abschnitt 2.2.1.8) in der EMF+‑Objekttabelle. Der Wert MUSS zwischen 0 und 63 liegen, inklusiv. |
| [setObjectId(byte value)](#setObjectId-byte-) | Liest oder setzt den Index eines EmfPlusRegion‑Objekts (Abschnitt 2.2.1.8) in der EMF+‑Objekttabelle. Der Wert MUSS zwischen 0 und 63 liegen, inklusiv. |
### EmfPlusSetClipRegion(EmfPlusRecord source) {#EmfPlusSetClipRegion-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetClipRegion(EmfPlusRecord source)
```


Initialisiert eine neue Instanz der `EmfPlusSetClipRegion`‑Klasse.

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


Liest oder setzt den Index eines EmfPlusRegion‑Objekts (Abschnitt 2.2.1.8) in der EMF+‑Objekttabelle. Der Wert MUSS zwischen 0 und 63 liegen, inklusiv.

Wert: Die Objektkennung.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Liest oder setzt den Index eines EmfPlusRegion‑Objekts (Abschnitt 2.2.1.8) in der EMF+‑Objekttabelle. Der Wert MUSS zwischen 0 und 63 liegen, inklusiv.

Wert: Die Objektkennung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

