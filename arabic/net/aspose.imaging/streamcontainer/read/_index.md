---
title: "StreamContainer.Read"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة StreamContainer. تقرأ البايتات لملء المخزن المؤقت للبايتات المحدد"
type: docs
weight: 110
url: /ar/net/aspose.imaging/streamcontainer/read/
---
## Read(byte[]) {#read}

يقرأ بايتات لملء المخزن المؤقت للبايتات المحدد.

```csharp
public virtual int Read(byte[] bytes)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| bytes | Byte[] | البايتات التي سيتم ملؤها. |

### قيمة الإرجاع

عدد البايتات المقروءة. يمكن أن تكون هذه القيمة أقل من عدد البايتات في المخزن المؤقت إذا لم يكن هناك ما يكفي من البايتات في الدفق.

### انظر أيضًا

* class [StreamContainer](../)
* namespace [Aspose.Imaging](../../streamcontainer/)
* assembly [Aspose.Imaging](../../../)

---

## Read(byte[], int, int) {#read_1}

يقرأ تسلسلًا من البايتات من الدفق الحالي ويقّدم الموضع داخل الدفق بعدد البايتات المقروءة.

```csharp
public virtual int Read(byte[] buffer, int offset, int count)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المخزن المؤقت | Byte[] | مصفوفة من البايتات. عندما تعود هذه الطريقة، يحتوي المخزن المؤقت على مصفوفة البايتات المحددة مع القيم بين *offset* و(*offset* + *count* - 1) المستبدلة بالبايتات المقروءة من المصدر الحالي. |
| الإزاحة | Int32 | الإزاحة الصفرية للبايت في *buffer* التي يبدأ عندها تخزين البيانات المقروءة من الدفق الحالي. |
| count | Int32 | العدد الأقصى للبايتات التي سيتم قراءتها من الدفق الحالي. |

### قيمة الإرجاع

إجمالي عدد البايتات المقروءة إلى المخزن المؤقت. يمكن أن يكون أقل من عدد البايتات المطلوبة إذا لم تتوفر تلك البايتات حاليًا، أو صفر (0) إذا تم الوصول إلى نهاية الدفق.

### انظر أيضًا

* class [StreamContainer](../)
* namespace [Aspose.Imaging](../../streamcontainer/)
* assembly [Aspose.Imaging](../../../)


