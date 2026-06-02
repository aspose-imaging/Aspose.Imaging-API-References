---
title: "EmfPlusPixelOffsetMode"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تحدد تعداد PixelOffsetMode كيفية إزاحة البكسلات مما يحدد الموازنة بين سرعة العرض وجودته."
type: docs
weight: 44
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixeloffsetmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusPixelOffsetMode extends System.Enum
```

تحدد تعداد PixelOffsetMode كيفية إزاحة البكسلات، مما يحدد التوازن بين سرعة العرض والجودة.
## الحقول

| حقل | الوصف |
| --- | --- |
| [PixelOffsetModeDefault](#PixelOffsetModeDefault) | البكسلات متمركزة على إحداثيات صحيحة، مما يفضّل السرعة على الجودة. |
| [PixelOffsetModeHighSpeed](#PixelOffsetModeHighSpeed) | البكسلات متمركزة على إحداثيات صحيحة، كما في PixelOffsetModeNone. |
| [PixelOffsetModeHighQuality](#PixelOffsetModeHighQuality) | البكسلات متمركزة على إحداثيات نصف صحيحة، كما في PixelOffsetModeHalf. |
| [PixelOffsetModeNone](#PixelOffsetModeNone) | البكسلات متمركزة على الأصل، مما يعني أن البكسل يغطي المنطقة من -0.5 إلى 0.5 على كل من المحورين x و y ومركزه عند (0,0). |
| [PixelOffsetModeHalf](#PixelOffsetModeHalf) | البكسلات متمركزة على إحداثيات نصف صحيحة، مما يعني أن البكسل يغطي المنطقة من 0 إلى 1 على كل من المحورين x و y ومركزه عند (0.5,0.5). |
### PixelOffsetModeDefault {#PixelOffsetModeDefault}
```
public static final byte PixelOffsetModeDefault
```


البكسلات متمركزة على إحداثيات صحيحة، مما يفضّل السرعة على الجودة.

### PixelOffsetModeHighSpeed {#PixelOffsetModeHighSpeed}
```
public static final byte PixelOffsetModeHighSpeed
```


البكسلات متمركزة على إحداثيات صحيحة، كما في PixelOffsetModeNone. يتم تحديد سرعة أعلى على حساب الجودة.

### PixelOffsetModeHighQuality {#PixelOffsetModeHighQuality}
```
public static final byte PixelOffsetModeHighQuality
```


البكسلات متمركزة على إحداثيات نصف صحيحة، كما في PixelOffsetModeHalf. يتم تحديد جودة أعلى على حساب السرعة.

### PixelOffsetModeNone {#PixelOffsetModeNone}
```
public static final byte PixelOffsetModeNone
```


البكسلات متمركزة على الأصل، مما يعني أن البكسل يغطي المنطقة من -0.5 إلى 0.5 على كل من المحورين x و y ومركزه عند (0,0).

### PixelOffsetModeHalf {#PixelOffsetModeHalf}
```
public static final byte PixelOffsetModeHalf
```


البكسلات متمركزة على إحداثيات نصف صحيحة، مما يعني أن البكسل يغطي المنطقة من 0 إلى 1 على كل من المحورين x و y ومركزه عند (0.5,0.5). من خلال إزاحة البكسلات أثناء العرض، يمكن تحسين جودة العرض على حساب سرعة العرض.

