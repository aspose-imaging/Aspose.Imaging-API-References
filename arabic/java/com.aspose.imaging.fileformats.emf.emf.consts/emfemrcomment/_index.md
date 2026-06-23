---
title: "EmfEmrComment"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تحدد تعداد EmrComment أنواع البيانات التي يمكن أن يحتويها سجل التعليق العام كما هو موضح في القسم 2.3.3.4."
type: docs
weight: 18
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.consts/emfemrcomment/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfEmrComment extends System.Enum
```

تعداد EmrComment يحدد أنواع البيانات التي يمكن أن يحتويها سجل التعليق العام، كما هو موضح في القسم 2.3.3.4.
## الحقول

| حقل | الوصف |
| --- | --- |
| [EMR_COMMENT_WINDOWS_METAFILE](#EMR-COMMENT-WINDOWS-METAFILE) | يحتوي سجل التعليق هذا على مواصفة لصورة في WMF. |
| [EMR_COMMENT_BEGINGROUP](#EMR-COMMENT-BEGINGROUP) | يحدد سجل التعليق هذا بداية مجموعة من سجلات الرسم. |
| [EMR_COMMENT_ENDGROUP](#EMR-COMMENT-ENDGROUP) | يحدد سجل التعليق هذا نهاية مجموعة من سجلات الرسم. |
| [EMR_COMMENT_MULTIFORMATS](#EMR-COMMENT-MULTIFORMATS) | يسمح سجل التعليق هذا بتضمين تعريفات متعددة لصورة في ملف الميتا. |
| [EMR_COMMENT_UNICODE_STRING](#EMR-COMMENT-UNICODE-STRING) | سجل التعليق هذا محجوز ولا يجوز استخدامه في ملف ميتا EMF. |
| [EMR_COMMENT_UNICODE_END](#EMR-COMMENT-UNICODE-END) | سجل التعليق هذا محجوز ولا يجوز استخدامه في ملف ميتا EMF. |
### EMR_COMMENT_WINDOWS_METAFILE {#EMR-COMMENT-WINDOWS-METAFILE}
```
public static final long EMR_COMMENT_WINDOWS_METAFILE
```


يحتوي سجل التعليق هذا على مواصفة لصورة في WMF. راجع [MS-WMF] لمزيد من المعلومات

### EMR_COMMENT_BEGINGROUP {#EMR-COMMENT-BEGINGROUP}
```
public static final long EMR_COMMENT_BEGINGROUP
```


يحدد سجل التعليق هذا بداية مجموعة من سجلات الرسم. كما يحدد كائنًا داخل ملف ميتا EMF.

### EMR_COMMENT_ENDGROUP {#EMR-COMMENT-ENDGROUP}
```
public static final long EMR_COMMENT_ENDGROUP
```


يحدد سجل التعليق هذا نهاية مجموعة من سجلات الرسم. يجب تضمين سجل EMR\_COMMENT\_ENDGROUP في ملف الميتا لكل سجل EMR\_COMMENT\_BEGINGROUP، وقد تكون هذه السجلات متداخلة.

### EMR_COMMENT_MULTIFORMATS {#EMR-COMMENT-MULTIFORMATS}
```
public static final long EMR_COMMENT_MULTIFORMATS
```


يسمح سجل التعليق هذا بتضمين تعريفات متعددة لصورة في ملف الميتا. باستخدام هذا التعليق، على سبيل المثال، يمكن لتطبيق أن يضمّن نص PostScript مغلق بالإضافة إلى تعريف EMF لصورة.

### EMR_COMMENT_UNICODE_STRING {#EMR-COMMENT-UNICODE-STRING}
```
public static final long EMR_COMMENT_UNICODE_STRING
```


سجل التعليق هذا محجوز ولا يجوز استخدامه في ملف ميتا EMF.

### EMR_COMMENT_UNICODE_END {#EMR-COMMENT-UNICODE-END}
```
public static final long EMR_COMMENT_UNICODE_END
```


سجل التعليق هذا محجوز ولا يجوز استخدامه في ملف ميتا EMF.

