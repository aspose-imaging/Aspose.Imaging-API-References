---
title: "ImageAttributes.SetWrapMode"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة ImageAttributes. تحدد وضع الالتفاف المستخدم لتحديد كيفية تغطية القوام على شكل أو عند حدود الشكل. يتم تغطية القوام على الشكل لملئه عندما يكون القوام أصغر من الشكل الذي يتم تغطيته."
type: docs
weight: 210
url: /ar/net/aspose.imaging/imageattributes/setwrapmode/
---
## SetWrapMode(WrapMode) {#setwrapmode}

يضبط وضع الالتفاف المستخدم لتحديد كيفية تكرار النسيج عبر الشكل، أو عند حدود الشكل. يتم تكرار النسيج عبر الشكل لملئه عندما يكون النسيج أصغر من الشكل الذي يتم ملئه.

```csharp
public void SetWrapMode(WrapMode mode)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| mode | WrapMode | عنصر من [`WrapMode`](../../wrapmode/) يحدد كيفية استخدام النسخ المتكررة من الصورة لتغطية مساحة. |

### انظر أيضًا

* enum [WrapMode](../../wrapmode/)
* class [ImageAttributes](../)
* namespace [Aspose.Imaging](../../imageattributes/)
* assembly [Aspose.Imaging](../../../)

---

## SetWrapMode(WrapMode, Color) {#setwrapmode_1}

يضبط وضع الالتفاف واللون المستخدم لتحديد كيفية تكرار النسيج عبر الشكل، أو عند حدود الشكل. يتم تكرار النسيج عبر الشكل لملئه عندما يكون النسيج أصغر من الشكل الذي يتم ملئه.

```csharp
public void SetWrapMode(WrapMode mode, Color color)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| mode | WrapMode | عنصر من [`WrapMode`](../../wrapmode/) يحدد كيفية استخدام النسخ المتكررة من الصورة لتغطية مساحة. |
| color | Color | كائن [`ImageAttributes`](../) يحدد لون البكسلات خارج الصورة المُرَسَمة. يكون هذا اللون مرئياً إذا تم تعيين معامل الوضع إلى Clamp وكان المستطيل المصدر الممرّر إلى DrawImage أكبر من الصورة نفسها. |

### انظر أيضًا

* enum [WrapMode](../../wrapmode/)
* struct [Color](../../color/)
* class [ImageAttributes](../)
* namespace [Aspose.Imaging](../../imageattributes/)
* assembly [Aspose.Imaging](../../../)

---

## SetWrapMode(WrapMode, Color, bool) {#setwrapmode_2}

يضبط وضع الالتفاف واللون المستخدم لتحديد كيفية تكرار النسيج عبر الشكل، أو عند حدود الشكل. يتم تكرار النسيج عبر الشكل لملئه عندما يكون النسيج أصغر من الشكل الذي يتم ملئه.

```csharp
public void SetWrapMode(WrapMode mode, Color color, bool clamp)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| mode | WrapMode | عنصر من [`WrapMode`](../../wrapmode/) يحدد كيفية استخدام النسخ المتكررة من الصورة لتغطية مساحة. |
| لون | لون | كائن لون يحدد لون البكسلات خارج الصورة المُرَسَمة. يكون هذا اللون مرئياً إذا تم تعيين معامل الوضع إلى Clamp وكان المستطيل المصدر الممرّر إلى DrawImage أكبر من الصورة نفسها. |
| clamp | Boolean | هذا المعامل ليس له أي تأثير. اضبطه على false. |

### انظر أيضًا

* enum [WrapMode](../../wrapmode/)
* struct [Color](../../color/)
* class [ImageAttributes](../)
* namespace [Aspose.Imaging](../../imageattributes/)
* assembly [Aspose.Imaging](../../../)


