---
title: "类 XmpPacketWrapper"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.Xmp.XmpPacketWrapper 类。包含标头和尾部的序列化 xmp 包"
type: docs
weight: 12450
url: /zh/net/aspose.imaging.xmp/xmppacketwrapper/
---
## XmpPacketWrapper class

包含已序列化的 xmp 包，包括标头和尾部。

```csharp
public class XmpPacketWrapper : IImageMetadataFormat, IXmlValue
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [XmpPacketWrapper](xmppacketwrapper/#constructor)() | 初始化 `XmpPacketWrapper` 类的新实例。 |
| [XmpPacketWrapper](xmppacketwrapper/#constructor_1)(XmpHeaderPi, XmpTrailerPi, XmpMeta) | 初始化 `XmpPacketWrapper` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [HeaderPi](../../aspose.imaging.xmp/xmppacketwrapper/headerpi/) { get; } | 获取标头处理指令。 |
| [Meta](../../aspose.imaging.xmp/xmppacketwrapper/meta/) { get; set; } | 获取 XMP 元数据。可选。 |
| [Packages](../../aspose.imaging.xmp/xmppacketwrapper/packages/) { get; } | 获取 XMP 中的 [`XmpPackage`](../xmppackage/) 数组。 |
| [PackagesCount](../../aspose.imaging.xmp/xmppacketwrapper/packagescount/) { get; } | 获取 XMP 结构中包的数量。 |
| [TrailerPi](../../aspose.imaging.xmp/xmppacketwrapper/trailerpi/) { get; } | 获取尾部处理指令。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddPackage](../../aspose.imaging.xmp/xmppacketwrapper/addpackage/)(XmpPackage) | 添加包。 |
| [ClearPackages](../../aspose.imaging.xmp/xmppacketwrapper/clearpackages/)() | 移除 XMP 中的所有 [`XmpPackage`](../xmppackage/)。 |
| [ContainsPackage](../../aspose.imaging.xmp/xmppacketwrapper/containspackage/)(string) | 确定包是否存在于 xmp 包装器中。 |
| [GetPackage](../../aspose.imaging.xmp/xmppacketwrapper/getpackage/)(string) | 按命名空间 URI 获取包。 |
| [GetXmlValue](../../aspose.imaging.xmp/xmppacketwrapper/getxmlvalue/)() | 将 XMP 值转换为 XML 表示形式。 |
| [RemovePackage](../../aspose.imaging.xmp/xmppacketwrapper/removepackage/)(XmpPackage) | 移除 XMP 包。 |
| override [ToString](../../aspose.imaging.xmp/xmppacketwrapper/tostring/)() | 返回表示当前对象的 XML 字符串。 |

## 备注

可以在 rdf:RDF 元素周围放置由一对 XML 处理指令 (PIs) 组成的包装器。

### 另请参见

* interface [IImageMetadataFormat](../../aspose.imaging.metadata/iimagemetadataformat/)
* interface [IXmlValue](../ixmlvalue/)
* namespace [Aspose.Imaging.Xmp](../../aspose.imaging.xmp/)
* assembly [Aspose.Imaging](../../)


