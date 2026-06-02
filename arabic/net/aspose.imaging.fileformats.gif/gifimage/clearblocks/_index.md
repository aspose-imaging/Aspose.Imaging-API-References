---
title: "GifImage.ClearBlocks"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة GifImage. مسح جميع كتل GIF يزيل أي بيانات موجودة مخزنة داخل الصورة. تقوم هذه العملية بإعادة تعيين الصورة إلى حالة فارغة، مما يزيل أي كتل مضافة مسبقًا. استخدم هذه الطريقة عندما تحتاج إلى البدء من جديد بصفحة نظيفة لإنشاء أو تعديل صورة GIF."
type: docs
weight: 270
url: /ar/net/aspose.imaging.fileformats.gif/gifimage/clearblocks/
---
## GifImage.ClearBlocks method

مسح جميع كتل GIF يزيل أي بيانات موجودة مخزنة داخل الصورة. تقوم هذه العملية بإعادة تعيين الصورة إلى حالة فارغة، وإزالة أي كتل مضافة مسبقًا. استخدم هذه الطريقة عندما تحتاج إلى بدء جديد بصفحة نظيفة لإنشاء أو تعديل صورة GIF.

```csharp
public void ClearBlocks()
```

## أمثلة

المثال التالي يوضح كيفية إزالة جميع الكتل من صورة GIF.

```csharp
[C#]

using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
{
    if (gifImage.ActiveFrame != null)
    {
        System.Console.WriteLine("Active frame size: {0}", gifImage.ActiveFrame.Size);
    }
    else
    {
        System.Console.WriteLine("Active frame is not set");
    }

    System.Console.WriteLine("Clear all the blocks");
    gifImage.ClearBlocks();

    if (gifImage.ActiveFrame != null)
    {
        System.Console.WriteLine("Active frame size: {0}", gifImage.ActiveFrame.Size);
    }
    else
    {
        System.Console.WriteLine("Active frame is not set");
    }
}

// الإخراج يبدو هكذا:
// حجم الإطار النشط: { Width = 100, Height = 100}
// مسح جميع الكتل
// الإطار النشط غير محدد
```

### انظر أيضًا

* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


