---
title: "فئة WmfDeviceIndependentBitmap"
type: docs
weight: 180
url: /ar/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/
---

**Summary:** The DeviceIndependentBitmap Object defines an image in<br/>                device-independent bitmap (DIB) format

**Module:** [aspose.imaging.fileformats.wmf.objects](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/)

**Full Name:** aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap

**Inheritance:** MetaObject

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [WmfDeviceIndependentBitmap()](#WmfDeviceIndependentBitmap__1) | يُنشئ مثلاً جديدًا من فئة WmfDeviceIndependentBitmap |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| a_data | System.Byte | r/w | يحصل أو يضبط مصفوفة من البايتات التي تُعرّف الصورة. الحجم و<br/>                الصيغة لهذا البيانات يتم تحديدهما بناءً على المعلومات في<br/>                حقل DIBHeaderInfo. |
| cached_image | System.Byte | r/w | يحصل أو يضبط الصورة النقطية المخزنة مؤقتًا. |
| colors_data | System.Byte | r/w | يحصل أو يضبط مصفوفة اختيارية إما لكائنات RGBQuad (القسم<br/>                2.2.2.20) أو أعداد صحيحة غير موقعة 16‑بت تُعرّف جدول ألوان. يجب تحديد حجم ومحتويات هذا الحقل بناءً على<br/>                سجل الميتافايل أو الكائن الذي يحتوي على هذا DeviceIndependentBitmap<br/>                ومن المعلومات في حقل DIBHeaderInfo. راجع تعداد ColorUsage<br/>                (القسم 2.1.1.6) وتعداد BitCount (القسم<br/>                2.1.1.3) للحصول على تفاصيل إضافية |
| header | [WmfBitmapBaseHeader](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/) | r/w | يحصل أو يضبط إما كائن BitmapCoreHeader (القسم 2.2.2.2) أو<br/>                كائن BitmapInfoHeader (القسم 2.2.2.3) الذي يحدد معلومات<br/>                حول الصورة |


### Constructor: WmfDeviceIndependentBitmap() {#WmfDeviceIndependentBitmap__1}


```
 WmfDeviceIndependentBitmap() 
```

يُنشئ مثلاً جديدًا من فئة WmfDeviceIndependentBitmap

