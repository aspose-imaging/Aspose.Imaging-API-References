---
title: "Region.IsVisible"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة Region. يختبر ما إذا كانت النقطة المحددة موجودة داخل هذا Region"
type: docs
weight: 100
url: /ar/net/aspose.imaging/region/isvisible/
---
## IsVisible(float, float) {#isvisible_11}

يختبر ما إذا كانت النقطة المحددة موجودة داخل هذا [`Region`](../).

```csharp
public bool IsVisible(float x, float y)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| x | فردي | الإحداثي x للنقطة المراد اختبارها. |
| y | فردي | الإحداثي y للنقطة المراد اختبارها. |

### قيمة الإرجاع

صحيح عندما تكون النقطة المحددة موجودة داخل هذا [`Region`](../)؛ وإلا، خطأ.

### انظر أيضًا

* class [Region](../)
* namespace [Aspose.Imaging](../../region/)
* assembly [Aspose.Imaging](../../../)

---

## IsVisible(PointF) {#isvisible_2}

يختبر ما إذا كانت بنية [`PointF`](../../pointf/) المحددة موجودة داخل هذا [`Region`](../).

```csharp
public bool IsVisible(PointF point)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| point | PointF | بنية [`PointF`](../../pointf/) للاختبار. |

### قيمة الإرجاع

صحيح عندما يكون *point* موجودًا داخل هذا [`Region`](../)؛ وإلا، خطأ.

### انظر أيضًا

* struct [PointF](../../pointf/)
* class [Region](../)
* namespace [Aspose.Imaging](../../region/)
* assembly [Aspose.Imaging](../../../)

---

## IsVisible(float, float, Graphics) {#isvisible_12}

يفحص ما إذا كانت النقطة المحددة موجودة داخل هذا [`Region`](../) عند رسمها باستخدام الـ [`Graphics`](../../graphics/) المحدد.

```csharp
public bool IsVisible(float x, float y, Graphics g)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| x | فردي | الإحداثي x للنقطة المراد اختبارها. |
| y | فردي | الإحداثي y للنقطة المراد اختبارها. |
| g | Graphics | كائن [`Graphics`](../../graphics/) يمثل سياق رسومي. |

### قيمة الإرجاع

صحيح عندما تكون النقطة المحددة موجودة داخل هذا [`Region`](../)؛ وإلا، خطأ.

### انظر أيضًا

* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.Imaging](../../region/)
* assembly [Aspose.Imaging](../../../)

---

## IsVisible(PointF, Graphics) {#isvisible_3}

يفحص ما إذا كانت بنية [`PointF`](../../pointf/) المحددة موجودة داخل هذا [`Region`](../) عند رسمها باستخدام الـ [`Graphics`](../../graphics/) المحدد.

```csharp
public bool IsVisible(PointF point, Graphics g)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| point | PointF | بنية [`PointF`](../../pointf/) للاختبار. |
| g | Graphics | كائن [`Graphics`](../../graphics/) يمثل سياق رسومي. |

### قيمة الإرجاع

صحيح عندما يكون *point* موجودًا داخل هذا [`Region`](../)؛ وإلا، خطأ.

### انظر أيضًا

* struct [PointF](../../pointf/)
* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.Imaging](../../region/)
* assembly [Aspose.Imaging](../../../)

---

## IsVisible(float, float, float, float) {#isvisible_13}

يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذا [`Region`](../).

```csharp
public bool IsVisible(float x, float y, float width, float height)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| x | فردي | الإحداثي السيني للزاوية العلوية اليسرى للمستطيل المراد اختباره. |
| y | فردي | الإحداثي الصادي للزاوية العلوية اليسرى للمستطيل المراد اختباره. |
| العرض | فردي | عرض المستطيل المراد اختباره. |
| الارتفاع | فردي | ارتفاع المستطيل المراد اختباره. |

### قيمة الإرجاع

صحيح عندما يكون أي جزء من المستطيل المحدد موجودًا داخل كائن [`Region`](../) هذا؛ وإلا، خطأ.

### انظر أيضًا

* class [Region](../)
* namespace [Aspose.Imaging](../../region/)
* assembly [Aspose.Imaging](../../../)

---

## IsVisible(RectangleF) {#isvisible_6}

يفحص ما إذا كان أي جزء من بنية [`RectangleF`](../../rectanglef/) المحددة موجودًا داخل هذا [`Region`](../).

```csharp
public bool IsVisible(RectangleF rect)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | RectangleF | بنية [`RectangleF`](../../rectanglef/) للاختبار. |

### قيمة الإرجاع

صحيح عندما يكون أي جزء من *rect* موجودًا داخل هذا [`Region`](../)؛ وإلا، خطأ.

### انظر أيضًا

* struct [RectangleF](../../rectanglef/)
* class [Region](../)
* namespace [Aspose.Imaging](../../region/)
* assembly [Aspose.Imaging](../../../)

---

## IsVisible(float, float, float, float, Graphics) {#isvisible_14}

يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذا [`Region`](../) عند رسمه باستخدام الـ [`Graphics`](../../graphics/) المحدد.

```csharp
public bool IsVisible(float x, float y, float width, float height, Graphics g)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| x | فردي | الإحداثي السيني للزاوية العلوية اليسرى للمستطيل المراد اختباره. |
| y | فردي | الإحداثي الصادي للزاوية العلوية اليسرى للمستطيل المراد اختباره. |
| العرض | فردي | عرض المستطيل المراد اختباره. |
| الارتفاع | فردي | ارتفاع المستطيل المراد اختباره. |
| g | Graphics | كائن [`Graphics`](../../graphics/) يمثل سياق رسومي. |

### قيمة الإرجاع

صحيح عندما يكون أي جزء من المستطيل المحدد موجودًا داخل هذا [`Region`](../)؛ وإلا، خطأ.

### انظر أيضًا

* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.Imaging](../../region/)
* assembly [Aspose.Imaging](../../../)

---

## IsVisible(RectangleF, Graphics) {#isvisible_7}

يفحص ما إذا كان أي جزء من بنية [`RectangleF`](../../rectanglef/) المحددة موجودًا داخل هذا [`Region`](../) عند رسمه باستخدام الـ [`Graphics`](../../graphics/) المحدد.

```csharp
public bool IsVisible(RectangleF rect, Graphics g)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | RectangleF | بنية [`RectangleF`](../../rectanglef/) للاختبار. |
| g | Graphics | كائن [`Graphics`](../../graphics/) يمثل سياق رسومي. |

### قيمة الإرجاع

صحيح عندما يكون *rect* موجودًا داخل هذا [`Region`](../)؛ وإلا، خطأ.

### انظر أيضًا

* struct [RectangleF](../../rectanglef/)
* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.Imaging](../../region/)
* assembly [Aspose.Imaging](../../../)

---

## IsVisible(int, int, Graphics) {#isvisible_8}

يفحص ما إذا كانت النقطة المحددة موجودة داخل كائن [`Region`](../) هذا عند رسمه باستخدام كائن [`Graphics`](../../graphics/) المحدد.

```csharp
public bool IsVisible(int x, int y, Graphics g)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| x | Int32 | الإحداثي x للنقطة المراد اختبارها. |
| y | Int32 | الإحداثي y للنقطة المراد اختبارها. |
| g | Graphics | كائن [`Graphics`](../../graphics/) يمثل سياق رسومي. |

### قيمة الإرجاع

صحيح عندما تكون النقطة المحددة موجودة داخل هذا [`Region`](../)؛ وإلا، خطأ.

### انظر أيضًا

* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.Imaging](../../region/)
* assembly [Aspose.Imaging](../../../)

---

## IsVisible(Point) {#isvisible}

يفحص ما إذا كانت بنية [`Point`](../../point/) المحددة موجودة داخل هذا [`Region`](../).

```csharp
public bool IsVisible(Point point)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| point | Point | بنية [`Point`](../../point/) للاختبار. |

### قيمة الإرجاع

صحيح عندما يكون *point* موجودًا داخل هذا [`Region`](../)؛ وإلا، خطأ.

### انظر أيضًا

* struct [Point](../../point/)
* class [Region](../)
* namespace [Aspose.Imaging](../../region/)
* assembly [Aspose.Imaging](../../../)

---

## IsVisible(Point, Graphics) {#isvisible_1}

يفحص ما إذا كانت بنية [`Point`](../../point/) المحددة موجودة داخل هذا [`Region`](../) عند رسمها باستخدام الـ [`Graphics`](../../graphics/) المحدد.

```csharp
public bool IsVisible(Point point, Graphics g)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| point | Point | بنية [`Point`](../../point/) للاختبار. |
| g | Graphics | كائن [`Graphics`](../../graphics/) يمثل سياق رسومي. |

### قيمة الإرجاع

صحيح عندما يكون *point* موجودًا داخل هذا [`Region`](../)؛ وإلا، خطأ.

### انظر أيضًا

* struct [Point](../../point/)
* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.Imaging](../../region/)
* assembly [Aspose.Imaging](../../../)

---

## IsVisible(int, int, int, int) {#isvisible_9}

يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذا [`Region`](../).

```csharp
public bool IsVisible(int x, int y, int width, int height)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| x | Int32 | الإحداثي السيني للزاوية العلوية اليسرى للمستطيل المراد اختباره. |
| y | Int32 | الإحداثي الصادي للزاوية العلوية اليسرى للمستطيل المراد اختباره. |
| العرض | Int32 | عرض المستطيل المراد اختباره. |
| الارتفاع | Int32 | ارتفاع المستطيل المراد اختباره. |

### قيمة الإرجاع

صحيح عندما يكون أي جزء من المستطيل المحدد موجودًا داخل هذا [`Region`](../)؛ وإلا، خطأ.

### انظر أيضًا

* class [Region](../)
* namespace [Aspose.Imaging](../../region/)
* assembly [Aspose.Imaging](../../../)

---

## IsVisible(Rectangle) {#isvisible_4}

يفحص ما إذا كان أي جزء من بنية [`Rectangle`](../../rectangle/) المحددة موجودًا داخل هذا [`Region`](../).

```csharp
public bool IsVisible(Rectangle rect)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | Rectangle | بنية [`Rectangle`](../../rectangle/) للاختبار. |

### قيمة الإرجاع

هذه الطريقة تُعيد true عندما يكون أي جزء من *rect* داخل هذا [`Region`](../)؛ وإلا، false.

### انظر أيضًا

* struct [Rectangle](../../rectangle/)
* class [Region](../)
* namespace [Aspose.Imaging](../../region/)
* assembly [Aspose.Imaging](../../../)

---

## IsVisible(int, int, int, int, Graphics) {#isvisible_10}

يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذا [`Region`](../) عند رسمه باستخدام الـ [`Graphics`](../../graphics/) المحدد.

```csharp
public bool IsVisible(int x, int y, int width, int height, Graphics g)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| x | Int32 | الإحداثي السيني للزاوية العلوية اليسرى للمستطيل المراد اختباره. |
| y | Int32 | الإحداثي الصادي للزاوية العلوية اليسرى للمستطيل المراد اختباره. |
| العرض | Int32 | عرض المستطيل المراد اختباره. |
| الارتفاع | Int32 | ارتفاع المستطيل المراد اختباره. |
| g | Graphics | كائن [`Graphics`](../../graphics/) يمثل سياق رسومي. |

### قيمة الإرجاع

صحيح عندما يكون أي جزء من المستطيل المحدد موجودًا داخل هذا [`Region`](../)؛ وإلا، خطأ.

### انظر أيضًا

* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.Imaging](../../region/)
* assembly [Aspose.Imaging](../../../)

---

## IsVisible(Rectangle, Graphics) {#isvisible_5}

يفحص ما إذا كان أي جزء من بنية [`Rectangle`](../../rectangle/) المحددة موجودًا داخل هذا [`Region`](../) عند رسمه باستخدام [`Graphics`](../../graphics/) المحدد.

```csharp
public bool IsVisible(Rectangle rect, Graphics g)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | Rectangle | بنية [`Rectangle`](../../rectangle/) للاختبار. |
| g | Graphics | كائن [`Graphics`](../../graphics/) يمثل سياق رسومي. |

### قيمة الإرجاع

true عندما يكون أي جزء من *rect* داخل هذا [`Region`](../)؛ وإلا، false.

### انظر أيضًا

* struct [Rectangle](../../rectangle/)
* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.Imaging](../../region/)
* assembly [Aspose.Imaging](../../../)


