---
title: "مقاس"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يوفر طرقًا محسوبة للتكامل"
type: docs
weight: 74
url: /ar/java/com.aspose.imaging/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

يوفر طرقًا محسوبة للتكامل

في هذا المثال، سيتم محاولة ضبط المفتاح العام والخاص المقاس

`// the component jar file: Metered metered = new Metered(); metered.setMeteredKey("PublicKey", "PrivateKey"); `
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Metered()](#Metered--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | يحصل على حجم ملف الاستهلاك |
| [getConsumptionCredit()](#getConsumptionCredit--) | يحصل على رصيد الاستهلاك |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | يضبط المفتاح العام والخاص المقاس. |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان الكائن المحدد يساوي هذه الحالة. |
### Metered() {#Metered--}
```
public Metered()
```


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


يحصل على حجم ملف الاستهلاك

**Returns:**
java.math.BigDecimal - حجم ملف الاستهلاك
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static BigDecimal getConsumptionCredit()
```


يحصل على رصيد الاستهلاك

**Returns:**
java.math.BigDecimal - كمية الاستهلاك
### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


يضبط المفتاح العام والخاص المقاس.

إذا قمت بشراء ترخيص مقاس، عند بدء التطبيق، يجب استدعاء هذه الـAPI، عادةً هذا يكفي. ومع ذلك، إذا فشل دائمًا في رفع بيانات الاستهلاك وتجاوز 24 ساعة، سيتم ضبط الترخيص إلى حالة التقييم، لتجنب هذه الحالة، يجب عليك فحص حالة الترخيص بانتظام، إذا كانت حالة التقييم، استدعِ هذه الـAPI مرة أخرى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| publicKey | java.lang.String | المفتاح العام |
| privateKey | java.lang.String | المفتاح الخاص |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كان الكائن المحدد يساوي هذه الحالة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن للمقارنة مع هذه الحالة. |

**Returns:**
boolean - `true` إذا كان الكائن المحدد يساوي هذه الحالة؛ وإلا، `false`.
