---
title: XmpBasicPackage
second_title: Aspose.Imaging for Java API Reference
description: Represents XMP basic namespace.
type: docs
weight: 10
url: /com.aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.XmpPackage](../../com.aspose.imaging.xmp/xmppackage)
```
public class XmpBasicPackage extends XmpPackage
```

Represents XMP basic namespace.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpBasicPackage()](#XmpBasicPackage--) | Initializes a new instance of the `XmpBasicPackage` class. |
| [XmpBasicPackage(String prefix, String namespaceUri)](#XmpBasicPackage-java.lang.String-java.lang.String-) | Initializes a new instance of the `XmpBasicPackage` class. |
## Fields

| Field | Description |
| --- | --- |
| [RATING_REJECTED](#RATING-REJECTED) | Rating rejected value. |
| [RATING_MIN](#RATING-MIN) | Rating min value. |
| [RATING_MAX](#RATING-MAX) | Rating max value. |
## Methods

| Method | Description |
| --- | --- |
| [setLabel(String label)](#setLabel-java.lang.String-) | Sets the label. |
| [addValue(String key, String value)](#addValue-java.lang.String-java.lang.String-) | Adds string property. |
| [setCreatedDate(Date createdDate)](#setCreatedDate-java.util.Date-) | Adds resource created date. |
| [setCreatedDate(String createdDate)](#setCreatedDate-java.lang.String-) | Adds resource created date. |
| [setCreatorTool(String creatorTool)](#setCreatorTool-java.lang.String-) | Sets the creator tool. |
| [setIdentifier(String[] identifier)](#setIdentifier-java.lang.String---) | Sets the identifier. |
| [setMetadataDate(Date metadataDate)](#setMetadataDate-java.util.Date-) | Adds metadata last changed date. |
| [setMetadataDate(String metadataDate)](#setMetadataDate-java.lang.String-) | Adds metadata last changed date. |
| [setModifyDate(Date modifiedDate)](#setModifyDate-java.util.Date-) | Adds resource last modified date. |
| [setModifyDate(String modifiedDate)](#setModifyDate-java.lang.String-) | Adds resource last modified date. |
| [setRating(int choice)](#setRating-int-) | Sets rating. |
### XmpBasicPackage() {#XmpBasicPackage--}
```
public XmpBasicPackage()
```


Initializes a new instance of the `XmpBasicPackage` class.

### XmpBasicPackage(String prefix, String namespaceUri) {#XmpBasicPackage-java.lang.String-java.lang.String-}
```
public XmpBasicPackage(String prefix, String namespaceUri)
```


Initializes a new instance of the `XmpBasicPackage` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| prefix | java.lang.String | The prefix. |
| namespaceUri | java.lang.String | The namespace URI. |

### RATING_REJECTED {#RATING-REJECTED}
```
public static final int RATING_REJECTED
```


Rating rejected value.

### RATING_MIN {#RATING-MIN}
```
public static final int RATING_MIN
```


Rating min value.

### RATING_MAX {#RATING-MAX}
```
public static final int RATING_MAX
```


Rating max value.

### setLabel(String label) {#setLabel-java.lang.String-}
```
public void setLabel(String label)
```


Sets the label.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| label | java.lang.String | The label. |

### addValue(String key, String value) {#addValue-java.lang.String-java.lang.String-}
```
public void addValue(String key, String value)
```


Adds string property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The string representation of key that is identified with added value. |
| value | java.lang.String | The string value. |

### setCreatedDate(Date createdDate) {#setCreatedDate-java.util.Date-}
```
public void setCreatedDate(Date createdDate)
```


Adds resource created date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createdDate | java.util.Date | Created date. |

### setCreatedDate(String createdDate) {#setCreatedDate-java.lang.String-}
```
public void setCreatedDate(String createdDate)
```


Adds resource created date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createdDate | java.lang.String | Created date. |

### setCreatorTool(String creatorTool) {#setCreatorTool-java.lang.String-}
```
public void setCreatorTool(String creatorTool)
```


Sets the creator tool.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| creatorTool | java.lang.String | Name of tool. |

### setIdentifier(String[] identifier) {#setIdentifier-java.lang.String---}
```
public void setIdentifier(String[] identifier)
```


Sets the identifier.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| identifier | java.lang.String[] | The identifier. |

### setMetadataDate(Date metadataDate) {#setMetadataDate-java.util.Date-}
```
public void setMetadataDate(Date metadataDate)
```


Adds metadata last changed date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| metadataDate | java.util.Date | Metadata date. |

### setMetadataDate(String metadataDate) {#setMetadataDate-java.lang.String-}
```
public void setMetadataDate(String metadataDate)
```


Adds metadata last changed date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| metadataDate | java.lang.String | Metadata date. |

### setModifyDate(Date modifiedDate) {#setModifyDate-java.util.Date-}
```
public void setModifyDate(Date modifiedDate)
```


Adds resource last modified date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| modifiedDate | java.util.Date | Last modified date. |

### setModifyDate(String modifiedDate) {#setModifyDate-java.lang.String-}
```
public void setModifyDate(String modifiedDate)
```


Adds resource last modified date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| modifiedDate | java.lang.String | Last modified date. |

### setRating(int choice) {#setRating-int-}
```
public void setRating(int choice)
```


Sets rating.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| choice | int | From -1 till 5 |

