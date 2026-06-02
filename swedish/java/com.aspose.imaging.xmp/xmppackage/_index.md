---
title: "XmpPackage"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar grundabstraktion för XMP‑paket."
type: docs
weight: 19
url: /sv/java/com.aspose.imaging.xmp/xmppackage/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public class XmpPackage implements IXmlValue, System.Collections.Generic.IGenericEnumerable<System.Collections.Generic.KeyValuePair<String,Object>>
```

Representerar grundabstraktion för XMP‑paket.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [XmpPackage(String prefix, String namespaceUri)](#XmpPackage-java.lang.String-java.lang.String-) | Initierar en ny instans av klassen `XmpPackage`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getXmlNamespace()](#getXmlNamespace--) | Hämtar XML-namnområdet. |
| [getPrefix()](#getPrefix--) | Hämtar prefixet. |
| [getNamespaceUri()](#getNamespaceUri--) | Hämtar namnrymdens URI. |
| [getKeys()](#getKeys--) | Hämtar nycklarna i XMP-paketet. |
| [getCount()](#getCount--) | Hämtar antalet XMP-nycklar. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Bestämmer om denna samling har den angivna nyckeln. |
| [get_Item(String key)](#get-Item-java.lang.String-) | Hämtar eller sätter `Object` med den angivna nyckeln. |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Sätter `Object` med den angivna nyckeln. |
| [addValue(String key, String value)](#addValue-java.lang.String-java.lang.String-) | Lägger till värdet till den angivna nyckeln. |
| [addValue(String key, Object value)](#addValue-java.lang.String-java.lang.Object-) | Lägger till värdet till den angivna nyckeln. |
| [tryGetValue(String key, Object[] value)](#tryGetValue-java.lang.String-java.lang.Object---) | Hämtar värdet med `key`. |
| [remove(String key)](#remove-java.lang.String-) | Tar bort värdet med den angivna nyckeln. |
| [clear()](#clear--) | Rensar denna instans. |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.imaging.xmp.IXmlValue-) | Ställer in värdet. |
| [setValue(String key, IXmpType value)](#setValue-java.lang.String-com.aspose.imaging.xmp.types.IXmpType-) | Ställer in värdet. |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.imaging.xmp.types.XmpTypeBase-) | Sätter XMP-typvärdet. |
| [getXmlValue()](#getXmlValue--) | Konverterar XMP-värde till XML-representationen. |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
### XmpPackage(String prefix, String namespaceUri) {#XmpPackage-java.lang.String-java.lang.String-}
```
public XmpPackage(String prefix, String namespaceUri)
```


Initierar en ny instans av klassen `XmpPackage`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prefix | java.lang.String | Prefixet. |
| namespaceUri | java.lang.String | Namnområdets URI. |

### getXmlNamespace() {#getXmlNamespace--}
```
public String getXmlNamespace()
```


Hämtar XML-namnområdet.

Värde: XML-namnutrymmet.

**Returns:**
java.lang.String
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Hämtar prefixet.

Värde: Prefixet.

**Returns:**
java.lang.String
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Hämtar namnrymdens URI.

Värde: Namnutrymmes-URI.

**Returns:**
java.lang.String
### getKeys() {#getKeys--}
```
public System.Collections.Generic.Dictionary.KeyCollection<String,Object> getKeys()
```


Hämtar nycklarna i XMP-paketet.

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary.KeyCollection<java.lang.String,java.lang.Object>
### getCount() {#getCount--}
```
public final int getCount()
```


Hämtar antalet XMP-nycklar.

**Returns:**
int - antalet XMP-nycklar.
### containsKey(String key) {#containsKey-java.lang.String-}
```
public boolean containsKey(String key)
```


Bestämmer om denna samling har den angivna nyckeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | java.lang.String | Nyckeln som ska kontrolleras. |

**Returns:**
boolean - `true` om samlingen innehåller den angivna nyckeln; annars `false`.
### get_Item(String key) {#get-Item-java.lang.String-}
```
public Object get_Item(String key)
```


Hämtar eller sätter `Object` med den angivna nyckeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | java.lang.String | Nyckeln som identifierar värdet. |

**Returns:**
java.lang.Object - Returnerar `Object` med den angivna nyckeln.
### set_Item(String key, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public void set_Item(String key, Object value)
```


Sätter `Object` med den angivna nyckeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | java.lang.String | Nyckeln som identifierar värdet. |
| värde | java.lang.Object | Värdet `Object`. |

### addValue(String key, String value) {#addValue-java.lang.String-java.lang.String-}
```
public void addValue(String key, String value)
```


Lägger till värdet till den angivna nyckeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | java.lang.String | Strängrepresentationen av nyckeln som identifieras med det tillagda värdet. |
| värde | java.lang.String | Värdet att lägga till. |

### addValue(String key, Object value) {#addValue-java.lang.String-java.lang.Object-}
```
public void addValue(String key, Object value)
```


Lägger till värdet till den angivna nyckeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | java.lang.String | Strängrepresentationen av nyckeln som identifieras med det tillagda värdet. |
| värde | java.lang.Object | Värdet att lägga till. |

### tryGetValue(String key, Object[] value) {#tryGetValue-java.lang.String-java.lang.Object---}
```
public final boolean tryGetValue(String key, Object[] value)
```


Hämtar värdet med `key`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | java.lang.String | XMP-elementets nyckel. |
| värde | java.lang.Object[] | XMP-värdet. |

**Returns:**
boolean - `true` om samlingen innehåller `key`; annars `false`.
### remove(String key) {#remove-java.lang.String-}
```
public boolean remove(String key)
```


Tar bort värdet med den angivna nyckeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | java.lang.String | Strängrepresentationen av nyckeln som identifieras med borttaget värde. |

**Returns:**
boolean - Returnerar true om värdet med den angivna nyckeln togs bort.
### clear() {#clear--}
```
public void clear()
```


Rensar denna instans.

### setValue(String key, IXmlValue value) {#setValue-java.lang.String-com.aspose.imaging.xmp.IXmlValue-}
```
public void setValue(String key, IXmlValue value)
```


Ställer in värdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | java.lang.String | Strängrepresentationen av nyckeln som identifieras med det tillagda värdet. |
| value | [IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue) | Värdet att lägga till. |

### setValue(String key, IXmpType value) {#setValue-java.lang.String-com.aspose.imaging.xmp.types.IXmpType-}
```
public void setValue(String key, IXmpType value)
```


Ställer in värdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | java.lang.String | Strängrepresentationen av nyckeln som identifieras med det tillagda värdet. |
| value | [IXmpType](../../com.aspose.imaging.xmp.types/ixmptype) | Värdet att lägga till. |

### setXmpTypeValue(String key, XmpTypeBase value) {#setXmpTypeValue-java.lang.String-com.aspose.imaging.xmp.types.XmpTypeBase-}
```
public void setXmpTypeValue(String key, XmpTypeBase value)
```


Sätter XMP-typvärdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | java.lang.String | Strängrepresentationen av nyckeln som identifieras med satt värde. |
| value | [XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase) | Värdet att sätta till. |

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Konverterar XMP-värde till XML-representationen.

**Returns:**
java.lang.String - Returnerar XMP‑värdet konverterat till XML-representationen.
### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,Object>> iterator()
```


Returnerar en enumerator som itererar genom samlingen.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object>> - En `T:System.Collections.Generic.IEnumerator\`1` som kan användas för att iterera genom samlingen.
