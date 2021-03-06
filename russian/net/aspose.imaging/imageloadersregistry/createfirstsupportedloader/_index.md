---
title: CreateFirstSupportedLoader
second_title: Справочник по Aspose.Imaging for .NET API
description: Создает первый найденный загрузчик подходящий для указанногоstreamи опциональноloadOptions.
type: docs
weight: 30
url: /ru/net/aspose.imaging/imageloadersregistry/createfirstsupportedloader/
---
## ImageLoadersRegistry.CreateFirstSupportedLoader method

Создает первый найденный загрузчик, подходящий для указанного*stream*и опционально*loadOptions*.

```csharp
public static IImageLoader CreateFirstSupportedLoader(Stream stream, LoadOptions loadOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток. |
| loadOptions | LoadOptions | Параметры загрузки. |

### Возвращаемое значение

Загрузчик, который поддерживает указанные*stream*и*loadOptions*или null если такой загрузчик не найден.

### Примечания

Первый загрузчик будет фактически последним зарегистрированным.

### Смотрите также

* interface [IImageLoader](../../iimageloader)
* class [LoadOptions](../../loadoptions)
* class [ImageLoadersRegistry](../../imageloadersregistry)
* пространство имен [Aspose.Imaging](../../imageloadersregistry)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
