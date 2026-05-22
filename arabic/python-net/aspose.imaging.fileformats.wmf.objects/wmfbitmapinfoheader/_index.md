---
title: "فئة WmfBitmapInfoHeader"
type: docs
weight: 70
url: /ar/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/
---

**Summary:** The BitmapInfoHeader Object contains information about the dimensions and color format of a device-independent<br/>                bitmap (DIB).

**Module:** [aspose.imaging.fileformats.wmf.objects](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/)

**Full Name:** aspose.imaging.fileformats.wmf.objects.WmfBitmapInfoHeader

**Inheritance:** WmfBitmapBaseHeader

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [WmfBitmapInfoHeader()](#WmfBitmapInfoHeader__1) | يقوم بإنشاء نسخة جديدة من فئة WmfBitmapInfoHeader |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| STRUCTURE_SIZE [static] | int | r | حجم البنية |
| bit_count | [DibBitCount](/imaging/python-net/aspose.imaging.apsbuilder.dib/dibbitcount/) | r/w | يحصل أو يضبط عددًا صحيحًا غير موقع 16-بت يحدد تنسيق<br/>                كل بكسل، والحد الأقصى لعدد الألوان في DIB. يجب أن تكون هذه القيمة<br/>                ضمن تعداد [WmfBitmapBaseHeader.bit_count](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/) (القسم 2.1.1.3). |
| color_important | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد فهارس الألوان المطلوبة لعرض<br/>                DIB.<br/>                إذا كانت هذه القيمة صفرًا، فإن جميع فهارس الألوان مطلوبة |
| color_used | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد الفهارس في جدول الألوان المستخدم بواسطة DIB، كما يلي:<br/>                إذا كانت هذه القيمة صفرًا، يستخدم DIB الحد الأقصى لعدد الألوان التي تتوافق مع قيمة BitCount.<br/>                إذا كانت هذه القيمة غير صفرية وكانت قيمة BitCount أقل من 16، تحدد هذه القيمة عدد الألوان المستخدمة بواسطة DIB.<br/>                إذا كانت هذه القيمة غير صفرية وكانت قيمة BitCount 16 أو أكثر، تحدد هذه القيمة حجم جدول الألوان المستخدم لتحسين أداء لوحة النظام.<br/>                ملاحظة: إذا كانت هذه القيمة غير صفرية وأكبر من الحد الأقصى الممكن لحجم جدول الألوان بناءً على قيمة BitCount، يجب افتراض الحد الأقصى لحجم جدول الألوان. |
| compression | [WmfCompression](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfcompression/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد وضع الضغط لـ DIB. يجب أن تكون هذه القيمة ضمن<br/>                تعداد Compression (القسم 2.1.1.7).<br/>                يجب ألا تحدد هذه القيمة تنسيقًا مضغوطًا إذا كان DIB صورة bitmap من الأعلى إلى الأسفل، كما هو موضح بقيمة Height. |
| header_size | int | r/w | يحصل أو يضبط عددًا صحيحًا غير موقع 32-بت يحدد حجم هذا<br/>                الكائن، بالبايت. |
| height | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد ارتفاع DIB بالبكسل. يجب ألا تكون هذه القيمة صفرًا.<br/>                إذا كانت هذه القيمة موجبة، يكون DIB صورة bitmap من الأسفل إلى الأعلى، وأصلها هو الزاوية السفلية اليسرى.<br/>                إذا كانت هذه القيمة سالبة، يكون DIB صورة bitmap من الأعلى إلى الأسفل، وأصلها هو الزاوية العلوية اليسرى. لا تدعم صور bitmap من الأعلى إلى الأسفل الضغط.<br/>                يجب أن يحدد هذا الحقل ارتفاع ملف الصورة غير المضغوط، إذا كانت قيمة Compression تحدد تنسيق JPEG أو PNG. |
| image_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد حجم الصورة بالبايت.<br/>                إذا كانت قيمة Compression هي BI_RGB، يجب أن تكون هذه القيمة صفرًا ويجب تجاهلها.<br/>                إذا كانت قيمة Compression هي BI_JPEG أو BI_PNG، يجب أن تحدد هذه القيمة حجم مخزن صورة JPEG أو PNG، على التوالي. |
| planes | int | r/w | يحصل أو يضبط عددًا صحيحًا غير موقع 16-بت يحدد عدد الـ<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/) للجهاز المستهدف. يجب أن تكون هذه القيمة<br/>                0x0001. |
| width | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد عرض DIB بالبكسل. يجب أن تكون هذه القيمة موجبة.<br/>                يجب أن يحدد هذا الحقل عرض ملف الصورة غير المضغوط، إذا كانت قيمة Compression تحدد تنسيق JPEG أو PNG. |
| x_pels_per_meter | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد الدقة الأفقية، بوحدة بكسل لكل متر، للجهاز المستهدف<br/>                لـ DIB |
| y_pels_per_meter | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد الدقة العمودية، بوحدة بكسل لكل متر، للجهاز المستهدف<br/>                لـ DIB |


### Constructor: WmfBitmapInfoHeader() {#WmfBitmapInfoHeader__1}


```
 WmfBitmapInfoHeader() 
```

يقوم بإنشاء نسخة جديدة من فئة WmfBitmapInfoHeader

