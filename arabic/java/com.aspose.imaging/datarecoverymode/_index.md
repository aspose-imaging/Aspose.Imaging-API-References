---
title: "DataRecoveryMode"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "وضع استعادة البيانات."
type: docs
weight: 38
url: /ar/java/com.aspose.imaging/datarecoverymode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class DataRecoveryMode extends System.Enum
```

وضع استعادة البيانات.
## الحقول

| حقل | الوصف |
| --- | --- |
| [None](#None) | لا يُفترض استعادة البيانات. |
| [ConsistentRecover](#ConsistentRecover) | تحاول وضعية الاستعادة المتسقة استعادة جميع البيانات طالما أن الفساد لا يكسر تنسيق الملف وتسمح بالمعالجة اللاحقة الصحيحة. |
| [MaximalRecover](#MaximalRecover) | تستعيد وضعية الاستعادة القصوى جميع البيانات حتى إذا كان تنسيق الملف يحتوي على بنية تالفة وقد تؤدي المعالجة اللاحقة إلى تأثيرات غير مقصودة. |
### None {#None}
```
public static final int None
```


لا يُفترض استعادة البيانات. كلما كان تنسيق الملف يحتوي على بعض البيانات الفاسدة يتم إلقاء الاستثناء المناسب.

### ConsistentRecover {#ConsistentRecover}
```
public static final int ConsistentRecover
```


تحاول وضعية الاستعادة المتسقة استعادة جميع البيانات طالما أن الفساد لا يكسر تنسيق الملف وتسمح بالمعالجة اللاحقة الصحيحة.

### MaximalRecover {#MaximalRecover}
```
public static final int MaximalRecover
```


تستعيد وضعية الاستعادة القصوى جميع البيانات حتى إذا كان تنسيق الملف يحتوي على بنية تالفة وقد تؤدي المعالجة اللاحقة إلى تأثيرات غير مقصودة.

