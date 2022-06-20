---
title: GetFirstSupportedDescriptor
second_title: Справочник по Aspose.Imaging for .NET API
description: Получает первый найденный поддерживаемый дескриптор подходящий для указанных параметров сохранения и изображения.
type: docs
weight: 40
url: /ru/net/aspose.imaging/imageexportersregistry/getfirstsupporteddescriptor/
---
## ImageExportersRegistry.GetFirstSupportedDescriptor method

Получает первый найденный поддерживаемый дескриптор, подходящий для указанных параметров сохранения и изображения.

```csharp
public static IImageExporterDescriptor GetFirstSupportedDescriptor(Image image, 
    ImageOptionsBase options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | Image | Изображение для экспорта. |
| options | ImageOptionsBase | Опции. |

### Возвращаемое значение

Дескриптор экспортера, который поддерживает указанное изображение и параметры сохранения, или ноль, если такой дескриптор не найден.

### Примечания

Первый дескриптор экспортера будет фактически последним зарегистрированным.

### Смотрите также

* interface [IImageExporterDescriptor](../../iimageexporterdescriptor)
* class [Image](../../image)
* class [ImageOptionsBase](../../imageoptionsbase)
* class [ImageExportersRegistry](../../imageexportersregistry)
* пространство имен [Aspose.Imaging](../../imageexportersregistry)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->