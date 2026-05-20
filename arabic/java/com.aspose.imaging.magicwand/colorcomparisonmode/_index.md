---
title: "ColorComparisonMode"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يحدد كيفية مقارنة الألوان أثناء خوارزمية Magic Wand."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.magicwand/colorcomparisonmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorComparisonMode extends System.Enum
```

يحدد كيفية مقارنة الألوان أثناء خوارزمية Magic Wand.
## الحقول

| حقل | الوصف |
| --- | --- |
| [RgbDefault](#RgbDefault) | يتم مقارنة الألوان في مساحة اللون RGB. |
| [YuvDefault](#YuvDefault) | يتم مقارنة الألوان في مساحة اللون YUV. |
| [YuvLessLumaSensitive](#YuvLessLumaSensitive) | يتم مقارنة الألوان في مساحة اللون YUV. |
| [Custom](#Custom) | خوارزمية مقارنة اللون يحددها المستخدم. |
### RgbDefault {#RgbDefault}
```
public static final int RgbDefault
```


يتم مقارنة الألوان في مساحة اللون RGB. يجب أن يفي كل فرق لوني بالحد.

### YuvDefault {#YuvDefault}
```
public static final int YuvDefault
```


يتم مقارنة الألوان في مساحة اللون YUV. يجب أن يفي كل فرق لوني بالحد.

### YuvLessLumaSensitive {#YuvLessLumaSensitive}
```
public static final int YuvLessLumaSensitive
```


يتم مقارنة الألوان في مساحة اللون YUV. يجب أن تفي اختلافات معلومات اللون بالحد، ويُضاعف الحد لمكوّن الإضاءة.

### Custom {#Custom}
```
public static final int Custom
```


خوارزمية مقارنة اللون يحددها المستخدم.

