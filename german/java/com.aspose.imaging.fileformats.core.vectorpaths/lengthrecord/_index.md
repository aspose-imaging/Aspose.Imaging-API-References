---
title: "LengthRecord"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Unterpfad-Längen-Aufzeichnungs-Klasse"
type: docs
weight: 13
url: /de/java/com.aspose.imaging.fileformats.core.vectorpaths/lengthrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.core.vectorpaths.VectorPathRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/vectorpathrecord)
```
public class LengthRecord extends VectorPathRecord
```

Unterpfad-Längen-Aufzeichnungs-Klasse
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [LengthRecord(byte[] data)](#LengthRecord-byte---) | Initialisiert eine neue Instanz der Klasse [LengthRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/lengthrecord). |
| [LengthRecord()](#LengthRecord--) | Initialisiert eine neue Instanz der Klasse [LengthRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/lengthrecord). |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isClosed()](#isClosed--) | Liefert einen Wert, der angibt, ob diese Instanz geschlossen ist. |
| [setClosed(boolean value)](#setClosed-boolean-) | Setzt einen Wert, der angibt, ob diese Instanz geschlossen ist. |
| [isOpen()](#isOpen--) | Liefert einen Wert, der angibt, ob diese Instanz geöffnet ist. |
| [setOpen(boolean value)](#setOpen-boolean-) | Setzt einen Wert, der angibt, ob diese Instanz geöffnet ist. |
| [getRecordCount()](#getRecordCount--) | Ruft die Datensatzanzahl ab. |
| [setRecordCount(int value)](#setRecordCount-int-) | Setzt die Datensatzanzahl. |
| [getType()](#getType--) | Liest den Typ. |
| [getBezierKnotRecordsCount()](#getBezierKnotRecordsCount--) | Ruft die Anzahl der Bezier-Knoten-Datensätze ab. |
| [setBezierKnotRecordsCount(int value)](#setBezierKnotRecordsCount-int-) | Setzt die Anzahl der Bezier-Knoten-Datensätze. |
| [getPathOperations()](#getPathOperations--) | Ruft die Pfadoperationen ab. |
| [setPathOperations(int value)](#setPathOperations-int-) | Setzt die Pfadoperationen. |
| [getShapeIndex()](#getShapeIndex--) | Ruft den Index der aktuellen Pfadform in der Ebene ab. |
| [setShapeIndex(int value)](#setShapeIndex-int-) | Setzt den Index der aktuellen Pfadform in der Ebene. |
### LengthRecord(byte[] data) {#LengthRecord-byte---}
```
public LengthRecord(byte[] data)
```


Initialisiert eine neue Instanz der Klasse [LengthRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/lengthrecord).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | byte[] | Die Daten des Datensatzes. |

### LengthRecord() {#LengthRecord--}
```
public LengthRecord()
```


Initialisiert eine neue Instanz der Klasse [LengthRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/lengthrecord).

### isClosed() {#isClosed--}
```
public final boolean isClosed()
```


Liefert einen Wert, der angibt, ob diese Instanz geschlossen ist.

Wert: `true`, wenn diese Instanz geschlossen ist; andernfalls `false`.

**Returns:**
boolean - ein Wert, der angibt, ob diese Instanz geschlossen ist.
### setClosed(boolean value) {#setClosed-boolean-}
```
public final void setClosed(boolean value)
```


Setzt einen Wert, der angibt, ob diese Instanz geschlossen ist.

Wert: `true`, wenn diese Instanz geschlossen ist; andernfalls `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | ein Wert, der angibt, ob diese Instanz geschlossen ist. |

### isOpen() {#isOpen--}
```
public final boolean isOpen()
```


Liefert einen Wert, der angibt, ob diese Instanz geöffnet ist.

Wert: `true`, wenn diese Instanz geöffnet ist; andernfalls `false`.

**Returns:**
boolean - ein Wert, der angibt, ob diese Instanz geöffnet ist.
### setOpen(boolean value) {#setOpen-boolean-}
```
public final void setOpen(boolean value)
```


Setzt einen Wert, der angibt, ob diese Instanz geöffnet ist.

Wert: `true`, wenn diese Instanz geöffnet ist; andernfalls `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | ein Wert, der angibt, ob diese Instanz geöffnet ist. |

### getRecordCount() {#getRecordCount--}
```
public final int getRecordCount()
```


Ruft die Datensatzanzahl ab.

Wert: Die Datensatzanzahl.

**Returns:**
int - die Datensatzanzahl.
### setRecordCount(int value) {#setRecordCount-int-}
```
public final void setRecordCount(int value)
```


Setzt die Datensatzanzahl.

Wert: Die Datensatzanzahl.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | die Datensatzanzahl. |

### getType() {#getType--}
```
public short getType()
```


Liest den Typ.

Wert: Der Typ.

**Returns:**
short - der Typ.
### getBezierKnotRecordsCount() {#getBezierKnotRecordsCount--}
```
public final int getBezierKnotRecordsCount()
```


Ruft die Anzahl der Bezier-Knoten-Datensätze ab.

**Returns:**
int - die Anzahl der Bezier-Knoten-Datensätze.
### setBezierKnotRecordsCount(int value) {#setBezierKnotRecordsCount-int-}
```
public final void setBezierKnotRecordsCount(int value)
```


Setzt die Anzahl der Bezier-Knoten-Datensätze.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | die Anzahl der Bezier-Knoten-Datensätze. |

### getPathOperations() {#getPathOperations--}
```
public final int getPathOperations()
```


Ruft die Pfadoperationen ab.

**Returns:**
int - die Pfadoperationen.
### setPathOperations(int value) {#setPathOperations-int-}
```
public final void setPathOperations(int value)
```


Setzt die Pfadoperationen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | die Pfadoperationen. |

### getShapeIndex() {#getShapeIndex--}
```
public final int getShapeIndex()
```


Ruft den Index der aktuellen Pfadform in der Ebene ab.

**Returns:**
int - der Index der aktuellen Pfadform in der Ebene.
### setShapeIndex(int value) {#setShapeIndex-int-}
```
public final void setShapeIndex(int value)
```


Setzt den Index der aktuellen Pfadform in der Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | der Index der aktuellen Pfadform in der Ebene. |

