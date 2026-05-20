---
title: "GifGraphicsControlBlock"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كتلة التحكم في رسومات GIF."
type: docs
weight: 13
url: /ar/java/com.aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.gif.GifBlock](../../com.aspose.imaging.fileformats.gif/gifblock)
```
public class GifGraphicsControlBlock extends GifBlock
```

كتلة التحكم في رسومات GIF.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [GifGraphicsControlBlock()](#GifGraphicsControlBlock--) | ينشئ مثيلاً جديداً من الفئة `GifGraphicsControlBlock`. |
| [GifGraphicsControlBlock(byte flags, int delayTime, byte transparentColorIndex)](#GifGraphicsControlBlock-byte-int-byte-) | ينشئ مثيلاً جديداً من الفئة `GifGraphicsControlBlock`. |
| [GifGraphicsControlBlock(int delayTime, boolean hasTransparentColor, byte transparentColorIndex, boolean requiresUserInput, int disposalMethod)](#GifGraphicsControlBlock-int-boolean-byte-boolean-int-) | ينشئ مثيلاً جديداً من الفئة `GifGraphicsControlBlock`. |
## الحقول

| حقل | الوصف |
| --- | --- |
| [BLOCK_HEADER_SIZE](#BLOCK-HEADER-SIZE) | يحدد حجم رأس الكتلة. |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | تسمية الامتداد. |
| [SUB_BLOCK_SIZE](#SUB-BLOCK-SIZE) | يحصل على حجم الكتلة الفرعية. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getDelayTime()](#getDelayTime--) | يحصل أو يضبط زمن تأخير الإطار معبرًا عنه بـ 1/100 ثانية. |
| [setDelayTime(int value)](#setDelayTime-int-) | يحصل أو يضبط زمن تأخير الإطار معبرًا عنه بـ 1/100 ثانية. |
| [getFlags()](#getFlags--) | يحصل أو يضبط العلامات. |
| [setFlags(byte value)](#setFlags-byte-) | يحصل أو يضبط العلامات. |
| [getTransparentColorIndex()](#getTransparentColorIndex--) | يحصل أو يضبط فهرس اللون الشفاف. |
| [setTransparentColorIndex(byte value)](#setTransparentColorIndex-byte-) | يحصل أو يضبط فهرس اللون الشفاف. |
| [getDisposalMethod()](#getDisposalMethod--) | يحصل أو يضبط طريقة التخلص. |
| [setDisposalMethod(int value)](#setDisposalMethod-int-) | يحصل أو يضبط طريقة التخلص. |
| [getUserInputExpected()](#getUserInputExpected--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان من المتوقع إدخال المستخدم. |
| [setUserInputExpected(boolean value)](#setUserInputExpected-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان من المتوقع إدخال المستخدم. |
| [hasTransparentColor()](#hasTransparentColor--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان كتلة التحكم الرسومية تحتوي على لون شفاف. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان كتلة التحكم الرسومية تحتوي على لون شفاف. |
| [createFlags(boolean hasTransparentColor, boolean requiresUserInput, int disposalMethod)](#createFlags-boolean-boolean-int-) | ينشئ العلامات. |
### GifGraphicsControlBlock() {#GifGraphicsControlBlock--}
```
public GifGraphicsControlBlock()
```


ينشئ مثيلاً جديداً من الفئة `GifGraphicsControlBlock`.

### GifGraphicsControlBlock(byte flags, int delayTime, byte transparentColorIndex) {#GifGraphicsControlBlock-byte-int-byte-}
```
public GifGraphicsControlBlock(byte flags, int delayTime, byte transparentColorIndex)
```


ينشئ مثيلاً جديداً من الفئة `GifGraphicsControlBlock`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الأعلام | byte | العلامات. |
| delayTime | int | زمن التأخير معبرًا عنه بـ 1/100 ثانية. |
| transparentColorIndex | byte | فهرس اللون الشفاف. |

### GifGraphicsControlBlock(int delayTime, boolean hasTransparentColor, byte transparentColorIndex, boolean requiresUserInput, int disposalMethod) {#GifGraphicsControlBlock-int-boolean-byte-boolean-int-}
```
public GifGraphicsControlBlock(int delayTime, boolean hasTransparentColor, byte transparentColorIndex, boolean requiresUserInput, int disposalMethod)
```


ينشئ مثيلاً جديداً من الفئة `GifGraphicsControlBlock`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| delayTime | int | زمن التأخير معبرًا عنه بـ 1/100 ثانية. |
| hasTransparentColor | boolean | إذا تم تعيينه إلى `true` فإن `transparentColorIndex` صالح. |
| transparentColorIndex | byte | فهرس اللون الشفاف. |
| requiresUserInput | boolean | إذا تم تعيينه إلى `true` فإن إدخال المستخدم متوقع. |
| disposalMethod | int | طريقة التخلص. |

### BLOCK_HEADER_SIZE {#BLOCK-HEADER-SIZE}
```
public static final int BLOCK_HEADER_SIZE
```


يحدد حجم رأس الكتلة.

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final byte EXTENSION_LABEL
```


تسمية الامتداد.

### SUB_BLOCK_SIZE {#SUB-BLOCK-SIZE}
```
public static final byte SUB_BLOCK_SIZE
```


يحصل على حجم الكتلة الفرعية.

### getDelayTime() {#getDelayTime--}
```
public int getDelayTime()
```


يحصل أو يضبط زمن تأخير الإطار معبرًا عنه بـ 1/100 ثانية.

**Returns:**
int
### setDelayTime(int value) {#setDelayTime-int-}
```
public void setDelayTime(int value)
```


يحصل أو يضبط زمن تأخير الإطار معبرًا عنه بـ 1/100 ثانية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getFlags() {#getFlags--}
```
public byte getFlags()
```


يحصل أو يضبط العلامات.

القيمة: العلامات.

**Returns:**
byte
### setFlags(byte value) {#setFlags-byte-}
```
public void setFlags(byte value)
```


يحصل أو يضبط العلامات.

القيمة: العلامات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte |  |

### getTransparentColorIndex() {#getTransparentColorIndex--}
```
public byte getTransparentColorIndex()
```


يحصل أو يضبط فهرس اللون الشفاف.

القيمة: فهرس اللون الشفاف.

**Returns:**
byte
### setTransparentColorIndex(byte value) {#setTransparentColorIndex-byte-}
```
public void setTransparentColorIndex(byte value)
```


يحصل أو يضبط فهرس اللون الشفاف.

القيمة: فهرس اللون الشفاف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte |  |

### getDisposalMethod() {#getDisposalMethod--}
```
public int getDisposalMethod()
```


يحصل أو يضبط طريقة التخلص.

القيمة: طريقة التخلص.

**Returns:**
int
### setDisposalMethod(int value) {#setDisposalMethod-int-}
```
public void setDisposalMethod(int value)
```


يحصل أو يضبط طريقة التخلص.

القيمة: طريقة التخلص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getUserInputExpected() {#getUserInputExpected--}
```
public boolean getUserInputExpected()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان من المتوقع إدخال المستخدم.

القيمة: `true` إذا كان إدخال المستخدم متوقعًا؛ وإلا `false`.

**Returns:**
boolean
### setUserInputExpected(boolean value) {#setUserInputExpected-boolean-}
```
public void setUserInputExpected(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان من المتوقع إدخال المستخدم.

القيمة: `true` إذا كان إدخال المستخدم متوقعًا؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان كتلة التحكم الرسومية تحتوي على لون شفاف.

القيمة: `true` إذا كان كتلة التحكم الرسومية تحتوي على لون شفاف؛ وإلا `false`.

**Returns:**
boolean
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان كتلة التحكم الرسومية تحتوي على لون شفاف.

القيمة: `true` إذا كان كتلة التحكم الرسومية تحتوي على لون شفاف؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### createFlags(boolean hasTransparentColor, boolean requiresUserInput, int disposalMethod) {#createFlags-boolean-boolean-int-}
```
public static byte createFlags(boolean hasTransparentColor, boolean requiresUserInput, int disposalMethod)
```


ينشئ العلامات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| hasTransparentColor | boolean | إذا تم تعيينه إلى `true` فإن `GifGraphicsControlBlock` يحتوي على فهرس لون شفاف صالح. |
| requiresUserInput | boolean | إذا تم تعيينه إلى `true` فإن إدخال المستخدم متوقع. |
| disposalMethod | int | طريقة التخلص. |

**Returns:**
byte - العلامات المُولَّدة.
