---
title: Class XmpPacketWrapper
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.Xmp.XmpPacketWrapper class. Contains serialized xmp package including header and trailer
type: docs
weight: 12440
url: /net/aspose.imaging.xmp/xmppacketwrapper/
---
## XmpPacketWrapper class

Contains serialized xmp package including header and trailer.

```csharp
public class XmpPacketWrapper : IImageMetadataFormat, IXmlValue
```

## Constructors

| Name | Description |
| --- | --- |
| [XmpPacketWrapper](xmppacketwrapper/#constructor)() | Initializes a new instance of the `XmpPacketWrapper` class. |
| [XmpPacketWrapper](xmppacketwrapper/#constructor_1)(XmpHeaderPi, XmpTrailerPi, XmpMeta) | Initializes a new instance of the `XmpPacketWrapper` class. |

## Properties

| Name | Description |
| --- | --- |
| [HeaderPi](../../aspose.imaging.xmp/xmppacketwrapper/headerpi/) { get; } | Gets the header processing instruction. |
| [Meta](../../aspose.imaging.xmp/xmppacketwrapper/meta/) { get; set; } | Gets the XMP meta. Optional. |
| [Packages](../../aspose.imaging.xmp/xmppacketwrapper/packages/) { get; } | Gets array of [`XmpPackage`](../xmppackage/) inside XMP. |
| [PackagesCount](../../aspose.imaging.xmp/xmppacketwrapper/packagescount/) { get; } | Gets amount of packages inside XMP structure. |
| [TrailerPi](../../aspose.imaging.xmp/xmppacketwrapper/trailerpi/) { get; } | Gets the trailer processing instruction. |

## Methods

| Name | Description |
| --- | --- |
| [AddPackage](../../aspose.imaging.xmp/xmppacketwrapper/addpackage/)(XmpPackage) | Adds the package. |
| [ClearPackages](../../aspose.imaging.xmp/xmppacketwrapper/clearpackages/)() | Removes all [`XmpPackage`](../xmppackage/) inside XMP. |
| [ContainsPackage](../../aspose.imaging.xmp/xmppacketwrapper/containspackage/)(string) | Determines whethere package is exist in xmp wrapper. |
| [GetPackage](../../aspose.imaging.xmp/xmppacketwrapper/getpackage/)(string) | Gets package by namespace URI. |
| [GetXmlValue](../../aspose.imaging.xmp/xmppacketwrapper/getxmlvalue/)() | Converts XMP value to the XML representation. |
| [RemovePackage](../../aspose.imaging.xmp/xmppacketwrapper/removepackage/)(XmpPackage) | Removes the XMP package. |
| override [ToString](../../aspose.imaging.xmp/xmppacketwrapper/tostring/)() | Returns an XML string that represents the current object. |

## Remarks

A wrapper consisting of a pair of XML processing instructions (PIs) may be placed around the rdf:RDF element.

### See Also

* interface [IImageMetadataFormat](../../aspose.imaging.metadata/iimagemetadataformat/)
* interface [IXmlValue](../ixmlvalue/)
* namespace [Aspose.Imaging.Xmp](../../aspose.imaging.xmp/)
* assembly [Aspose.Imaging](../../)


