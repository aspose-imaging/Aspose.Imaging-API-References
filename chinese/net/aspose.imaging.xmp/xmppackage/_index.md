---
title: "类 XmpPackage"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.Xmp.XmpPackage 类。表示 XMP 包的基础抽象"
type: docs
weight: 12430
url: /zh/net/aspose.imaging.xmp/xmppackage/
---
## XmpPackage class

表示 XMP 包的基础抽象。

```csharp
public class XmpPackage : IEnumerable<KeyValuePair<string, object>>, IXmlValue
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Count](../../aspose.imaging.xmp/xmppackage/count/) { get; } | 获取 XMP 键的计数。 |
| virtual [Item](../../aspose.imaging.xmp/xmppackage/item/) { get; set; } | 获取或设置具有指定键的对象。 |
| virtual [Keys](../../aspose.imaging.xmp/xmppackage/keys/) { get; } | 获取 XMP 包中的键。 |
| [NamespaceUri](../../aspose.imaging.xmp/xmppackage/namespaceuri/) { get; } | 获取命名空间 URI。 |
| [Prefix](../../aspose.imaging.xmp/xmppackage/prefix/) { get; } | 获取前缀。 |
| [XmlNamespace](../../aspose.imaging.xmp/xmppackage/xmlnamespace/) { get; } | 获取 XML 命名空间。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [AddValue](../../aspose.imaging.xmp/xmppackage/addvalue/#addvalue)(string, object) | 将值添加到指定的键。 |
| virtual [AddValue](../../aspose.imaging.xmp/xmppackage/addvalue/#addvalue_1)(string, string) | 将值添加到指定的键。 |
| virtual [Clear](../../aspose.imaging.xmp/xmppackage/clear/)() | 清除此实例。 |
| virtual [ContainsKey](../../aspose.imaging.xmp/xmppackage/containskey/)(string) | 确定此集合是否具有指定键。 |
| [GetEnumerator](../../aspose.imaging.xmp/xmppackage/getenumerator/)() | 返回一个遍历集合的枚举器。 |
| virtual [GetXmlValue](../../aspose.imaging.xmp/xmppackage/getxmlvalue/)() | 将 XMP 值转换为 XML 表示形式。 |
| virtual [Remove](../../aspose.imaging.xmp/xmppackage/remove/)(string) | 移除具有指定键的值。 |
| virtual [SetValue](../../aspose.imaging.xmp/xmppackage/setvalue/#setvalue)(string, IXmlValue) | 设置值。 |
| virtual [SetValue](../../aspose.imaging.xmp/xmppackage/setvalue/#setvalue_1)(string, IXmpType) | 设置值。 |
| virtual [SetXmpTypeValue](../../aspose.imaging.xmp/xmppackage/setxmptypevalue/)(string, XmpTypeBase) | 设置 XMP 类型值。 |
| [TryGetValue](../../aspose.imaging.xmp/xmppackage/trygetvalue/)(string, out object) | 通过 *key* 获取值。 |

### 另请参见

* interface [IXmlValue](../ixmlvalue/)
* namespace [Aspose.Imaging.Xmp](../../aspose.imaging.xmp/)
* assembly [Aspose.Imaging](../../)


