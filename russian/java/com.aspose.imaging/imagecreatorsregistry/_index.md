---
title: "ImageCreatorsRegistry"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет реестр создателей изображений."
type: docs
weight: 58
url: /ru/java/com.aspose.imaging/imagecreatorsregistry/
---
**Inheritance:**
java.lang.Object
```
public final class ImageCreatorsRegistry
```

Представляет реестр создателей изображений.
## Методы

| Метод | Описание |
| --- | --- |
| [getRegisteredFormats()](#getRegisteredFormats--) | Получает зарегистрированные форматы создания изображений. |
| [getRegisteredDescriptors()](#getRegisteredDescriptors--) | Получает зарегистрированные дескрипторы. |
| [register(IImageCreatorDescriptor creatorDescriptor)](#register-com.aspose.imaging.IImageCreatorDescriptor-) | Регистрирует указанный дескриптор создателя изображений. |
| [getFirstSupportedDescriptor(ImageOptionsBase imageOptions)](#getFirstSupportedDescriptor-com.aspose.imaging.ImageOptionsBase-) | Получает первый найденный поддерживаемый дескриптор, подходящий для указанного. |
| [createFirstSupportedCreator(ImageOptionsBase imageOptions)](#createFirstSupportedCreator-com.aspose.imaging.ImageOptionsBase-) | Создаёт первый найденный создатель, подходящий для указанного. |
| [registerCreator(IImageCreatorDescriptor creatorDescriptor)](#registerCreator-com.aspose.imaging.IImageCreatorDescriptor-) | Регистрирует создателя. |
| [unregisterCreator(IImageCreatorDescriptor creatorDescriptor)](#unregisterCreator-com.aspose.imaging.IImageCreatorDescriptor-) | Отменяет регистрацию создателя. |
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


Получает зарегистрированные форматы создания изображений.

Значение: Зарегистрированные форматы создания изображений.

**Returns:**
long
### getRegisteredDescriptors() {#getRegisteredDescriptors--}
```
public static IImageCreatorDescriptor[] getRegisteredDescriptors()
```


Получает зарегистрированные дескрипторы.

Значение: Зарегистрированные дескрипторы.

**Returns:**
com.aspose.imaging.IImageCreatorDescriptor[]
### register(IImageCreatorDescriptor creatorDescriptor) {#register-com.aspose.imaging.IImageCreatorDescriptor-}
```
public static void register(IImageCreatorDescriptor creatorDescriptor)
```


Регистрирует указанный дескриптор создателя изображений.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| creatorDescriptor | [IImageCreatorDescriptor](../../com.aspose.imaging/iimagecreatordescriptor) | Дескриптор создателя изображений. |

### getFirstSupportedDescriptor(ImageOptionsBase imageOptions) {#getFirstSupportedDescriptor-com.aspose.imaging.ImageOptionsBase-}
```
public static IImageCreatorDescriptor getFirstSupportedDescriptor(ImageOptionsBase imageOptions)
```


Получает первый найденный поддерживаемый дескриптор, подходящий для указанного.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Параметры изображения. |

Первый дескриптор создателя будет фактически последним зарегистрированным. |

**Returns:**
[IImageCreatorDescriptor](../../com.aspose.imaging/iimagecreatordescriptor) - The creator descriptor which supports the specified or null if no such descriptor is found.
### createFirstSupportedCreator(ImageOptionsBase imageOptions) {#createFirstSupportedCreator-com.aspose.imaging.ImageOptionsBase-}
```
public static IImageCreator createFirstSupportedCreator(ImageOptionsBase imageOptions)
```


Создаёт первый найденный создатель, подходящий для указанного.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Параметры изображения. |

Первый создатель будет фактически последним зарегистрированным. |

**Returns:**
[IImageCreator](../../com.aspose.imaging/iimagecreator) - The creator which supports the specified or null if no such creator is found.
### registerCreator(IImageCreatorDescriptor creatorDescriptor) {#registerCreator-com.aspose.imaging.IImageCreatorDescriptor-}
```
public static void registerCreator(IImageCreatorDescriptor creatorDescriptor)
```


Регистрирует создателя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| creatorDescriptor | [IImageCreatorDescriptor](../../com.aspose.imaging/iimagecreatordescriptor) | Дескриптор создателя для регистрации. |

### unregisterCreator(IImageCreatorDescriptor creatorDescriptor) {#unregisterCreator-com.aspose.imaging.IImageCreatorDescriptor-}
```
public static void unregisterCreator(IImageCreatorDescriptor creatorDescriptor)
```


Отменяет регистрацию создателя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| creatorDescriptor | [IImageCreatorDescriptor](../../com.aspose.imaging/iimagecreatordescriptor) | Дескриптор создателя. |

