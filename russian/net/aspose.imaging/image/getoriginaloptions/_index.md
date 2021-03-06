---
title: GetOriginalOptions
second_title: Справочник по Aspose.Imaging for .NET API
description: Получает параметры на основе исходных настроек файла. Это может быть полезно для сохранения битовой глубины и других параметров исходного изображения без изменений. Например если мы загрузим черно-белое изображение PNG с 1 битом на пиксель а затем сохраним его с помощью Saveaspose.imaging/datastreamsupporter/saveбудет создано выходное изображение PNG с 8 битами на пиксель. Чтобы избежать этого и сохранить изображение PNG с 1 битом на пиксель используйте этот метод чтобы получить соответствующие параметры сохранения и передать их вSaveaspose.imaging/image/saveметод в качестве второго параметра.
type: docs
weight: 190
url: /ru/net/aspose.imaging/image/getoriginaloptions/
---
## Image.GetOriginalOptions method

Получает параметры на основе исходных настроек файла. Это может быть полезно для сохранения битовой глубины и других параметров исходного изображения без изменений. Например, если мы загрузим черно-белое изображение PNG с 1 битом на пиксель, а затем сохраним его с помощью [`Save`](../../datastreamsupporter/save)будет создано выходное изображение PNG с 8 битами на пиксель. Чтобы избежать этого и сохранить изображение PNG с 1 битом на пиксель, используйте этот метод, чтобы получить соответствующие параметры сохранения и передать их в[`Save`](../save)метод в качестве второго параметра.

```csharp
public virtual ImageOptionsBase GetOriginalOptions()
```

### Возвращаемое значение

Параметры основаны на исходных настройках файла.

### Смотрите также

* class [ImageOptionsBase](../../imageoptionsbase)
* class [Image](../../image)
* пространство имен [Aspose.Imaging](../../image)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
