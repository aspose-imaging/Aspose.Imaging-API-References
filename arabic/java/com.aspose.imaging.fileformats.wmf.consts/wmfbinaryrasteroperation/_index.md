---
title: "WmfBinaryRasterOperation"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "قسم التعداد BinaryRasterOperation يدرج رموز عمليات raster الثنائية."
type: docs
weight: 11
url: /ar/java/com.aspose.imaging.fileformats.wmf.consts/wmfbinaryrasteroperation/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfBinaryRasterOperation extends System.Enum
```

قسم تعداد BinaryRasterOperation يسرد رموز عمليات الرستر الثنائية. رموز عمليات الرستر تحدد كيفية دمج معالجة ملف الميتا للبتات من القلم المحدد مع البتات في صورة البت الوجهة.

--------------------

كل رمز عملية رستر يمثل عملية بوليانية يتم فيها دمج قيم البكسلات في القلم المحدد وصورة البت الوجهة. فيما يلي العاملان المستخدمان في هذه العمليات. العامل معنى P القلم المحدد D صورة البت الوجهة a AND بتية n NOT بتية (عكس) o OR بتية x XOR بتية حصرية.
## الحقول

| حقل | الوصف |
| --- | --- |
| [Black](#Black) | 0، البكسل دائمًا 0. |
| [Notmergepen](#Notmergepen) | DPon، البكسل هو عكس لون MERGEPEN |
| [Masknotpen](#Masknotpen) | DPna، البكسل هو مزيج من لون الشاشة وعكس لون القلم. |
| [Notcopypen](#Notcopypen) | Pn، البكسل هو عكس لون القلم. |
| [Maskpennot](#Maskpennot) | PDna، البكسل هو مزيج من الألوان المشتركة بين القلم وعكس الشاشة. |
| [Not](#Not) | Dn، البكسل هو عكس لون الشاشة. |
| [Xorpen](#Xorpen) | DPx، البكسل هو مزيج من الألوان في القلم أو في الشاشة، ولكن ليس في كليهما. |
| [Notmaskpen](#Notmaskpen) | DPan، البكسل هو عكس لون MASKPEN. |
| [Maskpen](#Maskpen) | DPa، البكسل هو مزيج من الألوان المشتركة بين القلم والشاشة. |
| [Notxorpen](#Notxorpen) | DPxn، البكسل هو عكس لون XORPEN. |
| [Nop](#Nop) | D، البكسل يبقى دون تغيير. |
| [Mergenotpen](#Mergenotpen) | DPno، البكسل هو مزيج من الألوان المشتركة بين الشاشة وعكس القلم. |
| [Copypen](#Copypen) | P, Pixel هو لون القلم. |
| [Mergepennot](#Mergepennot) | PDno, Pixel هو مزيج من لون القلم والعكس من لون الشاشة. |
| [Mergepen](#Mergepen) | DPo, Pixel هو مزيج من لون القلم ولون الشاشة. |
| [White](#White) | 1, Pixel دائمًا 1 |
### Black {#Black}
```
public static final int Black
```


0، البكسل دائمًا 0.

### Notmergepen {#Notmergepen}
```
public static final int Notmergepen
```


DPon، البكسل هو عكس لون MERGEPEN

### Masknotpen {#Masknotpen}
```
public static final int Masknotpen
```


DPna، البكسل هو مزيج من لون الشاشة وعكس لون القلم.

### Notcopypen {#Notcopypen}
```
public static final int Notcopypen
```


Pn، البكسل هو عكس لون القلم.

### Maskpennot {#Maskpennot}
```
public static final int Maskpennot
```


PDna، البكسل هو مزيج من الألوان المشتركة بين القلم وعكس الشاشة.

### Not {#Not}
```
public static final int Not
```


Dn، البكسل هو عكس لون الشاشة.

### Xorpen {#Xorpen}
```
public static final int Xorpen
```


DPx، البكسل هو مزيج من الألوان في القلم أو في الشاشة، ولكن ليس في كليهما.

### Notmaskpen {#Notmaskpen}
```
public static final int Notmaskpen
```


DPan، البكسل هو عكس لون MASKPEN.

### Maskpen {#Maskpen}
```
public static final int Maskpen
```


DPa، البكسل هو مزيج من الألوان المشتركة بين القلم والشاشة.

### Notxorpen {#Notxorpen}
```
public static final int Notxorpen
```


DPxn، البكسل هو عكس لون XORPEN.

### Nop {#Nop}
```
public static final int Nop
```


D، البكسل يبقى دون تغيير.

### Mergenotpen {#Mergenotpen}
```
public static final int Mergenotpen
```


DPno، البكسل هو مزيج من الألوان المشتركة بين الشاشة وعكس القلم.

### Copypen {#Copypen}
```
public static final int Copypen
```


P, Pixel هو لون القلم.

### Mergepennot {#Mergepennot}
```
public static final int Mergepennot
```


PDno, Pixel هو مزيج من لون القلم والعكس من لون الشاشة.

### Mergepen {#Mergepen}
```
public static final int Mergepen
```


DPo, Pixel هو مزيج من لون القلم ولون الشاشة.

### White {#White}
```
public static final int White
```


1, Pixel دائمًا 1

