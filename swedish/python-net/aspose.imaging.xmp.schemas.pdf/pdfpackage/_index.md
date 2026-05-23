---
title: "PdfPackage-klass"
type: docs
weight: 10
url: /sv/python-net/aspose.imaging.xmp.schemas.pdf/pdfpackage/
---

**Summary:** Represents Adobe Pdf namespace.

**Module:** [aspose.imaging.xmp.schemas.pdf](/imaging/python-net/aspose.imaging.xmp.schemas.pdf/)

**Full Name:** aspose.imaging.xmp.schemas.pdf.PdfPackage

**Inheritance:** IXmlValue, XmpPackage

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PdfPackage()](#PdfPackage__1) | Initierar en ny instans av klassen [PdfPackage](/imaging/python-net/aspose.imaging.xmp.schemas.pdf/pdfpackage/). |
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
| [add_value(key, value)](#add_value_key_value_1) | Lägger till strängegenskap. |
| [add_value(key, value)](#add_value_key_value_2) | Lägger till strängegenskap. |
| clear() | Rensar detta objekt. |
| [contains_key(key)](#contains_key_key_3) | Bestämmer om denna samling har den angivna nyckeln. |
| [get_prop_value(key)](#get_prop_value_key_4) | Hämtar objektet med den angivna nyckeln. |
| [get_xml_value()](#get_xml_value__5) | Konverterar XMP‑värde till XML‑representationen. |
| [remove(key)](#remove_key_6) | Tar bort värdet med den angivna nyckeln. |
| [set_keywords(keywords)](#set_keywords_keywords_7) | Anger nyckelorden. |
| [set_pdf_version(version)](#set_pdf_version_version_8) | Anger PDF-versionen. |
| [set_producer(producer)](#set_producer_producer_9) | Anger namnet på verktyget som skapade PDF:en. |
| [set_prop_value(key, value)](#set_prop_value_key_value_10) | Hämtar eller anger objektet med den angivna nyckeln. |
| [set_trapped(is_trapped)](#set_trapped_is_trapped_11) | Anger fångst. |
| [set_value(key, value)](#set_value_key_value_12) | Anger värdet. |
| [set_value(key, value)](#set_value_key_value_13) | Anger värdet. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_14) | Anger XMP‑typvärdet. |
| [try_get_value(key, value)](#try_get_value_key_value_15) | Hämtar värdet med _key_. |


### Constructor: PdfPackage() {#PdfPackage__1}


```
 PdfPackage() 
```

Initierar en ny instans av klassen [PdfPackage](/imaging/python-net/aspose.imaging.xmp.schemas.pdf/pdfpackage/).

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Lägger till strängegenskap.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| key | string | Strängrepresentationen av nyckeln som identifieras med det tillagda värdet. |
| värde | string | Strängvärdet. |

### Method: add_value(key, value) {#add_value_key_value_2}


```
 add_value(key, value) 
```

Lägger till strängegenskap.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| key | string | Strängrepresentationen av nyckeln som identifieras med det tillagda värdet. |
| värde | System.Object | Strängvärdet. |

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


### Method: set_keywords(keywords) {#set_keywords_keywords_7}


```
 set_keywords(keywords) 
```

Anger nyckelorden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| nyckelord | string | Nyckelorden. |

### Method: set_pdf_version(version) {#set_pdf_version_version_8}


```
 set_pdf_version(version) 
```

Anger PDF-versionen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| version | string | Pdf-version, till exempel: 1.0, 1.3 osv. |

### Method: set_producer(producer) {#set_producer_producer_9}


```
 set_producer(producer) 
```

Anger namnet på verktyget som skapade PDF:en.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| producent | string | Producentens namn. |

### Method: set_prop_value(key, value) {#set_prop_value_key_value_10}


```
 set_prop_value(key, value) 
```

Hämtar eller anger objektet med den angivna nyckeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| key | string | Nyckeln som identifierar värdet. |
| värde | System.Object | Objektet med den angivna nyckeln. |

### Method: set_trapped(is_trapped) {#set_trapped_is_trapped_11}


```
 set_trapped(is_trapped) 
```

Anger fångst.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| is_trapped | bool | om den är satt till <c>true</c> har dokumentet blivit trappat. |

### Method: set_value(key, value) {#set_value_key_value_12}


```
 set_value(key, value) 
```

Anger värdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| key | string | Strängrepresentationen av nyckeln som identifieras med det tillagda värdet. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | Värdet att lägga till. |

### Method: set_value(key, value) {#set_value_key_value_13}


```
 set_value(key, value) 
```

Anger värdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| key | string | Strängrepresentationen av nyckeln som identifieras med det tillagda värdet. |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | Värdet att lägga till. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_14}


```
 set_xmp_type_value(key, value) 
```

Anger XMP‑typvärdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| key | string | Strängrepresentationen av nyckeln som identifieras med satt värde. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | Värdet att sätta till. |

### Method: try_get_value(key, value) {#try_get_value_key_value_15}


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


