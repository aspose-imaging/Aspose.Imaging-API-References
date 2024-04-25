---
title: ImageAttributes
second_title: Aspose.Imaging لمرجع NET API
description: أنImageAttributes./imageattributes يحتوي الكائن على معلومات حول كيفية معالجة ألوان الصور النقطية وملفات التعريف أثناء العرض. انImageAttributes./imageattributesيحتفظ الكائن بالعديد من إعدادات ضبط اللون  بما في ذلك مصفوفات ضبط اللون  ومصفوفات ضبط التدرج الرمادي  وقيم تصحيح جاما  وجداول خريطة الألوان  وقيم عتبة اللون. أثناء التجسيد  يمكن تصحيح الألوان وتغميقها وتفتيحها وإزالتها. لتطبيق مثل هذه التلاعبات  قم بتهيئة ملفImageAttributes./imageattributes كائن وتمرير مسار ذلكImageAttributes./imageattributes كائن جنبًا إلى جنب مع مسار ملفImage./image  إلى طريقة DrawImage .
type: docs
weight: 9680
url: /ar/aspose.imaging/imageattributes/
---
## ImageAttributes class

أن[`ImageAttributes`](../imageattributes) يحتوي الكائن على معلومات حول كيفية معالجة ألوان الصور النقطية وملفات التعريف أثناء العرض. ان[`ImageAttributes`](../imageattributes)يحتفظ الكائن بالعديد من إعدادات ضبط اللون ، بما في ذلك مصفوفات ضبط اللون ، ومصفوفات ضبط التدرج الرمادي ، وقيم تصحيح جاما ، وجداول خريطة الألوان ، وقيم عتبة اللون. أثناء التجسيد ، يمكن تصحيح الألوان وتغميقها وتفتيحها وإزالتها. لتطبيق مثل هذه التلاعبات ، قم بتهيئة ملف[`ImageAttributes`](../imageattributes) كائن وتمرير مسار ذلك[`ImageAttributes`](../imageattributes) كائن (جنبًا إلى جنب مع مسار ملف[`Image`](../image) ) إلى طريقة DrawImage .

```csharp
public sealed class ImageAttributes
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [ImageAttributes](imageattributes)() | Default_Constructor |

## طُرق

| اسم | وصف |
| --- | --- |
| [ClearBrushRemapTable](../../aspose.imaging/imageattributes/clearbrushremaptable)() | يمسح جدول إعادة رسم خريطة لون الفرشاة لهذا[`ImageAttributes`](../imageattributes) الكائن . |
| [ClearColorKey](../../aspose.imaging/imageattributes/clearcolorkey#clearcolorkey)() | يمسح مفتاح اللون (نطاق الشفافية) للفئة الافتراضية. |
| [ClearColorKey](../../aspose.imaging/imageattributes/clearcolorkey#clearcolorkey_1)(ColorAdjustType) | يمسح مفتاح اللون (نطاق الشفافية) لفئة محددة. |
| [ClearColorMatrix](../../aspose.imaging/imageattributes/clearcolormatrix#clearcolormatrix)() | يمسح مصفوفة ضبط اللون للفئة الافتراضية. |
| [ClearColorMatrix](../../aspose.imaging/imageattributes/clearcolormatrix#clearcolormatrix_1)(ColorAdjustType) | يمسح مصفوفة ضبط اللون لفئة محددة. |
| [ClearGamma](../../aspose.imaging/imageattributes/cleargamma#cleargamma)() | تعطيل تصحيح جاما للفئة الافتراضية. |
| [ClearGamma](../../aspose.imaging/imageattributes/cleargamma#cleargamma_1)(ColorAdjustType) | تعطيل تصحيح جاما لفئة محددة. |
| [ClearNoOp](../../aspose.imaging/imageattributes/clearnoop#clearnoop)() | يمسح إعداد NoOp للفئة الافتراضية. |
| [ClearNoOp](../../aspose.imaging/imageattributes/clearnoop#clearnoop_1)(ColorAdjustType) | يمسح إعداد NoOp لفئة محددة. |
| [ClearOutputChannel](../../aspose.imaging/imageattributes/clearoutputchannel#clearoutputchannel)() | يمسح إعداد قناة الإخراج CMYK (سماوي-أرجواني-أصفر-أسود) للفئة الافتراضية. |
| [ClearOutputChannel](../../aspose.imaging/imageattributes/clearoutputchannel#clearoutputchannel_1)(ColorAdjustType) | يمسح إعداد قناة الإخراج (سماوي - أرجواني - أصفر - أسود) لفئة محددة. |
| [ClearOutputChannelColorProfile](../../aspose.imaging/imageattributes/clearoutputchannelcolorprofile#clearoutputchannelcolorprofile)() | يمسح إعداد ملف تعريف لون قناة الإخراج للفئة الافتراضية. |
| [ClearOutputChannelColorProfile](../../aspose.imaging/imageattributes/clearoutputchannelcolorprofile#clearoutputchannelcolorprofile_1)(ColorAdjustType) | يمسح إعداد ملف تعريف لون قناة الإخراج لفئة محددة. |
| [ClearRemapTable](../../aspose.imaging/imageattributes/clearremaptable#clearremaptable)() | يمسح جدول إعادة تعيين الألوان للفئة الافتراضية. |
| [ClearRemapTable](../../aspose.imaging/imageattributes/clearremaptable#clearremaptable_1)(ColorAdjustType) | يمسح جدول إعادة رسم خريطة الألوان لفئة محددة. |
| [ClearThreshold](../../aspose.imaging/imageattributes/clearthreshold#clearthreshold)() | مسح القيمة الحدية للفئة الافتراضية. |
| [ClearThreshold](../../aspose.imaging/imageattributes/clearthreshold#clearthreshold_1)(ColorAdjustType) | مسح القيمة الحدية لفئة محددة. |
| [SetBrushRemapTable](../../aspose.imaging/imageattributes/setbrushremaptable)(ColorMap[]) | يضبط جدول إعادة رسم خريطة الألوان لفئة الفرشاة. |
| [SetColorKey](../../aspose.imaging/imageattributes/setcolorkey#setcolorkey)(Color, Color) | يضبط مفتاح اللون للفئة الافتراضية. |
| [SetColorKey](../../aspose.imaging/imageattributes/setcolorkey#setcolorkey_1)(Color, Color, ColorAdjustType) | يضبط مفتاح اللون (نطاق الشفافية) لفئة محددة. |
| [SetColorMatrices](../../aspose.imaging/imageattributes/setcolormatrices#setcolormatrices)(ColorMatrix, ColorMatrix) | يضبط مصفوفة ضبط اللون ومصفوفة ضبط التدرج الرمادي للفئة الافتراضية. |
| [SetColorMatrices](../../aspose.imaging/imageattributes/setcolormatrices#setcolormatrices_1)(ColorMatrix, ColorMatrix, ColorMatrixFlag) | يضبط مصفوفة ضبط اللون ومصفوفة ضبط التدرج الرمادي للفئة الافتراضية. |
| [SetColorMatrices](../../aspose.imaging/imageattributes/setcolormatrices#setcolormatrices_2)(ColorMatrix, ColorMatrix, ColorMatrixFlag, ColorAdjustType) | يضبط مصفوفة ضبط اللون ومصفوفة ضبط التدرج الرمادي لفئة محددة. |
| [SetColorMatrix](../../aspose.imaging/imageattributes/setcolormatrix#setcolormatrix)(ColorMatrix) | يضبط مصفوفة ضبط اللون للفئة الافتراضية. |
| [SetColorMatrix](../../aspose.imaging/imageattributes/setcolormatrix#setcolormatrix_1)(ColorMatrix, ColorMatrixFlag) | يضبط مصفوفة ضبط اللون للفئة الافتراضية. |
| [SetColorMatrix](../../aspose.imaging/imageattributes/setcolormatrix#setcolormatrix_2)(ColorMatrix, ColorMatrixFlag, ColorAdjustType) | يضبط مصفوفة ضبط اللون لفئة محددة. |
| [SetGamma](../../aspose.imaging/imageattributes/setgamma#setgamma)(float) | يضبط قيمة جاما للفئة الافتراضية. |
| [SetGamma](../../aspose.imaging/imageattributes/setgamma#setgamma_1)(float, ColorAdjustType) | يضبط قيمة جاما لفئة محددة. |
| [SetNoOp](../../aspose.imaging/imageattributes/setnoop#setnoop)() | لإيقاف تشغيل ضبط اللون للفئة الافتراضية. |
| [SetNoOp](../../aspose.imaging/imageattributes/setnoop#setnoop_1)(ColorAdjustType) | لإيقاف تشغيل ضبط اللون لفئة محددة. |
| [SetOutputChannel](../../aspose.imaging/imageattributes/setoutputchannel#setoutputchannel)(ColorChannelFlag) | يضبط قناة الإخراج CMYK (سماوي-أرجواني-أصفر-أسود) للفئة الافتراضية. |
| [SetOutputChannel](../../aspose.imaging/imageattributes/setoutputchannel#setoutputchannel_1)(ColorChannelFlag, ColorAdjustType) | يضبط قناة الإخراج CMYK (سماوي-أرجواني-أصفر-أسود) لفئة محددة. |
| [SetOutputChannelColorProfile](../../aspose.imaging/imageattributes/setoutputchannelcolorprofile#setoutputchannelcolorprofile)(string) | يضبط ملف ملف تعريف لون قناة الإخراج للفئة الافتراضية. |
| [SetOutputChannelColorProfile](../../aspose.imaging/imageattributes/setoutputchannelcolorprofile#setoutputchannelcolorprofile_1)(string, ColorAdjustType) | يضبط ملف ملف تعريف لون قناة الإخراج لفئة محددة. |
| [SetRemapTable](../../aspose.imaging/imageattributes/setremaptable#setremaptable)(ColorMap[]) | يضبط جدول إعادة رسم خريطة الألوان للفئة الافتراضية. |
| [SetRemapTable](../../aspose.imaging/imageattributes/setremaptable#setremaptable_1)(ColorMap[], ColorAdjustType) | يضبط جدول إعادة رسم خريطة اللون لفئة محددة. |
| [SetThreshold](../../aspose.imaging/imageattributes/setthreshold#setthreshold)(float) | يضبط الحد (نطاق الشفافية) للفئة الافتراضية. |
| [SetThreshold](../../aspose.imaging/imageattributes/setthreshold#setthreshold_1)(float, ColorAdjustType) | يضبط العتبة (نطاق الشفافية) لفئة محددة . |
| [SetWrapMode](../../aspose.imaging/imageattributes/setwrapmode#setwrapmode)(WrapMode) | يضبط وضع الالتفاف المستخدم لتحديد كيفية تجانب نسيج عبر شكل ما ، أو عند حدود الشكل. يتم تجانب النسيج عبر شكل لملئه عندما يكون النسيج أصغر من الشكل الذي يملأه. |
| [SetWrapMode](../../aspose.imaging/imageattributes/setwrapmode#setwrapmode_1)(WrapMode, Color) | يضبط وضع الالتفاف واللون المستخدم لتحديد كيفية تجانب نسيج عبر شكل ما ، أو عند حدود الشكل. يتم تجانب النسيج عبر شكل لملئه عندما يكون النسيج أصغر من الشكل الذي يملأه. |
| [SetWrapMode](../../aspose.imaging/imageattributes/setwrapmode#setwrapmode_2)(WrapMode, Color, bool) | يضبط وضع الالتفاف واللون المستخدم لتحديد كيفية تجانب نسيج عبر شكل ما ، أو عند حدود الشكل. يتم تجانب النسيج عبر شكل لملئه عندما يكون النسيج أصغر من الشكل الذي يملأه. |

### أنظر أيضا

* مساحة الاسم [Aspose.Imaging](../../aspose.imaging)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
