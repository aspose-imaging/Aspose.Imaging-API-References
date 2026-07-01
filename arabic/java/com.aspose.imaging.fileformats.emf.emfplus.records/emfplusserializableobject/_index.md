---
title: "EmfPlusSerializableObject"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EmfPlusSerializableObject يعرّف كتلة معلمات تأثيرات الصورة التي تم تسلسلها إلى مخزن بيانات."
type: docs
weight: 53
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusObjectRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusobjectrecordtype)
```
public final class EmfPlusSerializableObject extends EmfPlusObjectRecordType
```

سجل EmfPlusSerializableObject يعرّف كتلة معلمات تأثيرات الصورة التي تم تسلسلها إلى مخزن بيانات.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusSerializableObject(EmfPlusRecord source)](#EmfPlusSerializableObject-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | يُنشئ مثيلاً جديدًا للفئة `EmfPlusSerializableObject`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFlags()](#getFlags--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت غير مستخدم. |
| [setFlags(short value)](#setFlags-short-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت غير مستخدم. |
| [getObjectGuid()](#getObjectGuid--) | يحصل أو يعيّن قيمة تمثيل حزمة GUID ([MS-DTYP] القسم 2.3.4.2) لتأثير الصورة. |
| [setObjectGuid(GuidPacketRepresentation value)](#setObjectGuid-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-) | يحصل أو يعيّن قيمة تمثيل حزمة GUID ([MS-DTYP] القسم 2.3.4.2) لتأثير الصورة. |
| [getBufferSize()](#getBufferSize--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد الحجم بالبايت لحقل Buffer المحاذى إلى 32 بت. |
| [setBufferSize(int value)](#setBufferSize-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد الحجم بالبايت لحقل Buffer المحاذى إلى 32 بت. |
| [getBuffer()](#getBuffer--) | يحصل أو يعيّن مصفوفة من بايتات BufferSize التي تحتوي على كتلة معلمات تأثيرات الصورة المتسلسلة والتي تتطابق مع GUID في حقل ObjectGUID. |
| [setBuffer(byte[] value)](#setBuffer-byte---) | يحصل أو يعيّن مصفوفة من بايتات BufferSize التي تحتوي على كتلة معلمات تأثيرات الصورة المتسلسلة والتي تتطابق مع GUID في حقل ObjectGUID. |
| [getImageEffect()](#getImageEffect--) | يحصل أو يعيّن تأثير الصورة. |
| [setImageEffect(EmfPlusImageEffectsObjectType value)](#setImageEffect-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType-) | يحصل أو يعيّن تأثير الصورة. |
### EmfPlusSerializableObject(EmfPlusRecord source) {#EmfPlusSerializableObject-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSerializableObject(EmfPlusRecord source)
```


يُنشئ مثيلاً جديدًا للفئة `EmfPlusSerializableObject`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | المصدر. |

### getFlags() {#getFlags--}
```
public short getFlags()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت غير مستخدم. يجب أن يُضبط هذا الحقل على الصفر ويجب تجاهله عند الاستلام.

القيمة: العلامات.

**Returns:**
قصير
### setFlags(short value) {#setFlags-short-}
```
public void setFlags(short value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت غير مستخدم. يجب أن يُضبط هذا الحقل على الصفر ويجب تجاهله عند الاستلام.

القيمة: العلامات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | قصير |  |

### getObjectGuid() {#getObjectGuid--}
```
public GuidPacketRepresentation getObjectGuid()
```


يحصل أو يعيّن قيمة تمثيل حزمة GUID ([MS-DTYP] القسم 2.3.4.2) لتأثير الصورة. يجب أن تتطابق هذه القيمة مع أحد معرفات ImageEffects (القسم 2.1.3.1).

**Returns:**
[GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation)
### setObjectGuid(GuidPacketRepresentation value) {#setObjectGuid-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-}
```
public void setObjectGuid(GuidPacketRepresentation value)
```


يحصل أو يعيّن قيمة تمثيل حزمة GUID ([MS-DTYP] القسم 2.3.4.2) لتأثير الصورة. يجب أن تتطابق هذه القيمة مع أحد معرفات ImageEffects (القسم 2.1.3.1).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation) |  |

### getBufferSize() {#getBufferSize--}
```
public int getBufferSize()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد الحجم بالبايت لحقل Buffer المحاذى إلى 32 بت.

**Returns:**
int
### setBufferSize(int value) {#setBufferSize-int-}
```
public void setBufferSize(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد الحجم بالبايت لحقل Buffer المحاذى إلى 32 بت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getBuffer() {#getBuffer--}
```
public byte[] getBuffer()
```


يحصل أو يعيّن مصفوفة من بايتات BufferSize التي تحتوي على كتلة معلمات تأثيرات الصورة المتسلسلة والتي تتطابق مع GUID في حقل ObjectGUID. يجب أن تكون هذه واحدة من كائنات تأثيرات الصورة (القسم 2.2.3).

**Returns:**
byte[]
### setBuffer(byte[] value) {#setBuffer-byte---}
```
public void setBuffer(byte[] value)
```


يحصل أو يعيّن مصفوفة من بايتات BufferSize التي تحتوي على كتلة معلمات تأثيرات الصورة المتسلسلة والتي تتطابق مع GUID في حقل ObjectGUID. يجب أن تكون هذه واحدة من كائنات تأثيرات الصورة (القسم 2.2.3).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte[] |  |

### getImageEffect() {#getImageEffect--}
```
public EmfPlusImageEffectsObjectType getImageEffect()
```


يحصل أو يعيّن تأثير الصورة.

القيمة: تأثير الصورة.

**Returns:**
[EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
### setImageEffect(EmfPlusImageEffectsObjectType value) {#setImageEffect-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType-}
```
public void setImageEffect(EmfPlusImageEffectsObjectType value)
```


يحصل أو يعيّن تأثير الصورة.

القيمة: تأثير الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype) |  |

