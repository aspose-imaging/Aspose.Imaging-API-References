---
title: "ImageExportersRegistry"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет реестр экспортеров изображений."
type: docs
weight: 59
url: /ru/java/com.aspose.imaging/imageexportersregistry/
---
**Inheritance:**
java.lang.Object
```
public final class ImageExportersRegistry
```

Представляет реестр экспортеров изображений.
## Методы

| Метод | Описание |
| --- | --- |
| [getRegisteredFormats()](#getRegisteredFormats--) | Получает зарегистрированные форматы экспорта. |
| [getRegisteredExporterDescriptors()](#getRegisteredExporterDescriptors--) | Получает зарегистрированные дескрипторы экспортёров. |
| [register(IImageExporterDescriptor exporterDescriptor)](#register-com.aspose.imaging.IImageExporterDescriptor-) | Регистрирует указанный дескриптор экспортёра изображений. |
| [getFirstSupportedDescriptor(Image image, ImageOptionsBase options)](#getFirstSupportedDescriptor-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-) | Получает первый найденный поддерживаемый дескриптор, подходящий для указанных параметров сохранения и изображения. |
| [createFirstSupportedExporter(Image image, ImageOptionsBase options)](#createFirstSupportedExporter-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-) | Создаёт первый найденный экспортер, подходящий для указанных параметров сохранения и изображения. |
| [registerExporter(IImageExporterDescriptor exporterDescriptor)](#registerExporter-com.aspose.imaging.IImageExporterDescriptor-) | Регистрирует экспортер. |
| [unregisterExporter(IImageExporterDescriptor exporterDescriptor)](#unregisterExporter-com.aspose.imaging.IImageExporterDescriptor-) | Отменяет регистрацию экспортера. |
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


Получает зарегистрированные форматы экспорта.

Значение: Зарегистрированные форматы экспорта.

**Returns:**
long
### getRegisteredExporterDescriptors() {#getRegisteredExporterDescriptors--}
```
public static IImageExporterDescriptor[] getRegisteredExporterDescriptors()
```


Получает зарегистрированные дескрипторы экспортёров.

Значение: Зарегистрированные дескрипторы экспортёров.

**Returns:**
com.aspose.imaging.IImageExporterDescriptor[]
### register(IImageExporterDescriptor exporterDescriptor) {#register-com.aspose.imaging.IImageExporterDescriptor-}
```
public static void register(IImageExporterDescriptor exporterDescriptor)
```


Регистрирует указанный дескриптор экспортёра изображений.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.imaging/iimageexporterdescriptor) | Дескриптор экспортёра изображений. |

### getFirstSupportedDescriptor(Image image, ImageOptionsBase options) {#getFirstSupportedDescriptor-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-}
```
public static IImageExporterDescriptor getFirstSupportedDescriptor(Image image, ImageOptionsBase options)
```


Получает первый найденный поддерживаемый дескриптор, подходящий для указанных параметров сохранения и изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Изображение для экспорта. |
|  | options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Параметры. |

Первый дескриптор экспортёра фактически будет последним зарегистрированным. |

**Returns:**
[IImageExporterDescriptor](../../com.aspose.imaging/iimageexporterdescriptor) - The exporter descriptor which supports the specified image and save options or null if no such descriptor is found.
### createFirstSupportedExporter(Image image, ImageOptionsBase options) {#createFirstSupportedExporter-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-}
```
public static IImageExporter createFirstSupportedExporter(Image image, ImageOptionsBase options)
```


Создаёт первый найденный экспортер, подходящий для указанных параметров сохранения и изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Изображение для экспорта. |
|  | options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Параметры сохранения, используемые для экспорта. |

Первый экспортер фактически будет последним зарегистрированным. |

**Returns:**
[IImageExporter](../../com.aspose.imaging/iimageexporter) - The exporter which supports the specified image and save options or null if no such exporter is found.
### registerExporter(IImageExporterDescriptor exporterDescriptor) {#registerExporter-com.aspose.imaging.IImageExporterDescriptor-}
```
public static void registerExporter(IImageExporterDescriptor exporterDescriptor)
```


Регистрирует экспортер.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.imaging/iimageexporterdescriptor) | Дескриптор экспортера для регистрации. |

### unregisterExporter(IImageExporterDescriptor exporterDescriptor) {#unregisterExporter-com.aspose.imaging.IImageExporterDescriptor-}
```
public static void unregisterExporter(IImageExporterDescriptor exporterDescriptor)
```


Отменяет регистрацию экспортера.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.imaging/iimageexporterdescriptor) | Дескриптор экспортера для отмены регистрации. |

