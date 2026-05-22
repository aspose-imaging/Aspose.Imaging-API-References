---
title: "EmfPlusPixelOffsetMode تعداد"
type: docs
weight: 350
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixeloffsetmode/
---

تحدد تعداد PixelOffsetMode كيفية إزاحة البكسلات، مما يحدد التوازن بين سرعة العرض والجودة.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusPixelOffsetMode

## **Members**
| **اسم العضو** | **الوصف** |
| :- | :- |
| PIXEL_OFFSET_MODE_DEFAULT | يتم تمركز البكسلات على إحداثيات صحيحة، مع تحديد السرعة على الجودة. |
| PIXEL_OFFSET_MODE_HALF | يتم تمركز البكسلات على إحداثيات نصف صحيحة، مما يعني أن البكسل يغطي المنطقة من 0 إلى 1 على كل من المحورين x و y ومركزه يقع عند (0.5,0.5). من خلال إزاحة البكسلات أثناء التصيير، يمكن تحسين جودة التصيير على حساب سرعة التصيير. |
| PIXEL_OFFSET_MODE_HIGH_QUALITY | يتم تمركز البكسلات على إحداثيات نصف صحيحة، كما هو الحال مع PixelOffsetModeHalf. يتم تحديد جودة أعلى على حساب السرعة. |
| PIXEL_OFFSET_MODE_HIGH_SPEED | يتم تمركز البكسلات على إحداثيات صحيحة، كما هو الحال مع PixelOffsetModeNone. يتم تحديد سرعة أعلى على حساب الجودة. |
| PIXEL_OFFSET_MODE_NONE | يتم تمركز البكسلات على الأصل، مما يعني أن البكسل يغطي المنطقة من -0.5 إلى 0.5 على كل من المحورين x و y ومركزه يقع عند (0,0). |
