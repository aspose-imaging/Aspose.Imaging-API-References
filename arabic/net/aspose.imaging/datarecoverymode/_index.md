---
title: "تعداد DataRecoveryMode"
second_title: "Aspose.Imaging for .NET API Reference"
description: "تعداد Aspose.Imaging.DataRecoveryMode. وضع استعادة البيانات"
type: docs
weight: 810
url: /ar/net/aspose.imaging/datarecoverymode/
---
## DataRecoveryMode enumeration

وضع استعادة البيانات.

```csharp
public enum DataRecoveryMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| None | `0` | لا يُفترض استعادة البيانات. كلما كان تنسيق الملف يحتوي على بيانات تالفة يتم رمي الاستثناء المناسب. |
| ConsistentRecover | `1` | وضع الاستعادة المتسق يحاول استعادة جميع البيانات طالما أن الفساد لا يكسر تنسيق الملف ويسمح بالمعالجة اللاحقة الصحيحة. |
| MaximalRecover | `2` | وضع الاستعادة القصوى يستعيد جميع البيانات حتى إذا كان تنسيق الملف يحتوي على بنية تالفة وقد تؤدي المعالجة اللاحقة إلى تأثيرات غير مقصودة. |

### انظر أيضًا

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


