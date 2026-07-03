---
title: XmpPacketWrapper
second_title: Aspose.Imaging for Java API Reference
description: Contains serialized xmp package including header and trailer.
type: docs
weight: 20
url: /java/com.aspose.imaging.xmp/xmppacketwrapper/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), [com.aspose.imaging.metadata.IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)
```
public class XmpPacketWrapper implements IXmlValue, IImageMetadataFormat
```

Contains serialized xmp package including header and trailer.

A wrapper consisting of a pair of XML processing instructions (PIs) may be placed around the rdf:RDF element.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpPacketWrapper()](#XmpPacketWrapper--) | Initializes a new instance of the [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) class. |
| [XmpPacketWrapper(byte[] bytes)](#XmpPacketWrapper-byte---) | Initializes a new instance of the [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) class. |
| [XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)](#XmpPacketWrapper-com.aspose.imaging.xmp.XmpHeaderPi-com.aspose.imaging.xmp.XmpTrailerPi-com.aspose.imaging.xmp.XmpMeta-) | Initializes a new instance of the `XmpPacketWrapper` class. |
## Methods

| Method | Description |
| --- | --- |
| [getHeaderPi()](#getHeaderPi--) | Gets the header processing instruction. |
| [getMeta()](#getMeta--) | Gets the XMP meta. |
| [getTrailerPi()](#getTrailerPi--) | Gets the trailer processing instruction. |
| [getPackages()](#getPackages--) | Gets array of `XmpPackage` inside XMP. |
| [getPackagesCount()](#getPackagesCount--) | Gets amount of packages inside XMP structure. |
| [getBytes()](#getBytes--) | Gets the original Xmp bytes. |
| [addPackage(XmpPackage package_)](#addPackage-com.aspose.imaging.xmp.XmpPackage-) | Adds the package. |
| [getPackage(String namespaceUri)](#getPackage-java.lang.String-) | Gets package by namespace URI. |
| [containsPackage(String namespaceUri)](#containsPackage-java.lang.String-) | Determines whether a `namespaceUri` exists in the Xmp instance. |
| [removePackage(XmpPackage package_)](#removePackage-com.aspose.imaging.xmp.XmpPackage-) | Removes the XMP package. |
| [clearPackages()](#clearPackages--) | Removes all `XmpPackage` inside XMP. |
| [getXmlValue()](#getXmlValue--) | Converts XMP value to the XML representation. |
| [toString()](#toString--) | Returns an XML string that represents the current object. |
### XmpPacketWrapper() {#XmpPacketWrapper--}
```
public XmpPacketWrapper()
```


Initializes a new instance of the [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) class.

### XmpPacketWrapper(byte[] bytes) {#XmpPacketWrapper-byte---}
```
public XmpPacketWrapper(byte[] bytes)
```


Initializes a new instance of the [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bytes | byte[] | The original Xmp metadata bytes. |

### XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta) {#XmpPacketWrapper-com.aspose.imaging.xmp.XmpHeaderPi-com.aspose.imaging.xmp.XmpTrailerPi-com.aspose.imaging.xmp.XmpMeta-}
```
public XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)
```


Initializes a new instance of the `XmpPacketWrapper` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| header | [XmpHeaderPi](../../com.aspose.imaging.xmp/xmpheaderpi) | The XMP header of processing instruction. |
| trailer | [XmpTrailerPi](../../com.aspose.imaging.xmp/xmptrailerpi) | The XMP trailer of processing instruction. |
| xmpMeta | [XmpMeta](../../com.aspose.imaging.xmp/xmpmeta) | The XMP metadata. |

### getHeaderPi() {#getHeaderPi--}
```
public XmpHeaderPi getHeaderPi()
```


Gets the header processing instruction.

**Returns:**
[XmpHeaderPi](../../com.aspose.imaging.xmp/xmpheaderpi) - The Header processing instruction.
### getMeta() {#getMeta--}
```
public XmpMeta getMeta()
```


Gets the XMP meta. Optional.

**Returns:**
[XmpMeta](../../com.aspose.imaging.xmp/xmpmeta) - The XMP meta. Optional.
### getTrailerPi() {#getTrailerPi--}
```
public XmpTrailerPi getTrailerPi()
```


Gets the trailer processing instruction.

**Returns:**
[XmpTrailerPi](../../com.aspose.imaging.xmp/xmptrailerpi) - Trailer processing instruction.
### getPackages() {#getPackages--}
```
public final XmpPackage[] getPackages()
```


Gets array of `XmpPackage` inside XMP.

**Returns:**
com.aspose.imaging.xmp.XmpPackage[] - The array of `XmpPackage` inside XMP.
### getPackagesCount() {#getPackagesCount--}
```
public final int getPackagesCount()
```


Gets amount of packages inside XMP structure.

Value: The amount of packages inside XMP structure.

**Returns:**
int - amount of packages inside XMP structure.
### getBytes() {#getBytes--}
```
public final byte[] getBytes()
```


Gets the original Xmp bytes.

**Returns:**
byte[] - the copy of original Xmp bytes.
### addPackage(XmpPackage package_) {#addPackage-com.aspose.imaging.xmp.XmpPackage-}
```
public void addPackage(XmpPackage package_)
```


Adds the package.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.imaging.xmp/xmppackage) | The package. |

### getPackage(String namespaceUri) {#getPackage-java.lang.String-}
```
public XmpPackage getPackage(String namespaceUri)
```


Gets package by namespace URI.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| namespaceUri | java.lang.String | The package schema URI. |

**Returns:**
[XmpPackage](../../com.aspose.imaging.xmp/xmppackage) - Returns the XMP package for specified namespace URI.
### containsPackage(String namespaceUri) {#containsPackage-java.lang.String-}
```
public boolean containsPackage(String namespaceUri)
```


Determines whether a `namespaceUri` exists in the Xmp instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| namespaceUri | java.lang.String | The Xmp package schema uri. |

**Returns:**
boolean - Returns true if package with specified namespace Uri exist in XMP wrapper.
### removePackage(XmpPackage package_) {#removePackage-com.aspose.imaging.xmp.XmpPackage-}
```
public void removePackage(XmpPackage package_)
```


Removes the XMP package.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.imaging.xmp/xmppackage) | The package. |

### clearPackages() {#clearPackages--}
```
public void clearPackages()
```


Removes all `XmpPackage` inside XMP.

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Converts XMP value to the XML representation.

**Returns:**
java.lang.String - Returns converted XMP value to XML.
### toString() {#toString--}
```
public String toString()
```


Returns an XML string that represents the current object.

**Returns:**
java.lang.String - An XML string that represents the current object.
