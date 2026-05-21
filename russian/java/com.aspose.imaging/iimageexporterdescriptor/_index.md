---
title: "IImageExporterDescriptor"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет дескриптор экспортера изображения."
type: docs
weight: 132
url: /ru/java/com.aspose.imaging/iimageexporterdescriptor/
---
**All Implemented Interfaces:**
[com.aspose.imaging.IImageDescriptor](../../com.aspose.imaging/iimagedescriptor)
```
public interface IImageExporterDescriptor extends IImageDescriptor
```

Представляет дескриптор экспортера изображений. Дескриптор экспортера используется для устранения необходимости хранить каждый экземпляр экспортера в памяти и проблем многопоточности.
## Методы

| Метод | Описание |
| --- | --- |
| [canExport(Image image, ImageOptionsBase optionsBase)](#canExport-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-) | Определяет, может ли экспортер изображений экспортировать указанное изображение в указанный формат изображения, заданный параметрами сохранения. |
| [createInstance()](#createInstance--) | Создаёт новый экземпляр экспортера. |
### canExport(Image image, ImageOptionsBase optionsBase) {#canExport-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-}
```
public abstract boolean canExport(Image image, ImageOptionsBase optionsBase)
```


Определяет, может ли экспортер изображений экспортировать указанное изображение в указанный формат изображения, заданный параметрами сохранения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Изображение для экспорта. |
| optionsBase | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | База параметров. |

**Returns:**
boolean — `true`, если экспортер, созданный этим дескриптором, может экспортировать указанное изображение в указанный файловый формат; иначе `false`.
### createInstance() {#createInstance--}
```
public abstract IImageExporter createInstance()
```


Создаёт новый экземпляр экспортера.

**Returns:**
[IImageExporter](../../com.aspose.imaging/iimageexporter) - A new exporter instance.
