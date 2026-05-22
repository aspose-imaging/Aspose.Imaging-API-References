---
title: "فئة EmfRasterizationOptions"
type: docs
weight: 100
url: /ar/python-net/aspose.imaging.imageoptions/emfrasterizationoptions/
---

**Summary:** The Emf rasterization options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.EmfRasterizationOptions

**Inheritance:** MetafileRasterizationOptions

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfRasterizationOptions()](#EmfRasterizationOptions__1) | يقوم بإنشاء نسخة جديدة من الفئة EmfRasterizationOptions |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | يحصل أو يعيّن لون خلفية. |
| border_x | float | r/w | الحصول أو تعيين الحد X. |
| border_y | float | r/w | الحصول أو تعيين الحد Y. |
| center_drawing | bool | r/w | الحصول أو تعيين قيمة تشير إلى ما إذا كان يتم الرسم في المركز. |
| draw_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | الحصول أو تعيين لون المقدمة. |
| page_height | float | r/w | الحصول أو تعيين ارتفاع الصفحة.<br/>            إذا كانت القيمة 0، سيتم الحفاظ على نسبة أبعاد الصورة الأصلية. |
| page_size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r/w | الحصول أو تعيين حجم الصفحة.<br/>            إذا كان أحد أبعاد [SizeF](/imaging/python-net/aspose.imaging/sizef/) يساوي 0، سيتم الحفاظ على نسبة أبعاد الصورة الأصلية. |
| page_width | float | r/w | الحصول أو تعيين عرض الصفحة.<br/>            إذا كانت القيمة 0، سيتم الحفاظ على نسبة أبعاد الصورة الأصلية. |
| positioning | [PositioningTypes](/imaging/python-net/aspose.imaging.imageoptions/positioningtypes/) | r/w | الحصول أو تعيين الموضع. |
| render_mode | [EmfRenderMode](/imaging/python-net/aspose.imaging.fileformats.emf/emfrendermode/) | r/w | يحصل أو يضبط وضعية العرض. |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | يحصل أو يضبط وضع التنعيم. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | يحصل أو يضبط تلميح عرض النص. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [clone()](#clone__1) | ينشئ كائنًا جديدًا هو نسخة سطحية من المثيل الحالي. |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | ينسخ هذا إلى _vectorRasterizationOptions_. |


### Constructor: EmfRasterizationOptions() {#EmfRasterizationOptions__1}


```
 EmfRasterizationOptions() 
```

يقوم بإنشاء نسخة جديدة من الفئة EmfRasterizationOptions

### Method: clone() {#clone__1}


```
 clone() 
```

ينشئ كائنًا جديدًا هو نسخة سطحية من المثيل الحالي.

**Returns**

| نوع | الوصف |
| :- | :- |
| System.Object | كائن جديد هو نسخة سطحية من هذا المثيل. |


### Method: copy_to(vector_rasterization_options) {#copy_to_vector_rasterization_options_2}


```
 copy_to(vector_rasterization_options) 
```

ينسخ هذا إلى _vectorRasterizationOptions_.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | vectorRasterizationOptions |

