---
title: RawDataFormat
second_title: Справочник по Aspose.Imaging for .NET API
description: Получает формат необработанных данных.
type: docs
weight: 80
url: /ru/net/aspose.imaging/rasterimage/rawdataformat/
---
## RasterImage.RawDataFormat property

Получает формат необработанных данных.

```csharp
public virtual PixelDataFormat RawDataFormat { get; }
```

### Стоимость имущества

Формат необработанных данных.

### Примеры

В следующем примере загружаются растровые изображения и печатается информация о формате необработанных данных и альфа-канале.

```csharp
[C#]

// Файлы изображений для загрузки.
string[] fileNames = new string[]
{
    @"c:\temp\sample.bmp",
    @"c:\temp\alpha.png",
};

foreach (string fileName in fileNames)
{
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(fileName))
    {
        Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;
        System.Console.WriteLine("ImageFile={0}, FileFormat={1}, HasAlpha={2}", fileName, rasterImage.RawDataFormat, rasterImage.HasAlpha);
    }
}

// Вывод может выглядеть так:
// ImageFile=c:\temp\sample.bmp, FileFormat=Rgb24Bpp, используемые каналы: 8,8,8, HasAlpha=False
// ImageFile=c:\temp\alpha.png, FileFormat=RGBA32Bpp, используемые каналы: 8,8,8,8, HasAlpha=True
```

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

* class [PixelDataFormat](../../pixeldataformat)
* class [RasterImage](../../rasterimage)
* пространство имен [Aspose.Imaging](../../rasterimage)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
