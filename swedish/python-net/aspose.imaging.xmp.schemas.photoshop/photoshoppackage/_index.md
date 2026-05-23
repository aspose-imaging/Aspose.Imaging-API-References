---
title: "PhotoshopPackage-klass"
type: docs
weight: 20
url: /sv/python-net/aspose.imaging.xmp.schemas.photoshop/photoshoppackage/
---

**Summary:** Represents Adobe Photoshop namespace.

**Module:** [aspose.imaging.xmp.schemas.photoshop](/imaging/python-net/aspose.imaging.xmp.schemas.photoshop/)

**Full Name:** aspose.imaging.xmp.schemas.photoshop.PhotoshopPackage

**Inheritance:** IXmlValue, XmpPackage

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PhotoshopPackage()](#PhotoshopPackage__1) | Initierar en ny instans av klassen [PhotoshopPackage](/imaging/python-net/aspose.imaging.xmp.schemas.photoshop/photoshoppackage/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| URGENCY_MAX [statisk] | int | r | Högsta brådskevärde. |
| URGENCY_MIN [statisk] | int | r | Minsta brådskevärde. |
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
| [set_authors_position(authors_position)](#set_authors_position_authors_position_7) | Ställer in författarens position. |
| [set_caption_writer(caption_writer)](#set_caption_writer_caption_writer_8) | Ställer in bildtextens författare. |
| [set_category(category)](#set_category_category_9) | Ställer in kategorin. |
| [set_city(city)](#set_city_city_10) | Ställer in staden. |
| [set_color_mode(color_mode)](#set_color_mode_color_mode_11) | Ställer in färgläget. |
| [set_country(country)](#set_country_country_12) | Ställer in landet. |
| [set_created_date(created_date)](#set_created_date_created_date_13) | Ställer in skapelsedatum. |
| [set_credit(credit)](#set_credit_credit_14) | Ställer in krediten. |
| [set_document_ancestors(ancestors)](#set_document_ancestors_ancestors_15) | Ställer in dokumentets förfäder. |
| [set_headline(headline)](#set_headline_headline_16) | Ställer in rubriken. |
| [set_history(history)](#set_history_history_17) | Ställer in historiken. |
| [set_icc_profile(icc_profile)](#set_icc_profile_icc_profile_18) | Ställer in icc-profilen. |
| [set_instructions(instructions)](#set_instructions_instructions_19) | Ställer in instruktionerna. |
| [set_prop_value(key, value)](#set_prop_value_key_value_20) | Hämtar eller anger objektet med den angivna nyckeln. |
| [set_source(source)](#set_source_source_21) | Ställer in källan. |
| [set_state(state)](#set_state_state_22) | Ställer in staten. |
| [set_supplemental_categories(supplemental_categories)](#set_supplemental_categories_supplemental_categories_23) | Ställer in kompletterande kategorier. |
| [set_transmission_reference(transmission_reference)](#set_transmission_reference_transmission_reference_24) | Ställer in överföringsreferensen. |
| [set_urgency(urgency)](#set_urgency_urgency_25) | Ställer in brådskan. |
| [set_value(key, value)](#set_value_key_value_26) | Anger värdet. |
| [set_value(key, value)](#set_value_key_value_27) | Anger värdet. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_28) | Anger XMP‑typvärdet. |
| [try_get_value(key, value)](#try_get_value_key_value_29) | Hämtar värdet med _key_. |


### Constructor: PhotoshopPackage() {#PhotoshopPackage__1}


```
 PhotoshopPackage() 
```

Initierar en ny instans av klassen [PhotoshopPackage](/imaging/python-net/aspose.imaging.xmp.schemas.photoshop/photoshoppackage/).

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


### Method: set_authors_position(authors_position) {#set_authors_position_authors_position_7}


```
 set_authors_position(authors_position) 
```

Ställer in författarens position.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| authors_position | string | Författarnas position. |

### Method: set_caption_writer(caption_writer) {#set_caption_writer_caption_writer_8}


```
 set_caption_writer(caption_writer) 
```

Ställer in bildtextens författare.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| caption_writer | string | Bildtextförfattaren. |

### Method: set_category(category) {#set_category_category_9}


```
 set_category(category) 
```

Ställer in kategorin.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| category | string | Kategorin. |

### Method: set_city(city) {#set_city_city_10}


```
 set_city(city) 
```

Ställer in staden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| city | string | Stadens namn. |

### Method: set_color_mode(color_mode) {#set_color_mode_color_mode_11}


```
 set_color_mode(color_mode) 
```

Ställer in färgläget.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| color_mode | [ColorMode](/imaging/python-net/aspose.imaging.xmp.schemas.photoshop/colormode/) | Färgläget. |

### Method: set_country(country) {#set_country_country_12}


```
 set_country(country) 
```

Ställer in landet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| country | string | Landet. |

### Method: set_created_date(created_date) {#set_created_date_created_date_13}


```
 set_created_date(created_date) 
```

Ställer in skapelsedatum.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| created_date | System.DateTime | Det skapade datumet. |

### Method: set_credit(credit) {#set_credit_credit_14}


```
 set_credit(credit) 
```

Ställer in krediten.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| credit | string | Krediten. |

### Method: set_document_ancestors(ancestors) {#set_document_ancestors_ancestors_15}


```
 set_document_ancestors(ancestors) 
```

Ställer in dokumentets förfäder.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ancestors | string[] | Förfäderna. |

### Method: set_headline(headline) {#set_headline_headline_16}


```
 set_headline(headline) 
```

Ställer in rubriken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| headline | string | Rubriken. |

### Method: set_history(history) {#set_history_history_17}


```
 set_history(history) 
```

Ställer in historiken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| history | string | Historien. |

### Method: set_icc_profile(icc_profile) {#set_icc_profile_icc_profile_18}


```
 set_icc_profile(icc_profile) 
```

Ställer in icc-profilen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| icc_profile | string | ICC-profilen. |

### Method: set_instructions(instructions) {#set_instructions_instructions_19}


```
 set_instructions(instructions) 
```

Ställer in instruktionerna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| instructions | string | Instruktionerna. |

### Method: set_prop_value(key, value) {#set_prop_value_key_value_20}


```
 set_prop_value(key, value) 
```

Hämtar eller anger objektet med den angivna nyckeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| key | string | Nyckeln som identifierar värdet. |
| värde | System.Object | Objektet med den angivna nyckeln. |

### Method: set_source(source) {#set_source_source_21}


```
 set_source(source) 
```

Ställer in källan.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| källa | string | Källan. |

### Method: set_state(state) {#set_state_state_22}


```
 set_state(state) 
```

Ställer in staten.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| tillstånd | string | Tillståndet. |

### Method: set_supplemental_categories(supplemental_categories) {#set_supplemental_categories_supplemental_categories_23}


```
 set_supplemental_categories(supplemental_categories) 
```

Ställer in kompletterande kategorier.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| supplemental_categories | string[] | De kompletterande kategorierna. |

### Method: set_transmission_reference(transmission_reference) {#set_transmission_reference_transmission_reference_24}


```
 set_transmission_reference(transmission_reference) 
```

Ställer in överföringsreferensen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| transmission_reference | string | Referensen för överföringen. |

### Method: set_urgency(urgency) {#set_urgency_urgency_25}


```
 set_urgency(urgency) 
```

Ställer in brådskan.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| urgency | int | Brådskan. |

### Method: set_value(key, value) {#set_value_key_value_26}


```
 set_value(key, value) 
```

Anger värdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| key | string | Strängrepresentationen av nyckeln som identifieras med det tillagda värdet. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | Värdet att lägga till. |

### Method: set_value(key, value) {#set_value_key_value_27}


```
 set_value(key, value) 
```

Anger värdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| key | string | Strängrepresentationen av nyckeln som identifieras med det tillagda värdet. |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | Värdet att lägga till. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_28}


```
 set_xmp_type_value(key, value) 
```

Anger XMP‑typvärdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| key | string | Strängrepresentationen av nyckeln som identifieras med satt värde. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | Värdet att sätta till. |

### Method: try_get_value(key, value) {#try_get_value_key_value_29}


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


