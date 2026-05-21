---
title: "JpegLsInterleaveMode"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Определяет режим чередования для многокомпонентных цветовых пиксельных данных."
type: docs
weight: 15
url: /ru/java/com.aspose.imaging.fileformats.jpeg/jpeglsinterleavemode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class JpegLsInterleaveMode extends System.Enum
```

Определяет режим чередования для многокомпонентных (цветовых) пиксельных данных.
## Поля

| Поле | Описание |
| --- | --- |
| [None](#None) | Данные кодируются и сохраняются по компонентам: RRRGGGBBB. |
| [Line](#Line) | Режим чередования — по строкам. |
| [Sample](#Sample) | Данные кодируются и сохраняются по образцам. |
### None {#None}
```
public static final int None
```


Данные кодируются и сохраняются по компонентам: RRRGGGBBB.

### Line {#Line}
```
public static final int Line
```


Режим чередования — по строкам. Полная строка каждого компонента кодируется перед переходом к следующей строке.

### Sample {#Sample}
```
public static final int Sample
```


Данные кодируются и сохраняются по образцам. Для цветных изображений это формат типа RGBRGBRGB.

