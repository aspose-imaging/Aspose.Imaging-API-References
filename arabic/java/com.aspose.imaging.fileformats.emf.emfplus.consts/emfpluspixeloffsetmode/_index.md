---
title: "EmfPlusPixelOffsetMode"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تحدد تعداد PixelOffsetMode كيفية إزاحة البكسلات، مما يحدد الموازنة بين سرعة العرض والجودة."
type: docs
weight: 44
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixeloffsetmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusPixelOffsetMode extends System.Enum
```

تحدد تعداد PixelOffsetMode كيفية إزاحة البكسلات، مما يحدد التوازن بين سرعة العرض وجودته.
## الحقول

| حقل | الوصف |
| --- | --- |
| [PixelOffsetModeDefault](#PixelOffsetModeDefault) | يتم تمركز البكسلات على إحداثيات صحيحة، مع تحديد السرعة على حساب الجودة. |
| [PixelOffsetModeHighSpeed](#PixelOffsetModeHighSpeed) | يتم تمركز البكسلات على إحداثيات صحيحة، كما هو الحال مع PixelOffsetModeNone. |
| [PixelOffsetModeHighQuality](#PixelOffsetModeHighQuality) | يتم تمركز البكسلات على إحداثيات نصف صحيحة، كما هو الحال مع PixelOffsetModeHalf. |
| [PixelOffsetModeNone](#PixelOffsetModeNone) | يتم تمركز البكسلات على الأصل، مما يعني أن البكسل يغطي المنطقة من -0.5 إلى 0.5 على كل من محوري x و y ومركزه عند (0,0). |
| [PixelOffsetModeHalf](#PixelOffsetModeHalf) | يتم تمركز البكسلات على إحداثيات نصف صحيحة، مما يعني أن البكسل يغطي المنطقة من 0 إلى 1 على كل من محوري x و y ومركزه عند (0.5,0.5). |
### PixelOffsetModeDefault {#PixelOffsetModeDefault}
```
public static final byte PixelOffsetModeDefault
```


يتم تمركز البكسلات على إحداثيات صحيحة، مع تحديد السرعة على حساب الجودة.

### PixelOffsetModeHighSpeed {#PixelOffsetModeHighSpeed}
```
public static final byte PixelOffsetModeHighSpeed
```


يتم تمركز البكسلات على إحداثيات صحيحة، كما هو الحال مع PixelOffsetModeNone. يتم تحديد سرعة أعلى على حساب الجودة.

### PixelOffsetModeHighQuality {#PixelOffsetModeHighQuality}
```
public static final byte PixelOffsetModeHighQuality
```


يتم تمركز البكسلات على إحداثيات نصف صحيحة، كما هو الحال مع PixelOffsetModeHalf. يتم تحديد جودة أعلى على حساب السرعة.

### PixelOffsetModeNone {#PixelOffsetModeNone}
```
public static final byte PixelOffsetModeNone
```


يتم تمركز البكسلات على الأصل، مما يعني أن البكسل يغطي المنطقة من -0.5 إلى 0.5 على كل من محوري x و y ومركزه عند (0,0).

### PixelOffsetModeHalf {#PixelOffsetModeHalf}
```
public static final byte PixelOffsetModeHalf
```


يتم تمركز البكسلات على إحداثيات نصف صحيحة، مما يعني أن البكسل يغطي المنطقة من 0 إلى 1 على كل من محوري x و y ومركزه عند (0.5,0.5). من خلال إزاحة البكسلات أثناء التصيير، يمكن تحسين جودة التصيير على حساب سرعة التصيير.

