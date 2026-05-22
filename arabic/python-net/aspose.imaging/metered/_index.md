---
title: "فئة مقنّطة"
type: docs
weight: 6150
url: /ar/python-net/aspose.imaging/metered/
---

**Summary:** Provides metered methods for integration

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Metered

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [Metered()](#Metered__1) | يُنشئ مثيلاً جديداً لهذه الفئة. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_consumption_credit()](#get_consumption_credit__1) | يحصل على رصيد الاستهلاك |
| [get_consumption_quantity()](#get_consumption_quantity__2) | يحصل على حجم ملف الاستهلاك |
| [set_metered_key(public_key, private_key)](#set_metered_key_public_key_private_key_3) | يضبط المفتاح العام والخاص المقنن.<br/>            إذا قمت بشراء ترخيص مقنن، عند بدء التطبيق، يجب استدعاء هذه الواجهة البرمجية، عادةً هذا يكفي. <br/>            ومع ذلك، إذا فشل دائمًا تحميل بيانات الاستهلاك وتجاوز 24 ساعة، سيتم تعيين الترخيص إلى حالة التقييم، <br/>            لتجنب هذه الحالة، يجب عليك فحص حالة الترخيص بانتظام، إذا كانت حالة التقييم، استدعِ هذه الواجهة البرمجية مرة أخرى. |


### Constructor: Metered() {#Metered__1}


```
 Metered() 
```

يُنشئ مثيلاً جديداً لهذه الفئة.

### Method: get_consumption_credit()  [static] {#get_consumption_credit__1}


```
 get_consumption_credit() 
```

يحصل على رصيد الاستهلاك

**Returns**

| نوع | الوصف |
| :- | :- |
| System.Decimal | كمية الاستهلاك |


### Method: get_consumption_quantity()  [static] {#get_consumption_quantity__2}


```
 get_consumption_quantity() 
```

يحصل على حجم ملف الاستهلاك

**Returns**

| نوع | الوصف |
| :- | :- |
| System.Decimal | كمية الاستهلاك |


### Method: set_metered_key(public_key, private_key) {#set_metered_key_public_key_private_key_3}


```
 set_metered_key(public_key, private_key) 
```

يضبط المفتاح العام والخاص المقنن.<br/>            إذا قمت بشراء ترخيص مقنن، عند بدء التطبيق، يجب استدعاء هذه الواجهة البرمجية، عادةً هذا يكفي. <br/>            ومع ذلك، إذا فشل دائمًا تحميل بيانات الاستهلاك وتجاوز 24 ساعة، سيتم تعيين الترخيص إلى حالة التقييم، <br/>            لتجنب هذه الحالة، يجب عليك فحص حالة الترخيص بانتظام، إذا كانت حالة التقييم، استدعِ هذه الواجهة البرمجية مرة أخرى.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| public_key | string | المفتاح العام |
| private_key | string | المفتاح الخاص |

