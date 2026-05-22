---
title: "فئة CustomLineCap"
type: docs
weight: 1350
url: /ar/python-net/aspose.imaging/customlinecap/
---

**Summary:** Encapsulates a custom user-defined line cap.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.CustomLineCap

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [CustomLineCap(fill_path, stroke_path)](#CustomLineCap_fill_path_stroke_path_1) | يُنشئ مثيلاً جديدًا من الفئة [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) بالمخطط والملء المحددين. |
| [CustomLineCap(fill_path, stroke_path, base_cap)](#CustomLineCap_fill_path_stroke_path_base_cap_2) | يُنشئ مثيلاً جديدًا من الفئة [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) استنادًا إلى تعداد [LineCap](/imaging/python-net/aspose.imaging/linecap/) الموجود المحدد، مع المخطط والملء المحددين. |
| [CustomLineCap(fill_path, stroke_path, base_cap, base_inset)](#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3) | يُنشئ مثيلاً جديدًا من الفئة [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) استنادًا إلى تعداد [LineCap](/imaging/python-net/aspose.imaging/linecap/) الموجود المحدد، مع المخطط والملء والداخلية المحددة. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| base_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | r/w | يحصل أو يضبط تعداد [LineCap](/imaging/python-net/aspose.imaging/linecap/) الذي تستند إليه هذه [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/). |
| base_inset | float | r/w | يحصل أو يضبط المسافة بين القمة والخط. |
| fill_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | r/w | يحصل أو يضبط الكائن الذي يحدد الملء للقمة المخصصة. |
| stroke_join | [LineJoin](/imaging/python-net/aspose.imaging/linejoin/) | r/w | يحصل أو يضبط تعداد [LineJoin](/imaging/python-net/aspose.imaging/linejoin/) الذي يحدد كيفية ربط الخطوط التي تُكوّن كائن [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/). |
| stroke_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | r/w | يحصل أو يضبط الكائن الذي يحدد المخطط للقمة المخصصة. |
| width_scale | float | r/w | يحصل أو يضبط مقدار التحجيم لهذا كائن الفئة [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) بالنسبة إلى عرض الكائن. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_stroke_caps(start_cap, end_cap)](#get_stroke_caps_start_cap_end_cap_1) | يحصل على القمم المستخدمة لبدء وإنهاء الخطوط التي تُكوّن هذه القمة المخصصة. |
| [set_stroke_caps(start_cap, end_cap)](#set_stroke_caps_start_cap_end_cap_2) | يضبط القمم المستخدمة لبدء وإنهاء الخطوط التي تُكوّن هذه القمة المخصصة. |


### Constructor: CustomLineCap(fill_path, stroke_path) {#CustomLineCap_fill_path_stroke_path_1}


```
 CustomLineCap(fill_path, stroke_path) 
```

يُنشئ مثيلاً جديدًا من الفئة [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) بالمخطط والملء المحددين.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| fill_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | كائن [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) يحدد الملء للقمة المخصصة. |
| stroke_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | كائن [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) يحدد المخطط للقمة المخصصة. |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap) {#CustomLineCap_fill_path_stroke_path_base_cap_2}


```
 CustomLineCap(fill_path, stroke_path, base_cap) 
```

يُنشئ مثيلاً جديدًا من الفئة [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) استنادًا إلى تعداد [LineCap](/imaging/python-net/aspose.imaging/linecap/) الموجود المحدد، مع المخطط والملء المحددين.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| fill_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | كائن [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) يحدد الملء للقمة المخصصة. |
| stroke_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | كائن [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) يحدد المخطط للقمة المخصصة. |
| base_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | قمة الخط التي يُنشأ منها القمة المخصصة. |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap, base_inset) {#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3}


```
 CustomLineCap(fill_path, stroke_path, base_cap, base_inset) 
```

يُنشئ مثيلاً جديدًا من الفئة [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) استنادًا إلى تعداد [LineCap](/imaging/python-net/aspose.imaging/linecap/) الموجود المحدد، مع المخطط والملء والداخلية المحددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| fill_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | كائن [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) يحدد الملء للقمة المخصصة. |
| stroke_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | كائن [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) يحدد المخطط للقمة المخصصة. |
| base_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | قمة الخط التي يُنشأ منها القمة المخصصة. |
| base_inset | float | المسافة بين القمة والخط. |

### Method: get_stroke_caps(start_cap, end_cap) {#get_stroke_caps_start_cap_end_cap_1}


```
 get_stroke_caps(start_cap, end_cap) 
```

يحصل على القمم المستخدمة لبدء وإنهاء الخطوط التي تُكوّن هذه القمة المخصصة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| start_cap | [LineCap[]](/imaging/python-net/aspose.imaging/linecap/) | تعداد [LineCap](/imaging/python-net/aspose.imaging/linecap/) المستخدم في بداية الخط داخل هذه القمة. |
| end_cap | [LineCap[]](/imaging/python-net/aspose.imaging/linecap/) | تعداد [LineCap](/imaging/python-net/aspose.imaging/linecap/) المستخدم في نهاية الخط داخل هذه القمة. |

### Method: set_stroke_caps(start_cap, end_cap) {#set_stroke_caps_start_cap_end_cap_2}


```
 set_stroke_caps(start_cap, end_cap) 
```

يضبط القمم المستخدمة لبدء وإنهاء الخطوط التي تُكوّن هذه القمة المخصصة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| start_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | تعداد [LineCap](/imaging/python-net/aspose.imaging/linecap/) المستخدم في بداية الخط داخل هذه القمة. |
| end_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | تعداد [LineCap](/imaging/python-net/aspose.imaging/linecap/) المستخدم في نهاية الخط داخل هذه القمة. |

