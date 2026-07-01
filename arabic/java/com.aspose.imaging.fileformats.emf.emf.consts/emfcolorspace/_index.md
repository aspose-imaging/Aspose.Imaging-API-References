---
title: "EmfColorSpace"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "التعداد ColorSpace يُستخدم لتحديد متى يتم تشغيل وإيقاف إثبات اللون ومتى يتم حذف التحويلات."
type: docs
weight: 15
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.consts/emfcolorspace/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfColorSpace extends System.Enum
```

تعداد ColorSpace يُستخدم لتحديد متى يتم تشغيل أو إيقاف إثبات اللون، ومتى يتم حذف التحويلات.
## الحقول

| حقل | الوصف |
| --- | --- |
| [CS_ENABLE](#CS-ENABLE) | يرسم الألوان إلى نطاق ألوان الجهاز الهدف. |
| [CS_DISABLE](#CS-DISABLE) | يعطل إثبات اللون. |
| [CS_DELETE_TRANSFORM](#CS-DELETE-TRANSFORM) | إذا كان إدارة اللون مفعلة للملف التعريفي الهدف، يعطلها ويحذف التحويل المتسلسل. |
### CS_ENABLE {#CS-ENABLE}
```
public static final int CS_ENABLE
```


يرسم الألوان إلى نطاق ألوان الجهاز الهدف. هذا يُفعّل إثبات اللون. جميع أوامر الرسم اللاحقة لسياق جهاز التشغيل ستُظهر الألوان كما ستظهر على الجهاز الهدف.

### CS_DISABLE {#CS-DISABLE}
```
public static final int CS_DISABLE
```


يعطل إثبات اللون.

### CS_DELETE_TRANSFORM {#CS-DELETE-TRANSFORM}
```
public static final int CS_DELETE_TRANSFORM
```


إذا كان إدارة اللون مفعلة للملف التعريفي الهدف، يعطلها ويحذف التحويل المتسلسل.

