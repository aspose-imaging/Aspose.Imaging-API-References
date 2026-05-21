---
title: "ImageLoadersRegistry"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет реестр загрузчиков изображений."
type: docs
weight: 61
url: /ru/java/com.aspose.imaging/imageloadersregistry/
---
**Inheritance:**
java.lang.Object
```
public final class ImageLoadersRegistry
```

Представляет реестр загрузчиков изображений.
## Методы

| Метод | Описание |
| --- | --- |
| [getRegisteredFormats()](#getRegisteredFormats--) | Получает зарегистрированные форматы загрузки изображений. |
| [getRegisteredDescriptors()](#getRegisteredDescriptors--) | Получает зарегистрированные дескрипторы. |
| [register(IImageLoaderDescriptor imageLoaderDescriptor)](#register-com.aspose.imaging.IImageLoaderDescriptor-) | Регистрирует указанный дескриптор загрузчика изображений. |
| [getFirstSupportedDescriptorByTypeName(String descriptorTypeName)](#getFirstSupportedDescriptorByTypeName-java.lang.String-) | Получает первый поддерживаемый дескриптор по его имени типа. |
| [getFirstSupportedDescriptorByFileFormat(long fileFormat)](#getFirstSupportedDescriptorByFileFormat-long-) | Получает первый поддерживаемый формат файла по его имени типа. |
| [getFirstSupportedDescriptor(InputStream stream, LoadOptions loadOptions)](#getFirstSupportedDescriptor-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Получает первый найденный поддерживаемый дескриптор, подходящий для указанного `stream` и, при необходимости, `loadOptions`. |
| [createFirstSupportedLoader(InputStream stream, LoadOptions loadOptions)](#createFirstSupportedLoader-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Создает первый найденный загрузчик, подходящий для указанного `stream` и при необходимости `loadOptions`. |
| [registerLoader(IImageLoaderDescriptor loaderDescriptor)](#registerLoader-com.aspose.imaging.IImageLoaderDescriptor-) | Регистрирует загрузчик. |
| [unregisterLoader(IImageLoaderDescriptor loaderDescriptor)](#unregisterLoader-com.aspose.imaging.IImageLoaderDescriptor-) | Снимает регистрацию загрузчика. |
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


Получает зарегистрированные форматы загрузки изображений.

Значение: Зарегистрированные форматы загрузки изображений.

**Returns:**
long
### getRegisteredDescriptors() {#getRegisteredDescriptors--}
```
public static IImageLoaderDescriptor[] getRegisteredDescriptors()
```


Получает зарегистрированные дескрипторы.

Значение: Зарегистрированные дескрипторы.

**Returns:**
com.aspose.imaging.IImageLoaderDescriptor[]
### register(IImageLoaderDescriptor imageLoaderDescriptor) {#register-com.aspose.imaging.IImageLoaderDescriptor-}
```
public static synchronized void register(IImageLoaderDescriptor imageLoaderDescriptor)
```


Регистрирует указанный дескриптор загрузчика изображений.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| imageLoaderDescriptor | [IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) | Дескриптор загрузчика изображений. |

### getFirstSupportedDescriptorByTypeName(String descriptorTypeName) {#getFirstSupportedDescriptorByTypeName-java.lang.String-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptorByTypeName(String descriptorTypeName)
```


Получает первый поддерживаемый дескриптор по его имени типа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | descriptorTypeName | java.lang.String | Имя типа дескриптора. |

Первый дескриптор загрузчика будет фактически последним зарегистрированным. |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) - The first found loader descriptor or null if not such descriptor is found.
### getFirstSupportedDescriptorByFileFormat(long fileFormat) {#getFirstSupportedDescriptorByFileFormat-long-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptorByFileFormat(long fileFormat)
```


Получает первый поддерживаемый формат файла по его имени типа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fileFormat | long | Поддерживаемый файловый формат дескриптора. |

Первый дескриптор загрузчика будет фактически последним зарегистрированным. |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) - The first found loader descriptor or null if not such descriptor is found.
### getFirstSupportedDescriptor(InputStream stream, LoadOptions loadOptions) {#getFirstSupportedDescriptor-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptor(InputStream stream, LoadOptions loadOptions)
```


Получает первый найденный поддерживаемый дескриптор, подходящий для указанного `stream` и, при необходимости, `loadOptions`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток. |
|  | loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Параметры загрузки. |

Первый дескриптор загрузчика будет фактически последним зарегистрированным. |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) - The loader descriptor which supports the specified `stream` and `loadOptions` or null if no such descriptor is found.
### createFirstSupportedLoader(InputStream stream, LoadOptions loadOptions) {#createFirstSupportedLoader-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public static IImageLoader createFirstSupportedLoader(InputStream stream, LoadOptions loadOptions)
```


Создает первый найденный загрузчик, подходящий для указанного `stream` и при необходимости `loadOptions`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток. |
|  | loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Параметры загрузки. |

Первый загрузчик будет фактически последним зарегистрированным. |

**Returns:**
[IImageLoader](../../com.aspose.imaging/iimageloader) - The loader which supports the specified `stream` and `loadOptions` or null if no such loader is found.
### registerLoader(IImageLoaderDescriptor loaderDescriptor) {#registerLoader-com.aspose.imaging.IImageLoaderDescriptor-}
```
public static void registerLoader(IImageLoaderDescriptor loaderDescriptor)
```


Регистрирует загрузчик.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| loaderDescriptor | [IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) | Дескриптор загрузчика для регистрации. |

### unregisterLoader(IImageLoaderDescriptor loaderDescriptor) {#unregisterLoader-com.aspose.imaging.IImageLoaderDescriptor-}
```
public static synchronized void unregisterLoader(IImageLoaderDescriptor loaderDescriptor)
```


Снимает регистрацию загрузчика.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| loaderDescriptor | [IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) | Дескриптор загрузчика для снятия регистрации. |

