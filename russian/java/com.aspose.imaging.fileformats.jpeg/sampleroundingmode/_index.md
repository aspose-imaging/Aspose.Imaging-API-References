---
title: "SampleRoundingMode"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Определяет способ, которым n-битное значение преобразуется в 8-битное значение."
type: docs
weight: 17
url: /ru/java/com.aspose.imaging.fileformats.jpeg/sampleroundingmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class SampleRoundingMode extends System.Enum
```

Определяет способ, которым n-битное значение преобразуется в 8-битное значение.
## Поля

| Поле | Описание |
| --- | --- |
| [Extrapolate](#Extrapolate) | Экстраполировать 8-битное значение, чтобы разместить его в n битах, где 1 < n < 8. |
| [Truncate](#Truncate) | Обрезать 8-битное значение, чтобы разместить его в n битах, где 1 < n < 8. |
### Extrapolate {#Extrapolate}
```
public static final int Extrapolate
```


Экстраполировать 8-битное значение, чтобы разместить его в n битах, где 1 < n < 8. Количество всех возможных 8-битных значений равно 1 << 8 = 256, от 0 до 255. Количество всех возможных n-битных значений равно 1 << n, от 0 до (1 << n) - 1. Наиболее разумное n-битное значение Vn, соответствующее некоторому 8-битному значению V8, равно Vn = V8 >> (8 - n).

### Truncate {#Truncate}
```
public static final int Truncate
```


Обрезать 8-битное значение, чтобы разместить его в n битах, где 1 < n < 8. Количество всех возможных n-битных значений равно 1 << n, от 0 до (1 << n) - 1. Наиболее разумное n-битное значение Vn, соответствующее некоторому 8-битному значению V8, равно Vn = V8 & ((1 << n) - 1).

