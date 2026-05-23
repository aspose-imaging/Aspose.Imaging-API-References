---
title: "XmpPackage-klass"
type: docs
weight: 460
url: /sv/python-net/aspose.imaging.xmp/xmppackage/
---

**Summary:** Represents base abstraction for XMP package.

**Module:** [aspose.imaging.xmp](/imaging/python-net/aspose.imaging.xmp/)

**Full Name:** aspose.imaging.xmp.XmpPackage

**Inheritance:** IXmlValue

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| count | int | r | Hämtar antalet XMP-nycklar. |
| namespace_uri | string | r | Hämtar namnrymdens URI. |
| prefix | string | r | Hämtar prefixet. |
| xml_namespace | string | r | Hämtar XML-namnrymden. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Lägger till värdet i den angivna nyckeln. |
| [add_value(key, value)](#add_value_key_value_2) | Lägger till värdet i den angivna nyckeln. |
| clear() | Rensar detta objekt. |
| [contains_key(key)](#contains_key_key_3) | Bestämmer om denna samling har den angivna nyckeln. |
| [get_prop_value(key)](#get_prop_value_key_4) | Hämtar objektet med den angivna nyckeln. |
| [get_xml_value()](#get_xml_value__5) | Konverterar XMP‑värde till XML‑representationen. |
| [remove(key)](#remove_key_6) | Tar bort värdet med den angivna nyckeln. |
| [set_prop_value(key, value)](#set_prop_value_key_value_7) | Hämtar eller anger objektet med den angivna nyckeln. |
| [set_value(key, value)](#set_value_key_value_8) | Anger värdet. |
| [set_value(key, value)](#set_value_key_value_9) | Anger värdet. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_10) | Anger XMP‑typvärdet. |
| [try_get_value(key, value)](#try_get_value_key_value_11) | Hämtar värdet med _key_. |


### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Lägger till värdet i den angivna nyckeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| key | string | Strängrepresentationen av nyckeln som identifieras med det tillagda värdet. |
| värde | string | Värdet att lägga till. |

### Method: add_value(key, value) {#add_value_key_value_2}


```
 add_value(key, value) 
```

Lägger till värdet i den angivna nyckeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| key | string | Strängrepresentationen av nyckeln som identifieras med det tillagda värdet. |
| värde | System.Object | Värdet att lägga till. |

### Method: contains_key(key) {#contains_key_key_3}


```
 contains_key(key) 
```

Bestämmer om denna samling har den angivna nyckeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| key | string | Nyckeln som ska kontrolleras. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | **True** om den  innehåller den angivna nyckeln; annars, **False**. |


### Method: get_prop_value(key) {#get_prop_value_key_4}


```
 get_prop_value(key) 
```

Hämtar objektet med den angivna nyckeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| key | string | Nyckeln som identifierar värdet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| System.Object | Returnerar objektet med den angivna nyckeln. |


### Method: get_xml_value() {#get_xml_value__5}


```
 get_xml_value() 
```

Konverterar XMP‑värde till XML‑representationen.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string | Returnerar XMP‑värdet konverterat till XML‑representationen. |


### Method: remove(key) {#remove_key_6}


```
 remove(key) 
```

Tar bort värdet med den angivna nyckeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| key | string | Strängrepresentationen av nyckeln som identifieras med borttaget värde. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Returnerar true om värdet med den angivna nyckeln togs bort. |


### Method: set_prop_value(key, value) {#set_prop_value_key_value_7}


```
 set_prop_value(key, value) 
```

Hämtar eller anger objektet med den angivna nyckeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| key | string | Nyckeln som identifierar värdet. |
| värde | System.Object | Objektet med den angivna nyckeln. |

### Method: set_value(key, value) {#set_value_key_value_8}


```
 set_value(key, value) 
```

Anger värdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| key | string | Strängrepresentationen av nyckeln som identifieras med det tillagda värdet. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | Värdet att lägga till. |

### Method: set_value(key, value) {#set_value_key_value_9}


```
 set_value(key, value) 
```

Anger värdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| key | string | Strängrepresentationen av nyckeln som identifieras med det tillagda värdet. |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | Värdet att lägga till. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_10}


```
 set_xmp_type_value(key, value) 
```

Anger XMP‑typvärdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| key | string | Strängrepresentationen av nyckeln som identifieras med satt värde. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | Värdet att sätta till. |

### Method: try_get_value(key, value) {#try_get_value_key_value_11}


```
 try_get_value(key, value) 
```

Hämtar värdet med _key_.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| key | string | XMP‑elementnyckeln. |
| värde | System.Object | XMP‑värdet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | **True**, om den innehåller _key_; annars **False**. |


