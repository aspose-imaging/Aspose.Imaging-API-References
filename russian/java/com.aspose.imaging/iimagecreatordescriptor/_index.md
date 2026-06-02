---
title: "IImageCreatorDescriptor"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Дескриптор создателя изображения, указывающий свойства создателя."
type: docs
weight: 129
url: /ru/java/com.aspose.imaging/iimagecreatordescriptor/
---
**All Implemented Interfaces:**
[com.aspose.imaging.IImageDescriptor](../../com.aspose.imaging/iimagedescriptor)
```
public interface IImageCreatorDescriptor extends IImageDescriptor
```

Дескриптор создателя изображения, указывающий свойства создателя. Дескриптор создателя используется для преодоления необходимости содержать каждый экземпляр создателя изображения в памяти и проблем многопоточности.
## Методы

| Метод | Описание |
| --- | --- |
| [canCreate(ImageOptionsBase imageOptions)](#canCreate-com.aspose.imaging.ImageOptionsBase-) | Определяет, может ли создатель изображения создать новое изображение, используя `imageOptions`. |
| [createInstance()](#createInstance--) | Создаёт новый экземпляр создателя. |
### canCreate(ImageOptionsBase imageOptions) {#canCreate-com.aspose.imaging.ImageOptionsBase-}
```
public abstract boolean canCreate(ImageOptionsBase imageOptions)
```


Определяет, может ли создатель изображения создать новое изображение, используя `imageOptions`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Параметры изображения. |

**Returns:**
boolean — `true`, если создатель изображения, созданный этим дескриптором, может создавать данные изображения, используя указанные `imageOptions`; в противном случае — `false`.
### createInstance() {#createInstance--}
```
public abstract IImageCreator createInstance()
```


Создаёт новый экземпляр создателя.

**Returns:**
[IImageCreator](../../com.aspose.imaging/iimagecreator) - A new creator instance.
