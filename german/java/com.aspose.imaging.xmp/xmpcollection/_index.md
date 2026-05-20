---
title: "XmpCollection"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Eine XMP-Elementsammlung."
type: docs
weight: 15
url: /de/java/com.aspose.imaging.xmp/xmpcollection/
---
**Inheritance:**
java.lang.Object, java.util.AbstractCollection, java.util.AbstractList, java.util.ArrayList

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.types.IXmpType](../../com.aspose.imaging.xmp.types/ixmptype)
```
public class XmpCollection extends ArrayList<IXmpType> implements IXmpType
```

Eine XMP-Elementsammlung.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [XmpCollection()](#XmpCollection--) | Initialisiert eine neue Instanz der [XmpCollection](../../com.aspose.imaging.xmp/xmpcollection)-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addItem(Object item)](#addItem-java.lang.Object-) | Fügt ein neues Element hinzu. |
| [addObject(Object item)](#addObject-java.lang.Object-) | Fügt ein XMP-Daten-Element hinzu. |
| [removeAt(int index)](#removeAt-int-) | Entfernt das Element am angegebenen Index. |
| [add(IXmpType item)](#add-com.aspose.imaging.xmp.types.IXmpType-) | Fügt ein Element zur Sammlung hinzu. |
| [copyTo(IXmpType[] array, int arrayIndex)](#copyTo-com.aspose.imaging.xmp.types.IXmpType---int-) | Kopiert die Elemente der Sammlung in ein Array, beginnend bei einem bestimmten Array-Index. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Liest den XMP-Stringwert dieses Objekts. |
| [getXmlValue()](#getXmlValue--) | Konvertiert den XMP-Wert in die XML-Darstellung. |
| [toString()](#toString--) | Gibt einen XML-String zurück, der diese Instanz darstellt. |
### XmpCollection() {#XmpCollection--}
```
public XmpCollection()
```


Initialisiert eine neue Instanz der [XmpCollection](../../com.aspose.imaging.xmp/xmpcollection)-Klasse.

### addItem(Object item) {#addItem-java.lang.Object-}
```
public final void addItem(Object item)
```


Fügt ein neues Element hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Element | java.lang.Object | Das Element, das zur Liste der Elemente hinzugefügt werden soll. |

### addObject(Object item) {#addObject-java.lang.Object-}
```
public final void addObject(Object item)
```


Fügt ein XMP-Daten-Element hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Element | java.lang.Object | Ein XMP-Element. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Entfernt das Element am angegebenen Index.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index des zu entfernenden Elements. |

### add(IXmpType item) {#add-com.aspose.imaging.xmp.types.IXmpType-}
```
public final boolean add(IXmpType item)
```


Fügt ein Element zur Sammlung hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IXmpType](../../com.aspose.imaging.xmp.types/ixmptype) | Das Objekt, das zur Sammlung hinzugefügt werden soll. |

**Returns:**
boolean
### copyTo(IXmpType[] array, int arrayIndex) {#copyTo-com.aspose.imaging.xmp.types.IXmpType---int-}
```
public final void copyTo(IXmpType[] array, int arrayIndex)
```


Kopiert die Elemente der Sammlung in ein Array, beginnend bei einem bestimmten Array-Index.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | [IXmpType\[\]](../../com.aspose.imaging.xmp.types/ixmptype) | Das eindimensionale Array, das das Ziel der aus der Sammlung kopierten Elemente ist. Das Array muss nullbasierte Indizierung haben. |
| `arrayIndex` | int | Der nullbasierte Index im Array, an dem das Kopieren beginnt. |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public final String getXmpRepresentation()
```


Liest den XMP-Stringwert dieses Objekts.

**Returns:**
java.lang.String - Gibt den im String enthaltenen Wert im XMP-Format zurück.
### getXmlValue() {#getXmlValue--}
```
public final String getXmlValue()
```


Konvertiert den XMP-Wert in die XML-Darstellung.

**Returns:**
java.lang.String - Gibt den XMP-Wert zurück, der in die XML-Darstellung konvertiert wurde.
### toString() {#toString--}
```
public String toString()
```


Gibt einen XML-String zurück, der diese Instanz darstellt.

**Returns:**
java.lang.String - Ein XML-String, der diese Instanz darstellt.
