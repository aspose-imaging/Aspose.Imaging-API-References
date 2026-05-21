---
title: "ColorComparisonMode"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Указывает, как сравниваются цвета во время работы алгоритма Magic Wand."
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.magicwand/colorcomparisonmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorComparisonMode extends System.Enum
```

Указывает, как сравниваются цвета во время работы алгоритма Magic Wand.
## Поля

| Поле | Описание |
| --- | --- |
| [RgbDefault](#RgbDefault) | Цвета сравниваются в цветовом пространстве RGB. |
| [YuvDefault](#YuvDefault) | Цвета сравниваются в цветовом пространстве YUV. |
| [YuvLessLumaSensitive](#YuvLessLumaSensitive) | Цвета сравниваются в цветовом пространстве YUV. |
| [Custom](#Custom) | Алгоритм сравнения цветов задаётся пользователем. |
### RgbDefault {#RgbDefault}
```
public static final int RgbDefault
```


Цвета сравниваются в цветовом пространстве RGB. Каждое различие цветов должно удовлетворять порогу.

### YuvDefault {#YuvDefault}
```
public static final int YuvDefault
```


Цвета сравниваются в цветовом пространстве YUV. Каждое различие цветов должно удовлетворять порогу.

### YuvLessLumaSensitive {#YuvLessLumaSensitive}
```
public static final int YuvLessLumaSensitive
```


Цвета сравниваются в цветовом пространстве YUV. Различия в цветовой информации должны удовлетворять порогу, порог для компоненты яркости удваивается.

### Custom {#Custom}
```
public static final int Custom
```


Алгоритм сравнения цветов задаётся пользователем.

