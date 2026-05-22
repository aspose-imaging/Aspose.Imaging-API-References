---
title: "فئة EmfPixelFormatDescriptor"
type: docs
weight: 220
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/
---

**Summary:** The PixelFormatDescriptor object can be used in EMR_HEADER records (section 2.3.4.2) to specify the pixel format of the output surface for the playback device context.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfPixelFormatDescriptor

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPixelFormatDescriptor()](#EmfPixelFormatDescriptor__1) | يُنشئ مثيلًا جديدًا من فئة EmfPixelFormatDescriptor |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| b_reserved | System.Byte | r/w | يحصل أو يضبط يحدد عدد مستويات التراكب والطبقة السفلية. <br/>            تحدد البتات 0 إلى 3 ما يصل إلى 15 مستوى تراكب وتحدد البتات 4 إلى 7 ما يصل إلى 15 مستوى طبقة سفلية |
| c_accum_alpha_bits | System.Byte | r/w | يحصل أو يضبط يحدد عدد طبقات بيت ألفا في مخزن التجميع |
| c_accum_bits | System.Byte | r/w | الحصول أو الضبط يحدد العدد الإجمالي لطبقات البت في مخزن التجميع. |
| c_accum_blue_bits | System.Byte | r/w | الحصول أو الضبط يحدد عدد طبقات البت الزرقاء في مخزن التجميع. |
| c_accum_green_bits | System.Byte | r/w | الحصول أو الضبط يحدد عدد طبقات البت الخضراء في التجميع |
| c_accum_red_bits | System.Byte | r/w | الحصول أو الضبط يحدد عدد طبقات البت الحمراء في مخزن التجميع. |
| c_alpha_bits | System.Byte | r/w | الحصول أو الضبط يحدد عدد طبقات البت ألفا في كل مخزن ألوان RGBA. |
| c_alpha_shift | System.Byte | r/w | الحصول أو الضبط يحدد عدد الإزاحة لطبقات البت ألفا في كل مخزن ألوان RGBA. |
| c_aux_buffers | System.Byte | r/w | الحصول أو الضبط يحدد عدد المخازن المساعدة. المخازن المساعدة غير مدعومة. |
| c_blue_bits | System.Byte | r/w | الحصول أو الضبط يحدد عدد طبقات البت الزرقاء في كل مخزن ألوان RGBA. |
| c_blue_shift | System.Byte | r/w | الحصول أو الضبط يحدد عدد الإزاحة لطبقات البت الزرقاء في كل مخزن ألوان RGBA. |
| c_color_bits | System.Byte | r/w | الحصول أو الضبط يحدد عدد البتات لكل بكسل لأنواع بكسلات RGBA، باستثناء طبقات البت ألفا. بالنسبة لبكسلات جدول الألوان، فهو حجم كل فهرس في جدول الألوان. |
| c_depth_bits | System.Byte | r/w | الحصول أو الضبط يحدد عمق مخزن العمق (محور z). |
| c_green_bits | System.Byte | r/w | الحصول أو الضبط يحدد عدد طبقات البت الخضراء في كل مخزن ألوان RGBA. |
| c_green_shift | System.Byte | r/w | الحصول أو الضبط يحدد عدد الإزاحات لطبقات البت الخضراء في كل مخزن ألوان RGBA. |
| c_red_bits | System.Byte | r/w | الحصول أو الضبط يحدد عدد طبقات البت الحمراء في كل مخزن ألوان RGBA |
| c_red_shift | System.Byte | r/w | الحصول أو الضبط يحدد عدد الإزاحات بالبتات لطبقات البت الحمراء في كل مخزن ألوان RGBA. |
| c_stencil_bits | System.Byte | r/w | الحصول أو الضبط يحدد عمق مخزن القالب. |
| dw_damage_mask | int | r/w | الحصول أو الضبط قد يتم تجاهل هذا الحقل |
| dw_flags | int | r/w | الحصول أو الضبط علامات البت التي تحدد خصائص مخزن البكسل المستخدم <br/>            للإخراج إلى سطح الرسم. هذه الخصائص ليست جميعها متعارضة <br/>            بشكل متبادل؛ يُسمح بتركيبات من العلامات، باستثناء ما هو مذكور خلاف ذلك. |
| dw_layer_mask | int | r/w | الحصول أو الضبط قد يتم تجاهل هذا الحقل. |
| dw_visible_mask | int | r/w | الحصول أو الضبط يحدد اللون الشفاف أو الفهرس لطائرة تحتية. عندما يكون نوع البكسل <br/>            RGBA، يكون dwVisibleMask قيمة لون RGB شفافة. عندما يكون نوع البكسل <br/>            فهرس ألوان، يكون قيمة فهرس شفافة. |
| layer_type | System.Byte | r/w | الحصول أو الضبط قد يتم تجاهل هذا الحقل |
| n_size | int | r/w | الحصول أو الضبط عدد صحيح 16-بت يحدد الحجم بالبايت لهذه البنية البيانات. |
| n_version | int | r/w | الحصول أو الضبط عدد صحيح 16-بت يجب تعيينه إلى 0x0001. |
| pixel_type | System.Byte | r/w | الحصول أو الضبط نوع بيانات البكسل<br/>            PFD_TYPE_RGBA       0x00 تنسيق البكسل هو RGBA.<br/>            PFD_TYPE_COLORINDEX 0x01 كل بكسل هو فهرس في جدول ألوان. |


### Constructor: EmfPixelFormatDescriptor() {#EmfPixelFormatDescriptor__1}


```
 EmfPixelFormatDescriptor() 
```

يُنشئ مثيلًا جديدًا من فئة EmfPixelFormatDescriptor

