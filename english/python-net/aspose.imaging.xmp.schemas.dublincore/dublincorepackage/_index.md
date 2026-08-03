---
title: DublinCorePackage Class
type: docs
weight: 10
url: /python-net/aspose.imaging.xmp.schemas.dublincore/dublincorepackage/
---

**Summary:** Represents Dublin Core schema.

**Module:** [aspose.imaging.xmp.schemas.dublincore](/imaging/python-net/aspose.imaging.xmp.schemas.dublincore/)

**Full Name:** aspose.imaging.xmp.schemas.dublincore.DublinCorePackage

**Inheritance:** XmpPackage

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [DublinCorePackage()](#DublinCorePackage__1) | Initializes a new instance of the [DublinCorePackage](/imaging/python-net/aspose.imaging.xmp.schemas.dublincore/dublincorepackage/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| count | int | r | Gets the XMP key count. |
| keys | System.Collections.Generic.ICollection`1[[System.String]] | r | Gets the keys in XMP package. |
| namespace_uri | string | r | Gets the namespace URI. |
| prefix | string | r | Gets the prefix. |
| xml_namespace | string | r | Gets the XML namespace. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Adds string property. |
| [add_value(key, value)](#add_value_key_value_2) | Adds string property. |
| clear() | Clears this instance. |
| [contains_key(key)](#contains_key_key_3) | Determines whether this collection specified key. |
| [get_prop_value(key)](#get_prop_value_key_4) | Gets the first XMP attribute or element value with by specified _key_. |
| [remove(key)](#remove_key_5) | Removes the first element or attribute value with the specified key. |
| [set_author(author)](#set_author_author_6) | Adds the author. |
| [set_author(author)](#set_author_author_7) | Adds the author. |
| [set_author_array(author)](#set_author_array_author_8) | Adds the author. |
| [set_description(desc)](#set_description_desc_9) | Adds the description. |
| [set_description(desc)](#set_description_desc_10) | Adds the description. |
| [set_description_lang_alt(desc)](#set_description_lang_alt_desc_11) | Adds the description. |
| [set_description_str(desc)](#set_description_str_desc_12) | Adds the description. |
| [set_prop_value(key, value)](#set_prop_value_key_value_13) | Sets the first XMP attribute or element value with by specified _key_. |
| [set_publisher(publisher)](#set_publisher_publisher_14) | Adds the publisher. |
| [set_publisher(publisher)](#set_publisher_publisher_15) | Adds the publisher. |
| [set_publisher_array(publisher)](#set_publisher_array_publisher_16) | Adds the publisher. |
| [set_subject(subject)](#set_subject_subject_17) | Adds the subject. |
| [set_subject(subject)](#set_subject_subject_18) | Adds the subject. |
| [set_subject_array(subject)](#set_subject_array_subject_19) | Adds the subject. |
| [set_title(title)](#set_title_title_20) | Adds Dublin Core title. |
| [set_title(title)](#set_title_title_21) | Adds Dublin Core title. |
| [set_title_lang_alt(title)](#set_title_lang_alt_title_22) | Adds Dublin Core title for different languages. |
| [set_title_str(title)](#set_title_str_title_23) | Adds Dublin Core title. |
| [set_value(key, value)](#set_value_key_value_24) | Sets the value. |
| [set_value(key, value)](#set_value_key_value_25) | Sets the value. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_26) | Sets the XMP type value. |
| [try_get_value(key, value)](#try_get_value_key_value_27) | Gets the value by the _key_. |


### Constructor: DublinCorePackage() {#DublinCorePackage__1}


```
 DublinCorePackage() 
```

Initializes a new instance of the [DublinCorePackage](/imaging/python-net/aspose.imaging.xmp.schemas.dublincore/dublincorepackage/) class.

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Adds string property.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with added value. |
| value | string | The string value. |

### Method: add_value(key, value) {#add_value_key_value_2}


```
 add_value(key, value) 
```

Adds string property.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with added value. |
| value | System.Object | The string value. |

### Method: contains_key(key) {#contains_key_key_3}


```
 contains_key(key) 
```

Determines whether this collection specified key.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The key to be checked. |

**Returns**

| Type | Description |
| :- | :- |
| bool | **True** if the  contains the specified key; otherwise, **False**. |


### Method: get_prop_value(key) {#get_prop_value_key_4}


```
 get_prop_value(key) 
```

Gets the first XMP attribute or element value with by specified _key_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The key that identifies value. |

**Returns**

| Type | Description |
| :- | :- |
| [XmpValue](/imaging/python-net/aspose.imaging.xmp.types/xmpvalue/) | Returns the [XmpValue](/imaging/python-net/aspose.imaging.xmp.types/xmpvalue/) by the specified key. |


### Method: remove(key) {#remove_key_5}


```
 remove(key) 
```

Removes the first element or attribute value with the specified key.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with removed value. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Returns true if the value with the specified key was removed. |


### Method: set_author(author) {#set_author_author_6}


```
 set_author(author) 
```

Adds the author.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| author | string | The author. |

### Method: set_author(author) {#set_author_author_7}


```
 set_author(author) 
```

Adds the author.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| author | string[] | The author. |

### Method: set_author_array(author) {#set_author_array_author_8}


```
 set_author_array(author) 
```

Adds the author.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| author | string[] | The author. |

### Method: set_description(desc) {#set_description_desc_9}


```
 set_description(desc) 
```

Adds the description.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| desc | string | The description. |

### Method: set_description(desc) {#set_description_desc_10}


```
 set_description(desc) 
```

Adds the description.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| desc | [LangAlt](/imaging/python-net/aspose.imaging.xmp/langalt/) | The description. |

### Method: set_description_lang_alt(desc) {#set_description_lang_alt_desc_11}


```
 set_description_lang_alt(desc) 
```

Adds the description.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| desc | [LangAlt](/imaging/python-net/aspose.imaging.xmp/langalt/) | The description. |

### Method: set_description_str(desc) {#set_description_str_desc_12}


```
 set_description_str(desc) 
```

Adds the description.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| desc | string | The description. |

### Method: set_prop_value(key, value) {#set_prop_value_key_value_13}


```
 set_prop_value(key, value) 
```

Sets the first XMP attribute or element value with by specified _key_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The key that identifies value. |
| value | [XmpValue](/imaging/python-net/aspose.imaging.xmp.types/xmpvalue/) | The [XmpValue](/imaging/python-net/aspose.imaging.xmp.types/xmpvalue/) value. |

### Method: set_publisher(publisher) {#set_publisher_publisher_14}


```
 set_publisher(publisher) 
```

Adds the publisher.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| publisher | string | The publisher. |

### Method: set_publisher(publisher) {#set_publisher_publisher_15}


```
 set_publisher(publisher) 
```

Adds the publisher.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| publisher | string[] | The publisher. |

### Method: set_publisher_array(publisher) {#set_publisher_array_publisher_16}


```
 set_publisher_array(publisher) 
```

Adds the publisher.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| publisher | string[] | The publisher. |

### Method: set_subject(subject) {#set_subject_subject_17}


```
 set_subject(subject) 
```

Adds the subject.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| subject | string | The subject. |

### Method: set_subject(subject) {#set_subject_subject_18}


```
 set_subject(subject) 
```

Adds the subject.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| subject | string[] | The subject. |

### Method: set_subject_array(subject) {#set_subject_array_subject_19}


```
 set_subject_array(subject) 
```

Adds the subject.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| subject | string[] | The subject. |

### Method: set_title(title) {#set_title_title_20}


```
 set_title(title) 
```

Adds Dublin Core title.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| title | string | The title. |

### Method: set_title(title) {#set_title_title_21}


```
 set_title(title) 
```

Adds Dublin Core title.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| title | [LangAlt](/imaging/python-net/aspose.imaging.xmp/langalt/) | The title. |

### Method: set_title_lang_alt(title) {#set_title_lang_alt_title_22}


```
 set_title_lang_alt(title) 
```

Adds Dublin Core title for different languages.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| title | [LangAlt](/imaging/python-net/aspose.imaging.xmp/langalt/) | Instance of [LangAlt](/imaging/python-net/aspose.imaging.xmp/langalt/). |

### Method: set_title_str(title) {#set_title_str_title_23}


```
 set_title_str(title) 
```

Adds Dublin Core title.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| title | string | The title. |

### Method: set_value(key, value) {#set_value_key_value_24}


```
 set_value(key, value) 
```

Sets the value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with added value. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | The value to add to. |

### Method: set_value(key, value) {#set_value_key_value_25}


```
 set_value(key, value) 
```

Sets the value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with added value. |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | The value to add to. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_26}


```
 set_xmp_type_value(key, value) 
```

Sets the XMP type value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with set value. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | The value to set to. |

### Method: try_get_value(key, value) {#try_get_value_key_value_27}


```
 try_get_value(key, value) 
```

Gets the value by the _key_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The XMP element key. |
| value | [XmpValue[]](/imaging/python-net/aspose.imaging.xmp.types/xmpvalue/) | The XMP value. |

**Returns**

| Type | Description |
| :- | :- |
| bool | **True**, if the  contains the _key_; otherwise, **False**. |


