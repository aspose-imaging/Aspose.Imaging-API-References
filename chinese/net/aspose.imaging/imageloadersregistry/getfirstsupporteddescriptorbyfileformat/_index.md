---
title: "ImageLoadersRegistry.GetFirstSupportedDescriptorByFileFormat"
second_title: "Aspose.Imaging for .NET API 参考"
description: "ImageLoadersRegistry 方法。根据其类型名称获取第一个受支持的文件格式"
type: docs
weight: 50
url: /zh/net/aspose.imaging/imageloadersregistry/getfirstsupporteddescriptorbyfileformat/
---
## ImageLoadersRegistry.GetFirstSupportedDescriptorByFileFormat method

通过其类型名称获取第一个受支持的文件格式。

```csharp
public static IImageLoaderDescriptor GetFirstSupportedDescriptorByFileFormat(FileFormat fileFormat)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileFormat | FileFormat | 受支持的描述符文件格式。 |

### 返回值

找到的第一个加载器描述符，若未找到则为 null。

## 备注

第一个加载器描述符实际上是最后注册的。

### 另请参见

* interface [IImageLoaderDescriptor](../../iimageloaderdescriptor/)
* enum [FileFormat](../../fileformat/)
* class [ImageLoadersRegistry](../)
* namespace [Aspose.Imaging](../../imageloadersregistry/)
* assembly [Aspose.Imaging](../../../)


