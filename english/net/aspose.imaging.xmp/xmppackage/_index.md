---
title: Class XmpPackage
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.Xmp.XmpPackage class. Represents base abstraction for XMP package
type: docs
weight: 12450
url: /net/aspose.imaging.xmp/xmppackage/
---
## XmpPackage class

Represents base abstraction for XMP package.

```csharp
public class XmpPackage : IEnumerable<KeyValuePair<string, XmpValue>>
```

## Properties

| Name | Description |
| --- | --- |
| [Count](../../aspose.imaging.xmp/xmppackage/count/) { get; } | Gets the XMP key count. |
| virtual [Item](../../aspose.imaging.xmp/xmppackage/item/) { get; set; } | Gets or sets the first XMP attribute or element value with by specified *key*. |
| virtual [Keys](../../aspose.imaging.xmp/xmppackage/keys/) { get; } | Gets the keys in XMP package. |
| [NamespaceUri](../../aspose.imaging.xmp/xmppackage/namespaceuri/) { get; } | Gets the namespace URI. |
| [Prefix](../../aspose.imaging.xmp/xmppackage/prefix/) { get; } | Gets the prefix. |
| [XmlNamespace](../../aspose.imaging.xmp/xmppackage/xmlnamespace/) { get; } | Gets the XML namespace. |

## Methods

| Name | Description |
| --- | --- |
| virtual [AddValue](../../aspose.imaging.xmp/xmppackage/addvalue/#addvalue)(string, object) | Adds the value to the specified key. |
| virtual [AddValue](../../aspose.imaging.xmp/xmppackage/addvalue/#addvalue_1)(string, string) | Adds the value to the specified key. |
| virtual [Clear](../../aspose.imaging.xmp/xmppackage/clear/)() | Clears this instance. |
| virtual [ContainsKey](../../aspose.imaging.xmp/xmppackage/containskey/)(string) | Determines whether this collection specified key. |
| [GetEnumerator](../../aspose.imaging.xmp/xmppackage/getenumerator/)() | Returns an enumerator that iterates through the collection. |
| virtual [Remove](../../aspose.imaging.xmp/xmppackage/remove/)(string) | Removes the first element or attribute value with the specified key. |
| virtual [SetValue](../../aspose.imaging.xmp/xmppackage/setvalue/#setvalue)(string, IXmlValue) | Sets the value. |
| virtual [SetValue](../../aspose.imaging.xmp/xmppackage/setvalue/#setvalue_1)(string, IXmpType) | Sets the value. |
| virtual [SetXmpTypeValue](../../aspose.imaging.xmp/xmppackage/setxmptypevalue/)(string, XmpTypeBase) | Sets the XMP type value. |
| [TryGetValue](../../aspose.imaging.xmp/xmppackage/trygetvalue/)(string, out XmpValue) | Gets the value by the *key*. |

### See Also

* struct [XmpValue](../../aspose.imaging.xmp.types/xmpvalue/)
* namespace [Aspose.Imaging.Xmp](../../aspose.imaging.xmp/)
* assembly [Aspose.Imaging](../../)


