---
title: XmpPacketWrapper
second_title: Aspose.Imaging for .NET API 参考
description: 包含序列化的 xmp 包包括头和尾
type: docs
weight: 11800
url: /zh/net/aspose.imaging.xmp/xmppacketwrapper/
---
## XmpPacketWrapper class

包含序列化的 xmp 包，包括头和尾。

```csharp
public class XmpPacketWrapper
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [XmpPacketWrapper](xmppacketwrapper#constructor)() | 初始化[`XmpPacketWrapper`](../xmppacketwrapper)类. |
| [XmpPacketWrapper](xmppacketwrapper#constructor_1)(XmpHeaderPi, XmpTrailerPi, XmpMeta) | 初始化[`XmpPacketWrapper`](../xmppacketwrapper)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [HeaderPi](../../aspose.imaging.xmp/xmppacketwrapper/headerpi) { get; } | 获取头部处理指令。 |
| [Meta](../../aspose.imaging.xmp/xmppacketwrapper/meta) { get; set; } | 获取 XMP 元数据。可选的. |
| [Packages](../../aspose.imaging.xmp/xmppacketwrapper/packages) { get; } | 获取数组[`XmpPackage`](../xmppackage)在 XMP. 里面 |
| [PackagesCount](../../aspose.imaging.xmp/xmppacketwrapper/packagescount) { get; } | 获取 XMP 结构中的包数量。 |
| [TrailerPi](../../aspose.imaging.xmp/xmppacketwrapper/trailerpi) { get; } | 获取预告片处理指令。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddPackage](../../aspose.imaging.xmp/xmppacketwrapper/addpackage)(XmpPackage) | 添加包。 |
| [ClearPackages](../../aspose.imaging.xmp/xmppacketwrapper/clearpackages)() | 删除所有[`XmpPackage`](../xmppackage)在 XMP. 里面 |
| [ContainsPackage](../../aspose.imaging.xmp/xmppacketwrapper/containspackage)(string) | 确定 xmp 包装器中是否存在包。 |
| [GetPackage](../../aspose.imaging.xmp/xmppacketwrapper/getpackage)(string) | 通过命名空间 URI 获取包。 |
| [RemovePackage](../../aspose.imaging.xmp/xmppacketwrapper/removepackage)(XmpPackage) | 删除 XMP 包。 |

### 评论

可以在 rdf:RDF 元素周围放置由一对 XML 处理指令 (PI) 组成的包装器。

### 也可以看看

* 命名空间 [Aspose.Imaging.Xmp](../../aspose.imaging.xmp)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
