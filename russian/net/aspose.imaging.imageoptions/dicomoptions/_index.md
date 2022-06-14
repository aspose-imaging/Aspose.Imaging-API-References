---
title: DicomOptions
second_title: Справочник по Aspose.Imaging for .NET API
description: Параметры создания файла формата DICOM.
type: docs
weight: 9940
url: /ru/net/aspose.imaging.imageoptions/dicomoptions/
---
## DicomOptions class

Параметры создания файла формата DICOM.

```csharp
public class DicomOptions : ImageOptionsBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [DicomOptions](dicomoptions)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Получает или устанавливает подсказку о размере буфера, которая определяет максимально допустимый размер для всех внутренних буферов. |
| [ColorType](../../aspose.imaging.imageoptions/dicomoptions/colortype) { get; set; } | Получает или задает тип цвета. |
| [Compression](../../aspose.imaging.imageoptions/dicomoptions/compression) { get; set; } | Получает или задает сжатие. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Получает или задает значение, указывающее, является ли [полный кадр]. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Многостраничные параметры |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Получает или задает цветовую палитру. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Получает или задает обработчик события выполнения. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Получает или задает параметры разрешения. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Получает или задает источник для создания изображения. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Получает или задает параметры векторной растеризации. |
| override [XmpData](../../aspose.imaging.imageoptions/dicomoptions/xmpdata) { get; set; } | Получает или задает данные Xmp. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Клонирует этот экземпляр. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Удаляет текущий экземпляр. |

### Примеры

Изменение типа цвета при сжатии DICOM.

```csharp
[C#]

using (DicomImage image = (DicomImage)Image.Create(
        new DicomOptions() { Source = new StreamSource(new MemoryStream()) },
        100,
        100))
{
     // Нарисуйте что-нибудь, используя векторную графику
    Graphics graphics = new Graphics(image);
    graphics.FillRectangle(new SolidBrush(Color.BlueViolet), image.Bounds);
    graphics.FillRectangle(new SolidBrush(Color.Aqua), 10, 20, 50, 20);
    graphics.FillEllipse(new SolidBrush(Color.Orange), 30, 50, 70, 30);

    // Сохраняем пиксели нарисованного изображения. Теперь они на первой странице изображения Dicom.
    int[] pixels = image.LoadArgb32Pixels(image.Bounds);

     // Добавляем несколько страниц после, делая их темнее
    for (int i = 1; i < 5; i++)
    {
        DicomPage page = image.AddPage();
        page.SaveArgb32Pixels(page.Bounds, pixels);
        page.AdjustBrightness(i * 30);
    }

     // Добавляем несколько страниц перед главной, делая их ярче
    for (int i = 1; i < 5; i++)
    {
        DicomPage page = image.InsertPage(0);
        page.SaveArgb32Pixels(page.Bounds, pixels);
        page.AdjustBrightness(-i * 30);
    }

     // Сохраняем созданное многостраничное изображение в выходной файл file
    image.Save("MultiPage.dcm");
}
```

Использовать сжатие RLE в изображении DICOM.

```csharp
[C#]

using (DicomImage image = (DicomImage)Image.Create(
        new DicomOptions() { Source = new StreamSource(new MemoryStream()) },
        100,
        100))
{
     // Нарисуйте что-нибудь, используя векторную графику
    Graphics graphics = new Graphics(image);
    graphics.FillRectangle(new SolidBrush(Color.BlueViolet), image.Bounds);
    graphics.FillRectangle(new SolidBrush(Color.Aqua), 10, 20, 50, 20);
    graphics.FillEllipse(new SolidBrush(Color.Orange), 30, 50, 70, 30);

    // Сохраняем пиксели нарисованного изображения. Теперь они на первой странице изображения Dicom.
    int[] pixels = image.LoadArgb32Pixels(image.Bounds);

     // Добавляем несколько страниц после, делая их темнее
    for (int i = 1; i < 5; i++)
    {
        DicomPage page = image.AddPage();
        page.SaveArgb32Pixels(page.Bounds, pixels);
        page.AdjustBrightness(i * 30);
    }

     // Добавляем несколько страниц перед главной, делая их ярче
    for (int i = 1; i < 5; i++)
    {
        DicomPage page = image.InsertPage(0);
        page.SaveArgb32Pixels(page.Bounds, pixels);
        page.AdjustBrightness(-i * 30);
    }

     // Сохраняем созданное многостраничное изображение в выходной файл file
    image.Save("MultiPage.dcm");
}
```

Использовать сжатие JPEG 2000 в изображении DICOM.

```csharp
[C#]

using (DicomImage image = (DicomImage)Image.Create(
        new DicomOptions() { Source = new StreamSource(new MemoryStream()) },
        100,
        100))
{
     // Нарисуйте что-нибудь, используя векторную графику
    Graphics graphics = new Graphics(image);
    graphics.FillRectangle(new SolidBrush(Color.BlueViolet), image.Bounds);
    graphics.FillRectangle(new SolidBrush(Color.Aqua), 10, 20, 50, 20);
    graphics.FillEllipse(new SolidBrush(Color.Orange), 30, 50, 70, 30);

    // Сохраняем пиксели нарисованного изображения. Теперь они на первой странице изображения Dicom.
    int[] pixels = image.LoadArgb32Pixels(image.Bounds);

     // Добавляем несколько страниц после, делая их темнее
    for (int i = 1; i < 5; i++)
    {
        DicomPage page = image.AddPage();
        page.SaveArgb32Pixels(page.Bounds, pixels);
        page.AdjustBrightness(i * 30);
    }

     // Добавляем несколько страниц перед главной, делая их ярче
    for (int i = 1; i < 5; i++)
    {
        DicomPage page = image.InsertPage(0);
        page.SaveArgb32Pixels(page.Bounds, pixels);
        page.AdjustBrightness(-i * 30);
    }

     // Сохраняем созданное многостраничное изображение в выходной файл file
    image.Save("MultiPage.dcm");
}
```

Использовать сжатие JPEG в изображении DICOM.

```csharp
[C#]

using (DicomImage image = (DicomImage)Image.Create(
        new DicomOptions() { Source = new StreamSource(new MemoryStream()) },
        100,
        100))
{
     // Нарисуйте что-нибудь, используя векторную графику
    Graphics graphics = new Graphics(image);
    graphics.FillRectangle(new SolidBrush(Color.BlueViolet), image.Bounds);
    graphics.FillRectangle(new SolidBrush(Color.Aqua), 10, 20, 50, 20);
    graphics.FillEllipse(new SolidBrush(Color.Orange), 30, 50, 70, 30);

    // Сохраняем пиксели нарисованного изображения. Теперь они на первой странице изображения Dicom.
    int[] pixels = image.LoadArgb32Pixels(image.Bounds);

     // Добавляем несколько страниц после, делая их темнее
    for (int i = 1; i < 5; i++)
    {
        DicomPage page = image.AddPage();
        page.SaveArgb32Pixels(page.Bounds, pixels);
        page.AdjustBrightness(i * 30);
    }

     // Добавляем несколько страниц перед главной, делая их ярче
    for (int i = 1; i < 5; i++)
    {
        DicomPage page = image.InsertPage(0);
        page.SaveArgb32Pixels(page.Bounds, pixels);
        page.AdjustBrightness(-i * 30);
    }

     // Сохраняем созданное многостраничное изображение в выходной файл file
    image.Save("MultiPage.dcm");
}
```

В следующем примере показан экспорт в формат файла DICOM (одностраничный и многостраничный).

```csharp
[C#]

using (DicomImage image = (DicomImage)Image.Create(
        new DicomOptions() { Source = new StreamSource(new MemoryStream()) },
        100,
        100))
{
     // Нарисуйте что-нибудь, используя векторную графику
    Graphics graphics = new Graphics(image);
    graphics.FillRectangle(new SolidBrush(Color.BlueViolet), image.Bounds);
    graphics.FillRectangle(new SolidBrush(Color.Aqua), 10, 20, 50, 20);
    graphics.FillEllipse(new SolidBrush(Color.Orange), 30, 50, 70, 30);

    // Сохраняем пиксели нарисованного изображения. Теперь они на первой странице изображения Dicom.
    int[] pixels = image.LoadArgb32Pixels(image.Bounds);

     // Добавляем несколько страниц после, делая их темнее
    for (int i = 1; i < 5; i++)
    {
        DicomPage page = image.AddPage();
        page.SaveArgb32Pixels(page.Bounds, pixels);
        page.AdjustBrightness(i * 30);
    }

     // Добавляем несколько страниц перед главной, делая их ярче
    for (int i = 1; i < 5; i++)
    {
        DicomPage page = image.InsertPage(0);
        page.SaveArgb32Pixels(page.Bounds, pixels);
        page.AdjustBrightness(-i * 30);
    }

     // Сохраняем созданное многостраничное изображение в выходной файл file
    image.Save("MultiPage.dcm");
}
```

Создание многостраничного изображения Dicom.

```csharp
[C#]

using (DicomImage image = (DicomImage)Image.Create(
        new DicomOptions() { Source = new StreamSource(new MemoryStream()) },
        100,
        100))
{
     // Нарисуйте что-нибудь, используя векторную графику
    Graphics graphics = new Graphics(image);
    graphics.FillRectangle(new SolidBrush(Color.BlueViolet), image.Bounds);
    graphics.FillRectangle(new SolidBrush(Color.Aqua), 10, 20, 50, 20);
    graphics.FillEllipse(new SolidBrush(Color.Orange), 30, 50, 70, 30);

    // Сохраняем пиксели нарисованного изображения. Теперь они на первой странице изображения Dicom.
    int[] pixels = image.LoadArgb32Pixels(image.Bounds);

     // Добавляем несколько страниц после, делая их темнее
    for (int i = 1; i < 5; i++)
    {
        DicomPage page = image.AddPage();
        page.SaveArgb32Pixels(page.Bounds, pixels);
        page.AdjustBrightness(i * 30);
    }

     // Добавляем несколько страниц перед главной, делая их ярче
    for (int i = 1; i < 5; i++)
    {
        DicomPage page = image.InsertPage(0);
        page.SaveArgb32Pixels(page.Bounds, pixels);
        page.AdjustBrightness(-i * 30);
    }

     // Сохраняем созданное многостраничное изображение в выходной файл file
    image.Save("MultiPage.dcm");
}
```

### Смотрите также

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase)
* пространство имен [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
