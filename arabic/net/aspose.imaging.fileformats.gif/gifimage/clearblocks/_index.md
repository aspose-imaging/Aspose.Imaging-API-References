---
title: ClearBlocks
second_title: Aspose.Imaging لمرجع NET API
description: يمسح كل كتل GIF .
type: docs
weight: 290
url: /ar/net/aspose.imaging.fileformats.gif/gifimage/clearblocks/
---
## GifImage.ClearBlocks method

يمسح كل كتل GIF .

```csharp
public void ClearBlocks()
```

### أمثلة

يوضح المثال التالي كيفية إزالة جميع الكتل من صورة GIF.

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

// يبدو الإخراج كالتالي:
// حجم الإطار النشط: {العرض = 100 ، الارتفاع = 100}
// امسح كل الكتل
// لم يتم تعيين الإطار النشط
```

### أنظر أيضا

* class [GifImage](../../gifimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
