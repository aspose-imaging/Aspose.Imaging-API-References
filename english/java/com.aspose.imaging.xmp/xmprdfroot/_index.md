---
title: XmpRdfRoot
second_title: Aspose.Imaging for Java API Reference
description: Represents rdfRDF element.
type: docs
weight: 21
url: /java/com.aspose.imaging.xmp/xmprdfroot/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.XmpElementBase](../../com.aspose.imaging.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue)
```
public final class XmpRdfRoot extends XmpElementBase implements IXmlValue
```

Represents rdf:RDF element. A single XMP packet shall be serialized using a single rdf:RDF XML element. The rdf:RDF element content shall consist of only zero or more rdf:Description elements.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpRdfRoot()](#XmpRdfRoot--) | Initializes a new instance of the `XmpRdfRoot` class. |
## Methods

| Method | Description |
| --- | --- |
| [registerNamespaceUri(String prefix, String namespaceUri)](#registerNamespaceUri-java.lang.String-java.lang.String-) | Adds namespace uri by prefix. |
| [getNamespaceUri(String prefix)](#getNamespaceUri-java.lang.String-) | Gets namespace URI by specific prefix. |
| [getXmlValue()](#getXmlValue--) | Converts xmp value to the xml representation. |
### XmpRdfRoot() {#XmpRdfRoot--}
```
public XmpRdfRoot()
```


Initializes a new instance of the `XmpRdfRoot` class.

### registerNamespaceUri(String prefix, String namespaceUri) {#registerNamespaceUri-java.lang.String-java.lang.String-}
```
public void registerNamespaceUri(String prefix, String namespaceUri)
```


Adds namespace uri by prefix. Prefix may start without xmlns.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| prefix | java.lang.String | The prefix. |
| namespaceUri | java.lang.String | Package schema uri. |

### getNamespaceUri(String prefix) {#getNamespaceUri-java.lang.String-}
```
public String getNamespaceUri(String prefix)
```


Gets namespace URI by specific prefix. Prefix may start without xmlns.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| prefix | java.lang.String | The prefix. |

**Returns:**
java.lang.String - Returns a package schema URI.
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Converts xmp value to the xml representation.

**Returns:**
java.lang.String - Returns XMP value converted to XML string.
