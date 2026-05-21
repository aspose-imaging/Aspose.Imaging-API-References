---
title: "RasterImage.LoadRawData"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة RasterImage. تقوم بتحميل البيانات الخام"
type: docs
weight: 470
url: /ar/net/aspose.imaging/rasterimage/loadrawdata/
---
## LoadRawData(Rectangle, RawDataSettings, IPartialRawDataLoader) {#loadrawdata}

يحمّل البيانات الخام.

```csharp
public void LoadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, 
    IPartialRawDataLoader rawDataLoader)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المستطيل | Rectangle | المستطيل الذي يتم تحميل البيانات الخام منه. |
| rawDataSettings | RawDataSettings | إعدادات البيانات الخام التي تُستخدم للبيانات المحملة. ملاحظة: إذا لم تكن البيانات بالتنسيق المحدد فسيتم إجراء تحويل للبيانات. |
| rawDataLoader | IPartialRawDataLoader | محمل البيانات الخام. |

## أمثلة

المثال التالي يوضح كيفية استخراج البكسلات من بيانات الصورة الخام باستخدام RawDataSettings. على سبيل المثال، اعتبر مشكلة عد البكسلات الشفافة بالكامل في صورة.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\GrayscaleWithAlpha.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;
    Aspose.Imaging.RawDataSettings settings = rasterImage.RawDataSettings;

    TransparentPixelRawDataCounter rawDataLoader = new TransparentPixelRawDataCounter(settings);

    // تحميل البكسلات للصورة بأكملها. يمكن تحديد أي جزء مستطيل من الصورة كمعامل لطريقة Aspose.Imaging.RasterImage.LoadRawData.
    rasterImage.LoadRawData(rasterImage.Bounds, settings, rawDataLoader);

    System.Console.WriteLine("The number of fully transparent pixels is {0}", rawDataLoader.Count);
    System.Console.WriteLine("The total number of pixels is {0}", image.Width * image.Height);
}

// في حالة البيانات الخام، قد يبدو العداد هكذا:
/// <summary>
/// يحسب عدد البكسلات الشفافة بالكامل ذات قيمة قناة ألفا 0.
/// </summary>
private class TransparentPixelRawDataCounter : IPartialRawDataLoader
{
    /// <summary>
    /// عدد البكسلات الشفافة بالكامل.
    /// </summary>
    private int count;

    /// <summary>
    /// إعدادات البيانات الخام للصورة المحملة.
    /// </summary>
    private Aspose.Imaging.RawDataSettings rawDataSettings;

    /// <summary>
    /// يحصل على عدد البكسلات الشفافة بالكامل.
    /// </summary>
    public int Count
    {
        get { return this.count; }
    }

    /// <summary>
    /// يهيئ نسخة جديدة من الفئة <see TransparentPixelRawDataCounter />.
    /// </summary>
    /// <param name="settings">إعدادات البيانات الخام تسمح باستخراج مكونات اللون من البيانات الخام.</param>
    public TransparentPixelRawDataCounter(Aspose.Imaging.RawDataSettings settings)
    {
        this.rawDataSettings = settings;
        this.count = 0;
    }

    /// <summary>
    /// يعالج البيانات الخام المحملة. يتم استدعاء هذه الطريقة كلما تم تحميل جزء جديد من البيانات الخام.
    /// </summary>
    /// <param name="dataRectangle">مستطيل البيانات الخام.</param>
    /// <param name="data">البيانات الخام.</param>
    /// <param name="start">نقطة بدء البيانات.</param>
    /// <param name="end">نقطة نهاية البيانات.</param>
    public void Process(Aspose.Imaging.Rectangle dataRectangle, byte[] data, Aspose.Imaging.Point start, Aspose.Imaging.Point end)
    {
        int[] channelBits = this.rawDataSettings.PixelDataFormat.ChannelBits;

        // يتم اعتبار الصيغ البسيطة فقط هنا لتبسيط الشيفرة.
        // لننظر فقط إلى الصور ذات 8 بت لكل عينة.
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
                        // ARGB
                        for (int i = 0; i < data.Length; i += 4)
                        {
                            // قناة ألفا تُخزن في النهاية، بعد مكونات اللون.
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
                        // تدرج الرمادي ألفا
                        for (int i = 0; i < data.Length; i += 2)
                        {
                            // قناة ألفا تُخزن في النهاية، بعد مكونات اللون.
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
    /// يعالج البيانات الخام المحملة. يتم استدعاء هذه الطريقة كلما تم تحميل جزء جديد من البيانات الخام.
    /// </summary>
    /// <param name="dataRectangle">مستطيل البيانات الخام.</param>
    /// <param name="data">البيانات الخام.</param>
    /// <param name="start">نقطة بدء البيانات.</param>
    /// <param name="end">نقطة نهاية البيانات.</param>
    /// <param name="loadOptions">خيارات التحميل.</param>
    public void Process(Aspose.Imaging.Rectangle dataRectangle, byte[] data, Aspose.Imaging.Point start, Aspose.Imaging.Point end, Aspose.Imaging.LoadOptions loadOptions)
    {
        this.Process(dataRectangle, data, start, end);
    }
}
```

### انظر أيضًا

* struct [Rectangle](../../rectangle/)
* class [RawDataSettings](../../rawdatasettings/)
* interface [IPartialRawDataLoader](../../ipartialrawdataloader/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)

---

## LoadRawData(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) {#loadrawdata_1}

يحمّل البيانات الخام.

```csharp
public void LoadRawData(Rectangle rectangle, Rectangle destImageBounds, 
    RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المستطيل | Rectangle | المستطيل الذي يتم تحميل البيانات الخام منه. |
| destImageBounds | Rectangle | حدود الصورة الوجهة. |
| rawDataSettings | RawDataSettings | إعدادات البيانات الخام التي تُستخدم للبيانات المحملة. ملاحظة: إذا لم تكن البيانات بالتنسيق المحدد فسيتم إجراء تحويل للبيانات. |
| rawDataLoader | IPartialRawDataLoader | محمل البيانات الخام. |

### انظر أيضًا

* struct [Rectangle](../../rectangle/)
* class [RawDataSettings](../../rawdatasettings/)
* interface [IPartialRawDataLoader](../../ipartialrawdataloader/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


