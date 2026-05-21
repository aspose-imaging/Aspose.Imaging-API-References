---
title: "فئة ImageAttributes"
second_title: "Aspose.Imaging for .NET API Reference"
description: "فئة Aspose.Imaging.ImageAttributes. يحتوي كائن ImageAttributes على معلومات حول كيفية تعديل ألوان البت ماب وملف التعريف أثناء العرض. يحافظ كائن ImageAttributes على عدة إعدادات لتعديل اللون بما في ذلك مصفوفات تعديل اللون، ومصفوفات تعديل التدرج الرمادي، وقيم تصحيح الجاما، وجداول خريطة الألوان، وقيم عتبة اللون. أثناء العرض يمكن تصحيح الألوان، تعتيمها، إضاءتها وإزالتها. لتطبيق هذه التعديلات، قم بإنشاء كائن ImageAttributes ومرّر مسار ذلك الكائن ImageAttributes مع مسار صورة إلى طريقة DrawImage."
type: docs
weight: 9880
url: /ar/net/aspose.imaging/imageattributes/
---
## ImageAttributes class

كائن `ImageAttributes` يحتوي على معلومات حول كيفية تعديل ألوان البت ماب وملف التعريف أثناء العرض. يحافظ كائن `ImageAttributes` على عدة إعدادات لتعديل اللون، بما في ذلك مصفوفات تعديل اللون، ومصفوفات تعديل التدرج الرمادي، وقيم تصحيح الجاما، وجداول خريطة الألوان، وقيم عتبة اللون. أثناء العرض، يمكن تصحيح الألوان، تعتيمها، إضاءتها وإزالتها. لتطبيق هذه التعديلات، قم بإنشاء كائن `ImageAttributes` ومرّر مسار ذلك الكائن `ImageAttributes` (مع مسار [`Image`](../image/)) إلى طريقة DrawImage.

```csharp
public sealed class ImageAttributes
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ImageAttributes](imageattributes/)() | المنشئ الافتراضي. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [ClearBrushRemapTable](../../aspose.imaging/imageattributes/clearbrushremaptable/)() | يمسح جدول إعادة تعيين ألوان الفرشاة لهذا الكائن `ImageAttributes`. |
| [ClearColorKey](../../aspose.imaging/imageattributes/clearcolorkey/#clearcolorkey)() | يمسح مفتاح اللون (نطاق الشفافية) للفئة الافتراضية. |
| [ClearColorKey](../../aspose.imaging/imageattributes/clearcolorkey/#clearcolorkey_1)(ColorAdjustType) | يمسح مفتاح اللون (نطاق الشفافية) لفئة محددة. |
| [ClearColorMatrix](../../aspose.imaging/imageattributes/clearcolormatrix/#clearcolormatrix)() | يمسح مصفوفة تعديل اللون للفئة الافتراضية. |
| [ClearColorMatrix](../../aspose.imaging/imageattributes/clearcolormatrix/#clearcolormatrix_1)(ColorAdjustType) | يمسح مصفوفة تعديل اللون لفئة محددة. |
| [ClearGamma](../../aspose.imaging/imageattributes/cleargamma/#cleargamma)() | يعطل تصحيح غاما للفئة الافتراضية. |
| [ClearGamma](../../aspose.imaging/imageattributes/cleargamma/#cleargamma_1)(ColorAdjustType) | يعطل تصحيح غاما لفئة محددة. |
| [ClearNoOp](../../aspose.imaging/imageattributes/clearnoop/#clearnoop)() | يمسح إعداد NoOp للفئة الافتراضية. |
| [ClearNoOp](../../aspose.imaging/imageattributes/clearnoop/#clearnoop_1)(ColorAdjustType) | يمسح إعداد NoOp لفئة محددة. |
| [ClearOutputChannel](../../aspose.imaging/imageattributes/clearoutputchannel/#clearoutputchannel)() | يمسح إعداد قناة الإخراج CMYK (سماوي-ماجنتا-أصفر-أسود) للفئة الافتراضية. |
| [ClearOutputChannel](../../aspose.imaging/imageattributes/clearoutputchannel/#clearoutputchannel_1)(ColorAdjustType) | يمسح إعداد قناة الإخراج (سماوي-ماجنتا-أصفر-أسود) لفئة محددة. |
| [ClearOutputChannelColorProfile](../../aspose.imaging/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile)() | يمسح إعداد ملف تعريف لون قناة الإخراج للفئة الافتراضية. |
| [ClearOutputChannelColorProfile](../../aspose.imaging/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile_1)(ColorAdjustType) | يمسح إعداد ملف تعريف لون قناة الإخراج لفئة محددة. |
| [ClearRemapTable](../../aspose.imaging/imageattributes/clearremaptable/#clearremaptable)() | يمسح جدول إعادة تعيين اللون للفئة الافتراضية. |
| [ClearRemapTable](../../aspose.imaging/imageattributes/clearremaptable/#clearremaptable_1)(ColorAdjustType) | يمسح جدول إعادة تعيين اللون لفئة محددة. |
| [ClearThreshold](../../aspose.imaging/imageattributes/clearthreshold/#clearthreshold)() | يمسح قيمة العتبة للفئة الافتراضية. |
| [ClearThreshold](../../aspose.imaging/imageattributes/clearthreshold/#clearthreshold_1)(ColorAdjustType) | يمسح قيمة العتبة لفئة محددة. |
| [SetBrushRemapTable](../../aspose.imaging/imageattributes/setbrushremaptable/)(ColorMap[]) | يضبط جدول إعادة تعيين اللون لفئة الفرشاة. |
| [SetColorKey](../../aspose.imaging/imageattributes/setcolorkey/#setcolorkey)(Color, Color) | يضبط مفتاح اللون للفئة الافتراضية. |
| [SetColorKey](../../aspose.imaging/imageattributes/setcolorkey/#setcolorkey_1)(Color, Color, ColorAdjustType) | يضبط مفتاح اللون (نطاق الشفافية) لفئة محددة. |
| [SetColorMatrices](../../aspose.imaging/imageattributes/setcolormatrices/#setcolormatrices)(ColorMatrix, ColorMatrix) | يضبط مصفوفة تعديل اللون ومصفوفة تعديل التدرج الرمادي للفئة الافتراضية. |
| [SetColorMatrices](../../aspose.imaging/imageattributes/setcolormatrices/#setcolormatrices_1)(ColorMatrix, ColorMatrix, ColorMatrixFlag) | يضبط مصفوفة تعديل اللون ومصفوفة تعديل التدرج الرمادي للفئة الافتراضية. |
| [SetColorMatrices](../../aspose.imaging/imageattributes/setcolormatrices/#setcolormatrices_2)(ColorMatrix, ColorMatrix, ColorMatrixFlag, ColorAdjustType) | يضبط مصفوفة تعديل اللون ومصفوفة تعديل التدرج الرمادي لفئة محددة. |
| [SetColorMatrix](../../aspose.imaging/imageattributes/setcolormatrix/#setcolormatrix)(ColorMatrix) | يضبط مصفوفة تعديل اللون للفئة الافتراضية. |
| [SetColorMatrix](../../aspose.imaging/imageattributes/setcolormatrix/#setcolormatrix_1)(ColorMatrix, ColorMatrixFlag) | يضبط مصفوفة تعديل اللون للفئة الافتراضية. |
| [SetColorMatrix](../../aspose.imaging/imageattributes/setcolormatrix/#setcolormatrix_2)(ColorMatrix, ColorMatrixFlag, ColorAdjustType) | يضبط مصفوفة تعديل اللون لفئة محددة. |
| [SetGamma](../../aspose.imaging/imageattributes/setgamma/#setgamma)(float) | يضبط قيمة غاما للفئة الافتراضية. |
| [SetGamma](../../aspose.imaging/imageattributes/setgamma/#setgamma_1)(float, ColorAdjustType) | يضبط قيمة غاما لفئة محددة. |
| [SetNoOp](../../aspose.imaging/imageattributes/setnoop/#setnoop)() | يقوم بإيقاف تعديل اللون للفئة الافتراضية. |
| [SetNoOp](../../aspose.imaging/imageattributes/setnoop/#setnoop_1)(ColorAdjustType) | يقوم بإيقاف تعديل اللون لفئة محددة. |
| [SetOutputChannel](../../aspose.imaging/imageattributes/setoutputchannel/#setoutputchannel)(ColorChannelFlag) | يضبط قناة الإخراج CMYK (سماوي-ماجنتا-أصفر-أسود) للفئة الافتراضية. |
| [SetOutputChannel](../../aspose.imaging/imageattributes/setoutputchannel/#setoutputchannel_1)(ColorChannelFlag, ColorAdjustType) | يضبط قناة الإخراج CMYK (سماوي-ماجنتا-أصفر-أسود) لفئة محددة. |
| [SetOutputChannelColorProfile](../../aspose.imaging/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile)(string) | يضبط ملف ملف تعريف ألوان قناة الإخراج للفئة الافتراضية. |
| [SetOutputChannelColorProfile](../../aspose.imaging/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile_1)(string, ColorAdjustType) | يضبط ملف ملف تعريف ألوان قناة الإخراج لفئة محددة. |
| [SetRemapTable](../../aspose.imaging/imageattributes/setremaptable/#setremaptable)(ColorMap[]) | يضبط جدول إعادة تعيين الألوان للفئة الافتراضية. |
| [SetRemapTable](../../aspose.imaging/imageattributes/setremaptable/#setremaptable_1)(ColorMap[], ColorAdjustType) | يضبط جدول إعادة تعيين الألوان لفئة محددة. |
| [SetThreshold](../../aspose.imaging/imageattributes/setthreshold/#setthreshold)(float) | يضبط العتبة (نطاق الشفافية) للفئة الافتراضية. |
| [SetThreshold](../../aspose.imaging/imageattributes/setthreshold/#setthreshold_1)(float, ColorAdjustType) | يضبط العتبة (نطاق الشفافية) لفئة محددة. |
| [SetWrapMode](../../aspose.imaging/imageattributes/setwrapmode/#setwrapmode)(WrapMode) | يضبط وضع الالتفاف المستخدم لتحديد كيفية تكرار النسيج عبر الشكل، أو عند حدود الشكل. يتم تكرار النسيج عبر الشكل لملئه عندما يكون النسيج أصغر من الشكل الذي يتم ملئه. |
| [SetWrapMode](../../aspose.imaging/imageattributes/setwrapmode/#setwrapmode_1)(WrapMode, Color) | يضبط وضع الالتفاف واللون المستخدم لتحديد كيفية تكرار النسيج عبر الشكل، أو عند حدود الشكل. يتم تكرار النسيج عبر الشكل لملئه عندما يكون النسيج أصغر من الشكل الذي يتم ملئه. |
| [SetWrapMode](../../aspose.imaging/imageattributes/setwrapmode/#setwrapmode_2)(WrapMode, Color, bool) | يضبط وضع الالتفاف واللون المستخدم لتحديد كيفية تكرار النسيج عبر الشكل، أو عند حدود الشكل. يتم تكرار النسيج عبر الشكل لملئه عندما يكون النسيج أصغر من الشكل الذي يتم ملئه. |

### انظر أيضًا

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


