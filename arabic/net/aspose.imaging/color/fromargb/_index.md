---
title: "Color.FromArgb"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة Color. تنشئ هيكل Color من قيمة ARGB 32‑بت"
type: docs
weight: 1430
url: /ar/net/aspose.imaging/color/fromargb/
---
## FromArgb(int) {#fromargb}

ينشئ هيكل [`Color`](../) من قيمة ARGB 32‑بت.

```csharp
public static Color FromArgb(int argb)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| argb | Int32 | قيمة تحدد قيمة ARGB 32‑بت. |

### قيمة الإرجاع

هيكل [`Color`](../) الذي تنشئه هذه الطريقة.

### انظر أيضًا

* struct [Color](../)
* namespace [Aspose.Imaging](../../color/)
* assembly [Aspose.Imaging](../../../)

---

## FromArgb(int, int, int, int) {#fromargb_3}

ينشئ بنية [`Color`](../) من القيم الأربعة لمكوّنات ARGB (alpha، red، green، و blue). على الرغم من أن هذه الطريقة تسمح بتمرير قيمة 32‑بت لكل مكوّن، فإن قيمة كل مكوّن محدودة بـ 8‑بت.

```csharp
public static Color FromArgb(int alpha, int red, int green, int blue)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| alpha | Int32 | مكوّن alpha. القيم الصالحة هي من 0 إلى 255. |
| red | Int32 | مكوّن red. القيم الصالحة هي من 0 إلى 255. |
| green | Int32 | مكوّن green. القيم الصالحة هي من 0 إلى 255. |
| blue | Int32 | مكوّن blue. القيم الصالحة هي من 0 إلى 255. |

### قيمة الإرجاع

الـ[`Color`](../) الذي تنشئه هذه الطريقة.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | *alpha*، *red*، *green* أو *blue* أقل من 0 أو أكبر من 255. |

### انظر أيضًا

* struct [Color](../)
* namespace [Aspose.Imaging](../../color/)
* assembly [Aspose.Imaging](../../../)

---

## FromArgb(int, Color) {#fromargb_1}

ينشئ بنية [`Color`](../) من البنية المحددة [`Color`](../)، ولكن مع قيمة alpha الجديدة المحددة. على الرغم من أن هذه الطريقة تسمح بتمرير قيمة 32‑بت لقيمة alpha، فإن القيمة محدودة بـ 8‑بت.

```csharp
public static Color FromArgb(int alpha, Color baseColor)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| alpha | Int32 | قيمة alpha للـ [`Color`](../) الجديد. القيم الصالحة هي من 0 إلى 255. |
| baseColor | Color | الـ [`Color`](../) الذي يُستخدم لإنشاء الـ [`Color`](../) الجديد. |

### قيمة الإرجاع

الـ[`Color`](../) الذي تنشئه هذه الطريقة.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | *alpha* أقل من 0 أو أكبر من 255. |

### انظر أيضًا

* struct [Color](../)
* namespace [Aspose.Imaging](../../color/)
* assembly [Aspose.Imaging](../../../)

---

## FromArgb(int, int, int) {#fromargb_2}

ينشئ بنية [`Color`](../) من قيم الألوان 8‑بت المحددة (red، green، و blue). قيمة alpha هي ضمنيًا 255 (معتمة تمامًا). على الرغم من أن هذه الطريقة تسمح بتمرير قيمة 32‑بت لكل مكوّن لون، فإن قيمة كل مكوّن محدودة بـ 8‑بت.

```csharp
public static Color FromArgb(int red, int green, int blue)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| red | Int32 | قيمة مكوّن red للـ [`Color`](../) الجديد. القيم الصالحة هي من 0 إلى 255. |
| green | Int32 | قيمة مكوّن green للـ [`Color`](../) الجديد. القيم الصالحة هي من 0 إلى 255. |
| blue | Int32 | قيمة مكوّن blue للـ [`Color`](../) الجديد. القيم الصالحة هي من 0 إلى 255. |

### قيمة الإرجاع

الـ[`Color`](../) الذي تنشئه هذه الطريقة.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | *red*، *green* أو *blue* أقل من 0 أو أكبر من 255. |

### انظر أيضًا

* struct [Color](../)
* namespace [Aspose.Imaging](../../color/)
* assembly [Aspose.Imaging](../../../)


