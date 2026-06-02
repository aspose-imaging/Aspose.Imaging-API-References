---
title: "EmfColorSpace"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يُستخدم تعداد ColorSpace لتحديد متى يتم تشغيل وإيقاف إثبات اللون ومتى يتم حذف التحويلات."
type: docs
weight: 15
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.consts/emfcolorspace/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfColorSpace extends System.Enum
```

يتم استخدام تعداد ColorSpace لتحديد متى يتم تشغيل وإيقاف إثبات اللون، ومتى يتم حذف التحويلات.
## الحقول

| حقل | الوصف |
| --- | --- |
| [CS_ENABLE](#CS-ENABLE) | يقوم بربط الألوان بنطاق ألوان الجهاز المستهدف. |
| [CS_DISABLE](#CS-DISABLE) | يعطل إثبات اللون. |
| [CS_DELETE_TRANSFORM](#CS-DELETE-TRANSFORM) | إذا تم تمكين إدارة اللون للملف التعريفي المستهدف، يتم تعطيله وحذف التحويل المتسلسل. |
### CS_ENABLE {#CS-ENABLE}
```
public static final int CS_ENABLE
```


يقوم بربط الألوان بنطاق ألوان الجهاز المستهدف. هذا يمكّن إثبات اللون. جميع أوامر الرسم اللاحقة إلى سياق جهاز التشغيل ستعرض الألوان كما تظهر على الجهاز المستهدف.

### CS_DISABLE {#CS-DISABLE}
```
public static final int CS_DISABLE
```


يعطل إثبات اللون.

### CS_DELETE_TRANSFORM {#CS-DELETE-TRANSFORM}
```
public static final int CS_DELETE_TRANSFORM
```


إذا تم تمكين إدارة اللون للملف التعريفي المستهدف، يتم تعطيله وحذف التحويل المتسلسل.

