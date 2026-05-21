---
title: "EmfEmrComment"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تحدد تعداد EmrComment أنواع البيانات التي يمكن لسجل التعليق العام أن يحتويها كما هو موضح في القسم 2.3.3.4."
type: docs
weight: 18
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.consts/emfemrcomment/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfEmrComment extends System.Enum
```

يحدد تعداد EmrComment أنواع البيانات التي يمكن أن يحتويها سجل التعليق العام، كما هو موضح في القسم 2.3.3.4.
## الحقول

| حقل | الوصف |
| --- | --- |
| [EMR_COMMENT_WINDOWS_METAFILE](#EMR-COMMENT-WINDOWS-METAFILE) | يحتوي سجل التعليق هذا على مواصفة صورة في WMF. |
| [EMR_COMMENT_BEGINGROUP](#EMR-COMMENT-BEGINGROUP) | يحدد سجل التعليق هذا بداية مجموعة من سجلات الرسم. |
| [EMR_COMMENT_ENDGROUP](#EMR-COMMENT-ENDGROUP) | يحدد سجل التعليق هذا نهاية مجموعة من سجلات الرسم. |
| [EMR_COMMENT_MULTIFORMATS](#EMR-COMMENT-MULTIFORMATS) | يسمح سجل التعليق هذا بتضمين تعريفات متعددة لصورة في ملف الميتا. |
| [EMR_COMMENT_UNICODE_STRING](#EMR-COMMENT-UNICODE-STRING) | سجل التعليق هذا محجوز ولا يجوز استخدامه في ملف ميتا EMF |
| [EMR_COMMENT_UNICODE_END](#EMR-COMMENT-UNICODE-END) | سجل التعليق هذا محجوز ولا يجوز استخدامه في ملف ميتا EMF |
### EMR_COMMENT_WINDOWS_METAFILE {#EMR-COMMENT-WINDOWS-METAFILE}
```
public static final long EMR_COMMENT_WINDOWS_METAFILE
```


يحتوي سجل التعليق هذا على مواصفة صورة في WMF. راجع [MS-WMF] لمزيد من المعلومات

### EMR_COMMENT_BEGINGROUP {#EMR-COMMENT-BEGINGROUP}
```
public static final long EMR_COMMENT_BEGINGROUP
```


يسجل هذا التعليق بداية مجموعة من سجلات الرسم. يحدد كائنًا داخل ملف تعريف EMF.

### EMR_COMMENT_ENDGROUP {#EMR-COMMENT-ENDGROUP}
```
public static final long EMR_COMMENT_ENDGROUP
```


يسجل هذا التعليق نهاية مجموعة من سجلات الرسم. لكل سجل EMR\_COMMENT\_BEGINGROUP، يجب تضمين سجل EMR\_COMMENT\_ENDGROUP في ملف التعريف، وقد يتم تضمينه بشكل متداخل.

### EMR_COMMENT_MULTIFORMATS {#EMR-COMMENT-MULTIFORMATS}
```
public static final long EMR_COMMENT_MULTIFORMATS
```


يسمح هذا السجل التعليقي بتضمين تعريفات متعددة لصورة في ملف التعريف. باستخدام هذا التعليق، على سبيل المثال، يمكن للتطبيق تضمين نص PostScript مغلف بالإضافة إلى تعريف EMF لصورة.

### EMR_COMMENT_UNICODE_STRING {#EMR-COMMENT-UNICODE-STRING}
```
public static final long EMR_COMMENT_UNICODE_STRING
```


سجل التعليق هذا محجوز ولا يجوز استخدامه في ملف ميتا EMF

### EMR_COMMENT_UNICODE_END {#EMR-COMMENT-UNICODE-END}
```
public static final long EMR_COMMENT_UNICODE_END
```


سجل التعليق هذا محجوز ولا يجوز استخدامه في ملف ميتا EMF

