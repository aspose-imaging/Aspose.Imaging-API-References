---
title: "EmfPlusFillPath"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Fill‑Path‑Datensatz‑FLAGS 16‑Bit‑unsigned‑Integer, der Informationen darüber liefert, wie die Operation ausgeführt werden soll und über die Struktur des Datensatzes."
type: docs
weight: 34
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillPath extends EmfPlusDrawingRecordType
```

Fill‑Path‑Datensatz‑FLAGS: 16‑Bit‑unsigned‑Integer, der Informationen darüber liefert, wie die Operation ausgeführt werden soll, und über die Struktur des Datensatzes. 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 S X X X X X X X | ObjectId | S (1 Bit): Dieses Bit gibt den Datentyp im BrushId‑Feld an. Wenn gesetzt, gibt BrushId eine Farbe als EmfPlusARGB‑Objekt (Abschnitt 2.2.2.1) an. Wenn nicht gesetzt, enthält BrushId den Index eines EmfPlusBrush‑Objekts (Abschnitt 2.2.1.1) in der EMF+‑Objekttabelle. X (1 Bit): Reserviert und MUSS ignoriert werden. ObjectId (1 Byte): Der Index des EmfPlusPath‑Objekts (Abschnitt 2.2.1.6), das im EMF+‑Objekttabelle zu füllen ist. Der Wert MUSS zwischen 0 und 63 liegen, inklusiv.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusFillPath(EmfPlusRecord source)](#EmfPlusFillPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialisiert eine neue Instanz der Klasse `EmfPlusFillPath`. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isColor()](#isColor--) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob diese Instanz farbig ist. |
| [setColor(boolean value)](#setColor-boolean-) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob diese Instanz farbig ist. |
| [getObjectId()](#getObjectId--) | Liest oder setzt die Objektkennung. |
| [setObjectId(byte value)](#setObjectId-byte-) | Liest oder setzt die Objektkennung. |
| [getBrushId()](#getBrushId--) | Liest oder setzt die Brush‑ID. Ein 32‑Bit‑unsigned‑Integer, der den Pinsel definiert, dessen Inhalt durch das S‑Bit im Flags‑Feld bestimmt wird. |
| [setBrushId(int value)](#setBrushId-int-) | Liest oder setzt die Brush‑ID. Ein 32‑Bit‑unsigned‑Integer, der den Pinsel definiert, dessen Inhalt durch das S‑Bit im Flags‑Feld bestimmt wird. |
### EmfPlusFillPath(EmfPlusRecord source) {#EmfPlusFillPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillPath(EmfPlusRecord source)
```


Initialisiert eine neue Instanz der Klasse `EmfPlusFillPath`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Die Quelle. |

### isColor() {#isColor--}
```
public boolean isColor()
```


Liest oder setzt einen Wert, der angibt, ob diese Instanz farbig ist. Wenn gesetzt, gibt BrushId eine Farbe als EmfPlusARGB‑Objekt (Abschnitt 2.2.2.1) an. Wenn nicht gesetzt, enthält BrushId den Index eines EmfPlusBrush‑Objekts (Abschnitt 2.2.1.1) in der EMF+‑Objekttabelle.

Wert: `true`, wenn diese Instanz farbig ist; andernfalls `false`.

**Returns:**
boolean
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob diese Instanz farbig ist. Wenn gesetzt, gibt BrushId eine Farbe als EmfPlusARGB‑Objekt (Abschnitt 2.2.2.1) an. Wenn nicht gesetzt, enthält BrushId den Index eines EmfPlusBrush‑Objekts (Abschnitt 2.2.1.1) in der EMF+‑Objekttabelle.

Wert: `true`, wenn diese Instanz farbig ist; andernfalls `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Liest oder setzt die Objektkennung. Der Index des EmfPlusPath‑Objekts (Abschnitt 2.2.1.6), das im EMF+‑Objekttabelle zu füllen ist. Der Wert MUSS zwischen 0 und 63 liegen, inklusiv.

Wert: Die Objektkennung.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Liest oder setzt die Objektkennung. Der Index des EmfPlusPath‑Objekts (Abschnitt 2.2.1.6), das im EMF+‑Objekttabelle zu füllen ist. Der Wert MUSS zwischen 0 und 63 liegen, inklusiv.

Wert: Die Objektkennung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Liest oder setzt die Brush‑ID. Ein 32‑Bit‑unsigned‑Integer, der den Pinsel definiert, dessen Inhalt durch das S‑Bit im Flags‑Feld bestimmt wird.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Liest oder setzt die Brush‑ID. Ein 32‑Bit‑unsigned‑Integer, der den Pinsel definiert, dessen Inhalt durch das S‑Bit im Flags‑Feld bestimmt wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

