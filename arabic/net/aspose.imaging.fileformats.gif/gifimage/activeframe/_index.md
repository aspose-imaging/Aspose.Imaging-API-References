---
title: "GifImage.ActiveFrame"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية GifImage. إدارة وتعديل الإطارات باستخدام هذه الخاصية مما يتيح تنقلاً سلساً وتعديل الإطار النشط داخل صورة GIF."
type: docs
weight: 20
url: /ar/net/aspose.imaging.fileformats.gif/gifimage/activeframe/
---
## GifImage.ActiveFrame property

قم بإدارة وتعديل الإطارات باستخدام هذه الخاصية، مما يتيح تنقلًا سلسًا وتعديلًا للإطار النشط داخل صورة GIF.

```csharp
public GifFrameBlock ActiveFrame { get; set; }
```

### Property Value

الإطار النشط.

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

* class [GifFrameBlock](../../../aspose.imaging.fileformats.gif.blocks/gifframeblock/)
* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


