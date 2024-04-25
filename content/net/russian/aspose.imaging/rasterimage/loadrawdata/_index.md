---
title: LoadRawData
second_title: Справочник по Aspose.Imaging for .NET API
description: Загружает необработанные данные.
type: docs
weight: 420
url: /ru/aspose.imaging/rasterimage/loadrawdata/
---
## LoadRawData(Rectangle, RawDataSettings, IPartialRawDataLoader) {#loadrawdata}

Загружает необработанные данные.

```csharp
public void LoadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, 
    IPartialRawDataLoader rawDataLoader)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | Rectangle | Прямоугольник, из которого загружаются необработанные данные. |
| rawDataSettings | RawDataSettings | Параметры необработанных данных, используемые для загруженных данных. Обратите внимание, что если данные не в указанном формате, будет выполнено преобразование данных. |
| rawDataLoader | IPartialRawDataLoader | Загрузчик необработанных данных. |

### Примеры

В следующем примере показано, как извлечь пиксели из необработанных данных изображения с помощью RawDataSettings. Например, рассмотрим задачу подсчета полностью прозрачных пикселей изображения.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\GrayscaleWithAlpha.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;
    Aspose.Imaging.RawDataSettings settings = rasterImage.RawDataSettings;

    TransparentPixelRawDataCounter rawDataLoader = new TransparentPixelRawDataCounter(settings);

    // Загрузить пиксели для всего изображения. Любая прямоугольная часть изображения может быть указана в качестве параметра метода Aspose.Imaging.RasterImage.LoadRawData.
    rasterImage.LoadRawData(rasterImage.Bounds, settings, rawDataLoader);

    System.Console.WriteLine("The number of fully transparent pixels is {0}", rawDataLoader.Count);
    System.Console.WriteLine("The total number of pixels is {0}", image.Width * image.Height);
}

// В случае необработанных данных счетчик может выглядеть так:
/// <summary>
/// Подсчитывает количество полностью прозрачных пикселей со значением альфа-канала, равным 0.
/// </summary>
private class TransparentPixelRawDataCounter : IPartialRawDataLoader
{
    /// <summary>
    /// Количество полностью прозрачных пикселей.
    /// </summary>
    private int count;

    /// <summary>
    /// Настройки необработанных данных загруженного изображения.
    /// </summary>
    private Aspose.Imaging.RawDataSettings rawDataSettings;

    /// <summary>
    /// Получает количество полностью прозрачных пикселей.
    /// </summary>
    public int Count
    {
        get { return this.count; }
    }

    /// <summary>
    /// Инициализирует новый экземпляр <see TransparentPixelRawDataCounter /> учебный класс.
    /// </summary>
    /// <param name="settings">Настройки необработанных данных позволяют извлекать компоненты цвета из необработанных данных.</param>
    public TransparentPixelRawDataCounter(Aspose.Imaging.RawDataSettings settings)
    {
        this.rawDataSettings = settings;
        this.count = 0;
    }

    /// <summary>
    /// Обрабатывает загруженные необработанные данные. Этот метод вызывается каждый раз, когда загружается новая порция необработанных данных.
    /// </summary>
    /// <param name="dataRectangle">Прямоугольник необработанных данных.</param>
    /// <param name="data">Необработанные данные.</param>
    /// <param name="start">Начальная точка данных.</param>
    /// <param name="end">Конечная точка данных.</param>
    public void Process(Aspose.Imaging.Rectangle dataRectangle, byte[] data, Aspose.Imaging.Point start, Aspose.Imaging.Point end)
    {
        int[] channelBits = this.rawDataSettings.PixelDataFormat.ChannelBits;

        // Здесь рассматриваются только простые форматы для упрощения кода.
        // Рассмотрим только изображения с 8 битами на выборку.
        for (int i = 0; i < channelBits.Length; i++)
        {
            if (channelBits[i] != 8)
            {
                throw new System.NotSupportedException();
            }
        }

        switch (this.rawDataSettings.PixelDataFormat.PixelFormat)
        {
            case PixelFormat.Rgb:
            case PixelFormat.Bgr:
                {
                    if (channelBits.Length == 4)
                    {
                        // АРГБ
                        for (int i = 0; i < data.Length; i += 4)
                        {
                            // Альфа-канал сохраняется последним, после компонентов цвета.
                            if (data[i + 3] == 0)
                            {
                                this.count++;
                            }
                        }
                    }
                }
                break;

            case PixelFormat.Grayscale:
                {
                    if (channelBits.Length == 2)
                    {
                        // Оттенки серого альфа
                        for (int i = 0; i < data.Length; i += 2)
                        {
                            // Альфа-канал сохраняется последним, после компонентов цвета.
                            if (data[i + 1] == 0)
                            {
                                this.count++;
                            }
                        }
                    }
                }
                break;

            default:
                throw new System.ArgumentOutOfRangeException("PixelFormat");
        }
    }

    /// <summary>
    /// Обрабатывает загруженные необработанные данные. Этот метод вызывается каждый раз, когда загружается новая порция необработанных данных.
    /// </summary>
    /// <param name="dataRectangle">Прямоугольник необработанных данных.</param>
    /// <param name="data">Необработанные данные.</param>
    /// <param name="start">Начальная точка данных.</param>
    /// <param name="end">Конечная точка данных.</param>
    /// <param name="loadOptions">Параметры загрузки.</param>
    public void Process(Aspose.Imaging.Rectangle dataRectangle, byte[] data, Aspose.Imaging.Point start, Aspose.Imaging.Point end, Aspose.Imaging.LoadOptions loadOptions)
    {
        this.Process(dataRectangle, data, start, end);
    }
}
```

### Смотрите также

* struct [Rectangle](../../rectangle)
* class [RawDataSettings](../../rawdatasettings)
* interface [IPartialRawDataLoader](../../ipartialrawdataloader)
* class [RasterImage](../../rasterimage)
* пространство имен [Aspose.Imaging](../../rasterimage)
* сборка [Aspose.Imaging](../../../)

---

## LoadRawData(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) {#loadrawdata_1}

Загружает необработанные данные.

```csharp
public void LoadRawData(Rectangle rectangle, Rectangle destImageBounds, 
    RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | Rectangle | Прямоугольник, из которого загружаются необработанные данные. |
| destImageBounds | Rectangle | Границы конечного изображения. |
| rawDataSettings | RawDataSettings | Параметры необработанных данных, используемые для загруженных данных. Обратите внимание, что если данные не в указанном формате, будет выполнено преобразование данных. |
| rawDataLoader | IPartialRawDataLoader | Загрузчик необработанных данных. |

### Смотрите также

* struct [Rectangle](../../rectangle)
* class [RawDataSettings](../../rawdatasettings)
* interface [IPartialRawDataLoader](../../ipartialrawdataloader)
* class [RasterImage](../../rasterimage)
* пространство имен [Aspose.Imaging](../../rasterimage)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
