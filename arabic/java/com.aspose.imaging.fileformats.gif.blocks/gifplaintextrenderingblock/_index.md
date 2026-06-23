---
title: "GifPlainTextRenderingBlock"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كتلة امتداد نص عادي Gif."
type: docs
weight: 14
url: /ar/java/com.aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.gif.GifBlock](../../com.aspose.imaging.fileformats.gif/gifblock)
```
public class GifPlainTextRenderingBlock extends GifBlock
```

كتلة امتداد النص العادي لـ Gif. يحتوي امتداد النص العادي على بيانات نصية والمعلمات اللازمة لعرض تلك البيانات كرسمة، بشكل بسيط.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [GifPlainTextRenderingBlock()](#GifPlainTextRenderingBlock--) | يُهيئ نسخة جديدة من الفئة `GifPlainTextRenderingBlock`. |
| [GifPlainTextRenderingBlock(int textGridLeftPosition, int textGridTopPosition, int textGridWidth, int textGridHeight, byte characterCellWidth, byte characterCellHeight, byte textForegroundColorIndex, byte textBackgroundColorIndex, byte[] data)](#GifPlainTextRenderingBlock-int-int-int-int-byte-byte-byte-byte-byte---) | يُهيئ نسخة جديدة من الفئة `GifPlainTextRenderingBlock`. |
## الحقول

| حقل | الوصف |
| --- | --- |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | تسمية امتداد النص العادي. |
| [SUB_BLOCK_SIZE](#SUB-BLOCK-SIZE) | حجم الكتلة الفرعية. |
| [BLOCK_SIZE](#BLOCK-SIZE) | الحجم الكلي للكتلة. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getTextForegroundColorIndex()](#getTextForegroundColorIndex--) | يحصل أو يعيّن فهرس اللون في لوحة الألوان العالمية المستخدمة لرسم مقدمة النص. |
| [setTextForegroundColorIndex(byte value)](#setTextForegroundColorIndex-byte-) | يحصل أو يعيّن فهرس اللون في لوحة الألوان العالمية المستخدمة لرسم مقدمة النص. |
| [getTextBackgroundColorIndex()](#getTextBackgroundColorIndex--) | يحصل أو يعيّن فهرس اللون في لوحة الألوان العالمية المستخدمة لرسم خلفية النص. |
| [setTextBackgroundColorIndex(byte value)](#setTextBackgroundColorIndex-byte-) | يحصل أو يعيّن فهرس اللون في لوحة الألوان العالمية المستخدمة لرسم خلفية النص. |
| [getCharacterCellWidth()](#getCharacterCellWidth--) | يحصل أو يعيّن عرض خلية الحرف، بالبكسل، لكل خلية في الشبكة. |
| [setCharacterCellWidth(byte value)](#setCharacterCellWidth-byte-) | يحصل أو يعيّن عرض خلية الحرف، بالبكسل، لكل خلية في الشبكة. |
| [getCharacterCellHeight()](#getCharacterCellHeight--) | يحصل أو يعيّن ارتفاع خلية الحرف، بالبكسل، لكل خلية في الشبكة. |
| [setCharacterCellHeight(byte value)](#setCharacterCellHeight-byte-) | يحصل أو يعيّن ارتفاع خلية الحرف، بالبكسل، لكل خلية في الشبكة. |
| [getTextGridLeftPosition()](#getTextGridLeftPosition--) | يحصل أو يعيّن موضع اليسار لشبكة النص. |
| [setTextGridLeftPosition(int value)](#setTextGridLeftPosition-int-) | يحصل أو يعيّن موضع اليسار لشبكة النص. |
| [getTextGridTopPosition()](#getTextGridTopPosition--) | يحصل أو يعيّن موضع الأعلى لشبكة النص. |
| [setTextGridTopPosition(int value)](#setTextGridTopPosition-int-) | يحصل أو يعيّن موضع الأعلى لشبكة النص. |
| [getTextGridWidth()](#getTextGridWidth--) | يحصل أو يعيّن عرض شبكة النص بالبكسل |
| [setTextGridWidth(int value)](#setTextGridWidth-int-) | يحصل أو يعيّن عرض شبكة النص بالبكسل |
| [getTextGridHeight()](#getTextGridHeight--) | يحصل أو يعيّن ارتفاع شبكة النص بالبكسل |
| [setTextGridHeight(int value)](#setTextGridHeight-int-) | يحصل أو يعيّن ارتفاع شبكة النص بالبكسل |
| [getPlainTextData()](#getPlainTextData--) | يحصل أو يعيّن بيانات النص العادي. |
| [setPlainTextData(byte[] value)](#setPlainTextData-byte---) | يحصل أو يعيّن بيانات النص العادي. |
### GifPlainTextRenderingBlock() {#GifPlainTextRenderingBlock--}
```
public GifPlainTextRenderingBlock()
```


يُهيئ نسخة جديدة من الفئة `GifPlainTextRenderingBlock`.

### GifPlainTextRenderingBlock(int textGridLeftPosition, int textGridTopPosition, int textGridWidth, int textGridHeight, byte characterCellWidth, byte characterCellHeight, byte textForegroundColorIndex, byte textBackgroundColorIndex, byte[] data) {#GifPlainTextRenderingBlock-int-int-int-int-byte-byte-byte-byte-byte---}
```
public GifPlainTextRenderingBlock(int textGridLeftPosition, int textGridTopPosition, int textGridWidth, int textGridHeight, byte characterCellWidth, byte characterCellHeight, byte textForegroundColorIndex, byte textBackgroundColorIndex, byte[] data)
```


يُهيئ نسخة جديدة من الفئة `GifPlainTextRenderingBlock`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| textGridLeftPosition | int | موضع اليسار لشبكة النص. |
| textGridTopPosition | int | موضع الأعلى لشبكة النص. |
| textGridWidth | int | عرض شبكة النص. |
| textGridHeight | int | ارتفاع شبكة النص. |
| characterCellWidth | byte | عرض خلية الحرف. |
| characterCellHeight | byte | ارتفاع خلية الحرف. |
| textForegroundColorIndex | byte | فهرس لون المقدمة. |
| textBackgroundColorIndex | byte | فهرس لون الخلفية. |
| البيانات | byte[] | بيانات النص العادي. |

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final byte EXTENSION_LABEL
```


تسمية امتداد النص العادي.

### SUB_BLOCK_SIZE {#SUB-BLOCK-SIZE}
```
public static final byte SUB_BLOCK_SIZE
```


حجم الكتلة الفرعية.

### BLOCK_SIZE {#BLOCK-SIZE}
```
public static final byte BLOCK_SIZE
```


الحجم الكلي للكتلة.

### getTextForegroundColorIndex() {#getTextForegroundColorIndex--}
```
public byte getTextForegroundColorIndex()
```


يحصل أو يعيّن فهرس اللون في لوحة الألوان العالمية المستخدمة لرسم مقدمة النص.

القيمة: فهرس لون المقدمة.

**Returns:**
byte
### setTextForegroundColorIndex(byte value) {#setTextForegroundColorIndex-byte-}
```
public void setTextForegroundColorIndex(byte value)
```


يحصل أو يعيّن فهرس اللون في لوحة الألوان العالمية المستخدمة لرسم مقدمة النص.

القيمة: فهرس لون المقدمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getTextBackgroundColorIndex() {#getTextBackgroundColorIndex--}
```
public byte getTextBackgroundColorIndex()
```


يحصل أو يعيّن فهرس اللون في لوحة الألوان العالمية المستخدمة لرسم خلفية النص.

القيمة: فهرس لون الخلفية.

**Returns:**
byte
### setTextBackgroundColorIndex(byte value) {#setTextBackgroundColorIndex-byte-}
```
public void setTextBackgroundColorIndex(byte value)
```


يحصل أو يعيّن فهرس اللون في لوحة الألوان العالمية المستخدمة لرسم خلفية النص.

القيمة: فهرس لون الخلفية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getCharacterCellWidth() {#getCharacterCellWidth--}
```
public byte getCharacterCellWidth()
```


يحصل أو يعيّن عرض خلية الحرف، بالبكسل، لكل خلية في الشبكة.

القيمة: عرض خلية الحرف.

**Returns:**
byte
### setCharacterCellWidth(byte value) {#setCharacterCellWidth-byte-}
```
public void setCharacterCellWidth(byte value)
```


يحصل أو يعيّن عرض خلية الحرف، بالبكسل، لكل خلية في الشبكة.

القيمة: عرض خلية الحرف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getCharacterCellHeight() {#getCharacterCellHeight--}
```
public byte getCharacterCellHeight()
```


يحصل أو يعيّن ارتفاع خلية الحرف، بالبكسل، لكل خلية في الشبكة.

القيمة: ارتفاع خلية الحرف.

**Returns:**
byte
### setCharacterCellHeight(byte value) {#setCharacterCellHeight-byte-}
```
public void setCharacterCellHeight(byte value)
```


يحصل أو يعيّن ارتفاع خلية الحرف، بالبكسل، لكل خلية في الشبكة.

القيمة: ارتفاع خلية الحرف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getTextGridLeftPosition() {#getTextGridLeftPosition--}
```
public int getTextGridLeftPosition()
```


يحصل أو يعيّن موضع اليسار لشبكة النص.

القيمة: موضع اليسار لشبكة النص.

هذا رقم العمود، بوحدات البكسل، للحافة اليسرى لشبكة النص، بالنسبة إلى الحافة اليسرى للشاشة المنطقية.

**Returns:**
int
### setTextGridLeftPosition(int value) {#setTextGridLeftPosition-int-}
```
public void setTextGridLeftPosition(int value)
```


يحصل أو يعيّن موضع اليسار لشبكة النص.

القيمة: موضع اليسار لشبكة النص.

هذا رقم العمود، بوحدات البكسل، للحافة اليسرى لشبكة النص، بالنسبة إلى الحافة اليسرى للشاشة المنطقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getTextGridTopPosition() {#getTextGridTopPosition--}
```
public int getTextGridTopPosition()
```


يحصل أو يعيّن موضع الأعلى لشبكة النص.

القيمة: موضع أعلى شبكة النص.

هذا رقم الصف، بوحدات البكسل، للحافة العليا لشكة النص، بالنسبة إلى الحافة العليا للشاشة المنطقية.

**Returns:**
int
### setTextGridTopPosition(int value) {#setTextGridTopPosition-int-}
```
public void setTextGridTopPosition(int value)
```


يحصل أو يعيّن موضع الأعلى لشبكة النص.

القيمة: موضع أعلى شبكة النص.

هذا رقم الصف، بوحدات البكسل، للحافة العليا لشكة النص، بالنسبة إلى الحافة العليا للشاشة المنطقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getTextGridWidth() {#getTextGridWidth--}
```
public int getTextGridWidth()
```


يحصل أو يعيّن عرض شبكة النص بالبكسل

القيمة: عرض شبكة النص بوحدات البكسل.

**Returns:**
int
### setTextGridWidth(int value) {#setTextGridWidth-int-}
```
public void setTextGridWidth(int value)
```


يحصل أو يعيّن عرض شبكة النص بالبكسل

القيمة: عرض شبكة النص بوحدات البكسل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getTextGridHeight() {#getTextGridHeight--}
```
public int getTextGridHeight()
```


يحصل أو يعيّن ارتفاع شبكة النص بالبكسل

القيمة: ارتفاع شبكة النص بوحدات البكسل.

**Returns:**
int
### setTextGridHeight(int value) {#setTextGridHeight-int-}
```
public void setTextGridHeight(int value)
```


يحصل أو يعيّن ارتفاع شبكة النص بالبكسل

القيمة: ارتفاع شبكة النص بوحدات البكسل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPlainTextData() {#getPlainTextData--}
```
public byte[] getPlainTextData()
```


يحصل أو يعيّن بيانات النص العادي.

القيمة: بيانات النص العادي.

**Returns:**
byte[]
### setPlainTextData(byte[] value) {#setPlainTextData-byte---}
```
public void setPlainTextData(byte[] value)
```


يحصل أو يعيّن بيانات النص العادي.

القيمة: بيانات النص العادي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte[] |  |

