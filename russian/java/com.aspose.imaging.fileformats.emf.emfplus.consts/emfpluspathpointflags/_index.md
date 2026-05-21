---
title: "EmfPlusPathPointFlags"
second_title: "Справочник API Aspose.Imaging для Java"
description: "32-битное беззнаковое целое число, которое определяет, как интерпретировать точки и связанные с ними типы точек, определённые этим объектом."
type: docs
weight: 38
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluspathpointflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusPathPointFlags extends System.Enum
```

32-битное беззнаковое целое, которое определяет, как интерпретировать точки и связанные типы точек, определённые этим объектом. C (1 бит): Если установлен, массив PathPoints задаёт абсолютные координаты в пространстве координат с 16‑битными целочисленными координатами. Если сброшен, массив PathPoints задаёт абсолютные координаты в пространстве координат с 32‑битными координатами с плавающей запятой. Примечание: если флаг P (см. ниже) установлен, этот флаг МОЖЕТ быть сброшен и ДОЛЖЕН игнорироваться. R (1 бит): Если установлен, типы точек в массиве PathPointTypes задаются объектами EmfPlusPathPointTypeRle (раздел 2.2.2.32), которые используют сжатие run-length encoding (RLE), и/или объектами EmfPlusPathPointType (раздел 2.2.2.31). См. [MS-WMF] раздел 3.1.6 для получения дополнительной информации о сжатии RLE. Если сброшен, типы точек в массиве PathPointTypes задаются объектами EmfPlusPathPointType. P (1 бит): Если установлен, каждый элемент массива PathPoints задаёт положение в пространстве координат, относительное к положению, указанному предыдущим элементом массива. Для первого элемента в PathPoints предполагается предыдущее положение с координатами (0,0). Если сброшен, каждый элемент массива PathPoints задаёт абсолютное положение.
## Поля

| Поле | Описание |
| --- | --- |
| [C](#C) | Флаг c |
| [R](#R) | Флаг r |
| [P](#P) | Флаг p |
### C {#C}
```
public static final short C
```


Флаг c

### R {#R}
```
public static final short R
```


Флаг r

### P {#P}
```
public static final short P
```


Флаг p

