---
title: FirstPage
second_title: Справочник по Aspose.Imaging for .NET API
description: Получает первую страницу документа
type: docs
weight: 60
url: /ru/net/aspose.imaging.fileformats.djvu/djvuimage/firstpage/
---
## DjvuImage.FirstPage property

Получает первую страницу документа

```csharp
public DjvuPage FirstPage { get; }
```

### Стоимость имущества

Первая страница.

### Исключения

| исключение | условие |
| --- | --- |
| [DjvuImageException](../../../aspose.imaging.coreexceptions.imageformats/djvuimageexception) | Не могу найти первую страницу |

### Примеры

В этом примере показано, как загрузить изображение DJVU из файлового потока и распечатать информацию о страницах.

```csharp
[C#]

string dir = "c:\\temp\\";

// Загружаем изображение DJVU из файлового потока.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.djvu"))
{
    using (Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = new Aspose.Imaging.FileFormats.Djvu.DjvuImage(stream))
    {
        System.Console.WriteLine("The total number of pages: {0}", djvuImage.Pages.Length);
        System.Console.WriteLine("The active page number:    {0}", djvuImage.ActivePage.PageNumber);
        System.Console.WriteLine("The first page number:     {0}", djvuImage.FirstPage.PageNumber);
        System.Console.WriteLine("The last page number:      {0}", djvuImage.LastPage.PageNumber);

        foreach (Aspose.Imaging.FileFormats.Djvu.DjvuPage djvuPage in djvuImage.Pages)
        {
            System.Console.WriteLine("--------------------------------------------------");
            System.Console.WriteLine("Page number:     {0}", djvuPage.PageNumber);
            System.Console.WriteLine("Page size:       {0}", djvuPage.Size);
            System.Console.WriteLine("Page raw format: {0}", djvuPage.RawDataFormat);
        }
    }
}

//Вывод может выглядеть так:
//Общее количество страниц: 2
//Номер активной страницы: 1
// Номер первой страницы: 1
// Номер последней страницы: 2
//------------------------------------------------ --
// Номер страницы: 1
//Размер страницы: {Ширина = 2481, Высота = 3508}
//Необработанный формат страницы: RgbIndexed1Bpp, используемые каналы: 1
//------------------------------------------------ --
// Номер страницы: 2
//Размер страницы: {Ширина = 2481, Высота = 3508}
//Необработанный формат страницы: RgbIndexed1Bpp, используемые каналы: 1
```

### Смотрите также

* class [DjvuPage](../../djvupage)
* class [DjvuImage](../../djvuimage)
* пространство имен [Aspose.Imaging.FileFormats.Djvu](../../djvuimage)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
