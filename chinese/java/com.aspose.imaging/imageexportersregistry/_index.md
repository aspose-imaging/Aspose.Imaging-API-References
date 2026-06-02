---
title: "ImageExportersRegistry"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "表示图像导出器注册表。"
type: docs
weight: 59
url: /zh/java/com.aspose.imaging/imageexportersregistry/
---
**Inheritance:**
java.lang.Object
```
public final class ImageExportersRegistry
```

表示图像导出器注册表。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getRegisteredFormats()](#getRegisteredFormats--) | 获取已注册的导出格式。 |
| [getRegisteredExporterDescriptors()](#getRegisteredExporterDescriptors--) | 获取已注册的导出器描述符。 |
| [register(IImageExporterDescriptor exporterDescriptor)](#register-com.aspose.imaging.IImageExporterDescriptor-) | 注册指定的图像导出器描述符。 |
| [getFirstSupportedDescriptor(Image image, ImageOptionsBase options)](#getFirstSupportedDescriptor-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-) | 获取首次找到的适用于指定保存选项和图像的受支持描述符。 |
| [createFirstSupportedExporter(Image image, ImageOptionsBase options)](#createFirstSupportedExporter-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-) | 创建首次找到的适用于指定保存选项和图像的导出器。 |
| [registerExporter(IImageExporterDescriptor exporterDescriptor)](#registerExporter-com.aspose.imaging.IImageExporterDescriptor-) | 注册导出器。 |
| [unregisterExporter(IImageExporterDescriptor exporterDescriptor)](#unregisterExporter-com.aspose.imaging.IImageExporterDescriptor-) | 注销导出器。 |
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


获取已注册的导出格式。

值：已注册的导出格式。

**Returns:**
long
### getRegisteredExporterDescriptors() {#getRegisteredExporterDescriptors--}
```
public static IImageExporterDescriptor[] getRegisteredExporterDescriptors()
```


获取已注册的导出器描述符。

值：已注册的导出器描述符。

**Returns:**
com.aspose.imaging.IImageExporterDescriptor[]
### register(IImageExporterDescriptor exporterDescriptor) {#register-com.aspose.imaging.IImageExporterDescriptor-}
```
public static void register(IImageExporterDescriptor exporterDescriptor)
```


注册指定的图像导出器描述符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.imaging/iimageexporterdescriptor) | 图像导出器描述符。 |

### getFirstSupportedDescriptor(Image image, ImageOptionsBase options) {#getFirstSupportedDescriptor-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-}
```
public static IImageExporterDescriptor getFirstSupportedDescriptor(Image image, ImageOptionsBase options)
```


获取首次找到的适用于指定保存选项和图像的受支持描述符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | 要导出的图像。 |
|  | options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | 选项。 |

第一个导出器描述符实际上是最后注册的。 |

**Returns:**
[IImageExporterDescriptor](../../com.aspose.imaging/iimageexporterdescriptor) - The exporter descriptor which supports the specified image and save options or null if no such descriptor is found.
### createFirstSupportedExporter(Image image, ImageOptionsBase options) {#createFirstSupportedExporter-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-}
```
public static IImageExporter createFirstSupportedExporter(Image image, ImageOptionsBase options)
```


创建首次找到的适用于指定保存选项和图像的导出器。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | 要导出的图像。 |
|  | options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | 用于导出的保存选项。 |

第一个导出器实际上将是最后注册的。 |

**Returns:**
[IImageExporter](../../com.aspose.imaging/iimageexporter) - The exporter which supports the specified image and save options or null if no such exporter is found.
### registerExporter(IImageExporterDescriptor exporterDescriptor) {#registerExporter-com.aspose.imaging.IImageExporterDescriptor-}
```
public static void registerExporter(IImageExporterDescriptor exporterDescriptor)
```


注册导出器。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.imaging/iimageexporterdescriptor) | 要注册的导出器描述符。 |

### unregisterExporter(IImageExporterDescriptor exporterDescriptor) {#unregisterExporter-com.aspose.imaging.IImageExporterDescriptor-}
```
public static void unregisterExporter(IImageExporterDescriptor exporterDescriptor)
```


注销导出器。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.imaging/iimageexporterdescriptor) | 要注销的导出器描述符。 |

