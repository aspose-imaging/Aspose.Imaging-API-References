---
title: Font
second_title: Aspose.Imaging لمرجع NET API
description: يقوم بتهيئة ملفFontaspose.imaging/font يستخدم المحدد الموجودFontaspose.imaging/font وFontStyleaspose.imaging/fontstyle التعداد .
type: docs
weight: 10
url: /ar/aspose.imaging/font/font/
---
## Font(Font, FontStyle) {#constructor}

يقوم بتهيئة ملف[`Font`](../../font) يستخدم المحدد الموجود[`Font`](../../font) و[`FontStyle`](../../fontstyle) التعداد .

```csharp
public Font(Font prototype, FontStyle newStyle)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| prototype | Font | الموجود[`Font`](../../font) التي يتم إنشاء الجديد منها[`Font`](../../font). |
| newStyle | FontStyle | ال[`FontStyle`](../../fontstyle)للتقدم إلى الجديد[`Font`](../../font) . قيم متعددة لـ[`FontStyle`](../../fontstyle) يمكن دمج التعداد مع عامل التشغيل OR. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *prototype* باطل. |

### أنظر أيضا

* enum [FontStyle](../../fontstyle)
* class [Font](../../font)
* مساحة الاسم [Aspose.Imaging](../../font)
* المجسم [Aspose.Imaging](../../../)

---

## Font(string, float) {#constructor_1}

يقوم بتهيئة ملف[`Font`](../../font) باستخدام حجم محدد. تم تعيين مجموعة الأحرف علىDefault ، وحدة الرسوماتPoint ، نمط الخط إلىRegular .

```csharp
public Font(string fontName, float emSize)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| fontName | String | تمثيل سلسلة من[`Font`](../../font) اسم. |
| emSize | Single | حجم em ، بالنقاط ، للخط الجديد. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* أصغر من أو يساوي 0 ، يتم تقييمه إلى ما لا نهاية أو أنه ليس رقمًا صالحًا. |
| ArgumentNullException | *fontName* باطل. |

### أنظر أيضا

* class [Font](../../font)
* مساحة الاسم [Aspose.Imaging](../../font)
* المجسم [Aspose.Imaging](../../../)

---

## Font(string, float, FontStyle) {#constructor_2}

يقوم بتهيئة ملف[`Font`](../../font) باستخدام حجم وأسلوب محددين. تم تعيين مجموعة الأحرف علىDefault ، وحدة الرسوماتPoint .

```csharp
public Font(string fontName, float emSize, FontStyle style)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| fontName | String | تمثيل سلسلة من[`Font`](../../font) اسم. |
| emSize | Single | حجم em ، بالنقاط ، للخط الجديد. |
| style | FontStyle | ال[`FontStyle`](../../fontstyle) من الخط الجديد. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* أصغر من أو يساوي 0 ، يتم تقييمه إلى ما لا نهاية أو أنه ليس رقمًا صالحًا. |
| ArgumentNullException | *fontName* باطل. |

### أنظر أيضا

* enum [FontStyle](../../fontstyle)
* class [Font](../../font)
* مساحة الاسم [Aspose.Imaging](../../font)
* المجسم [Aspose.Imaging](../../../)

---

## Font(string, float, GraphicsUnit) {#constructor_5}

يقوم بتهيئة ملف[`Font`](../../font) باستخدام حجم ووحدة محددين. تم تعيين مجموعة الأحرف علىDefault ، تم تعيين النمط علىRegular .

```csharp
public Font(string fontName, float emSize, GraphicsUnit unit)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| fontName | String | تمثيل سلسلة من[`Font`](../../font) اسم. |
| emSize | Single | حجم em للخط الجديد في الوحدات المحددة بواسطة*unit* معامل. |
| unit | GraphicsUnit | ال[`GraphicsUnit`](../../graphicsunit) من الخط الجديد. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* أصغر من أو يساوي 0 ، يتم تقييمه إلى ما لا نهاية أو أنه ليس رقمًا صالحًا. |
| ArgumentNullException | *fontName* باطل. |

### أنظر أيضا

* enum [GraphicsUnit](../../graphicsunit)
* class [Font](../../font)
* مساحة الاسم [Aspose.Imaging](../../font)
* المجسم [Aspose.Imaging](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit, CharacterSet) {#constructor_4}

يقوم بتهيئة ملف[`Font`](../../font) باستخدام حجم ونمط ووحدة ومجموعة أحرف محددة.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit, 
    CharacterSet characterSet)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| fontName | String | تمثيل سلسلة من[`Font`](../../font) اسم. |
| emSize | Single | حجم em للخط الجديد في الوحدات المحددة بواسطة*unit* معامل. |
| style | FontStyle | ال[`FontStyle`](../../fontstyle) من الخط الجديد. |
| unit | GraphicsUnit | ال[`GraphicsUnit`](../../graphicsunit) من الخط الجديد. |
| characterSet | CharacterSet | مجموعة أحرف لاستخدامها لهذا الخط. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* أصغر من أو يساوي 0 ، يتم تقييمه إلى ما لا نهاية أو أنه ليس رقمًا صالحًا. |
| ArgumentNullException | *fontName* باطل. |

### أنظر أيضا

* enum [FontStyle](../../fontstyle)
* enum [GraphicsUnit](../../graphicsunit)
* enum [CharacterSet](../../characterset)
* class [Font](../../font)
* مساحة الاسم [Aspose.Imaging](../../font)
* المجسم [Aspose.Imaging](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit) {#constructor_3}

يقوم بتهيئة ملف[`Font`](../../font) باستخدام حجم ونمط ووحدة محددة.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| fontName | String | تمثيل سلسلة من[`Font`](../../font) اسم. |
| emSize | Single | حجم em للخط الجديد في الوحدات المحددة بواسطة*unit* معامل. |
| style | FontStyle | ال[`FontStyle`](../../fontstyle) من الخط الجديد. |
| unit | GraphicsUnit | ال[`GraphicsUnit`](../../graphicsunit) من الخط الجديد. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* أصغر من أو يساوي 0 ، يتم تقييمه إلى ما لا نهاية أو أنه ليس رقمًا صالحًا. |
| ArgumentNullException | *fontName* باطل. |

### أنظر أيضا

* enum [FontStyle](../../fontstyle)
* enum [GraphicsUnit](../../graphicsunit)
* class [Font](../../font)
* مساحة الاسم [Aspose.Imaging](../../font)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
