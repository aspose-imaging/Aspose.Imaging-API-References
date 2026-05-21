---
title: "GraphicsPath.Warp"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة GraphicsPath. تُطبق تحويل تشويه يُعرّف بواسطة مستطيل ومُعَدل إلى هذا GraphicsPath"
type: docs
weight: 200
url: /ar/net/aspose.imaging/graphicspath/warp/
---
## Warp(PointF[], RectangleF) {#warp}

تُطبق تحويل تشويه، يُعرّف بواسطة مستطيل ومُعَدل، على هذا [`GraphicsPath`](../).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| destPoints | PointF[] | مصفوفة من هياكل [`PointF`](../../pointf/) التي تُعرّف مُعَدلًا يُحوَّل إليه المستطيل المُعرّف بـ *srcRect*. يمكن للمصفوفة أن تحتوي على ثلاثة أو أربعة عناصر. إذا احتوت المصفوفة على ثلاثة عناصر، فإن الزاوية السفلية اليمنى للمُعَدل تُستنتج من النقاط الثلاث الأولى. |
| srcRect | RectangleF | `[`RectangleF`](../../rectanglef/) التي تمثل المستطيل الذي يتم تحويله إلى المُعَدل المُعرّف بـ *destPoints*. |

### انظر أيضًا

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [GraphicsPath](../)
* namespace [Aspose.Imaging](../../graphicspath/)
* assembly [Aspose.Imaging](../../../)

---

## Warp(PointF[], RectangleF, Matrix) {#warp_1}

تُطبق تحويل تشويه، يُعرّف بواسطة مستطيل ومُعَدل، على هذا [`GraphicsPath`](../).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| destPoints | PointF[] | مصفوفة من هياكل [`PointF`](../../pointf/) التي تُعرّف مُعَدلًا يُحوَّل إليه المستطيل المُعرّف بـ *srcRect*. يمكن للمصفوفة أن تحتوي على ثلاثة أو أربعة عناصر. إذا احتوت المصفوفة على ثلاثة عناصر، فإن الزاوية السفلية اليمنى للمُعَدل تُستنتج من النقاط الثلاث الأولى. |
| srcRect | RectangleF | `[`RectangleF`](../../rectanglef/) التي تمثل المستطيل الذي يتم تحويله إلى المُعَدل المُعرّف بـ *destPoints*. |
| matrix | Matrix | `[`Matrix`](../../matrix/) التي تُحدد تحويلًا هندسيًا لتطبيقه على المسار. |

### انظر أيضًا

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.Imaging](../../graphicspath/)
* assembly [Aspose.Imaging](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode) {#warp_2}

تُطبق تحويل تشويه، يُعرّف بواسطة مستطيل ومُعَدل، على هذا [`GraphicsPath`](../).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| destPoints | PointF[] | مصفوفة من هياكل [`PointF`](../../pointf/) التي تُعرّف مُعَدلًا يُحوَّل إليه المستطيل المُعرّف بـ *srcRect*. يمكن للمصفوفة أن تحتوي على ثلاثة أو أربعة عناصر. إذا احتوت المصفوفة على ثلاثة عناصر، فإن الزاوية السفلية اليمنى للمُعَدل تُستنتج من النقاط الثلاث الأولى. |
| srcRect | RectangleF | `[`RectangleF`](../../rectanglef/) التي تمثل المستطيل الذي يتم تحويله إلى المُعَدل المُعرّف بـ *destPoints*. |
| matrix | Matrix | `[`Matrix`](../../matrix/) التي تُحدد تحويلًا هندسيًا لتطبيقه على المسار. |
| warpMode | WarpMode | تعداد [`WarpMode`](../../warpmode/) الذي يُحدد ما إذا كانت عملية التشويه هذه تستخدم وضع المنظور أو الوضع الثنائي الخط. |

### انظر أيضًا

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* namespace [Aspose.Imaging](../../graphicspath/)
* assembly [Aspose.Imaging](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode, float) {#warp_3}

تُطبق تحويل تشويه، يُعرّف بواسطة مستطيل ومُعَدل، على هذا [`GraphicsPath`](../).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode, 
    float flatness)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| destPoints | PointF[] | مصفوفة من هياكل [`PointF`](../../pointf/) التي تُعرّف مُعَدلًا يُحوَّل إليه المستطيل المُعرّف بـ *srcRect*. يمكن للمصفوفة أن تحتوي على ثلاثة أو أربعة عناصر. إذا احتوت المصفوفة على ثلاثة عناصر، فإن الزاوية السفلية اليمنى للمُعَدل تُستنتج من النقاط الثلاث الأولى. |
| srcRect | RectangleF | `[`RectangleF`](../../rectanglef/) التي تمثل المستطيل الذي يتم تحويله إلى المُعَدل المُعرّف بـ *destPoints*. |
| matrix | Matrix | `[`Matrix`](../../matrix/) التي تُحدد تحويلًا هندسيًا لتطبيقه على المسار. |
| warpMode | WarpMode | تعداد [`WarpMode`](../../warpmode/) الذي يُحدد ما إذا كانت عملية التشويه هذه تستخدم وضع المنظور أو الوضع الثنائي الخط. |
| flatness | Single | قيمة من 0 إلى 1 تُحدد مدى تسطح المسار الناتج. لمزيد من المعلومات، راجع طرق [`Flatten`](../flatten/). |

### انظر أيضًا

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* namespace [Aspose.Imaging](../../graphicspath/)
* assembly [Aspose.Imaging](../../../)


