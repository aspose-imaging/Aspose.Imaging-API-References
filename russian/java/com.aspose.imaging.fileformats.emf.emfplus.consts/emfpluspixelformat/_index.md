---
title: "EmfPlusPixelFormat"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Перечисление PixelFormat определяет форматы пикселей, поддерживаемые в EMF‑битмапах."
type: docs
weight: 43
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixelformat/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusPixelFormat extends System.Enum
```

Перечисление PixelFormat определяет форматы пикселей, поддерживаемые в битмапах EMF+.
## Поля

| Поле | Описание |
| --- | --- |
| [PixelFormatUndefined](#PixelFormatUndefined) | Формат не указан. |
| [PixelFormat1bppIndexed](#PixelFormat1bppIndexed) | Формат монохромный, используется таблица поиска цветовой палитры. |
| [PixelFormat4bppIndexed](#PixelFormat4bppIndexed) | Формат 16‑цветный, используется таблица поиска цветовой палитры. |
| [PixelFormat8bppIndexed](#PixelFormat8bppIndexed) | Формат 256‑цветный, используется таблица поиска цветовой палитры. |
| [PixelFormat16bppGrayScale](#PixelFormat16bppGrayScale) | Формат 16 бит на пиксель, градации серого. |
| [PixelFormat16bppRGB555](#PixelFormat16bppRGB555) | Формат 16 бит на пиксель; по 5 бит используется для красного, зелёного и синего компонентов. |
| [PixelFormat16bppRGB565](#PixelFormat16bppRGB565) | Формат 16 бит на пиксель; 5 бит используется для красного компонента, 6 бит — для зелёного, и 5 бит — для синего компонента. |
| [PixelFormat16bppARGB1555](#PixelFormat16bppARGB1555) | Формат 16 бит на пиксель; 1 бит используется для альфа‑компонента, а по 5 бит — для красного, зелёного и синего компонентов. |
| [PixelFormat24bppRGB](#PixelFormat24bppRGB) | Формат 24 бита на пиксель; по 8 бит используется для красного, зелёного и синего компонентов. |
| [PixelFormat32bppRGB](#PixelFormat32bppRGB) | Формат 32 бита на пиксель; по 8 бит используется для красного, зелёного и синего компонентов. |
| [PixelFormat32bppARGB](#PixelFormat32bppARGB) | Формат 32 бита на пиксель; по 8 бит используется для альфа, красного, зелёного и синего компонентов. |
| [PixelFormat32bppPARGB](#PixelFormat32bppPARGB) | Формат 32 бита на пиксель; по 8 бит используется для альфа, красного, зелёного и синего компонентов. |
| [PixelFormat48bppRGB](#PixelFormat48bppRGB) | Формат 48 бит на пиксель; по 16 бит используется для красного, зелёного и синего компонентов. |
| [PixelFormat64bppARGB](#PixelFormat64bppARGB) | Формат 64 бита на пиксель; по 16 бит используется для альфа, красного, зелёного и синего компонентов. |
| [PixelFormat64bppPARGB](#PixelFormat64bppPARGB) | Формат 64 бита на пиксель; по 16 бит используется для альфа, красного, зелёного и синего компонентов. |
### PixelFormatUndefined {#PixelFormatUndefined}
```
public static final int PixelFormatUndefined
```


Формат не указан.

--------------------

Форматы пикселей задаются объектами [EmfPlusBitmap](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap). Они кодируются следующим образом: - Биты 0‑7: Перечисление констант формата пикселя, начиная с нуля. - Биты 8‑15: Общее количество бит на пиксель. - Бит 16: Если установлен, значение цвета индексируется в палитре. - Бит 17: Если установлен, значение цвета находится в формате, поддерживаемом GDI. - Бит 18: Если установлен, значение цвета имеет альфа‑компонент. - Бит 19: Если установлен, значение цвета имеет предумноженный альфа‑компонент. - Бит 20: Если установлен, поддерживаются расширенные цвета, 16 бит на канал. - Биты 21‑31: Зарезервировано.

### PixelFormat1bppIndexed {#PixelFormat1bppIndexed}
```
public static final int PixelFormat1bppIndexed
```


Формат монохромный, используется таблица поиска цветовой палитры.

### PixelFormat4bppIndexed {#PixelFormat4bppIndexed}
```
public static final int PixelFormat4bppIndexed
```


Формат 16‑цветный, используется таблица поиска цветовой палитры.

### PixelFormat8bppIndexed {#PixelFormat8bppIndexed}
```
public static final int PixelFormat8bppIndexed
```


Формат 256‑цветный, используется таблица поиска цветовой палитры.

### PixelFormat16bppGrayScale {#PixelFormat16bppGrayScale}
```
public static final int PixelFormat16bppGrayScale
```


Формат 16 бит на пиксель, градации серого.

### PixelFormat16bppRGB555 {#PixelFormat16bppRGB555}
```
public static final int PixelFormat16bppRGB555
```


Формат 16 бит на пиксель; по 5 бит используется для красного, зелёного и синего компонентов. Оставшийся бит не используется.

### PixelFormat16bppRGB565 {#PixelFormat16bppRGB565}
```
public static final int PixelFormat16bppRGB565
```


Формат 16 бит на пиксель; 5 бит используется для красного компонента, 6 бит — для зелёного, и 5 бит — для синего компонента.

### PixelFormat16bppARGB1555 {#PixelFormat16bppARGB1555}
```
public static final int PixelFormat16bppARGB1555
```


Формат 16 бит на пиксель; 1 бит используется для альфа‑компонента, а по 5 бит — для красного, зелёного и синего компонентов.

### PixelFormat24bppRGB {#PixelFormat24bppRGB}
```
public static final int PixelFormat24bppRGB
```


Формат 24 бита на пиксель; по 8 бит используется для красного, зелёного и синего компонентов.

### PixelFormat32bppRGB {#PixelFormat32bppRGB}
```
public static final int PixelFormat32bppRGB
```


Формат 32 бита на пиксель; по 8 бит используется для красного, зелёного и синего компонентов. Оставшиеся 8 бит не используются.

### PixelFormat32bppARGB {#PixelFormat32bppARGB}
```
public static final int PixelFormat32bppARGB
```


Формат 32 бита на пиксель; по 8 бит используется для альфа, красного, зелёного и синего компонентов.

### PixelFormat32bppPARGB {#PixelFormat32bppPARGB}
```
public static final int PixelFormat32bppPARGB
```


Формат 32 бита на пиксель; по 8 бит используется для альфа, красного, зелёного и синего компонентов. Красный, зелёный и синий компоненты предумножены в соответствии с альфа‑компонентом.

### PixelFormat48bppRGB {#PixelFormat48bppRGB}
```
public static final int PixelFormat48bppRGB
```


Формат 48 бит на пиксель; по 16 бит используется для красного, зелёного и синего компонентов.

### PixelFormat64bppARGB {#PixelFormat64bppARGB}
```
public static final int PixelFormat64bppARGB
```


Формат 64 бита на пиксель; по 16 бит используется для альфа, красного, зелёного и синего компонентов.

### PixelFormat64bppPARGB {#PixelFormat64bppPARGB}
```
public static final int PixelFormat64bppPARGB
```


Формат 64 бита на пиксель; по 16 бит используется для альфа, красного, зелёного и синего компонентов. Красный, зелёный и синий компоненты предумножены в соответствии с альфа‑компонентом.

