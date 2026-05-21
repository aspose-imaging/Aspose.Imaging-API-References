---
title: "XmpPackage"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt die Basisklasse für XMP-Pakete dar."
type: docs
weight: 19
url: /de/java/com.aspose.imaging.xmp/xmppackage/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public class XmpPackage implements IXmlValue, System.Collections.Generic.IGenericEnumerable<System.Collections.Generic.KeyValuePair<String,Object>>
```

Stellt die Basisklasse für XMP-Pakete dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [XmpPackage(String prefix, String namespaceUri)](#XmpPackage-java.lang.String-java.lang.String-) | Initialisiert eine neue Instanz der Klasse `XmpPackage`. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getXmlNamespace()](#getXmlNamespace--) | Ruft den XML-Namespace ab. |
| [getPrefix()](#getPrefix--) | Ruft das Präfix ab. |
| [getNamespaceUri()](#getNamespaceUri--) | Ruft die Namespace-URI ab. |
| [getKeys()](#getKeys--) | Ruft die Schlüssel im XMP-Paket ab. |
| [getCount()](#getCount--) | Ruft die Anzahl der XMP-Schlüssel ab. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Bestimmt, ob diese Sammlung den angegebenen Schlüssel enthält. |
| [get_Item(String key)](#get-Item-java.lang.String-) | Ruft das `Object` mit dem angegebenen Schlüssel ab oder setzt es. |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Setzt das `Object` mit dem angegebenen Schlüssel. |
| [addValue(String key, String value)](#addValue-java.lang.String-java.lang.String-) | Fügt den Wert dem angegebenen Schlüssel hinzu. |
| [addValue(String key, Object value)](#addValue-java.lang.String-java.lang.Object-) | Fügt den Wert dem angegebenen Schlüssel hinzu. |
| [tryGetValue(String key, Object[] value)](#tryGetValue-java.lang.String-java.lang.Object---) | Ruft den Wert über den `key` ab. |
| [remove(String key)](#remove-java.lang.String-) | Entfernt den Wert mit dem angegebenen Schlüssel. |
| [clear()](#clear--) | Löscht diese Instanz. |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.imaging.xmp.IXmlValue-) | Legt den Wert fest. |
| [setValue(String key, IXmpType value)](#setValue-java.lang.String-com.aspose.imaging.xmp.types.IXmpType-) | Legt den Wert fest. |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.imaging.xmp.types.XmpTypeBase-) | Setzt den XMP-Typwert. |
| [getXmlValue()](#getXmlValue--) | Konvertiert den XMP-Wert in die XML-Darstellung. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der durch die Sammlung iteriert. |
### XmpPackage(String prefix, String namespaceUri) {#XmpPackage-java.lang.String-java.lang.String-}
```
public XmpPackage(String prefix, String namespaceUri)
```


Initialisiert eine neue Instanz der Klasse `XmpPackage`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Präfix | java.lang.String | Das Präfix. |
| namespaceUri | java.lang.String | Die Namespace-URI. |

### getXmlNamespace() {#getXmlNamespace--}
```
public String getXmlNamespace()
```


Ruft den XML-Namespace ab.

Wert: Der XML-Namespace.

**Returns:**
java.lang.String
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Ruft das Präfix ab.

Wert: Das Präfix.

**Returns:**
java.lang.String
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Ruft die Namespace-URI ab.

Wert: Der Namespace-URI.

**Returns:**
java.lang.String
### getKeys() {#getKeys--}
```
public System.Collections.Generic.Dictionary.KeyCollection<String,Object> getKeys()
```


Ruft die Schlüssel im XMP-Paket ab.

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary.KeyCollection<java.lang.String,java.lang.Object>
### getCount() {#getCount--}
```
public final int getCount()
```


Ruft die Anzahl der XMP-Schlüssel ab.

**Returns:**
int - die XMP-Schlüsselanzahl.
### containsKey(String key) {#containsKey-java.lang.String-}
```
public boolean containsKey(String key)
```


Bestimmt, ob diese Sammlung den angegebenen Schlüssel enthält.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Schlüssel | java.lang.String | Der Schlüssel, der geprüft werden soll. |

**Returns:**
boolean - `true`, wenn die Sammlung den angegebenen Schlüssel enthält; andernfalls `false`.
### get_Item(String key) {#get-Item-java.lang.String-}
```
public Object get_Item(String key)
```


Ruft das `Object` mit dem angegebenen Schlüssel ab oder setzt es.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Schlüssel | java.lang.String | Der Schlüssel, der den Wert identifiziert. |

**Returns:**
java.lang.Object - gibt das `Object` mit dem angegebenen Schlüssel zurück.
### set_Item(String key, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public void set_Item(String key, Object value)
```


Setzt das `Object` mit dem angegebenen Schlüssel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Schlüssel | java.lang.String | Der Schlüssel, der den Wert identifiziert. |
| Wert | java.lang.Object | Der `Object`-Wert. |

### addValue(String key, String value) {#addValue-java.lang.String-java.lang.String-}
```
public void addValue(String key, String value)
```


Fügt den Wert dem angegebenen Schlüssel hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Schlüssel | java.lang.String | Die String-Darstellung des Schlüssels, die mit dem hinzugefügten Wert identifiziert wird. |
| Wert | java.lang.String | Der Wert, zu dem hinzugefügt wird. |

### addValue(String key, Object value) {#addValue-java.lang.String-java.lang.Object-}
```
public void addValue(String key, Object value)
```


Fügt den Wert dem angegebenen Schlüssel hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Schlüssel | java.lang.String | Die String-Darstellung des Schlüssels, die mit dem hinzugefügten Wert identifiziert wird. |
| Wert | java.lang.Object | Der Wert, zu dem hinzugefügt wird. |

### tryGetValue(String key, Object[] value) {#tryGetValue-java.lang.String-java.lang.Object---}
```
public final boolean tryGetValue(String key, Object[] value)
```


Ruft den Wert über den `key` ab.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Schlüssel | java.lang.String | Der XMP-Elementschlüssel. |
| Wert | java.lang.Object[] | Der XMP-Wert. |

**Returns:**
boolean - `true`, wenn die Sammlung den `key` enthält; andernfalls `false`.
### remove(String key) {#remove-java.lang.String-}
```
public boolean remove(String key)
```


Entfernt den Wert mit dem angegebenen Schlüssel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Schlüssel | java.lang.String | Die Zeichenkettenrepräsentation des Schlüssels, der mit dem entfernten Wert identifiziert wird. |

**Returns:**
boolean - gibt true zurück, wenn der Wert mit dem angegebenen Schlüssel entfernt wurde.
### clear() {#clear--}
```
public void clear()
```


Löscht diese Instanz.

### setValue(String key, IXmlValue value) {#setValue-java.lang.String-com.aspose.imaging.xmp.IXmlValue-}
```
public void setValue(String key, IXmlValue value)
```


Legt den Wert fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Schlüssel | java.lang.String | Die String-Darstellung des Schlüssels, die mit dem hinzugefügten Wert identifiziert wird. |
| value | [IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue) | Der Wert, zu dem hinzugefügt wird. |

### setValue(String key, IXmpType value) {#setValue-java.lang.String-com.aspose.imaging.xmp.types.IXmpType-}
```
public void setValue(String key, IXmpType value)
```


Legt den Wert fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Schlüssel | java.lang.String | Die String-Darstellung des Schlüssels, die mit dem hinzugefügten Wert identifiziert wird. |
| value | [IXmpType](../../com.aspose.imaging.xmp.types/ixmptype) | Der Wert, zu dem hinzugefügt wird. |

### setXmpTypeValue(String key, XmpTypeBase value) {#setXmpTypeValue-java.lang.String-com.aspose.imaging.xmp.types.XmpTypeBase-}
```
public void setXmpTypeValue(String key, XmpTypeBase value)
```


Setzt den XMP-Typwert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Schlüssel | java.lang.String | Die Zeichenkettenrepräsentation des Schlüssels, der mit dem gesetzten Wert identifiziert wird. |
| value | [XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase) | Der Wert, auf den gesetzt werden soll. |

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Konvertiert den XMP-Wert in die XML-Darstellung.

**Returns:**
java.lang.String - Gibt den XMP-Wert zurück, der in die XML-Darstellung konvertiert wurde.
### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,Object>> iterator()
```


Gibt einen Enumerator zurück, der durch die Sammlung iteriert.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object>> - A `T:System.Collections.Generic.IEnumerator\`1` that can be used to iterate through the collection.
