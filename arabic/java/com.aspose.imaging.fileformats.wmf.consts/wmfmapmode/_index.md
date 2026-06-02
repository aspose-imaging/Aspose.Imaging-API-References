---
title: "WmfMapMode"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "أنماط الخريطة"
type: docs
weight: 23
url: /ar/java/com.aspose.imaging.fileformats.wmf.consts/wmfmapmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfMapMode extends System.Enum
```

أنماط الخريطة
## الحقول

| حقل | الوصف |
| --- | --- |
| [Text](#Text) | النص: كل وحدة منطقية تُطابق بكسل جهاز واحد. |
| [Lometric](#Lometric) | الوحدات اللومترية: كل وحدة منطقية تُطابق 0.1 مليمتر. |
| [Himetric](#Himetric) | الوحدات الهيمترية: كل وحدة منطقية تُطابق 0.01 مليمتر. |
| [Loenglish](#Loenglish) | الوحدات اللإنجليزية المنخفضة: كل وحدة منطقية تُطابق 0.01 بوصة. |
| [Hienglish](#Hienglish) | الوحدات الإنجليزية العالية: كل وحدة منطقية تُطابق 0.001 بوصة. |
| [Twips](#Twips) | الوحدات twips: كل وحدة منطقية تُطابق واحد من عشرين (1/20) من النقطة. |
| [Isotropic](#Isotropic) | الوحدات المتساوية الاتجاه: تُطابق الوحدات المنطقية إلى وحدات جهاز عشوائية مع محاور ذات مقياس متساوٍ؛ أي أن وحدة واحدة على المحور x تساوي وحدة واحدة على المحور y. |
| [Anisotropic](#Anisotropic) | الوحدات غير المتساوية الاتجاه: تُطابق الوحدات المنطقية إلى وحدات عشوائية مع محاور ذات مقياس عشوائي. |
### Text {#Text}
```
public static final short Text
```


النص: كل وحدة منطقية تُطابق بكسل جهاز واحد. x الموجبة إلى اليمين؛ y الموجبة إلى الأسفل.

### Lometric {#Lometric}
```
public static final short Lometric
```


الوحدات اللومترية كل وحدة منطقية تُقَصَد إلى 0.1 مليمتر. الـ x الموجب إلى اليمين؛ الـ y الموجب إلى الأعلى.

### Himetric {#Himetric}
```
public static final short Himetric
```


الوحدات الهيمترية كل وحدة منطقية تُقَصَد إلى 0.01 مليمتر. الـ x الموجب إلى اليمين؛ الـ y الموجب إلى الأعلى.

### Loenglish {#Loenglish}
```
public static final short Loenglish
```


الوحدات اللإنجليزية كل وحدة منطقية تُقَصَد إلى 0.01 بوصة. الـ x الموجب إلى اليمين؛ الـ y الموجب إلى الأعلى.

### Hienglish {#Hienglish}
```
public static final short Hienglish
```


الوحدات الهينغليش كل وحدة منطقية تُقَصَد إلى 0.001 بوصة. الـ x الموجب إلى اليمين؛ الـ y الموجب إلى الأعلى.

### Twips {#Twips}
```
public static final short Twips
```


الوحدات التويبس كل وحدة منطقية تُقَصَد إلى واحد من عشرين (1/20) من النقطة. في الطباعة، النقطة هي 1/72 بوصة؛ لذلك، 1/20 من النقطة هو 1/1440 بوصة. تُعرف هذه الوحدة أيضًا باسم \"twip\".

### Isotropic {#Isotropic}
```
public static final short Isotropic
```


الوحدات المتساوية الاتجاه كل الوحدات المنطقية تُقَصَد إلى وحدات جهاز عشوائية ذات محاور متساوية المقياس؛ أي أن وحدة واحدة على محور x تساوي وحدة واحدة على محور y. سجلات META\_SETWINDOWEXT و META\_SETVIEWPORTEXT تحدد الوحدات واتجاه المحاور.

### Anisotropic {#Anisotropic}
```
public static final short Anisotropic
```


الوحدات غير المتساوية الاتجاه: تُطابق الوحدات المنطقية إلى وحدات عشوائية مع محاور ذات مقياس عشوائي.

