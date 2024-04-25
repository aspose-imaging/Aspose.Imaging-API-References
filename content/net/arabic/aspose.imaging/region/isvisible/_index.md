---
title: IsVisible
second_title: Aspose.Imaging لمرجع NET API
description: يختبر ما إذا كانت النقطة المحددة متضمنة في هذاRegionaspose.imaging/region .
type: docs
weight: 90
url: /ar/aspose.imaging/region/isvisible/
---
## IsVisible(float, float) {#isvisible_11}

يختبر ما إذا كانت النقطة المحددة متضمنة في هذا[`Region`](../../region) .

```csharp
public bool IsVisible(float x, float y)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| x | Single | إحداثي x للنقطة المراد اختبارها. |
| y | Single | إحداثي ص للنقطة المراد اختبارها. |

### قيمة الإرجاع

صحيح عندما يتم احتواء النقطة المحددة في هذا[`Region`](../../region) ؛ وإلا ، خطأ .

### أنظر أيضا

* class [Region](../../region)
* مساحة الاسم [Aspose.Imaging](../../region)
* المجسم [Aspose.Imaging](../../../)

---

## IsVisible(PointF) {#isvisible_2}

تختبر ما إذا كان الملف المحدد[`PointF`](../../pointf) هيكل وارد في هذا[`Region`](../../region) .

```csharp
public bool IsVisible(PointF point)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| point | PointF | ال[`PointF`](../../pointf) هيكل للاختبار. |

### قيمة الإرجاع

صحيح عندما*point* وارد في هذا[`Region`](../../region) ؛ وإلا ، خطأ .

### أنظر أيضا

* struct [PointF](../../pointf)
* class [Region](../../region)
* مساحة الاسم [Aspose.Imaging](../../region)
* المجسم [Aspose.Imaging](../../../)

---

## IsVisible(float, float, Graphics) {#isvisible_12}

يختبر ما إذا كانت النقطة المحددة متضمنة في هذا[`Region`](../../region)عند رسمها باستخدام المحدد[`Graphics`](../../graphics) .

```csharp
public bool IsVisible(float x, float y, Graphics g)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| x | Single | إحداثي x للنقطة المراد اختبارها. |
| y | Single | إحداثي ص للنقطة المراد اختبارها. |
| g | Graphics | أ[`Graphics`](../../graphics) التي تمثل سياق رسومي. |

### قيمة الإرجاع

صحيح عندما يتم احتواء النقطة المحددة في هذا[`Region`](../../region) ؛ وإلا ، خطأ .

### أنظر أيضا

* class [Graphics](../../graphics)
* class [Region](../../region)
* مساحة الاسم [Aspose.Imaging](../../region)
* المجسم [Aspose.Imaging](../../../)

---

## IsVisible(PointF, Graphics) {#isvisible_3}

تختبر ما إذا كان الملف المحدد[`PointF`](../../pointf) هيكل وارد في هذا[`Region`](../../region)عند رسمها باستخدام المحدد[`Graphics`](../../graphics) .

```csharp
public bool IsVisible(PointF point, Graphics g)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| point | PointF | ال[`PointF`](../../pointf) هيكل للاختبار. |
| g | Graphics | أ[`Graphics`](../../graphics) التي تمثل سياق رسومي. |

### قيمة الإرجاع

صحيح عندما*point* وارد في هذا[`Region`](../../region) ؛ وإلا ، خطأ .

### أنظر أيضا

* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* class [Region](../../region)
* مساحة الاسم [Aspose.Imaging](../../region)
* المجسم [Aspose.Imaging](../../../)

---

## IsVisible(float, float, float, float) {#isvisible_13}

يختبر ما إذا كان أي جزء من المستطيل المحدد متضمنًا في هذا[`Region`](../../region) .

```csharp
public bool IsVisible(float x, float y, float width, float height)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| x | Single | إحداثي x للركن الأيسر العلوي للمستطيل المراد اختباره. |
| y | Single | إحداثي ص للركن الأيسر العلوي للمستطيل المراد اختباره. |
| width | Single | عرض المستطيل المراد اختباره. |
| height | Single | ارتفاع المستطيل المراد اختباره. |

### قيمة الإرجاع

يكون صحيحًا عندما يتم احتواء أي جزء من المستطيل المحدد داخل هذا[`Region`](../../region) هدف؛ وإلا ، خطأ .

### أنظر أيضا

* class [Region](../../region)
* مساحة الاسم [Aspose.Imaging](../../region)
* المجسم [Aspose.Imaging](../../../)

---

## IsVisible(RectangleF) {#isvisible_6}

اختبارات ما إذا كان أي جزء من المحدد[`RectangleF`](../../rectanglef) هيكل وارد في هذا[`Region`](../../region) .

```csharp
public bool IsVisible(RectangleF rect)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| rect | RectangleF | ال[`RectangleF`](../../rectanglef) هيكل للاختبار. |

### قيمة الإرجاع

صحيح عند أي جزء من*rect* وارد في هذا[`Region`](../../region) ؛ وإلا ، خطأ .

### أنظر أيضا

* struct [RectangleF](../../rectanglef)
* class [Region](../../region)
* مساحة الاسم [Aspose.Imaging](../../region)
* المجسم [Aspose.Imaging](../../../)

---

## IsVisible(float, float, float, float, Graphics) {#isvisible_14}

يختبر ما إذا كان أي جزء من المستطيل المحدد متضمنًا في هذا[`Region`](../../region)عند رسمها باستخدام المحدد[`Graphics`](../../graphics) .

```csharp
public bool IsVisible(float x, float y, float width, float height, Graphics g)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| x | Single | إحداثي x للركن الأيسر العلوي للمستطيل المراد اختباره. |
| y | Single | إحداثي ص للركن الأيسر العلوي للمستطيل المراد اختباره. |
| width | Single | عرض المستطيل المراد اختباره. |
| height | Single | ارتفاع المستطيل المراد اختباره. |
| g | Graphics | أ[`Graphics`](../../graphics) التي تمثل سياق رسومي. |

### قيمة الإرجاع

يكون صحيحًا عندما يتم احتواء أي جزء من المستطيل المحدد داخل هذا[`Region`](../../region) ؛ وإلا ، خطأ .

### أنظر أيضا

* class [Graphics](../../graphics)
* class [Region](../../region)
* مساحة الاسم [Aspose.Imaging](../../region)
* المجسم [Aspose.Imaging](../../../)

---

## IsVisible(RectangleF, Graphics) {#isvisible_7}

اختبارات ما إذا كان أي جزء من المحدد[`RectangleF`](../../rectanglef) هيكل وارد في هذا[`Region`](../../region)عند رسمها باستخدام المحدد[`Graphics`](../../graphics) .

```csharp
public bool IsVisible(RectangleF rect, Graphics g)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| rect | RectangleF | ال[`RectangleF`](../../rectanglef) هيكل للاختبار. |
| g | Graphics | أ[`Graphics`](../../graphics) التي تمثل سياق رسومي. |

### قيمة الإرجاع

صحيح عندما*rect* وارد في هذا[`Region`](../../region) ؛ وإلا ، خطأ .

### أنظر أيضا

* struct [RectangleF](../../rectanglef)
* class [Graphics](../../graphics)
* class [Region](../../region)
* مساحة الاسم [Aspose.Imaging](../../region)
* المجسم [Aspose.Imaging](../../../)

---

## IsVisible(int, int, Graphics) {#isvisible_8}

يختبر ما إذا كانت النقطة المحددة متضمنة في هذا[`Region`](../../region) الكائن عند رسمه باستخدام المحدد[`Graphics`](../../graphics) الكائن .

```csharp
public bool IsVisible(int x, int y, Graphics g)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| x | Int32 | إحداثي x للنقطة المراد اختبارها. |
| y | Int32 | إحداثي ص للنقطة المراد اختبارها. |
| g | Graphics | أ[`Graphics`](../../graphics) التي تمثل سياق رسومي. |

### قيمة الإرجاع

صحيح عندما يتم احتواء النقطة المحددة داخل هذا[`Region`](../../region) ؛ وإلا ، خطأ .

### أنظر أيضا

* class [Graphics](../../graphics)
* class [Region](../../region)
* مساحة الاسم [Aspose.Imaging](../../region)
* المجسم [Aspose.Imaging](../../../)

---

## IsVisible(Point) {#isvisible}

تختبر ما إذا كان الملف المحدد[`Point`](../../point) هيكل وارد في هذا[`Region`](../../region) .

```csharp
public bool IsVisible(Point point)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| point | Point | ال[`Point`](../../point) هيكل للاختبار. |

### قيمة الإرجاع

صحيح عندما*point* وارد في هذا[`Region`](../../region) ؛ وإلا ، خطأ .

### أنظر أيضا

* struct [Point](../../point)
* class [Region](../../region)
* مساحة الاسم [Aspose.Imaging](../../region)
* المجسم [Aspose.Imaging](../../../)

---

## IsVisible(Point, Graphics) {#isvisible_1}

تختبر ما إذا كان الملف المحدد[`Point`](../../point) هيكل وارد في هذا[`Region`](../../region)عند رسمها باستخدام المحدد[`Graphics`](../../graphics) .

```csharp
public bool IsVisible(Point point, Graphics g)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| point | Point | ال[`Point`](../../point) هيكل للاختبار. |
| g | Graphics | أ[`Graphics`](../../graphics) التي تمثل سياق رسومي. |

### قيمة الإرجاع

صحيح عندما*point* وارد في هذا[`Region`](../../region) ؛ وإلا ، خطأ .

### أنظر أيضا

* struct [Point](../../point)
* class [Graphics](../../graphics)
* class [Region](../../region)
* مساحة الاسم [Aspose.Imaging](../../region)
* المجسم [Aspose.Imaging](../../../)

---

## IsVisible(int, int, int, int) {#isvisible_9}

يختبر ما إذا كان أي جزء من المستطيل المحدد متضمنًا في هذا[`Region`](../../region) .

```csharp
public bool IsVisible(int x, int y, int width, int height)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| x | Int32 | إحداثي x للركن الأيسر العلوي للمستطيل المراد اختباره. |
| y | Int32 | إحداثي ص للركن الأيسر العلوي للمستطيل المراد اختباره. |
| width | Int32 | عرض المستطيل المراد اختباره. |
| height | Int32 | ارتفاع المستطيل المراد اختباره. |

### قيمة الإرجاع

يكون صحيحًا عندما يتم احتواء أي جزء من المستطيل المحدد داخل هذا[`Region`](../../region) ؛ وإلا ، خطأ .

### أنظر أيضا

* class [Region](../../region)
* مساحة الاسم [Aspose.Imaging](../../region)
* المجسم [Aspose.Imaging](../../../)

---

## IsVisible(Rectangle) {#isvisible_4}

اختبارات ما إذا كان أي جزء من المحدد[`Rectangle`](../../rectangle) هيكل وارد في هذا[`Region`](../../region) .

```csharp
public bool IsVisible(Rectangle rect)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| rect | Rectangle | ال[`Rectangle`](../../rectangle) هيكل للاختبار. |

### قيمة الإرجاع

هذه الطريقة ترجع صحيحًا عند أي جزء من*rect* وارد في هذا[`Region`](../../region) ؛ وإلا ، خطأ .

### أنظر أيضا

* struct [Rectangle](../../rectangle)
* class [Region](../../region)
* مساحة الاسم [Aspose.Imaging](../../region)
* المجسم [Aspose.Imaging](../../../)

---

## IsVisible(int, int, int, int, Graphics) {#isvisible_10}

يختبر ما إذا كان أي جزء من المستطيل المحدد متضمنًا في هذا[`Region`](../../region)عند رسمها باستخدام المحدد[`Graphics`](../../graphics) .

```csharp
public bool IsVisible(int x, int y, int width, int height, Graphics g)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| x | Int32 | إحداثي x للركن الأيسر العلوي للمستطيل المراد اختباره. |
| y | Int32 | إحداثي ص للركن الأيسر العلوي للمستطيل المراد اختباره. |
| width | Int32 | عرض المستطيل المراد اختباره. |
| height | Int32 | ارتفاع المستطيل المراد اختباره. |
| g | Graphics | أ[`Graphics`](../../graphics) التي تمثل سياق رسومي. |

### قيمة الإرجاع

يكون صحيحًا عندما يتم احتواء أي جزء من المستطيل المحدد داخل هذا[`Region`](../../region) ؛ وإلا ، خطأ .

### أنظر أيضا

* class [Graphics](../../graphics)
* class [Region](../../region)
* مساحة الاسم [Aspose.Imaging](../../region)
* المجسم [Aspose.Imaging](../../../)

---

## IsVisible(Rectangle, Graphics) {#isvisible_5}

اختبارات ما إذا كان أي جزء من المحدد[`Rectangle`](../../rectangle) هيكل وارد في هذا[`Region`](../../region)عند رسمها باستخدام المحدد[`Graphics`](../../graphics) .

```csharp
public bool IsVisible(Rectangle rect, Graphics g)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| rect | Rectangle | ال[`Rectangle`](../../rectangle) هيكل للاختبار. |
| g | Graphics | أ[`Graphics`](../../graphics) التي تمثل سياق رسومي. |

### قيمة الإرجاع

صحيح عندما يكون أي جزء من ملف*rect* وارد في هذا[`Region`](../../region) ؛ وإلا ، خطأ .

### أنظر أيضا

* struct [Rectangle](../../rectangle)
* class [Graphics](../../graphics)
* class [Region](../../region)
* مساحة الاسم [Aspose.Imaging](../../region)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
