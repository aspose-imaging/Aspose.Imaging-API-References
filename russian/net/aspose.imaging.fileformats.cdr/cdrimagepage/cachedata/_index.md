---
title: CacheData
second_title: Справочник по Aspose.Imaging for .NET API
description: Кэширует данные и гарантирует что дополнительная загрузка данных не будет выполняться из базовогоDataStreamContaineraspose.imaging/datastreamsupporter/datastreamcontainer.
type: docs
weight: 90
url: /ru/net/aspose.imaging.fileformats.cdr/cdrimagepage/cachedata/
---
## CdrImagePage.CacheData method

Кэширует данные и гарантирует, что дополнительная загрузка данных не будет выполняться из базового[`DataStreamContainer`](../../../aspose.imaging/datastreamsupporter/datastreamcontainer).

```csharp
public override void CacheData()
```

### Примеры

В следующем примере показано, как кэшировать все страницы образа CDR.

```csharp
[C#]

string dir = "c:\\temp\\";

 // Загрузить изображение из файла CDR.
using (Aspose.Imaging.FileFormats.Cdr.CdrImage image = (Aspose.Imaging.FileFormats.Cdr.CdrImage)Aspose.Imaging.Image.Load(dir + "sample.cdr"))
{
     // Этот вызов кэширует только страницу по умолчанию.
    image.CacheData();

     // Кэшируем все страницы, чтобы не выполнялась дополнительная загрузка данных из базового потока данных.
    foreach (Aspose.Imaging.FileFormats.Cdr.CdrImagePage page in image.Pages)
    {
        page.CacheData();
    }
}
```

### Смотрите также

* class [CdrImagePage](../../cdrimagepage)
* пространство имен [Aspose.Imaging.FileFormats.Cdr](../../cdrimagepage)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->