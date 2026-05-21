---
title: "StretchMode"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "التعداد يحدد وضع تمديد البت ماب الذي يحدد كيفية دمج النظام للصفوف أو الأعمدة من صورة البت ماب مع البكسلات الموجودة."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.fileformats.wmf.consts/stretchmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class StretchMode extends System.Enum
```

التعداد [StretchMode](../../com.aspose.imaging.fileformats.wmf.consts/stretchmode) يحدد وضع تمديد صورة البت ماب، والذي يحدد كيفية دمج النظام للصفوف أو الأعمدة من صورة البت ماب مع البكسلات الموجودة.
## الحقول

| حقل | الوصف |
| --- | --- |
| [BlackOnWhite](#BlackOnWhite) | ينفذ عملية AND منطقية باستخدام قيم اللون للبكسلات المحذوفة والقائمة. |
| [WhiteOnBlack](#WhiteOnBlack) | ينفذ عملية OR منطقية باستخدام قيم اللون للبكسلات المحذوفة والقائمة. |
| [ColorOnColor](#ColorOnColor) | يحذف البكسلات. |
| [HalfTone](#HalfTone) | يقوم بترسيم البكسلات من المستطيل المصدر إلى كتل من البكسلات في المستطيل الوجهة. |
### BlackOnWhite {#BlackOnWhite}
```
public static final int BlackOnWhite
```


ينفذ عملية AND منطقية باستخدام قيم اللون للبكسلات المحذوفة والقائمة. إذا كانت صورة البت ماب أحادية اللون، فإن هذا الوضع يحافظ على البكسلات السوداء على حساب البكسلات البيضاء.

### WhiteOnBlack {#WhiteOnBlack}
```
public static final int WhiteOnBlack
```


ينفذ عملية OR منطقية باستخدام قيم اللون للبكسلات المحذوفة والقائمة. إذا كانت صورة البت ماب أحادية اللون، فإن هذا الوضع يحافظ على البكسلات البيضاء على حساب البكسلات السوداء.

### ColorOnColor {#ColorOnColor}
```
public static final int ColorOnColor
```


يحذف البكسلات. هذا الوضع يحذف جميع خطوط البكسلات المُزالة دون محاولة الحفاظ على معلوماتها.

### HalfTone {#HalfTone}
```
public static final int HalfTone
```


يقوم بترسيم البكسلات من المستطيل المصدر إلى كتل من البكسلات في المستطيل الوجهة. اللون المتوسط للكتلة الوجهة من البكسلات يقترب من لون البكسلات المصدر.

