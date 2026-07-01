---
title: "IImageLoaderDescriptor"
second_title: "Aspose.Imaging for Java API 参考"
description: "指定加载器属性的图像加载器描述符。"
type: docs
weight: 134
url: /zh/java/com.aspose.imaging/iimageloaderdescriptor/
---
**All Implemented Interfaces:**
[com.aspose.imaging.IImageDescriptor](../../com.aspose.imaging/iimagedescriptor)
```
public interface IImageLoaderDescriptor extends IImageDescriptor
```

图像加载器描述符，指定加载器属性。加载器描述符用于克服必须在内存中保留每个图像加载器实例以及多线程问题的需求。
## 方法

| 方法 | 描述 |
| --- | --- |
| [canLoad(StreamContainer streamContainer, LoadOptions loadOptions)](#canLoad-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | 确定图像加载器是否可以从指定的流读取新图像，并可选地使用 `loadOptions`。 |
| [createInstance()](#createInstance--) | 创建一个新的加载器实例。 |
### canLoad(StreamContainer streamContainer, LoadOptions loadOptions) {#canLoad-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-}
```
public abstract boolean canLoad(StreamContainer streamContainer, LoadOptions loadOptions)
```


确定图像加载器是否可以从指定的流读取新图像，并可选地使用 `loadOptions`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | 流容器。 |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | 由 `loadOptions` 指定的文件格式详细信息。`loadOptions` 可能为 null。 |

**Returns:**
布尔值 - 如果由此描述符创建的图像加载器可以从流读取图像，则为 `true`；否则为 `false`。
### createInstance() {#createInstance--}
```
public abstract IImageLoader createInstance()
```


创建一个新的加载器实例。

**Returns:**
[IImageLoader](../../com.aspose.imaging/iimageloader) - A new loader instance.
