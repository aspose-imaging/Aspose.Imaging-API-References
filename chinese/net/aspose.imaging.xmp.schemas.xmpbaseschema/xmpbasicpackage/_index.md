---
title: "类 XmpBasicPackage"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.Xmp.Schemas.XmpBaseSchema.XmpBasicPackage 类。表示 XMP 基本命名空间"
type: docs
weight: 11980
url: /zh/net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---
## XmpBasicPackage class

表示 XMP 基本命名空间。

```csharp
public class XmpBasicPackage : XmpPackage
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [XmpBasicPackage](xmpbasicpackage/#constructor)() | 初始化 `XmpBasicPackage` 类的新实例。 |
| [XmpBasicPackage](xmpbasicpackage/#constructor_1)(string, string) | 初始化 `XmpBasicPackage` 类的新实例。 |

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
| virtual [AddValue](../../aspose.imaging.xmp/xmppackage/addvalue/)(string, object) | 将值添加到指定的键。 |
| override [AddValue](../../aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/addvalue/#addvalue_1)(string, string) | 添加字符串属性。 |
| virtual [Clear](../../aspose.imaging.xmp/xmppackage/clear/)() | 清除此实例。 |
| virtual [ContainsKey](../../aspose.imaging.xmp/xmppackage/containskey/)(string) | 确定此集合是否具有指定键。 |
| [GetEnumerator](../../aspose.imaging.xmp/xmppackage/getenumerator/)() | 返回一个遍历集合的枚举器。 |
| virtual [GetXmlValue](../../aspose.imaging.xmp/xmppackage/getxmlvalue/)() | 将 XMP 值转换为 XML 表示形式。 |
| virtual [Remove](../../aspose.imaging.xmp/xmppackage/remove/)(string) | 移除具有指定键的值。 |
| [SetCreatedDate](../../aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/setcreateddate/#setcreateddate)(DateTime) | 添加资源创建日期。 |
| [SetCreatedDate](../../aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/setcreateddate/#setcreateddate_1)(string) | 添加资源创建日期。 |
| [SetCreatorTool](../../aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/setcreatortool/)(string) | 设置创建工具。 |
| [SetIdentifier](../../aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/setidentifier/)(string[]) | 设置标识符。 |
| [SetLabel](../../aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/setlabel/)(string) | 设置标签。 |
| [SetMetadataDate](../../aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/setmetadatadate/#setmetadatadate)(DateTime) | 添加元数据最后更改日期。 |
| [SetMetadataDate](../../aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/setmetadatadate/#setmetadatadate_1)(string) | 添加元数据最后更改日期。 |
| [SetModifyDate](../../aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/setmodifydate/#setmodifydate)(DateTime) | 添加资源最后修改日期。 |
| [SetModifyDate](../../aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/setmodifydate/#setmodifydate_1)(string) | 添加资源最后修改日期。 |
| [SetRating](../../aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/setrating/)(int) | 设置评级。 |
| virtual [SetValue](../../aspose.imaging.xmp/xmppackage/setvalue/)(string, IXmlValue) | 设置值。 |
| virtual [SetValue](../../aspose.imaging.xmp/xmppackage/setvalue/)(string, IXmpType) | 设置值。 |
| virtual [SetXmpTypeValue](../../aspose.imaging.xmp/xmppackage/setxmptypevalue/)(string, XmpTypeBase) | 设置 XMP 类型值。 |
| [TryGetValue](../../aspose.imaging.xmp/xmppackage/trygetvalue/)(string, out object) | 通过 *key* 获取值。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [RatingMax](../../aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/ratingmax/) | 评级最大值。 |
| const [RatingMin](../../aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/ratingmin/) | 评级最小值。 |
| const [RatingRejected](../../aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/ratingrejected/) | 评级拒绝值。 |

### 另请参见

* class [XmpPackage](../../aspose.imaging.xmp/xmppackage/)
* namespace [Aspose.Imaging.Xmp.Schemas.XmpBaseSchema](../../aspose.imaging.xmp.schemas.xmpbaseschema/)
* assembly [Aspose.Imaging](../../)


