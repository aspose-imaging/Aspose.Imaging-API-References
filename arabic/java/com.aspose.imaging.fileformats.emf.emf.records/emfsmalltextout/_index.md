---
title: "EmfSmallTextOut"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_SMALLTEXTOUT يُخرج سلسلة نصية."
type: docs
weight: 147
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfSmallTextOut extends EmfDrawingRecordType
```

سجل EMR\_SMALLTEXTOUT يخرج سلسلة نصية.

إذا تم تعيين ETO\_SMALL\_CHARS في حقل fuOptions، فإن TextString يحتوي على رموز 8‑بت للأحرف، مستمدة من البايتات المنخفضة لرموز Unicode UTF16‑LE ذات 16‑بت، حيث يُفترض أن البايت العالي يساوي 0. إذا تم تعيين ETO\_NO\_RECT في حقل fuOptions، فإن حقل Bounds لا يُضمّن في السجل.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfSmallTextOut(EmfRecord source)](#EmfSmallTextOut-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يُنشئ مثيلاً جديدًا للفئة `EmfSmallTextOut`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getX()](#getX--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد إحداثي x لمكان وضع السلسلة. |
| [setX(int value)](#setX-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد إحداثي x لمكان وضع السلسلة. |
| [getY()](#getY--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد إحداثي y لمكان وضع السلسلة. |
| [setY(int value)](#setY-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد إحداثي y لمكان وضع السلسلة. |
| [getCChars()](#getCChars--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد الأحرف ذات 16‑بت في السلسلة. |
| [setCChars(int value)](#setCChars-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد الأحرف ذات 16‑بت في السلسلة. |
| [getFuOptions()](#getFuOptions--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد خيارات إخراج النص المستخدمة. |
| [setFuOptions(int value)](#setFuOptions-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد خيارات إخراج النص المستخدمة. |
| [getIGraphicsMode()](#getIGraphicsMode--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد وضع الرسومات، من تعداد GraphicsMode (القسم 2.1.16). |
| [setIGraphicsMode(int value)](#setIGraphicsMode-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد وضع الرسومات، من تعداد GraphicsMode (القسم 2.1.16). |
| [getExScale()](#getExScale--) | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد مقدار مقياس النص في اتجاه x. |
| [setExScale(float value)](#setExScale-float-) | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد مقدار مقياس النص في اتجاه x. |
| [getEyScale()](#getEyScale--) | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد مقدار مقياس النص في اتجاه y. |
| [setEyScale(float value)](#setEyScale-float-) | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد مقدار مقياس النص في اتجاه y. |
| [getBounds()](#getBounds--) | يحصل أو يعيّن كائن WMF RectL اختياري 128‑بت ([MS-WMF] القسم 2.2.2.19) يحدد المستطيل الحدودي بوحدات الجهاز. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | يحصل أو يعيّن كائن WMF RectL اختياري 128‑بت ([MS-WMF] القسم 2.2.2.19) يحدد المستطيل الحدودي بوحدات الجهاز. |
| [getTextString()](#getTextString--) | يحصل أو يعيّن سلسلة ذات طول متغيّر تحتوي على النص المراد رسمه، إما برموز 8‑بت أو 16‑بت، وفقًا لقيمة حقل fuOptions. |
| [setTextString(String value)](#setTextString-java.lang.String-) | يحصل أو يعيّن سلسلة ذات طول متغيّر تحتوي على النص المراد رسمه، إما برموز 8‑بت أو 16‑بت، وفقًا لقيمة حقل fuOptions. |
### EmfSmallTextOut(EmfRecord source) {#EmfSmallTextOut-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSmallTextOut(EmfRecord source)
```


يُنشئ مثيلاً جديدًا للفئة `EmfSmallTextOut`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### getX() {#getX--}
```
public int getX()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد إحداثي x لمكان وضع السلسلة.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد إحداثي x لمكان وضع السلسلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getY() {#getY--}
```
public int getY()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد إحداثي y لمكان وضع السلسلة.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public void setY(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد إحداثي y لمكان وضع السلسلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getCChars() {#getCChars--}
```
public int getCChars()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد الأحرف ذات 16‑بت في السلسلة. السلسلة ليست منتهية بـ null.

**Returns:**
int
### setCChars(int value) {#setCChars-int-}
```
public void setCChars(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد الأحرف ذات 16‑بت في السلسلة. السلسلة ليست منتهية بـ null.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getFuOptions() {#getFuOptions--}
```
public int getFuOptions()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد خيارات إخراج النص المستخدمة. تُحدد هذه الخيارات بواسطة قيمة واحدة أو مجموعة من القيم من تعداد ExtTextOutOptions (القسم 2.1.11).

**Returns:**
int
### setFuOptions(int value) {#setFuOptions-int-}
```
public void setFuOptions(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد خيارات إخراج النص المستخدمة. تُحدد هذه الخيارات بواسطة قيمة واحدة أو مجموعة من القيم من تعداد ExtTextOutOptions (القسم 2.1.11).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getIGraphicsMode() {#getIGraphicsMode--}
```
public int getIGraphicsMode()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد وضع الرسومات، من تعداد GraphicsMode (القسم 2.1.16).

**Returns:**
int
### setIGraphicsMode(int value) {#setIGraphicsMode-int-}
```
public void setIGraphicsMode(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد وضع الرسومات، من تعداد GraphicsMode (القسم 2.1.16).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getExScale() {#getExScale--}
```
public float getExScale()
```


يحصل أو يعيّن قيمة عائمة 32‑بت تحدد مقدار مقياس النص في اتجاه x.

**Returns:**
float
### setExScale(float value) {#setExScale-float-}
```
public void setExScale(float value)
```


يحصل أو يعيّن قيمة عائمة 32‑بت تحدد مقدار مقياس النص في اتجاه x.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### getEyScale() {#getEyScale--}
```
public float getEyScale()
```


يحصل أو يعيّن قيمة عائمة 32‑بت تحدد مقدار مقياس النص في اتجاه y.

**Returns:**
float
### setEyScale(float value) {#setEyScale-float-}
```
public void setEyScale(float value)
```


يحصل أو يعيّن قيمة عائمة 32‑بت تحدد مقدار مقياس النص في اتجاه y.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


يحصل أو يعيّن كائن WMF RectL اختياري 128‑بت ([MS-WMF] القسم 2.2.2.19) يحدد المستطيل الحدودي بوحدات الجهاز.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


يحصل أو يعيّن كائن WMF RectL اختياري 128‑بت ([MS-WMF] القسم 2.2.2.19) يحدد المستطيل الحدودي بوحدات الجهاز.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getTextString() {#getTextString--}
```
public String getTextString()
```


يحصل أو يعيّن سلسلة ذات طول متغيّر تحتوي على النص المراد رسمه، إما برموز 8‑بت أو 16‑بت، وفقًا لقيمة حقل fuOptions.

**Returns:**
java.lang.String
### setTextString(String value) {#setTextString-java.lang.String-}
```
public void setTextString(String value)
```


يحصل أو يعيّن سلسلة ذات طول متغيّر تحتوي على النص المراد رسمه، إما برموز 8‑بت أو 16‑بت، وفقًا لقيمة حقل fuOptions.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

