---
title: "XmpBasicPackage klass"
type: docs
weight: 10
url: /sv/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---

**Summary:** Represents XMP basic namespace.

**Module:** [aspose.imaging.xmp.schemas.xmpbaseschema](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/)

**Full Name:** aspose.imaging.xmp.schemas.xmpbaseschema.XmpBasicPackage

**Inheritance:** IXmlValue, XmpPackage

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpBasicPackage()](#XmpBasicPackage__1) | Initierar en ny instans av [XmpBasicPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/) klassen. |
| [XmpBasicPackage(prefix, namespace_uri)](#XmpBasicPackage_prefix_namespace_uri_2) | Initierar en ny instans av [XmpBasicPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/) klassen. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| RATING_MAX [statisk] | int | r | Maxvärde för betyg. |
| RATING_MIN [statisk] | int | r | Minvärde för betyg. |
| RATING_REJECTED [statisk] | int | r | Avvisat betygsvärde. |
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
| [set_created_date(created_date)](#set_created_date_created_date_7) | Lägger till resursens skapandedatum. |
| [set_created_date(created_date)](#set_created_date_created_date_8) | Lägger till resursens skapandedatum. |
| [set_created_date_str(created_date)](#set_created_date_str_created_date_9) | Lägger till resursens skapandedatum. |
| [set_creator_tool(creator_tool)](#set_creator_tool_creator_tool_10) | Ställer in skapandeverktyget. |
| [set_identifier(idenfifier)](#set_identifier_idenfifier_11) | Ställer in identifieraren. |
| [set_label(label)](#set_label_label_12) | Ställer in etiketten. |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_13) | Lägger till datum för senaste ändring av metadata. |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_14) | Lägger till datum för senaste ändring av metadata. |
| [set_metadata_date_str(metadata_date)](#set_metadata_date_str_metadata_date_15) | Lägger till datum för senaste ändring av metadata. |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_16) | Lägger till datum för senaste ändring av resursen. |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_17) | Lägger till datum för senaste ändring av resursen. |
| [set_modify_date_str(modified_date)](#set_modify_date_str_modified_date_18) | Lägger till datum för senaste ändring av resursen. |
| [set_prop_value(key, value)](#set_prop_value_key_value_19) | Hämtar eller anger objektet med den angivna nyckeln. |
| [set_rating(choise)](#set_rating_choise_20) | Ställer in betyg. |
| [set_value(key, value)](#set_value_key_value_21) | Anger värdet. |
| [set_value(key, value)](#set_value_key_value_22) | Anger värdet. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_23) | Anger XMP‑typvärdet. |
| [try_get_value(key, value)](#try_get_value_key_value_24) | Hämtar värdet med _key_. |


### Constructor: XmpBasicPackage() {#XmpBasicPackage__1}


```
 XmpBasicPackage() 
```

Initierar en ny instans av [XmpBasicPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/) klassen.

### Constructor: XmpBasicPackage(prefix, namespace_uri) {#XmpBasicPackage_prefix_namespace_uri_2}


```
 XmpBasicPackage(prefix, namespace_uri) 
```

Initierar en ny instans av [XmpBasicPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/) klassen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| prefix | string | Prefixet. |
| namespace_uri | string | Namnområdets URI. |

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


### Method: set_created_date(created_date) {#set_created_date_created_date_7}


```
 set_created_date(created_date) 
```

Lägger till resursens skapandedatum.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| created_date | System.DateTime | Skapandedatum. |

### Method: set_created_date(created_date) {#set_created_date_created_date_8}


```
 set_created_date(created_date) 
```

Lägger till resursens skapandedatum.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| created_date | string | Skapandedatum. |

### Method: set_created_date_str(created_date) {#set_created_date_str_created_date_9}


```
 set_created_date_str(created_date) 
```

Lägger till resursens skapandedatum.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| created_date | string | Skapandedatum. |

### Method: set_creator_tool(creator_tool) {#set_creator_tool_creator_tool_10}


```
 set_creator_tool(creator_tool) 
```

Ställer in skapandeverktyget.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| creator_tool | string | Namn på verktyg. |

### Method: set_identifier(idenfifier) {#set_identifier_idenfifier_11}


```
 set_identifier(idenfifier) 
```

Ställer in identifieraren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| idenfifier | string[] | Den idenfifier. |

### Method: set_label(label) {#set_label_label_12}


```
 set_label(label) 
```

Ställer in etiketten.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| label | string | Etiketten. |

### Method: set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_13}


```
 set_metadata_date(metadata_date) 
```

Lägger till datum för senaste ändring av metadata.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| metadata_date | System.DateTime | Metadata datum. |

### Method: set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_14}


```
 set_metadata_date(metadata_date) 
```

Lägger till datum för senaste ändring av metadata.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| metadata_date | string | Metadata datum. |

### Method: set_metadata_date_str(metadata_date) {#set_metadata_date_str_metadata_date_15}


```
 set_metadata_date_str(metadata_date) 
```

Lägger till datum för senaste ändring av metadata.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| metadata_date | string | Metadata datum. |

### Method: set_modify_date(modified_date) {#set_modify_date_modified_date_16}


```
 set_modify_date(modified_date) 
```

Lägger till datum för senaste ändring av resursen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| modified_date | System.DateTime | Senast ändrade datum. |

### Method: set_modify_date(modified_date) {#set_modify_date_modified_date_17}


```
 set_modify_date(modified_date) 
```

Lägger till datum för senaste ändring av resursen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| modified_date | string | Senast ändrade datum. |

### Method: set_modify_date_str(modified_date) {#set_modify_date_str_modified_date_18}


```
 set_modify_date_str(modified_date) 
```

Lägger till datum för senaste ändring av resursen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| modified_date | string | Senast ändrade datum. |

### Method: set_prop_value(key, value) {#set_prop_value_key_value_19}


```
 set_prop_value(key, value) 
```

Hämtar eller anger objektet med den angivna nyckeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| key | string | Nyckeln som identifierar värdet. |
| värde | System.Object | Objektet med den angivna nyckeln. |

### Method: set_rating(choise) {#set_rating_choise_20}


```
 set_rating(choise) 
```

Ställer in betyg.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| val | int | Från -1 till 5 |

### Method: set_value(key, value) {#set_value_key_value_21}


```
 set_value(key, value) 
```

Anger värdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| key | string | Strängrepresentationen av nyckeln som identifieras med det tillagda värdet. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | Värdet att lägga till. |

### Method: set_value(key, value) {#set_value_key_value_22}


```
 set_value(key, value) 
```

Anger värdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| key | string | Strängrepresentationen av nyckeln som identifieras med det tillagda värdet. |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | Värdet att lägga till. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_23}


```
 set_xmp_type_value(key, value) 
```

Anger XMP‑typvärdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| key | string | Strängrepresentationen av nyckeln som identifieras med satt värde. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | Värdet att sätta till. |

### Method: try_get_value(key, value) {#try_get_value_key_value_24}


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


