---
title: "EmfMapMode"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تعداد MapMode يُستخدم لتحديد وحدة القياس لتحويل وحدات مساحة الصفحة إلى وحدات مساحة الجهاز ولتحديد اتجاه محاور الرسم."
type: docs
weight: 30
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.consts/emfmapmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfMapMode extends System.Enum
```

تعداد MapMode يُستخدم لتحديد وحدة القياس لتحويل وحدات مساحة الصفحة إلى وحدات مساحة الجهاز ولتحديد اتجاه محاور الرسم.
## الحقول

| حقل | الوصف |
| --- | --- |
| [MM_TEXT](#MM-TEXT) | كل وحدة منطقية تُطابق بكسل جهاز واحد. |
| [MM_LOMETRIC](#MM-LOMETRIC) | كل وحدة منطقية تُطابق 0.1 مليمتر. |
| [MM_HIMETRIC](#MM-HIMETRIC) | كل وحدة منطقية تُطابق 0.01 مليمتر. |
| [MM_LOENGLISH](#MM-LOENGLISH) | كل وحدة منطقية تُطابق 0.01 بوصة. |
| [MM_HIENGLISH](#MM-HIENGLISH) | كل وحدة منطقية تُطابق 0.001 بوصة. |
| [MM_TWIPS](#MM-TWIPS) | كل وحدة منطقية تُطابق واحدًا من عشرين نقطة طابعة (1/1440 بوصة، وتُسمى أيضًا \"twip\"). |
| [MM_ISOTROPIC](#MM-ISOTROPIC) | الوحدات المنطقية تُطابق وحدات عشوائية مع محاور مُقاسة بالتساوي؛ أي أن وحدة واحدة على محور x تساوي وحدة واحدة على محور y. |
| [MM_ANISOTROPIC](#MM-ANISOTROPIC) | الوحدات المنطقية تُطابق وحدات عشوائية مع محاور مُقاسة عشوائيًا. |
### MM_TEXT {#MM-TEXT}
```
public static final int MM_TEXT
```


كل وحدة منطقية تُطابق بكسل جهاز واحد. x الموجبة إلى اليمين؛ y الموجبة إلى الأسفل.

### MM_LOMETRIC {#MM-LOMETRIC}
```
public static final int MM_LOMETRIC
```


كل وحدة منطقية تُطابق 0.1 مليمتر. x الموجبة إلى اليمين؛ y الموجبة إلى الأعلى.

### MM_HIMETRIC {#MM-HIMETRIC}
```
public static final int MM_HIMETRIC
```


كل وحدة منطقية تُقَاس إلى 0.01 مليمتر. المحور x الموجب إلى اليمين؛ والمحور y الموجب إلى الأعلى.

### MM_LOENGLISH {#MM-LOENGLISH}
```
public static final int MM_LOENGLISH
```


كل وحدة منطقية تُقَاس إلى 0.01 بوصة. المحور x الموجب إلى اليمين؛ والمحور y الموجب إلى الأعلى

### MM_HIENGLISH {#MM-HIENGLISH}
```
public static final int MM_HIENGLISH
```


كل وحدة منطقية تُقَاس إلى 0.001 بوصة. المحور x الموجب إلى اليمين؛ والمحور y الموجب إلى الأعلى.

### MM_TWIPS {#MM-TWIPS}
```
public static final int MM_TWIPS
```


كل وحدة منطقية تُقَاس إلى واحد من عشرين من نقطة الطابعة (1/1440 بوصة، وتُسمى أيضاً \\"twip\\"). المحور x الموجب إلى اليمين؛ والمحور y الموجب إلى الأعلى.

### MM_ISOTROPIC {#MM-ISOTROPIC}
```
public static final int MM_ISOTROPIC
```


الوحدات المنطقية تُقَاس إلى وحدات عشوائية مع محاور ذات مقياس متساوٍ؛ أي أن وحدة واحدة على محور x تساوي وحدة واحدة على محور y. يجب استخدام سجلات EMR\\_SETWINDOWEXTEX و EMR\\_SETVIEWPORTEXTEX لتحديد الوحدات واتجاه المحاور. يجب إجراء التعديلات حسب الضرورة لضمان بقاء وحدات x و y بنفس الحجم. على سبيل المثال، عندما يتم تعيين مدى النافذة، يجب تعديل منطقة العرض للحفاظ على تساوي الوحدات.

### MM_ANISOTROPIC {#MM-ANISOTROPIC}
```
public static final int MM_ANISOTROPIC
```


الوحدات المنطقية تُقَاس إلى وحدات عشوائية مع محاور ذات مقياس عشوائي. يجب استخدام سجلات EMR\\_SETWINDOWEXTEX و EMR\\_SETVIEWPORTEXTEX لتحديد الوحدات والاتجاه والقياس.

