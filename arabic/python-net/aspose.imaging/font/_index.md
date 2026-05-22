---
title: "فئة الخط"
type: docs
weight: 4830
url: /ar/python-net/aspose.imaging/font/
---

**Summary:** Defines a particular format for text, including font face, size, and style attributes. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Font

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [Font(font_name, em_size)](#Font_font_name_em_size_1) | ينشئ كائنًا جديدًا من [Font](/imaging/python-net/aspose.imaging/font/) باستخدام حجم محدد. يتم تعيين مجموعة الأحرف إلى [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/)، ووحدة الرسومات إلى [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/)، ونمط الخط إلى [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/). |
| [Font(font_name, em_size, style)](#Font_font_name_em_size_style_2) | ينشئ كائنًا جديدًا من [Font](/imaging/python-net/aspose.imaging/font/) باستخدام حجم ونمط محددين. يتم تعيين مجموعة الأحرف إلى [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/)، ووحدة الرسومات إلى [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/). |
| [Font(font_name, em_size, style, unit)](#Font_font_name_em_size_style_unit_3) | ينشئ كائنًا جديدًا من [Font](/imaging/python-net/aspose.imaging/font/) باستخدام حجم ونمط ووحدة محددين. |
| [Font(font_name, em_size, style, unit, character_set)](#Font_font_name_em_size_style_unit_character_set_4) | ينشئ كائنًا جديدًا من [Font](/imaging/python-net/aspose.imaging/font/) باستخدام حجم ونمط ووحدة ومجموعة أحرف محددة. |
| [Font(font_name, em_size, unit)](#Font_font_name_em_size_unit_5) | ينشئ كائنًا جديدًا من [Font](/imaging/python-net/aspose.imaging/font/) باستخدام حجم ووحدة محددين. يتم تعيين مجموعة الأحرف إلى [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/)، ويتم تعيين النمط إلى [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/). |
| [Font(prototype, new_style)](#Font_prototype_new_style_6) | ينشئ كائنًا جديدًا من [Font](/imaging/python-net/aspose.imaging/font/) يستخدم الـ [Font](/imaging/python-net/aspose.imaging/font/) الموجود المحدد وتعداد [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| bold | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا [Font](/imaging/python-net/aspose.imaging/font/) غامقًا. |
| character_set | [CharacterSet](/imaging/python-net/aspose.imaging/characterset/) | r | يحصل على قيمة بايت تحدد مجموعة الأحرف التي يستخدمها هذا [Font](/imaging/python-net/aspose.imaging/font/). |
| italic | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا [Font](/imaging/python-net/aspose.imaging/font/) مائلًا. |
| name | string | r | يحصل على اسم الوجه لهذا [Font](/imaging/python-net/aspose.imaging/font/). |
| size | float | r | يحصل على حجم الـ em لهذا [Font](/imaging/python-net/aspose.imaging/font/) مقاسًا بالوحدات المحددة بواسطة خاصية [Font.unit](/imaging/python-net/aspose.imaging/font/). |
| strikeout | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا [Font](/imaging/python-net/aspose.imaging/font/) يحدد خطًا أفقيًا عبر الخط. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | r | يحصل على معلومات النمط لهذا [Font](/imaging/python-net/aspose.imaging/font/). |
| underline | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا [Font](/imaging/python-net/aspose.imaging/font/) تحت خط. |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | r | يحصل على وحدة القياس لهذا [Font](/imaging/python-net/aspose.imaging/font/). |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_prototype(prototype, new_style)](#create_from_prototype_prototype_new_style_1) | ينشئ كائنًا جديدًا من [Font](/imaging/python-net/aspose.imaging/font/) يستخدم الـ [Font](/imaging/python-net/aspose.imaging/font/) الموجود المحدد وتعداد [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/). |
| [create_with_size(font_name, em_size)](#create_with_size_font_name_em_size_2) | ينشئ كائنًا جديدًا من [Font](/imaging/python-net/aspose.imaging/font/) باستخدام حجم محدد. يتم تعيين مجموعة الأحرف إلى [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/)، ووحدة الرسومات إلى [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/)، ونمط الخط إلى [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/). |
| [create_with_size_style(font_name, em_size, style)](#create_with_size_style_font_name_em_size_style_3) | ينشئ كائنًا جديدًا من [Font](/imaging/python-net/aspose.imaging/font/) باستخدام حجم ونمط محددين. يتم تعيين مجموعة الأحرف إلى [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/)، ووحدة الرسومات إلى [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/). |
| [create_with_size_unit(font_name, em_size, unit)](#create_with_size_unit_font_name_em_size_unit_4) | ينشئ كائنًا جديدًا من [Font](/imaging/python-net/aspose.imaging/font/) باستخدام حجم ووحدة محددين. يتم تعيين مجموعة الأحرف إلى [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/)، ويتم تعيين النمط إلى [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/). |
| [deep_clone()](#deep_clone__5) | ينشئ نسخة عميقة دقيقة من هذا [Font](/imaging/python-net/aspose.imaging/font/). |


### Constructor: Font(font_name, em_size) {#Font_font_name_em_size_1}


```
 Font(font_name, em_size) 
```

ينشئ كائنًا جديدًا من [Font](/imaging/python-net/aspose.imaging/font/) باستخدام حجم محدد. يتم تعيين مجموعة الأحرف إلى [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/)، ووحدة الرسومات إلى [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/)، ونمط الخط إلى [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| font_name | string | تمثيل نصي لاسم الـ [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | حجم الـ em، بالنقاط، للخط الجديد. |

### Constructor: Font(font_name, em_size, style) {#Font_font_name_em_size_style_2}


```
 Font(font_name, em_size, style) 
```

ينشئ كائنًا جديدًا من [Font](/imaging/python-net/aspose.imaging/font/) باستخدام حجم ونمط محددين. يتم تعيين مجموعة الأحرف إلى [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/)، ووحدة الرسومات إلى [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| font_name | string | تمثيل نصي لاسم الـ [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | حجم الـ em، بالنقاط، للخط الجديد. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | الـ [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) للخط الجديد. |

### Constructor: Font(font_name, em_size, style, unit) {#Font_font_name_em_size_style_unit_3}


```
 Font(font_name, em_size, style, unit) 
```

ينشئ كائنًا جديدًا من [Font](/imaging/python-net/aspose.imaging/font/) باستخدام حجم ونمط ووحدة محددين.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| font_name | string | تمثيل نصي لاسم الـ [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | حجم الـ em للخط الجديد بالوحدات المحددة بواسطة المعامل _unit_. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | الـ [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) للخط الجديد. |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | الـ [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) للخط الجديد. |

### Constructor: Font(font_name, em_size, style, unit, character_set) {#Font_font_name_em_size_style_unit_character_set_4}


```
 Font(font_name, em_size, style, unit, character_set) 
```

ينشئ كائنًا جديدًا من [Font](/imaging/python-net/aspose.imaging/font/) باستخدام حجم ونمط ووحدة ومجموعة أحرف محددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| font_name | string | تمثيل نصي لاسم الـ [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | حجم الـ em للخط الجديد بالوحدات المحددة بواسطة المعامل _unit_. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | الـ [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) للخط الجديد. |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | الـ [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) للخط الجديد. |
| character_set | [CharacterSet](/imaging/python-net/aspose.imaging/characterset/) | مجموعة أحرف لاستخدامها مع هذا الخط. |

### Constructor: Font(font_name, em_size, unit) {#Font_font_name_em_size_unit_5}


```
 Font(font_name, em_size, unit) 
```

ينشئ كائنًا جديدًا من [Font](/imaging/python-net/aspose.imaging/font/) باستخدام حجم ووحدة محددين. يتم تعيين مجموعة الأحرف إلى [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/)، ويتم تعيين النمط إلى [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| font_name | string | تمثيل نصي لاسم الـ [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | حجم الـ em للخط الجديد بالوحدات المحددة بواسطة المعامل _unit_. |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | الـ [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) للخط الجديد. |

### Constructor: Font(prototype, new_style) {#Font_prototype_new_style_6}


```
 Font(prototype, new_style) 
```

ينشئ كائنًا جديدًا من [Font](/imaging/python-net/aspose.imaging/font/) يستخدم الـ [Font](/imaging/python-net/aspose.imaging/font/) الموجود المحدد وتعداد [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| prototype | [Font](/imaging/python-net/aspose.imaging/font/) | الـ [Font](/imaging/python-net/aspose.imaging/font/) الموجود الذي يُستخدم لإنشاء الـ [Font](/imaging/python-net/aspose.imaging/font/) الجديد. |
| new_style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | الـ [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) لتطبيقه على الـ [Font](/imaging/python-net/aspose.imaging/font/) الجديد. يمكن دمج قيم متعددة من تعداد الـ [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) باستخدام عامل OR. |

### Method: create_from_prototype(prototype, new_style)  [static] {#create_from_prototype_prototype_new_style_1}


```
 create_from_prototype(prototype, new_style) 
```

ينشئ كائنًا جديدًا من [Font](/imaging/python-net/aspose.imaging/font/) يستخدم الـ [Font](/imaging/python-net/aspose.imaging/font/) الموجود المحدد وتعداد [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| prototype | [Font](/imaging/python-net/aspose.imaging/font/) | الـ [Font](/imaging/python-net/aspose.imaging/font/) الموجود الذي يُستخدم لإنشاء الـ [Font](/imaging/python-net/aspose.imaging/font/) الجديد. |
| new_style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | الـ [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) لتطبيقه على الـ [Font](/imaging/python-net/aspose.imaging/font/) الجديد. يمكن دمج قيم متعددة من تعداد الـ [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) باستخدام عامل OR. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) |  |


### Method: create_with_size(font_name, em_size)  [static] {#create_with_size_font_name_em_size_2}


```
 create_with_size(font_name, em_size) 
```

ينشئ كائنًا جديدًا من [Font](/imaging/python-net/aspose.imaging/font/) باستخدام حجم محدد. يتم تعيين مجموعة الأحرف إلى [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/)، ووحدة الرسومات إلى [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/)، ونمط الخط إلى [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| font_name | string | تمثيل نصي لاسم الـ [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | حجم الـ em، بالنقاط، للخط الجديد. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) |  |


### Method: create_with_size_style(font_name, em_size, style)  [static] {#create_with_size_style_font_name_em_size_style_3}


```
 create_with_size_style(font_name, em_size, style) 
```

ينشئ كائنًا جديدًا من [Font](/imaging/python-net/aspose.imaging/font/) باستخدام حجم ونمط محددين. يتم تعيين مجموعة الأحرف إلى [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/)، ووحدة الرسومات إلى [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| font_name | string | تمثيل نصي لاسم الـ [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | حجم الـ em، بالنقاط، للخط الجديد. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | الـ [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) للخط الجديد. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) |  |


### Method: create_with_size_unit(font_name, em_size, unit)  [static] {#create_with_size_unit_font_name_em_size_unit_4}


```
 create_with_size_unit(font_name, em_size, unit) 
```

ينشئ كائنًا جديدًا من [Font](/imaging/python-net/aspose.imaging/font/) باستخدام حجم ووحدة محددين. يتم تعيين مجموعة الأحرف إلى [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/)، ويتم تعيين النمط إلى [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| font_name | string | تمثيل نصي لاسم الـ [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | حجم الـ em للخط الجديد بالوحدات المحددة بواسطة المعامل _unit_. |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | الـ [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) للخط الجديد. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) |  |


### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

ينشئ نسخة عميقة دقيقة من هذا [Font](/imaging/python-net/aspose.imaging/font/).

**Returns**

| نوع | الوصف |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) | الـ [Font](/imaging/python-net/aspose.imaging/font/) الذي تنشئه هذه الطريقة. |


