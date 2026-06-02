---
title: "WmfClipPrecisionFlags"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تحدد ClipPrecision Flags دقة القص التي تحدد كيفية قص الأحرف التي تكون جزئياً خارج منطقة القص."
type: docs
weight: 14
url: /ar/java/com.aspose.imaging.fileformats.wmf.consts/wmfclipprecisionflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfClipPrecisionFlags extends System.Enum
```

تحدد ClipPrecision Flags دقة القص، والتي تحدد كيفية قص الأحرف التي تكون جزئياً خارج منطقة القص. يمكن دمج هذه العلامات لتحديد خيارات متعددة.
## الحقول

| حقل | الوصف |
| --- | --- |
| [Default](#Default) | يحدد أنه يجب استخدام القص الافتراضي. |
| [Character](#Character) | يجب عدم استخدام هذه القيمة. |
| [Stroke](#Stroke) | قد تُرجع هذه القيمة عند تعداد الخطوط الممسوحة، TrueType والخطوط المتجهة. |
| [LhAngles](#LhAngles) | تُستخدم هذه القيمة للتحكم في دوران الخط، كما يلي: - إذا تم تعيينها، يجب أن يُحدد دوران جميع الخطوط وفقاً لاتجاه نظام الإحداثيات؛ أي ما إذا كان الاتجاه أيسرًا أو أيمنًا. |
| [TtAlways](#TtAlways) | يجب عدم استخدام هذه القيمة [34]. |
| [DfaDisable](#DfaDisable) | تحدد هذه القيمة أنه يجب إيقاف ربط الخطوط [35]. |
| [Embedded](#Embedded) | تحدد هذه القيمة أنه يجب استخدام تضمين الخطوط لعرض محتوى المستند؛ الخطوط المضمنة للقراءة فقط. |
### Default {#Default}
```
public static final byte Default
```


يحدد أنه يجب استخدام القص الافتراضي.

### Character {#Character}
```
public static final byte Character
```


يجب عدم استخدام هذه القيمة.

### Stroke {#Stroke}
```
public static final byte Stroke
```


قد تُرجع هذه القيمة عند تعداد الخطوط الممسوحة، TrueType والخطوط المتجهة. [33] (Windows NT 3.1، Windows NT 3.5، Windows NT 3.51، Windows NT 4.0، Windows 2000، وWindows XP: تُرجع هذه القيمة دائمًا عند تعداد الخطوط.)

### LhAngles {#LhAngles}
```
public static final byte LhAngles
```


تُستخدم هذه القيمة للتحكم في دوران الخط، كما يلي: - إذا تم تعيينها، يجب أن يُحدد دوران جميع الخطوط وفقاً لاتجاه نظام الإحداثيات؛ أي ما إذا كان الاتجاه أيسرًا أو أيمنًا. - إذا لم تُعيّن، يجب أن تدور خطوط الجهاز عكس اتجاه عقارب الساعة، لكن يجب أن يُحدد دوران الخطوط الأخرى وفقاً لاتجاه نظام الإحداثيات.

### TtAlways {#TtAlways}
```
public static final byte TtAlways
```


يجب عدم استخدام هذه القيمة [34]. [34] تُهمل هذه القيمة في إصدارات Windows التالية: - Windows Vista - Windows Server 2008 - Windows 7 - Windows Server 2008 R2 - Windows 8 - Windows Server 2012 - Windows 8.1 - Windows Server 2012 R2

### DfaDisable {#DfaDisable}
```
public static final byte DfaDisable
```


تحدد هذه القيمة أنه يجب إيقاف ربط الخطوط [35]. [35] لا تُدعم هذه القيمة في Windows 95، Windows 98، وWindows Millennium Edition. يتم إيقاف ربط الخطوط في Windows 2000، Windows XP، وWindows Server 2003. تُهمل هذه القيمة في إصدارات Windows التالية: - Windows Vista - Windows Server 2008 - Windows 7 - Windows Server 2008 R2 - Windows 8 - Windows Server 2012 - Windows 8.1 - Windows Server 2012 R2

### Embedded {#Embedded}
```
public static final byte Embedded
```


تحدد هذه القيمة أنه يجب استخدام تضمين الخطوط لعرض محتوى المستند؛ الخطوط المضمنة للقراءة فقط.

