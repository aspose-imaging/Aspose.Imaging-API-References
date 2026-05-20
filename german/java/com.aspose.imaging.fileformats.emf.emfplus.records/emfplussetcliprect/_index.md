---
title: "EmfPlusSetClipRect"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EmfPlusSetClipRect-Datensatz kombiniert die aktuelle Clipping‑Region mit einem Rechteck."
type: docs
weight: 56
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetcliprect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusClippingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusclippingrecordtype)
```
public final class EmfPlusSetClipRect extends EmfPlusClippingRecordType
```

Der EmfPlusSetClipRect-Datensatz kombiniert die aktuelle Clipping‑Region mit einem Rechteck.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusSetClipRect(EmfPlusRecord source)](#EmfPlusSetClipRect-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialisiert eine neue Instanz der `EmfPlusSetClipRect`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCm()](#getCm--) | Liest oder setzt das CM (4 Bits): Gibt die logische Operation zum Kombinieren zweier Regionen an. |
| [setCm(byte value)](#setCm-byte-) | Liest oder setzt das CM (4 Bits): Gibt die logische Operation zum Kombinieren zweier Regionen an. |
| [getClipRect()](#getClipRect--) | Liest oder setzt ein EmfPlusRectF‑Objekt (Abschnitt 2.2.2.39), das das Rechteck definiert, das in der CombineMode‑Operation verwendet wird. |
| [setClipRect(RectangleF value)](#setClipRect-com.aspose.imaging.RectangleF-) | Liest oder setzt ein EmfPlusRectF‑Objekt (Abschnitt 2.2.2.39), das das Rechteck definiert, das in der CombineMode‑Operation verwendet wird. |
### EmfPlusSetClipRect(EmfPlusRecord source) {#EmfPlusSetClipRect-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetClipRect(EmfPlusRecord source)
```


Initialisiert eine neue Instanz der `EmfPlusSetClipRect`‑Klasse.

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

### getClipRect() {#getClipRect--}
```
public RectangleF getClipRect()
```


Liest oder setzt ein EmfPlusRectF‑Objekt (Abschnitt 2.2.2.39), das das Rechteck definiert, das in der CombineMode‑Operation verwendet wird.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setClipRect(RectangleF value) {#setClipRect-com.aspose.imaging.RectangleF-}
```
public void setClipRect(RectangleF value)
```


Liest oder setzt ein EmfPlusRectF‑Objekt (Abschnitt 2.2.2.39), das das Rechteck definiert, das in der CombineMode‑Operation verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

