---
title: "WmfExtTextOut"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "Wmf ext نص خارجي"
type: docs
weight: 36
url: /ar/java/com.aspose.imaging.fileformats.wmf.objects/wmfexttextout/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject), [com.aspose.imaging.fileformats.wmf.objects.WmfPointObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfpointobject)
```
public class WmfExtTextOut extends WmfPointObject
```

Wmf ext نص خارجي
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [WmfExtTextOut()](#WmfExtTextOut--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getStringLength()](#getStringLength--) | يحصل أو يعيّن طول السلسلة. |
| [setStringLength(int value)](#setStringLength-int-) | يحصل أو يعيّن طول السلسلة. |
| [getFwOpts()](#getFwOpts--) | يحصل أو يعيّن خيارات fw. |
| [setFwOpts(int value)](#setFwOpts-int-) | يحصل أو يعيّن خيارات fw. |
| [getRectangle()](#getRectangle--) | الحصول على أو تعيين المستطيل. |
| [setRectangle(Rectangle value)](#setRectangle-com.aspose.imaging.Rectangle-) | الحصول على أو تعيين المستطيل. |
| [getText()](#getText--) | يحصل أو يضبط النص. |
| [setText(String value)](#setText-java.lang.String-) | يحصل أو يضبط النص. |
| [getDx()](#getDx--) | يحصل أو يعيّن قيمة dx. |
| [setDx(short[] value)](#setDx-short---) | يحصل أو يعيّن قيمة dx. |
| [getExtendedByte()](#getExtendedByte--) | يحصل أو يعيّن البايت الموسع. |
| [setExtendedByte(byte value)](#setExtendedByte-byte-) | يحصل أو يعيّن البايت الموسع. |
### WmfExtTextOut() {#WmfExtTextOut--}
```
public WmfExtTextOut()
```


### getStringLength() {#getStringLength--}
```
public int getStringLength()
```


يحصل أو يعيّن طول السلسلة.

القيمة: طول السلسلة.

**Returns:**
int
### setStringLength(int value) {#setStringLength-int-}
```
public void setStringLength(int value)
```


يحصل أو يعيّن طول السلسلة.

القيمة: طول السلسلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getFwOpts() {#getFwOpts--}
```
public int getFwOpts()
```


يحصل أو يعيّن خيارات fw.

القيمة: الخيارات. يمكن أن يكون هذا العنصر مزيجًا من قيمة واحدة أو أكثر.

**Returns:**
int
### setFwOpts(int value) {#setFwOpts-int-}
```
public void setFwOpts(int value)
```


يحصل أو يعيّن خيارات fw.

القيمة: الخيارات. يمكن أن يكون هذا العنصر مزيجًا من قيمة واحدة أو أكثر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


الحصول على أو تعيين المستطيل.

القيمة: المستطيل.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setRectangle(Rectangle value) {#setRectangle-com.aspose.imaging.Rectangle-}
```
public void setRectangle(Rectangle value)
```


الحصول على أو تعيين المستطيل.

القيمة: المستطيل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getText() {#getText--}
```
public String getText()
```


يحصل أو يضبط النص.

القيمة: النص.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


يحصل أو يضبط النص.

القيمة: النص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getDx() {#getDx--}
```
public short[] getDx()
```


يحصل أو يعيّن قيمة dx.

القيمة: dx. تشير إلى المسافة بين أصول خلايا الأحرف المتجاورة. على سبيل المثال، وحدات Dx[i] المنطقية تفصل بين أصول خلية الحرف i وخلية الحرف i + 1. إذا كان هذا الحقل موجودًا، يجب أن يكون عدد القيم مساويًا لعدد الأحرف في السلسلة.

**Returns:**
short[]
### setDx(short[] value) {#setDx-short---}
```
public void setDx(short[] value)
```


يحصل أو يعيّن قيمة dx.

القيمة: dx. تشير إلى المسافة بين أصول خلايا الأحرف المتجاورة. على سبيل المثال، وحدات Dx[i] المنطقية تفصل بين أصول خلية الحرف i وخلية الحرف i + 1. إذا كان هذا الحقل موجودًا، يجب أن يكون عدد القيم مساويًا لعدد الأحرف في السلسلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short[] |  |

### getExtendedByte() {#getExtendedByte--}
```
public byte getExtendedByte()
```


يحصل أو يعيّن البايت الموسع.

القيمة: البايت الموسع.

**Returns:**
byte
### setExtendedByte(byte value) {#setExtendedByte-byte-}
```
public void setExtendedByte(byte value)
```


يحصل أو يعيّن البايت الموسع.

القيمة: البايت الموسع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte |  |

