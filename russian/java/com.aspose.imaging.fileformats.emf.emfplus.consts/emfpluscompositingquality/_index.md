---
title: "EmfPlusCompositingQuality"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Перечисление CompositingQuality определяет уровни качества при создании составных изображений."
type: docs
weight: 15
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluscompositingquality/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusCompositingQuality extends System.Enum
```

Перечисление CompositingQuality определяет уровни качества при создании составных изображений.
## Поля

| Поле | Описание |
| --- | --- |
| [CompositingQualityDefault](#CompositingQualityDefault) | Гамма‑коррекция не выполняется. |
| [CompositingQualityHighSpeed](#CompositingQualityHighSpeed) | Гамма‑коррекция не выполняется. |
| [CompositingQualityHighQuality](#CompositingQualityHighQuality) | Выполняется гамма‑коррекция. |
| [CompositingQualityGammaCorrected](#CompositingQualityGammaCorrected) | Включите гамма‑коррекцию для более качественного композитинга при более низкой скорости. |
| [CompositingQualityAssumeLinear](#CompositingQualityAssumeLinear) | Гамма‑коррекция не выполняется; однако использование линейных значений дает лучшее качество, чем значение по умолчанию, при слегка более низкой скорости. |
### CompositingQualityDefault {#CompositingQualityDefault}
```
public static final byte CompositingQualityDefault
```


Гамма‑коррекция не выполняется. Гамма‑коррекция управляет общей яркостью и контрастом изображения. Без гамма‑коррекции композитные изображения могут выглядеть слишком светлыми или слишком темными.

### CompositingQualityHighSpeed {#CompositingQualityHighSpeed}
```
public static final byte CompositingQualityHighSpeed
```


Гамма‑коррекция не выполняется. Приоритет отдается скорости композитинга в ущерб качеству. Что касается результата, то разницы между этим значением и CompositingQualityDefault нет.

### CompositingQualityHighQuality {#CompositingQualityHighQuality}
```
public static final byte CompositingQualityHighQuality
```


Выполняется гамма‑коррекция. Приоритет отдается качеству композитинга в ущерб скорости.

### CompositingQualityGammaCorrected {#CompositingQualityGammaCorrected}
```
public static final byte CompositingQualityGammaCorrected
```


Включите гамма‑коррекцию для более качественного композитинга при более низкой скорости. Что касается результата, то разницы между этим значением и CompositingQualityHighQuality нет.

### CompositingQualityAssumeLinear {#CompositingQualityAssumeLinear}
```
public static final byte CompositingQualityAssumeLinear
```


Гамма‑коррекция не выполняется; однако использование линейных значений дает лучшее качество, чем значение по умолчанию, при слегка более низкой скорости.

