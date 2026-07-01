---
title: "EmfSmallTextOut"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "السجل EMR_SMALLTEXTOUT يخرج سلسلة."
type: docs
weight: 147
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfSmallTextOut extends EmfDrawingRecordType
```

السجل EMR\_SMALLTEXTOUT يخرج سلسلة نصية.

إذا تم تعيين ETO\_SMALL\_CHARS في حقل fuOptions، فإن TextString يحتوي على رموز 8‑بت للأحرف، مستمدة من البايتات المنخفضة لأكواد Unicode UTF16-LE 16‑بت، حيث يُفترض أن البايت العالي يساوي 0. إذا تم تعيين ETO\_NO\_RECT في حقل fuOptions، فإن حقل Bounds غير مدرج في السجل.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfSmallTextOut(EmfRecord source)](#EmfSmallTextOut-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | ينشئ مثيلًا جديدًا من الفئة `EmfSmallTextOut`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getX()](#getX--) | يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد إحداثي x لمكان وضع السلسلة. |
| [setX(int value)](#setX-int-) | يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد إحداثي x لمكان وضع السلسلة. |
| [getY()](#getY--) | يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد إحداثي y لمكان وضع السلسلة. |
| [setY(int value)](#setY-int-) | يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد إحداثي y لمكان وضع السلسلة. |
| [getCChars()](#getCChars--) | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد عدد الأحرف 16‑بت في السلسلة. |
| [setCChars(int value)](#setCChars-int-) | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد عدد الأحرف 16‑بت في السلسلة. |
| [getFuOptions()](#getFuOptions--) | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد خيارات إخراج النص المستخدمة. |
| [setFuOptions(int value)](#setFuOptions-int-) | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد خيارات إخراج النص المستخدمة. |
| [getIGraphicsMode()](#getIGraphicsMode--) | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد وضع الرسومات، من تعداد GraphicsMode (القسم 2.1.16). |
| [setIGraphicsMode(int value)](#setIGraphicsMode-int-) | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد وضع الرسومات، من تعداد GraphicsMode (القسم 2.1.16). |
| [getExScale()](#getExScale--) | يحصل أو يضبط قيمة نقطية عائمة 32‑بت تحدد مقدار تكبير النص في اتجاه x. |
| [setExScale(float value)](#setExScale-float-) | يحصل أو يضبط قيمة نقطية عائمة 32‑بت تحدد مقدار تكبير النص في اتجاه x. |
| [getEyScale()](#getEyScale--) | يحصل أو يضبط قيمة نقطية عائمة 32‑بت تحدد مقدار تكبير النص في اتجاه y. |
| [setEyScale(float value)](#setEyScale-float-) | يحصل أو يضبط قيمة نقطية عائمة 32‑بت تحدد مقدار تكبير النص في اتجاه y. |
| [getBounds()](#getBounds--) | يحصل أو يضبط كائن WMF RectL اختياري 128‑بت ([MS-WMF] القسم 2.2.2.19) يحدد المستطيل الحدودي بوحدات الجهاز. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | يحصل أو يضبط كائن WMF RectL اختياري 128‑بت ([MS-WMF] القسم 2.2.2.19) يحدد المستطيل الحدودي بوحدات الجهاز. |
| [getTextString()](#getTextString--) | يحصل أو يضبط سلسلة ذات طول متغيّر تحتوي على نص الرسم، إما بأكواد أحرف 8‑بت أو 16‑بت، وفقًا لقيمة حقل fuOptions. |
| [setTextString(String value)](#setTextString-java.lang.String-) | يحصل أو يضبط سلسلة ذات طول متغيّر تحتوي على نص الرسم، إما بأكواد أحرف 8‑بت أو 16‑بت، وفقًا لقيمة حقل fuOptions. |
### EmfSmallTextOut(EmfRecord source) {#EmfSmallTextOut-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSmallTextOut(EmfRecord source)
```


ينشئ مثيلًا جديدًا من الفئة `EmfSmallTextOut`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### getX() {#getX--}
```
public int getX()
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد إحداثي x لمكان وضع السلسلة.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد إحداثي x لمكان وضع السلسلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public int getY()
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد إحداثي y لمكان وضع السلسلة.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public void setY(int value)
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد إحداثي y لمكان وضع السلسلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getCChars() {#getCChars--}
```
public int getCChars()
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد عدد الأحرف 16‑بت في السلسلة. السلسلة ليست منتهية بـ null.

**Returns:**
int
### setCChars(int value) {#setCChars-int-}
```
public void setCChars(int value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد عدد الأحرف 16‑بت في السلسلة. السلسلة ليست منتهية بـ null.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getFuOptions() {#getFuOptions--}
```
public int getFuOptions()
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد خيارات إخراج النص المستخدمة. تُحدد هذه الخيارات بواسطة قيمة واحدة أو مجموعة من القيم من تعداد ExtTextOutOptions (القسم 2.1.11).

**Returns:**
int
### setFuOptions(int value) {#setFuOptions-int-}
```
public void setFuOptions(int value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد خيارات إخراج النص المستخدمة. تُحدد هذه الخيارات بواسطة قيمة واحدة أو مجموعة من القيم من تعداد ExtTextOutOptions (القسم 2.1.11).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getIGraphicsMode() {#getIGraphicsMode--}
```
public int getIGraphicsMode()
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد وضع الرسومات، من تعداد GraphicsMode (القسم 2.1.16).

**Returns:**
int
### setIGraphicsMode(int value) {#setIGraphicsMode-int-}
```
public void setIGraphicsMode(int value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد وضع الرسومات، من تعداد GraphicsMode (القسم 2.1.16).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getExScale() {#getExScale--}
```
public float getExScale()
```


يحصل أو يضبط قيمة نقطية عائمة 32‑بت تحدد مقدار تكبير النص في اتجاه x.

**Returns:**
float
### setExScale(float value) {#setExScale-float-}
```
public void setExScale(float value)
```


يحصل أو يضبط قيمة نقطية عائمة 32‑بت تحدد مقدار تكبير النص في اتجاه x.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getEyScale() {#getEyScale--}
```
public float getEyScale()
```


يحصل أو يضبط قيمة نقطية عائمة 32‑بت تحدد مقدار تكبير النص في اتجاه y.

**Returns:**
float
### setEyScale(float value) {#setEyScale-float-}
```
public void setEyScale(float value)
```


يحصل أو يضبط قيمة نقطية عائمة 32‑بت تحدد مقدار تكبير النص في اتجاه y.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


يحصل أو يضبط كائن WMF RectL اختياري 128‑بت ([MS-WMF] القسم 2.2.2.19) يحدد المستطيل الحدودي بوحدات الجهاز.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


يحصل أو يضبط كائن WMF RectL اختياري 128‑بت ([MS-WMF] القسم 2.2.2.19) يحدد المستطيل الحدودي بوحدات الجهاز.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getTextString() {#getTextString--}
```
public String getTextString()
```


يحصل أو يضبط سلسلة ذات طول متغيّر تحتوي على نص الرسم، إما بأكواد أحرف 8‑بت أو 16‑بت، وفقًا لقيمة حقل fuOptions.

**Returns:**
java.lang.String
### setTextString(String value) {#setTextString-java.lang.String-}
```
public void setTextString(String value)
```


يحصل أو يضبط سلسلة ذات طول متغيّر تحتوي على نص الرسم، إما بأكواد أحرف 8‑بت أو 16‑بت، وفقًا لقيمة حقل fuOptions.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

