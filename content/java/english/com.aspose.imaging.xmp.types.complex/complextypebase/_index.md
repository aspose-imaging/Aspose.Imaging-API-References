---
title: ComplexTypeBase
second_title: Aspose.Imaging for Java API Reference
description: Represents base abstraction for XMP Complex value type.
type: docs
weight: 10
url: /com.aspose.imaging.xmp.types.complex/complextypebase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)
```
public class ComplexTypeBase extends XmpTypeBase
```

Represents base abstraction for XMP Complex value type.

See more: XMP Specification Part 2, Chapter 1.2.2
## Constructors

| Constructor | Description |
| --- | --- |
| [ComplexTypeBase(String prefix, String namespaceUri)](#ComplexTypeBase-java.lang.String-java.lang.String-) | Initializes a new instance of the `ComplexTypeBase` class. |
## Methods

| Method | Description |
| --- | --- |
| [getPrefix()](#getPrefix--) | Gets the prefix. |
| [getNamespaceUri()](#getNamespaceUri--) | Gets the default namespace URI. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Gets the string contained value in XMP format. |
### ComplexTypeBase(String prefix, String namespaceUri) {#ComplexTypeBase-java.lang.String-java.lang.String-}
```
public ComplexTypeBase(String prefix, String namespaceUri)
```


Initializes a new instance of the `ComplexTypeBase` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| prefix | java.lang.String | The prefix. |
| namespaceUri | java.lang.String | The namespace URI. |

### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Gets the prefix.

**Returns:**
java.lang.String - The prefix.
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Gets the default namespace URI.

**Returns:**
java.lang.String - The default namespace URI.
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Gets the string contained value in XMP format.

**Returns:**
java.lang.String - Returns the string contained value in XMP format.
