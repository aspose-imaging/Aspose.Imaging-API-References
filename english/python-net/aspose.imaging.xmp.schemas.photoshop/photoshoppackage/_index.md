---
title: PhotoshopPackage Class
type: docs
weight: 20
url: /python-net/aspose.imaging.xmp.schemas.photoshop/photoshoppackage/
---

Represents Adobe Photoshop namespace.

**Module:** [aspose.imaging.xmp.schemas.photoshop](/imaging/python-net/aspose.imaging.xmp.schemas.photoshop/)

**Full Name:** aspose.imaging.xmp.schemas.photoshop.PhotoshopPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.Imaging Version:** 23.6

The PhotoshopPackage type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [PhotoshopPackage()](#PhotoshopPackage__0) | Initializes a new instance of the [PhotoshopPackage](/imaging/python-net/aspose.imaging.xmp.schemas.photoshop/photoshoppackage/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| xml_namespace | string | r | Gets the XML namespace. |
| prefix | string | r | Gets the prefix. |
| namespace_uri | string | r | Gets the namespace URI. |
| URGENCY_MAX [static] | int | r | Urgency max value. |
| URGENCY_MIN [static] | int | r | Urgency min value. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [contains_key(key)](#contains_key_key_1) | Determines whether the specified key contains key. |
| [get_prop_value(key)](#get_prop_value_key_2) | Gets the object with the specified key. |
| [set_prop_value(key, value)](#set_prop_value_key_value_3) | Gets or sets the object with the specified key. |
| [add_value(key, value)](#add_value_key_value_4) | Adds string property. |
| [remove(key)](#remove_key_5) | Remove the value with the specified key. |
| clear() | Clears this instance. |
| [set_value(key, value)](#set_value_key_value_6) | Sets the value. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_7) | Sets the XMP type value. |
| [get_xml_value()](#get_xml_value__8) | Converts XMP value to the XML representation. |
| [set_authors_position(authors_position)](#set_authors_position_authors_position_9) | Sets the authors position. |
| [set_caption_writer(caption_writer)](#set_caption_writer_caption_writer_10) | Sets the caption writer. |
| [set_category(category)](#set_category_category_11) | Sets the category. |
| [set_city(city)](#set_city_city_12) | Sets the city. |
| [set_color_mode(color_mode)](#set_color_mode_color_mode_13) | Sets the color mode. |
| [set_country(country)](#set_country_country_14) | Sets the country. |
| [set_credit(credit)](#set_credit_credit_15) | Sets the credit. |
| [set_created_date(created_date)](#set_created_date_created_date_16) | Sets created date. |
| [set_document_ancestors(ancestors)](#set_document_ancestors_ancestors_17) | Sets the document ancestors. |
| [set_headline(headline)](#set_headline_headline_18) | Sets the headline. |
| [set_history(history)](#set_history_history_19) | Sets the history. |
| [set_icc_profile(icc_profile)](#set_icc_profile_icc_profile_20) | Sets the icc profile. |
| [set_instructions(instructions)](#set_instructions_instructions_21) | Sets the instructions. |
| [set_source(source)](#set_source_source_22) | Sets the source. |
| [set_state(state)](#set_state_state_23) | Sets the state. |
| [set_supplemental_categories(supplemental_categories)](#set_supplemental_categories_supplemental_categories_24) | Sets supplemental categories. |
| [set_transmission_reference(transmission_reference)](#set_transmission_reference_transmission_reference_25) | Sets the transmission reference. |
| [set_urgency(urgency)](#set_urgency_urgency_26) | Sets the urgency. |

### PhotoshopPackage() {#PhotoshopPackage__0}


```
 PhotoshopPackage() 
```

Initializes a new instance of the [PhotoshopPackage](/imaging/python-net/aspose.imaging.xmp.schemas.photoshop/photoshoppackage/) class.

### contains_key(key) {#contains_key_key_1}


```
 contains_key(key) 
```

Determines whether the specified key contains key.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The key to be checked. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Returns true if the specified key contains key. |


### get_prop_value(key) {#get_prop_value_key_2}


```
 get_prop_value(key) 
```

Gets the object with the specified key.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The key that identifies value. |

**Returns**

| Type | Description |
| :- | :- |
| object | Returns the object with the specified key. |


### set_prop_value(key, value) {#set_prop_value_key_value_3}


```
 set_prop_value(key, value) 
```

Gets or sets the object with the specified key.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The key that identifies value. |
| value | object | The object with the specified key. |

### add_value(key, value) {#add_value_key_value_4}


```
 add_value(key, value) 
```

Adds string property.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with added value. |
| value | string | The string value. |

### remove(key) {#remove_key_5}


```
 remove(key) 
```

Remove the value with the specified key.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with removed value. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Returns true if the value with the specified key was removed. |


### set_value(key, value) {#set_value_key_value_6}


```
 set_value(key, value) 
```

Sets the value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with added value. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue) | The value to add to. |

### set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_7}


```
 set_xmp_type_value(key, value) 
```

Sets the XMP type value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with set value. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | The value to set to. |

### get_xml_value() {#get_xml_value__8}


```
 get_xml_value() 
```

Converts XMP value to the XML representation.

**Returns**

| Type | Description |
| :- | :- |
| string | Returns the XMP value converted to the XML representation. |


### set_authors_position(authors_position) {#set_authors_position_authors_position_9}


```
 set_authors_position(authors_position) 
```

Sets the authors position.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| authors_position | string | The authors position. |

### set_caption_writer(caption_writer) {#set_caption_writer_caption_writer_10}


```
 set_caption_writer(caption_writer) 
```

Sets the caption writer.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| caption_writer | string | The caption writer. |

### set_category(category) {#set_category_category_11}


```
 set_category(category) 
```

Sets the category.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| category | string | The category. |

### set_city(city) {#set_city_city_12}


```
 set_city(city) 
```

Sets the city.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| city | string | The city name. |

### set_color_mode(color_mode) {#set_color_mode_color_mode_13}


```
 set_color_mode(color_mode) 
```

Sets the color mode.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| color_mode | [ColorMode](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colormode) | The color mode. |

### set_country(country) {#set_country_country_14}


```
 set_country(country) 
```

Sets the country.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| country | string | The country. |

### set_credit(credit) {#set_credit_credit_15}


```
 set_credit(credit) 
```

Sets the credit.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| credit | string | The credit. |

### set_created_date(created_date) {#set_created_date_created_date_16}


```
 set_created_date(created_date) 
```

Sets created date.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| created_date | datetime | The created date. |

### set_document_ancestors(ancestors) {#set_document_ancestors_ancestors_17}


```
 set_document_ancestors(ancestors) 
```

Sets the document ancestors.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| ancestors | string | The ancestors. |

### set_headline(headline) {#set_headline_headline_18}


```
 set_headline(headline) 
```

Sets the headline.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| headline | string | The headline. |

### set_history(history) {#set_history_history_19}


```
 set_history(history) 
```

Sets the history.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| history | string | The history. |

### set_icc_profile(icc_profile) {#set_icc_profile_icc_profile_20}


```
 set_icc_profile(icc_profile) 
```

Sets the icc profile.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| icc_profile | string | The icc profile. |

### set_instructions(instructions) {#set_instructions_instructions_21}


```
 set_instructions(instructions) 
```

Sets the instructions.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| instructions | string | The instructions. |

### set_source(source) {#set_source_source_22}


```
 set_source(source) 
```

Sets the source.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | string | The source. |

### set_state(state) {#set_state_state_23}


```
 set_state(state) 
```

Sets the state.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| state | string | The state. |

### set_supplemental_categories(supplemental_categories) {#set_supplemental_categories_supplemental_categories_24}


```
 set_supplemental_categories(supplemental_categories) 
```

Sets supplemental categories.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| supplemental_categories | string | The supplemental categories. |

### set_transmission_reference(transmission_reference) {#set_transmission_reference_transmission_reference_25}


```
 set_transmission_reference(transmission_reference) 
```

Sets the transmission reference.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| transmission_reference | string | The transmission reference. |

### set_urgency(urgency) {#set_urgency_urgency_26}


```
 set_urgency(urgency) 
```

Sets the urgency.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| urgency | int | The urgency. |

