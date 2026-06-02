---
title: "ImageAttributes"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن com.aspose.imaging.ImageAttributes يحتوي على معلومات حول كيفية تعديل ألوان bitmap و metafile أثناء العرض."
type: docs
weight: 57
url: /ar/java/com.aspose.imaging/imageattributes/
---
**Inheritance:**
java.lang.Object
```
public final class ImageAttributes
```

كائن `com.aspose.imaging.ImageAttributes` يحتوي على معلومات حول كيفية تعديل ألوان البت ماب وملفات الميتا أثناء التصيير. كائن `com.aspose.imaging.ImageAttributes` يحافظ على عدة إعدادات لتعديل اللون، بما في ذلك مصفوفات تعديل اللون، ومصفوفات تعديل التدرج الرمادي، وقيم تصحيح غاما، وجداول خريطة الألوان، وقيم عتبة اللون. أثناء التصيير، يمكن تصحيح الألوان، تعتيمها، إضاءتها، وإزالتها. لتطبيق مثل هذه التعديلات، قم بتهيئة كائن `com.aspose.imaging.ImageAttributes` ومرّر مسار ذلك الكائن (إلى جانب مسار [Image](../../com.aspose.imaging/image)) إلى طريقة drawImage.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [ImageAttributes()](#ImageAttributes--) | يقوم بتهيئة نسخة جديدة من الفئة `com.aspose.imaging.ImageAttributes`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [setColorMatrix(ColorMatrix newColorMatrix)](#setColorMatrix-com.aspose.imaging.ColorMatrix-) | يضبط مصفوفة تعديل اللون للفئة الافتراضية. |
| [setColorMatrix(ColorMatrix newColorMatrix, int flags)](#setColorMatrix-com.aspose.imaging.ColorMatrix-int-) | يضبط مصفوفة تعديل اللون للفئة الافتراضية. |
| [setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)](#setColorMatrix-com.aspose.imaging.ColorMatrix-int-int-) | يضبط مصفوفة تعديل اللون لفئة محددة. |
| [clearColorMatrix()](#clearColorMatrix--) | يمسح مصفوفة تعديل اللون للفئة الافتراضية. |
| [clearColorMatrix(int type)](#clearColorMatrix-int-) | يمسح مصفوفة تعديل اللون لفئة محددة. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)](#setColorMatrices-com.aspose.imaging.ColorMatrix-com.aspose.imaging.ColorMatrix-) | يضبط مصفوفة تعديل اللون ومصفوفة تعديل التدرج الرمادي للفئة الافتراضية. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)](#setColorMatrices-com.aspose.imaging.ColorMatrix-com.aspose.imaging.ColorMatrix-int-) | يضبط مصفوفة تعديل اللون ومصفوفة تعديل التدرج الرمادي للفئة الافتراضية. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)](#setColorMatrices-com.aspose.imaging.ColorMatrix-com.aspose.imaging.ColorMatrix-int-int-) | يضبط مصفوفة تعديل اللون ومصفوفة تعديل التدرج الرمادي لفئة محددة. |
| [setThreshold(float threshold)](#setThreshold-float-) | يضبط العتبة (نطاق الشفافية) للفئة الافتراضية. |
| [setThreshold(float threshold, int type)](#setThreshold-float-int-) | يضبط العتبة (نطاق الشفافية) لفئة محددة. |
| [clearThreshold()](#clearThreshold--) | يمسح قيمة العتبة للفئة الافتراضية. |
| [clearThreshold(int type)](#clearThreshold-int-) | يمسح قيمة العتبة لفئة محددة. |
| [setGamma(float gamma)](#setGamma-float-) | يضبط قيمة غاما للفئة الافتراضية. |
| [setGamma(float gamma, int type)](#setGamma-float-int-) | يضبط قيمة غاما لفئة محددة. |
| [clearGamma()](#clearGamma--) | يعطل تصحيح غاما للفئة الافتراضية. |
| [clearGamma(int type)](#clearGamma-int-) | يعطل تصحيح غاما لفئة محددة. |
| [setNoOp()](#setNoOp--) | يقوم بإيقاف تعديل اللون للفئة الافتراضية. |
| [setNoOp(int type)](#setNoOp-int-) | يقوم بإيقاف تعديل اللون لفئة محددة. |
| [clearNoOp()](#clearNoOp--) | يمسح إعداد NoOp للفئة الافتراضية. |
| [clearNoOp(int type)](#clearNoOp-int-) | يمسح إعداد NoOp لفئة محددة. |
| [setColorKey(Color colorLow, Color colorHigh)](#setColorKey-com.aspose.imaging.Color-com.aspose.imaging.Color-) | يضبط مفتاح اللون للفئة الافتراضية. |
| [setColorKey(Color colorLow, Color colorHigh, int type)](#setColorKey-com.aspose.imaging.Color-com.aspose.imaging.Color-int-) | يضبط مفتاح اللون (نطاق الشفافية) لفئة محددة. |
| [clearColorKey()](#clearColorKey--) | يمسح مفتاح اللون (نطاق الشفافية) للفئة الافتراضية. |
| [clearColorKey(int type)](#clearColorKey-int-) | يمسح مفتاح اللون (نطاق الشفافية) لفئة محددة. |
| [setOutputChannel(int flags)](#setOutputChannel-int-) | يضبط قناة الإخراج CMYK (سماوي-ماجنتا-أصفر-أسود) للفئة الافتراضية. |
| [setOutputChannel(int flags, int type)](#setOutputChannel-int-int-) | يضبط قناة الإخراج CMYK (سماوي-ماجنتا-أصفر-أسود) لفئة محددة. |
| [clearOutputChannel()](#clearOutputChannel--) | يمسح إعداد قناة الإخراج CMYK (سماوي-ماجنتا-أصفر-أسود) للفئة الافتراضية. |
| [clearOutputChannel(int type)](#clearOutputChannel-int-) | يمسح إعداد قناة الإخراج (سماوي-ماجنتا-أصفر-أسود) لفئة محددة. |
| [setOutputChannelColorProfile(String colorProfileFilename)](#setOutputChannelColorProfile-java.lang.String-) | يضبط ملف تعريف ألوان قناة الإخراج للفئة الافتراضية. |
| [setOutputChannelColorProfile(String colorProfileFilename, int type)](#setOutputChannelColorProfile-java.lang.String-int-) | يضبط ملف تعريف ألوان قناة الإخراج لفئة محددة. |
| [clearOutputChannelColorProfile()](#clearOutputChannelColorProfile--) | يمسح إعداد ملف تعريف ألوان قناة الإخراج للفئة الافتراضية. |
| [clearOutputChannelColorProfile(int type)](#clearOutputChannelColorProfile-int-) | يمسح إعداد ملف تعريف ألوان قناة الإخراج لفئة محددة. |
| [setRemapTable(ColorMap[] map)](#setRemapTable-com.aspose.imaging.ColorMap---) | يضبط جدول إعادة تعيين الألوان للفئة الافتراضية. |
| [setRemapTable(ColorMap[] map, int type)](#setRemapTable-com.aspose.imaging.ColorMap---int-) | يضبط جدول إعادة تعيين الألوان لفئة محددة. |
| [clearRemapTable()](#clearRemapTable--) | يمسح جدول إعادة تعيين الألوان للفئة الافتراضية. |
| [clearRemapTable(int type)](#clearRemapTable-int-) | يمسح جدول إعادة تعيين الألوان لفئة محددة. |
| [setBrushRemapTable(ColorMap[] map)](#setBrushRemapTable-com.aspose.imaging.ColorMap---) | يضبط جدول إعادة تعيين الألوان لفئة الفرشاة. |
| [clearBrushRemapTable()](#clearBrushRemapTable--) | يمسح جدول إعادة تعيين ألوان الفرشاة لهذا الكائن `com.aspose.imaging.ImageAttributes`. |
| [setWrapMode(int mode)](#setWrapMode-int-) | يضبط وضع الالتفاف المستخدم لتحديد كيفية تكرار النسيج عبر الشكل أو عند حدود الشكل. |
| [setWrapMode(int mode, Color color)](#setWrapMode-int-com.aspose.imaging.Color-) | يضبط وضع الالتفاف واللون المستخدم لتحديد كيفية تكرار النسيج عبر الشكل أو عند حدود الشكل. |
| [setWrapMode(int mode, Color color, boolean clamp)](#setWrapMode-int-com.aspose.imaging.Color-boolean-) | يضبط وضع الالتفاف واللون المستخدم لتحديد كيفية تكرار النسيج عبر الشكل أو عند حدود الشكل. |
| [equals(Object o)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
### ImageAttributes() {#ImageAttributes--}
```
public ImageAttributes()
```


يقوم بتهيئة نسخة جديدة من الفئة `com.aspose.imaging.ImageAttributes`.

### setColorMatrix(ColorMatrix newColorMatrix) {#setColorMatrix-com.aspose.imaging.ColorMatrix-}
```
public void setColorMatrix(ColorMatrix newColorMatrix)
```


يضبط مصفوفة تعديل اللون للفئة الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | مصفوفة تعديل اللون. |

### setColorMatrix(ColorMatrix newColorMatrix, int flags) {#setColorMatrix-com.aspose.imaging.ColorMatrix-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int flags)
```


يضبط مصفوفة تعديل اللون للفئة الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | مصفوفة تعديل اللون. |
| الأعلام | int | عنصر من `Aspose.Imaging.ColorMatrixFlag` يحدد نوع الصورة واللون اللذين سيتأثران بمصفوفة تعديل اللون. |

### setColorMatrix(ColorMatrix newColorMatrix, int mode, int type) {#setColorMatrix-com.aspose.imaging.ColorMatrix-int-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)
```


يضبط مصفوفة تعديل اللون لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | مصفوفة تعديل اللون. |
| الوضع | int | عنصر من `Aspose.Imaging.ColorMatrixFlag` يحدد نوع الصورة واللون اللذين سيتأثران بمصفوفة تعديل اللون. |
| النوع | int | عنصر من `Aspose.Imaging.ColorAdjustType` يحدد الفئة التي تم ضبط مصفوفة تعديل اللون لها. |

### clearColorMatrix() {#clearColorMatrix--}
```
public void clearColorMatrix()
```


يمسح مصفوفة تعديل اللون للفئة الافتراضية.

### clearColorMatrix(int type) {#clearColorMatrix-int-}
```
public void clearColorMatrix(int type)
```


يمسح مصفوفة تعديل اللون لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| النوع | int | عنصر من `Aspose.Imaging.ColorAdjustType` يحدد الفئة التي تم مسح مصفوفة تعديل اللون لها. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix) {#setColorMatrices-com.aspose.imaging.ColorMatrix-com.aspose.imaging.ColorMatrix-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)
```


يضبط مصفوفة تعديل اللون ومصفوفة تعديل التدرج الرمادي للفئة الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | مصفوفة تعديل اللون. |
| grayMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | مصفوفة تعديل التدرج الرمادي. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags) {#setColorMatrices-com.aspose.imaging.ColorMatrix-com.aspose.imaging.ColorMatrix-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)
```


يضبط مصفوفة تعديل اللون ومصفوفة تعديل التدرج الرمادي للفئة الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | مصفوفة تعديل اللون. |
| grayMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | مصفوفة تعديل التدرج الرمادي. |
| الأعلام | int | عنصر من `Aspose.Imaging.ColorMatrixFlag` يحدد نوع الصورة واللون اللذين سيتأثران بمصفوفات تعديل اللون وتعديل التدرج الرمادي. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type) {#setColorMatrices-com.aspose.imaging.ColorMatrix-com.aspose.imaging.ColorMatrix-int-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)
```


يضبط مصفوفة تعديل اللون ومصفوفة تعديل التدرج الرمادي لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | مصفوفة تعديل اللون. |
| grayMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | مصفوفة تعديل التدرج الرمادي. |
| الوضع | int | عنصر من `Aspose.Imaging.ColorMatrixFlag` يحدد نوع الصورة واللون اللذين سيتأثران بمصفوفات تعديل اللون وتعديل التدرج الرمادي. |
| النوع | int | عنصر من `Aspose.Imaging.ColorAdjustType` يحدد الفئة التي تم ضبط مصفوفات تعديل اللون وتعديل التدرج الرمادي لها. |

### setThreshold(float threshold) {#setThreshold-float-}
```
public void setThreshold(float threshold)
```


يضبط العتبة (نطاق الشفافية) للفئة الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| threshold | float | عدد حقيقي يحدد قيمة العتبة. |

### setThreshold(float threshold, int type) {#setThreshold-float-int-}
```
public void setThreshold(float threshold, int type)
```


يضبط العتبة (نطاق الشفافية) لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| threshold | float | قيمة عتبة من 0.0 إلى 1.0 تُستخدم كنقطة توقف لفرز الألوان التي سيتم تعيينها إما إلى قيمة قصوى أو دنيا. |
| النوع | int | عنصر من `Aspose.Imaging.ColorAdjustType` يحدد الفئة التي يتم فيها تعيين عتبة اللون. |

### clearThreshold() {#clearThreshold--}
```
public void clearThreshold()
```


يمسح قيمة العتبة للفئة الافتراضية.

### clearThreshold(int type) {#clearThreshold-int-}
```
public void clearThreshold(int type)
```


يمسح قيمة العتبة لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| النوع | int | عنصر من `Aspose.Imaging.ColorAdjustType` يحدد الفئة التي يتم فيها مسح العتبة. |

### setGamma(float gamma) {#setGamma-float-}
```
public void setGamma(float gamma)
```


يضبط قيمة غاما للفئة الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| غاما | float | قيمة تصحيح الجاما. |

### setGamma(float gamma, int type) {#setGamma-float-int-}
```
public void setGamma(float gamma, int type)
```


يضبط قيمة غاما لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| غاما | float | قيمة تصحيح الجاما. |
| النوع | int | عنصر من تعداد `Aspose.Imaging.ColorAdjustType` يحدد الفئة التي يتم فيها تعيين قيمة الجاما. |

### clearGamma() {#clearGamma--}
```
public void clearGamma()
```


يعطل تصحيح غاما للفئة الافتراضية.

### clearGamma(int type) {#clearGamma-int-}
```
public void clearGamma(int type)
```


يعطل تصحيح غاما لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| النوع | int | عنصر من `Aspose.Imaging.ColorAdjustType` يحدد الفئة التي يتم فيها تعطيل تصحيح الجاما. |

### setNoOp() {#setNoOp--}
```
public void setNoOp()
```


يقوم بإيقاف تعديل اللون للفئة الافتراضية.

### setNoOp(int type) {#setNoOp-int-}
```
public void setNoOp(int type)
```


يقوم بإيقاف تعديل اللون لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| النوع | int | عنصر من `Aspose.Imaging.ColorAdjustType` يحدد الفئة التي يتم فيها إيقاف تصحيح اللون. |

### clearNoOp() {#clearNoOp--}
```
public void clearNoOp()
```


يمسح إعداد NoOp للفئة الافتراضية.

### clearNoOp(int type) {#clearNoOp-int-}
```
public void clearNoOp(int type)
```


يمسح إعداد NoOp لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| النوع | int | عنصر من `Aspose.Imaging.ColorAdjustType` يحدد الفئة التي يتم فيها مسح إعداد NoOp. |

### setColorKey(Color colorLow, Color colorHigh) {#setColorKey-com.aspose.imaging.Color-com.aspose.imaging.Color-}
```
public void setColorKey(Color colorLow, Color colorHigh)
```


يضبط مفتاح اللون للفئة الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.imaging/color) | قيمة مفتاح اللون المنخفض. |
| colorHigh | [Color](../../com.aspose.imaging/color) | قيمة مفتاح اللون العالي. |

### setColorKey(Color colorLow, Color colorHigh, int type) {#setColorKey-com.aspose.imaging.Color-com.aspose.imaging.Color-int-}
```
public void setColorKey(Color colorLow, Color colorHigh, int type)
```


يضبط مفتاح اللون (نطاق الشفافية) لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.imaging/color) | قيمة مفتاح اللون المنخفض. |
| colorHigh | [Color](../../com.aspose.imaging/color) | قيمة مفتاح اللون العالي. |
| النوع | int | عنصر من `Aspose.Imaging.ColorAdjustType` يحدد الفئة التي يتم فيها تعيين مفتاح اللون. |

### clearColorKey() {#clearColorKey--}
```
public void clearColorKey()
```


يمسح مفتاح اللون (نطاق الشفافية) للفئة الافتراضية.

### clearColorKey(int type) {#clearColorKey-int-}
```
public void clearColorKey(int type)
```


يمسح مفتاح اللون (نطاق الشفافية) لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| النوع | int | عنصر من `Aspose.Imaging.ColorAdjustType` يحدد الفئة التي يتم فيها مسح مفتاح اللون. |

### setOutputChannel(int flags) {#setOutputChannel-int-}
```
public void setOutputChannel(int flags)
```


يضبط قناة الإخراج CMYK (سماوي-ماجنتا-أصفر-أسود) للفئة الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الأعلام | int | عنصر من `Aspose.Imaging.ColorChannelFlag` يحدد القناة الخارجة. |

### setOutputChannel(int flags, int type) {#setOutputChannel-int-int-}
```
public void setOutputChannel(int flags, int type)
```


يضبط قناة الإخراج CMYK (سماوي-ماجنتا-أصفر-أسود) لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الأعلام | int | عنصر من `Aspose.Imaging.ColorChannelFlag` يحدد القناة الخارجة. |
| النوع | int | عنصر من `Aspose.Imaging.ColorAdjustType` يحدد الفئة التي يتم فيها تعيين القناة الخارجة. |

### clearOutputChannel() {#clearOutputChannel--}
```
public void clearOutputChannel()
```


يمسح إعداد قناة الإخراج CMYK (سماوي-ماجنتا-أصفر-أسود) للفئة الافتراضية.

### clearOutputChannel(int type) {#clearOutputChannel-int-}
```
public void clearOutputChannel(int type)
```


يمسح إعداد قناة الإخراج (سماوي-ماجنتا-أصفر-أسود) لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| النوع | int | عنصر من `Aspose.Imaging.ColorAdjustType` يحدد الفئة التي يتم فيها مسح إعداد القناة الخارجة. |

### setOutputChannelColorProfile(String colorProfileFilename) {#setOutputChannelColorProfile-java.lang.String-}
```
public void setOutputChannelColorProfile(String colorProfileFilename)
```


يضبط ملف تعريف ألوان قناة الإخراج للفئة الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | اسم المسار لملف ملف تعريف اللون. إذا كان ملف تعريف اللون موجودًا في الدليل %SystemRoot%\\System32\\Spool\\Drivers\\Color، يمكن أن يكون هذا المعامل اسم الملف. وإلا، يجب أن يكون هذا المعامل اسم المسار الكامل المؤهل. |

### setOutputChannelColorProfile(String colorProfileFilename, int type) {#setOutputChannelColorProfile-java.lang.String-int-}
```
public void setOutputChannelColorProfile(String colorProfileFilename, int type)
```


يضبط ملف تعريف ألوان قناة الإخراج لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | اسم المسار لملف ملف تعريف اللون. إذا كان ملف تعريف اللون موجودًا في الدليل %SystemRoot%\\System32\\Spool\\Drivers\\Color، يمكن أن يكون هذا المعامل اسم الملف. وإلا، يجب أن يكون هذا المعامل اسم المسار الكامل المؤهل. |
| النوع | int | عنصر من `Aspose.Imaging.ColorAdjustType` يحدد الفئة التي يتم فيها تعيين ملف تعريف اللون للقناة الخارجة. |

### clearOutputChannelColorProfile() {#clearOutputChannelColorProfile--}
```
public void clearOutputChannelColorProfile()
```


يمسح إعداد ملف تعريف ألوان قناة الإخراج للفئة الافتراضية.

### clearOutputChannelColorProfile(int type) {#clearOutputChannelColorProfile-int-}
```
public void clearOutputChannelColorProfile(int type)
```


يمسح إعداد ملف تعريف ألوان قناة الإخراج لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| النوع | int | عنصر من `Aspose.Imaging.ColorAdjustType` يحدد الفئة التي يتم فيها مسح إعداد ملف تعريف القناة الخارجة. |

### setRemapTable(ColorMap[] map) {#setRemapTable-com.aspose.imaging.ColorMap---}
```
public void setRemapTable(ColorMap[] map)
```


يضبط جدول إعادة تعيين الألوان للفئة الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.imaging/colormap) | مصفوفة من أزواج الألوان من النوع `com.aspose.imaging.ColorMap`. يحتوي كل زوج ألوان على لون موجود (القيمة الأولى) واللون الذي سيتم تحويله إليه (القيمة الثانية). |

### setRemapTable(ColorMap[] map, int type) {#setRemapTable-com.aspose.imaging.ColorMap---int-}
```
public void setRemapTable(ColorMap[] map, int type)
```


يضبط جدول إعادة تعيين الألوان لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.imaging/colormap) | مصفوفة من أزواج الألوان من النوع `com.aspose.imaging.ColorMap`. يحتوي كل زوج ألوان على لون موجود (القيمة الأولى) واللون الذي سيتم تحويله إليه (القيمة الثانية). |
| النوع | int | عنصر من `Aspose.Imaging.ColorAdjustType` يحدد الفئة التي يتم فيها تعيين جدول إعادة تعيين اللون. |

### clearRemapTable() {#clearRemapTable--}
```
public void clearRemapTable()
```


يمسح جدول إعادة تعيين الألوان للفئة الافتراضية.

### clearRemapTable(int type) {#clearRemapTable-int-}
```
public void clearRemapTable(int type)
```


يمسح جدول إعادة تعيين الألوان لفئة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| النوع | int | عنصر من `Aspose.Imaging.ColorAdjustType` يحدد الفئة التي يتم فيها مسح جدول إعادة التعيين. |

### setBrushRemapTable(ColorMap[] map) {#setBrushRemapTable-com.aspose.imaging.ColorMap---}
```
public void setBrushRemapTable(ColorMap[] map)
```


يضبط جدول إعادة تعيين الألوان لفئة الفرشاة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.imaging/colormap) | مصفوفة من كائنات `com.aspose.imaging.ColorMap`. |

### clearBrushRemapTable() {#clearBrushRemapTable--}
```
public void clearBrushRemapTable()
```


يمسح جدول إعادة تعيين ألوان الفرشاة لهذا الكائن `com.aspose.imaging.ImageAttributes`.

### setWrapMode(int mode) {#setWrapMode-int-}
```
public void setWrapMode(int mode)
```


يضبط وضع الالتفاف المستخدم لتحديد كيفية تجانب النسيج عبر الشكل، أو عند حدود الشكل. يتم تجانب النسيج عبر الشكل لملئه عندما يكون النسيج أصغر من الشكل الذي يتم ملئه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الوضع | int | عنصر من `Aspose.Imaging.WrapMode` يحدد كيفية استخدام النسخ المتكررة لصورة لتغطية منطقة. |

### setWrapMode(int mode, Color color) {#setWrapMode-int-com.aspose.imaging.Color-}
```
public void setWrapMode(int mode, Color color)
```


يضبط وضع الالتفاف واللون المستخدم لتحديد كيفية تغطية نسيج عبر شكل، أو عند حدود الشكل. يتم تغطية النسيج عبر الشكل لملئه عندما يكون النسيج أصغر من الشكل الذي يملأه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الوضع | int | عنصر من `Aspose.Imaging.WrapMode` يحدد كيفية استخدام النسخ المتكررة لصورة لتغطية منطقة. |
| color | [Color](../../com.aspose.imaging/color) | كائن `com.aspose.imaging.ImageAttributes` يحدد لون البكسلات خارج الصورة المرسومة. يكون هذا اللون مرئياً إذا تم تعيين معامل الوضع إلى `WrapMode.Clamp` وكان المستطيل المصدر الممرّر إلى DrawImage أكبر من الصورة نفسها. |

### setWrapMode(int mode, Color color, boolean clamp) {#setWrapMode-int-com.aspose.imaging.Color-boolean-}
```
public void setWrapMode(int mode, Color color, boolean clamp)
```


يضبط وضع الالتفاف واللون المستخدم لتحديد كيفية تغطية نسيج عبر شكل، أو عند حدود الشكل. يتم تغطية النسيج عبر الشكل لملئه عندما يكون النسيج أصغر من الشكل الذي يملأه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الوضع | int | عنصر من `Aspose.Imaging.WrapMode` يحدد كيفية استخدام النسخ المتكررة لصورة لتغطية منطقة. |
| color | [Color](../../com.aspose.imaging/color) | كائن لون يحدد لون البكسلات خارج الصورة المرسومة. يكون هذا اللون مرئياً إذا تم تعيين معامل الوضع إلى `WrapMode.Clamp` وكان المستطيل المصدر الممرّر إلى DrawImage أكبر من الصورة نفسها. |
| قفل | boolean | هذا المعامل لا يؤثر. اضبطه على false. |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| o | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
