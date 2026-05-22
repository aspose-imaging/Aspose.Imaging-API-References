---
title: "接口 IImageLoaderDescriptor"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.IImageLoaderDescriptor 接口。指定加载器属性的图像加载器描述符。使用加载器描述符可以避免将每个图像加载器实例保存在内存中以及多线程问题。"
type: docs
weight: 9710
url: /zh/net/aspose.imaging/iimageloaderdescriptor/
---
## IImageLoaderDescriptor interface

指定加载器属性的图像加载器描述符。使用加载器描述符可以避免在内存中保留每个图像加载器实例以及多线程问题。

```csharp
public interface IImageLoaderDescriptor : IImageDescriptor
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [CanLoad](../../aspose.imaging/iimageloaderdescriptor/canload/)(StreamContainer, LoadOptions) | 确定图像加载器是否可以从指定的流读取新图像，并可选地使用 *loadOptions*。 |
| [CreateInstance](../../aspose.imaging/iimageloaderdescriptor/createinstance/)() | 创建一个新的加载器实例。 |

### 另请参见

* interface [IImageDescriptor](../iimagedescriptor/)
* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


