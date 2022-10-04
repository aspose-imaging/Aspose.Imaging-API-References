---
title: Read
second_title: Aspose.Imaging لمرجع NET API
description: يقرأ البايت لملء المخزن المؤقت للبايتات المحدد.
type: docs
weight: 110
url: /ar/net/aspose.imaging/splitstreamcontainer/read/
---
## Read(byte[]) {#read}

يقرأ البايت لملء المخزن المؤقت للبايتات المحدد.

```csharp
public override int Read(byte[] bytes)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| bytes | Byte[] | بايت لملء. |

### قيمة الإرجاع

عدد البايت المقروء. يمكن أن تكون هذه القيمة أقل من عدد البايت في المخزن المؤقت في حالة عدم وجود وحدات بايت كافية في الدفق.

### أنظر أيضا

* class [SplitStreamContainer](../../splitstreamcontainer)
* مساحة الاسم [Aspose.Imaging](../../splitstreamcontainer)
* المجسم [Aspose.Imaging](../../../)

---

## Read(byte[], int, int) {#read_1}

يقرأ تسلسل البايت من الدفق الحالي ويقدم الموضع داخل الدفق بعدد البايت المقروء.

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| buffer | Byte[] | مصفوفة من البايت. عند إرجاع هذا الأسلوب ، يحتوي المخزن المؤقت على صفيف البايت المحدد مع القيم الواقعة بين*offset* و (*offset* +*count* - 1) استبداله بالبايتات المقروءة من المصدر الحالي. |
| offset | Int32 | إزاحة البايت الصفري في*buffer* حيث يتم بدء تخزين البيانات المقروءة من الدفق الحالي. |
| count | Int32 | أقصى عدد للبايتات المراد قراءتها من الدفق الحالي. |

### قيمة الإرجاع

إجمالي عدد وحدات البايت المقروءة في المخزن المؤقت. يمكن أن يكون هذا أقل من عدد البايت المطلوب إذا كان هذا العدد الكبير من البايت غير متوفر حاليًا ، أو صفرًا (0) إذا تم الوصول إلى نهاية الدفق.

### أنظر أيضا

* class [SplitStreamContainer](../../splitstreamcontainer)
* مساحة الاسم [Aspose.Imaging](../../splitstreamcontainer)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->