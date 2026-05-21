---
title: "EmfPlusDrawPath"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EmfPlusDrawPath-Datensatz gibt das Zeichnen eines Grafikpfads an."
type: docs
weight: 25
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawPath extends EmfPlusDrawingRecordType
```

Der EmfPlusDrawPath-Datensatz gibt das Zeichnen eines Grafikpfads an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusDrawPath(EmfPlusRecord source)](#EmfPlusDrawPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialisiert eine neue Instanz der `EmfPlusDrawPath`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getObjectId()](#getObjectId--) | Liest oder setzt die Objektkennung. |
| [setObjectId(byte value)](#setObjectId-byte-) | Liest oder setzt die Objektkennung. |
| [getPenId()](#getPenId--) | Liest oder setzt den Stiftbezeichner. Ein 32‑Bit‑vorzeichenloser Integer, der einen Index in der EMF+ Object Table für ein EmfPlusPen‑Objekt (Abschnitt 2.2.1.7) angibt, das zum Zeichnen des EmfPlusPath verwendet wird. |
| [setPenId(int value)](#setPenId-int-) | Liest oder setzt den Stiftbezeichner. Ein 32‑Bit‑vorzeichenloser Integer, der einen Index in der EMF+ Object Table für ein EmfPlusPen‑Objekt (Abschnitt 2.2.1.7) angibt, das zum Zeichnen des EmfPlusPath verwendet wird. |
### EmfPlusDrawPath(EmfPlusRecord source) {#EmfPlusDrawPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawPath(EmfPlusRecord source)
```


Initialisiert eine neue Instanz der `EmfPlusDrawPath`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Die Quelle. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Liest oder setzt den Objektbezeichner. Der Index des EmfPlusPath‑Objekts (Abschnitt 2.2.1.6), das gezeichnet werden soll, in der EMF+ Object Table. Der Wert MUSS zwischen 0 und 63 liegen, einschließlich.

Wert: Die Objektkennung.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Liest oder setzt den Objektbezeichner. Der Index des EmfPlusPath‑Objekts (Abschnitt 2.2.1.6), das gezeichnet werden soll, in der EMF+ Object Table. Der Wert MUSS zwischen 0 und 63 liegen, einschließlich.

Wert: Die Objektkennung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getPenId() {#getPenId--}
```
public int getPenId()
```


Liest oder setzt den Stiftbezeichner. Ein 32‑Bit‑vorzeichenloser Integer, der einen Index in der EMF+ Object Table für ein EmfPlusPen‑Objekt (Abschnitt 2.2.1.7) angibt, das zum Zeichnen des EmfPlusPath verwendet wird. Der Wert MUSS zwischen 0 und 63 liegen, einschließlich.

**Returns:**
int
### setPenId(int value) {#setPenId-int-}
```
public void setPenId(int value)
```


Liest oder setzt den Stiftbezeichner. Ein 32‑Bit‑vorzeichenloser Integer, der einen Index in der EMF+ Object Table für ein EmfPlusPen‑Objekt (Abschnitt 2.2.1.7) angibt, das zum Zeichnen des EmfPlusPath verwendet wird. Der Wert MUSS zwischen 0 und 63 liegen, einschließlich.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

