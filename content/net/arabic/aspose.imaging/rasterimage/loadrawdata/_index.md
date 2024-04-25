---
title: LoadRawData
second_title: Aspose.Imaging لمرجع NET API
description: تحميل البيانات الأولية .
type: docs
weight: 420
url: /ar/aspose.imaging/rasterimage/loadrawdata/
---
## LoadRawData(Rectangle, RawDataSettings, IPartialRawDataLoader) {#loadrawdata}

تحميل البيانات الأولية .

```csharp
public void LoadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, 
    IPartialRawDataLoader rawDataLoader)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| rectangle | Rectangle | المستطيل المراد تحميل البيانات الأولية منه. |
| rawDataSettings | RawDataSettings | إعدادات البيانات الأولية لاستخدامها في تحميل البيانات. لاحظ أنه إذا لم تكن البيانات بالتنسيق المحدد ، فسيتم إجراء تحويل البيانات. |
| rawDataLoader | IPartialRawDataLoader | محمل البيانات الخام. |

### أمثلة

يوضح المثال التالي كيفية استخراج وحدات البكسل من بيانات الصورة الأولية باستخدام RawDataSettings. على سبيل المثال ، ضع في اعتبارك مشكلة حساب وحدات البكسل الشفافة تمامًا للصورة.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\GrayscaleWithAlpha.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;
    Aspose.Imaging.RawDataSettings settings = rasterImage.RawDataSettings;

    TransparentPixelRawDataCounter rawDataLoader = new TransparentPixelRawDataCounter(settings);

    // تحميل بكسل للصورة بأكملها. يمكن تحديد أي جزء مستطيل من الصورة كمعامل لطريقة Aspose.Imaging.RasterImage.LoadRawData.
    rasterImage.LoadRawData(rasterImage.Bounds, settings, rawDataLoader);

    System.Console.WriteLine("The number of fully transparent pixels is {0}", rawDataLoader.Count);
    System.Console.WriteLine("The total number of pixels is {0}", image.Width * image.Height);
}

// في حالة البيانات الأولية ، قد يبدو العداد كما يلي:
/// <summary>
/// تحسب عدد وحدات البكسل الشفافة بالكامل بقيمة قناة ألفا تساوي 0.
/// </summary>
private class TransparentPixelRawDataCounter : IPartialRawDataLoader
{
    /// <summary>
    /// عدد وحدات البكسل الشفافة بالكامل.
    /// </summary>
    private int count;

    /// <summary>
    /// إعدادات البيانات الأولية للصورة المحملة.
    /// </summary>
    private Aspose.Imaging.RawDataSettings rawDataSettings;

    /// <summary>
    /// يحصل على عدد وحدات البكسل الشفافة بالكامل.
    /// </summary>
    public int Count
    {
        get { return this.count; }
    }

    /// <summary>
    /// تهيئة نسخة جديدة من العلامة < راجع TransparentPixelRawDataCounter / > صف دراسي.
    /// </summary>
    /// < param name = "settings" > تسمح إعدادات البيانات الأولية باستخراج مكونات اللون من البيانات الأولية. < / param >
    public TransparentPixelRawDataCounter(Aspose.Imaging.RawDataSettings settings)
    {
        this.rawDataSettings = settings;
        this.count = 0;
    }

    /// <summary>
    /// يعالج البيانات الأولية المحملة. يتم استدعاء هذه الطريقة مرة أخرى في كل مرة يتم فيها تحميل جزء جديد من البيانات الأولية.
    /// </summary>
    /// < param name = "dataRectangle" > مستطيل البيانات الخام. < / param >
    /// < param name = "data" > البيانات الأولية. < / param >
    /// < param name = "start" > نقطة بيانات البداية. < / param >
    /// < param name = "end" > نقطة بيانات النهاية. < / param >
    public void Process(Aspose.Imaging.Rectangle dataRectangle, byte[] data, Aspose.Imaging.Point start, Aspose.Imaging.Point end)
    {
        int[] channelBits = this.rawDataSettings.PixelDataFormat.ChannelBits;

        // يتم استخدام التنسيقات البسيطة فقط هنا لتبسيط الكود.
        // دعنا ننظر فقط إلى الصور ذات 8 بتات لكل عينة.
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
                            // يتم تخزين قناة ألفا أخيرًا ، بعد مكونات اللون.
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
                        // Grayscale Alpha
                        for (int i = 0; i < data.Length; i += 2)
                        {
                            // يتم تخزين قناة ألفا أخيرًا ، بعد مكونات اللون.
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
    /// يعالج البيانات الأولية المحملة. يتم استدعاء هذه الطريقة مرة أخرى في كل مرة يتم فيها تحميل جزء جديد من البيانات الأولية.
    /// </summary>
    /// < param name = "dataRectangle" > مستطيل البيانات الخام. < / param >
    /// < param name = "data" > البيانات الأولية. < / param >
    /// < param name = "start" > نقطة بيانات البداية. < / param >
    /// < param name = "end" > نقطة بيانات النهاية. < / param >
    /// < param name = "loadOptions" > خيارات التحميل. < / param >
    public void Process(Aspose.Imaging.Rectangle dataRectangle, byte[] data, Aspose.Imaging.Point start, Aspose.Imaging.Point end, Aspose.Imaging.LoadOptions loadOptions)
    {
        this.Process(dataRectangle, data, start, end);
    }
}
```

### أنظر أيضا

* struct [Rectangle](../../rectangle)
* class [RawDataSettings](../../rawdatasettings)
* interface [IPartialRawDataLoader](../../ipartialrawdataloader)
* class [RasterImage](../../rasterimage)
* مساحة الاسم [Aspose.Imaging](../../rasterimage)
* المجسم [Aspose.Imaging](../../../)

---

## LoadRawData(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) {#loadrawdata_1}

تحميل البيانات الأولية .

```csharp
public void LoadRawData(Rectangle rectangle, Rectangle destImageBounds, 
    RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| rectangle | Rectangle | المستطيل المراد تحميل البيانات الأولية منه. |
| destImageBounds | Rectangle | حدود الصورة Dest. |
| rawDataSettings | RawDataSettings | إعدادات البيانات الأولية لاستخدامها في تحميل البيانات. لاحظ أنه إذا لم تكن البيانات بالتنسيق المحدد ، فسيتم إجراء تحويل البيانات. |
| rawDataLoader | IPartialRawDataLoader | محمل البيانات الخام. |

### أنظر أيضا

* struct [Rectangle](../../rectangle)
* class [RawDataSettings](../../rawdatasettings)
* interface [IPartialRawDataLoader](../../ipartialrawdataloader)
* class [RasterImage](../../rasterimage)
* مساحة الاسم [Aspose.Imaging](../../rasterimage)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
