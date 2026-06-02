---
title: "عدد EmfPlusPixelOffsetMode"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusPixelOffsetMode تعداد. يحدد تعداد PixelOffsetMode كيفية إزاحة البكسلات والذي يحدد التوازن بين سرعة العرض وجودته."
type: docs
weight: 5140
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixeloffsetmode/
---
## EmfPlusPixelOffsetMode enumeration

تحدد تعداد PixelOffsetMode كيفية إزاحة البكسلات، مما يحدد التوازن بين سرعة العرض والجودة.

```csharp
public enum EmfPlusPixelOffsetMode : byte
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| PixelOffsetModeDefault | `0` | يتم تمركز البكسلات على إحداثيات صحيحة، مما يفضّل السرعة على الجودة. |
| PixelOffsetModeHighSpeed | `1` | يتم تمركز البكسلات على إحداثيات صحيحة، كما في PixelOffsetModeNone. يتم تحديد سرعة أعلى على حساب الجودة. |
| PixelOffsetModeHighQuality | `2` | يتم تمركز البكسلات على إحداثيات نصف صحيحة، كما في PixelOffsetModeHalf. يتم تحديد جودة أعلى على حساب السرعة. |
| PixelOffsetModeNone | `3` | يتم تمركز البكسلات على الأصل، مما يعني أن البكسل يغطي المنطقة من -0.5 إلى 0.5 على كل من المحورين x و y ومركزه عند (0,0). |
| PixelOffsetModeHalf | `4` | يتم تمركز البكسلات على إحداثيات نصف صحيحة، مما يعني أن البكسل يغطي المنطقة من 0 إلى 1 على كل من المحورين x و y ومركزه عند (0.5,0.5). من خلال إزاحة البكسلات أثناء العرض، يمكن تحسين جودة العرض على حساب سرعة العرض. |

### انظر أيضًا

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)


