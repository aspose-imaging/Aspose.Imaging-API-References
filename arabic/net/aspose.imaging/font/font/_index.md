---
title: "Font.Font"
second_title: "Aspose.Imaging for .NET API Reference"
description: "منشئ Font. يهيئ Font جديد يستخدم Font الموجود المحدد وتعداد FontStyle."
type: docs
weight: 10
url: /ar/net/aspose.imaging/font/font/
---
## Font(Font, FontStyle) {#constructor}

يهيئ [`Font`](../) جديد يستخدم [`Font`](../) الموجود المحدد وتعداد [`FontStyle`](../../fontstyle/).

```csharp
public Font(Font prototype, FontStyle newStyle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| prototype | Font | الـ[`Font`](../) الموجود الذي سيتم إنشاء [`Font`](../) الجديد منه. |
| newStyle | FontStyle | الـ[`FontStyle`](../../fontstyle/) لتطبيقه على الـ[`Font`](../) الجديد. يمكن دمج قيم متعددة من تعداد [`FontStyle`](../../fontstyle/) باستخدام عامل OR. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *prototype* فارغ. |

### انظر أيضًا

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* namespace [Aspose.Imaging](../../font/)
* assembly [Aspose.Imaging](../../../)

---

## Font(string, float) {#constructor_1}

يهيئ [`Font`](../) جديد باستخدام حجم محدد. يتم تعيين مجموعة الأحرف إلى Default، ووحدة الرسومات إلى Point، ونمط الخط إلى Regular.

```csharp
public Font(string fontName, float emSize)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| fontName | String | تمثيل نصي لاسم الـ[`Font`](../). |
| emSize | فردي | حجم الـem، بالنقاط، للخط الجديد. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* أقل من أو يساوي 0، أو يساوي ما لا نهائي، أو ليس رقمًا صالحًا. |
| ArgumentNullException | *fontName* فارغ. |

### انظر أيضًا

* class [Font](../)
* namespace [Aspose.Imaging](../../font/)
* assembly [Aspose.Imaging](../../../)

---

## Font(string, float, FontStyle) {#constructor_2}

يهيئ [`Font`](../) جديد باستخدام حجم ونمط محددين. يتم تعيين مجموعة الأحرف إلى Default، ووحدة الرسومات إلى Point.

```csharp
public Font(string fontName, float emSize, FontStyle style)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| fontName | String | تمثيل نصي لاسم الـ[`Font`](../). |
| emSize | فردي | حجم الـem، بالنقاط، للخط الجديد. |
| style | FontStyle | الـ[`FontStyle`](../../fontstyle/) للخط الجديد. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* أقل من أو يساوي 0، أو يساوي ما لا نهائي، أو ليس رقمًا صالحًا. |
| ArgumentNullException | *fontName* فارغ. |

### انظر أيضًا

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* namespace [Aspose.Imaging](../../font/)
* assembly [Aspose.Imaging](../../../)

---

## Font(string, float, GraphicsUnit) {#constructor_5}

يهيئ [`Font`](../) جديد باستخدام حجم ووحدة محددين. يتم تعيين مجموعة الأحرف إلى Default، والنمط إلى Regular.

```csharp
public Font(string fontName, float emSize, GraphicsUnit unit)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| fontName | String | تمثيل نصي لاسم الـ[`Font`](../). |
| emSize | فردي | حجم الـem للخط الجديد بالوحدات المحددة بواسطة معامل *unit*. |
| unit | GraphicsUnit | الـ[`GraphicsUnit`](../../graphicsunit/) للخط الجديد. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* أقل من أو يساوي 0، أو يساوي ما لا نهائي، أو ليس رقمًا صالحًا. |
| ArgumentNullException | *fontName* فارغ. |

### انظر أيضًا

* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* namespace [Aspose.Imaging](../../font/)
* assembly [Aspose.Imaging](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit, CharacterSet) {#constructor_4}

يهيئ [`Font`](../) جديد باستخدام حجم، نمط، وحدة، ومجموعة أحرف محددة.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit, 
    CharacterSet characterSet)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| fontName | String | تمثيل نصي لاسم الـ[`Font`](../). |
| emSize | فردي | حجم الـem للخط الجديد بالوحدات المحددة بواسطة معامل *unit*. |
| style | FontStyle | الـ[`FontStyle`](../../fontstyle/) للخط الجديد. |
| unit | GraphicsUnit | الـ[`GraphicsUnit`](../../graphicsunit/) للخط الجديد. |
| characterSet | CharacterSet | مجموعة أحرف لاستخدامها مع هذا الخط. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* أقل من أو يساوي 0، أو يساوي ما لا نهائي، أو ليس رقمًا صالحًا. |
| ArgumentNullException | *fontName* فارغ. |

### انظر أيضًا

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* enum [CharacterSet](../../characterset/)
* class [Font](../)
* namespace [Aspose.Imaging](../../font/)
* assembly [Aspose.Imaging](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit) {#constructor_3}

يهيئ [`Font`](../) جديد باستخدام حجم، نمط، ووحدة محددة.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| fontName | String | تمثيل نصي لاسم الـ[`Font`](../). |
| emSize | فردي | حجم الـem للخط الجديد بالوحدات المحددة بواسطة معامل *unit*. |
| style | FontStyle | الـ[`FontStyle`](../../fontstyle/) للخط الجديد. |
| unit | GraphicsUnit | الـ[`GraphicsUnit`](../../graphicsunit/) للخط الجديد. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* أقل من أو يساوي 0، أو يساوي ما لا نهائي، أو ليس رقمًا صالحًا. |
| ArgumentNullException | *fontName* فارغ. |

### انظر أيضًا

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* namespace [Aspose.Imaging](../../font/)
* assembly [Aspose.Imaging](../../../)


