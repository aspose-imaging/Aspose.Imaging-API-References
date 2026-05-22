---
title: "接口 IImageExporterDescriptor"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.IImageExporterDescriptor 接口。表示图像导出器描述符。使用导出器描述符可克服在内存中保留每个导出器实例以及多线程问题的必要性"
type: docs
weight: 9690
url: /zh/net/aspose.imaging/iimageexporterdescriptor/
---
## IImageExporterDescriptor interface

表示图像导出器描述符。使用导出器描述符可以避免在内存中保留每个导出器实例以及多线程问题。

```csharp
public interface IImageExporterDescriptor : IImageDescriptor
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [CanExport](../../aspose.imaging/iimageexporterdescriptor/canexport/)(Image, ImageOptionsBase) | 确定图像导出器是否可以将指定的图像导出为保存选项中指定的图像格式。 |
| [CreateInstance](../../aspose.imaging/iimageexporterdescriptor/createinstance/)() | 创建一个新的导出器实例。 |

### 另请参见

* interface [IImageDescriptor](../iimagedescriptor/)
* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


