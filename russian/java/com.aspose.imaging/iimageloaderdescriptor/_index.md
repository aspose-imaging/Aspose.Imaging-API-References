---
title: "IImageLoaderDescriptor"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Дескриптор загрузчика изображения, указывающий свойства загрузчика."
type: docs
weight: 134
url: /ru/java/com.aspose.imaging/iimageloaderdescriptor/
---
**All Implemented Interfaces:**
[com.aspose.imaging.IImageDescriptor](../../com.aspose.imaging/iimagedescriptor)
```
public interface IImageLoaderDescriptor extends IImageDescriptor
```

Дескриптор загрузчика изображений, указывающий свойства загрузчика. Дескриптор загрузчика используется для устранения необходимости держать каждый экземпляр загрузчика изображений в памяти и проблем многопоточности.
## Методы

| Метод | Описание |
| --- | --- |
| [canLoad(StreamContainer streamContainer, LoadOptions loadOptions)](#canLoad-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | Определяет, может ли загрузчик изображений прочитать новое изображение из указанного потока, при необходимости используя `loadOptions`. |
| [createInstance()](#createInstance--) | Создаёт новый экземпляр загрузчика. |
### canLoad(StreamContainer streamContainer, LoadOptions loadOptions) {#canLoad-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-}
```
public abstract boolean canLoad(StreamContainer streamContainer, LoadOptions loadOptions)
```


Определяет, может ли загрузчик изображений прочитать новое изображение из указанного потока, при необходимости используя `loadOptions`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Контейнер потока. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Подробности формата файла, указанные в `loadOptions`. `loadOptions` может быть null. |

**Returns:**
логический - `true`, если загрузчик изображений, созданный этим дескриптором, может читать изображение из потока; иначе `false`.
### createInstance() {#createInstance--}
```
public abstract IImageLoader createInstance()
```


Создаёт новый экземпляр загрузчика.

**Returns:**
[IImageLoader](../../com.aspose.imaging/iimageloader) - A new loader instance.
