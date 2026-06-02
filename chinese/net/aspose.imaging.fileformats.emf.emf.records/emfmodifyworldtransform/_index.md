---
title: "类 EmfModifyWorldTransform"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfModifyWorldTransform 类。EMR_MODIFYWORLDTRANSFORM 记录在回放设备上下文中修改当前的世界空间到页面空间的变换。"
type: docs
weight: 3940
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/
---
## EmfModifyWorldTransform class

EMR_MODIFYWORLDTRANSFORM 记录修改回放设备上下文中当前的世界空间到页面空间的变换。

```csharp
public sealed class EmfModifyWorldTransform : EmfTransformRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfModifyWorldTransform](emfmodifyworldtransform/#constructor)() | 初始化 `EmfModifyWorldTransform` 类的新实例。 |
| [EmfModifyWorldTransform](emfmodifyworldtransform/#constructor_1)(EmfRecord) | 初始化 `EmfModifyWorldTransform` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ModifyWorldTransformMode](../../aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/modifyworldtransformmode/) { get; set; } | 获取或设置一个 32 位无符号整数，指定 Xform 中指定的变换的使用方式。该值必须属于 ModifyWorldTransformMode 枚举（第 2.1.24 节）。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |
| [Xform](../../aspose.imaging.fileformats.emf.emf.records/emftransformrecordtype/xform/) { get; set; } | 获取或设置一个 XForm 对象（第 2.2.28 节），该对象定义世界空间到页面空间的变换。 |

## 备注

有关变换和坐标空间的更多信息，请参阅 [MSDN-WRLDPGSPC]。有关其他变换记录类型的规范，请参见第 2.3.12 节。

### 另请参见

* class [EmfTransformRecordType](../emftransformrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


