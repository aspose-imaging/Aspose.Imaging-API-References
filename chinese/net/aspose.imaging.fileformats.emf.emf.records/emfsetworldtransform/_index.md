---
title: "类 EmfSetWorldTransform"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSetWorldTransform 类。EMR_SETWORLDTRANSFORM 记录指定在回放设备上下文中将当前世界空间转换为页面空间的变换。"
type: docs
weight: 4680
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfsetworldtransform/
---
## EmfSetWorldTransform class

EMR_SETWORLDTRANSFORM 记录指定回放设备上下文中当前世界空间到页面空间的变换。

```csharp
public sealed class EmfSetWorldTransform : EmfTransformRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfSetWorldTransform](emfsetworldtransform/#constructor)() | 初始化 `EmfSetWorldTransform` 类的新实例。 |
| [EmfSetWorldTransform](emfsetworldtransform/#constructor_1)(EmfRecord) | 初始化 `EmfSetWorldTransform` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |
| [Xform](../../aspose.imaging.fileformats.emf.emf.records/emftransformrecordtype/xform/) { get; set; } | 获取或设置一个 XForm 对象（第 2.2.28 节），该对象定义世界空间到页面空间的变换。 |

## 备注

有关变换和坐标空间的更多信息，请参阅 [MSDN-WRLDPGSPC]。有关其他变换记录类型的规范，请参见第 2.3.12 节。

### 另请参见

* class [EmfTransformRecordType](../emftransformrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


