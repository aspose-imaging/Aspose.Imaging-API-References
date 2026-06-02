---
title: "EmfPenStyle"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Перечисление PenStyle определяет атрибуты перьев, которые могут использоваться в графических операциях."
type: docs
weight: 34
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.consts/emfpenstyle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPenStyle extends System.Enum
```

Перечисление PenStyle определяет атрибуты перьев, которые могут использоваться в графических операциях. Стиль пера представляет собой комбинацию типа пера, стиля линии, окончания линии и соединения линии.
## Поля

| Поле | Описание |
| --- | --- |
| [PS_COSMETIC](#PS-COSMETIC) | Тип пера, который задаёт линию шириной в одну логическую единицу и стиль, представляющий сплошной цвет |
| [PS_ENDCAP_ROUND](#PS-ENDCAP-ROUND) | Окончание линии, которое задаёт круглые концы. |
| [PS_JOIN_ROUND](#PS-JOIN-ROUND) | Соединение линии, которое задаёт круглые соединения |
| [PS_SOLID](#PS-SOLID) | Стиль линии, представляющий сплошной цвет |
| [PS_DASH](#PS-DASH) | Стиль линии, представляющий пунктир |
| [PS_DOT](#PS-DOT) | Стиль линии, представляющий точечный. |
| [PS_DASHDOT](#PS-DASHDOT) | Стиль линии, состоящий из чередующихся тире и точек |
| [PS_DASHDOTDOT](#PS-DASHDOTDOT) | Стиль линии, состоящий из тире и двойных точек. |
| [PS_NULL](#PS-NULL) | Стиль линии, который невидим. |
| [PS_INSIDEFRAME](#PS-INSIDEFRAME) | Стиль линии, представляющий сплошной цвет. |
| [PS_USERSTYLE](#PS-USERSTYLE) | Стиль линии, определяемый массивом стилей, который задает длины тире и промежутков в линии. |
| [PS_ALTERNATE](#PS-ALTERNATE) | Стиль линии, в которой каждый второй пиксель установлен. |
| [PS_ENDCAP_SQUARE](#PS-ENDCAP-SQUARE) | Конец линии, указывающий квадратные окончания. |
| [PS_ENDCAP_FLAT](#PS-ENDCAP-FLAT) | Конец линии, указывающий плоские окончания. |
| [PS_JOIN_BEVEL](#PS-JOIN-BEVEL) | Соединение линий, указывающее фасетные соединения. |
| [PS_JOIN_MITER](#PS-JOIN-MITER) | Соединение линий, указывающее на срезанные соединения, когда длина соединений находится в пределах текущего предела длины среза, установленного в контексте устройства воспроизведения. |
| [PS_GEOMETRIC](#PS-GEOMETRIC) | Тип пера, указывающий линию с шириной, измеряемой в логических единицах, и стиль, который может содержать любые атрибуты кисти. |
| [StyleMask](#StyleMask) | Маска стиля |
| [EndCapMask](#EndCapMask) | Маска конца |
| [JoinMask](#JoinMask) | Маска соединения |
| [TypeMask](#TypeMask) | Маска типа |
### PS_COSMETIC {#PS-COSMETIC}
```
public static final int PS_COSMETIC
```


Тип пера, который задаёт линию шириной в одну логическую единицу и стиль, представляющий сплошной цвет

### PS_ENDCAP_ROUND {#PS-ENDCAP-ROUND}
```
public static final int PS_ENDCAP_ROUND
```


Окончание линии, которое задаёт круглые концы.

### PS_JOIN_ROUND {#PS-JOIN-ROUND}
```
public static final int PS_JOIN_ROUND
```


Соединение линии, которое задаёт круглые соединения

### PS_SOLID {#PS-SOLID}
```
public static final int PS_SOLID
```


Стиль линии, представляющий сплошной цвет

### PS_DASH {#PS-DASH}
```
public static final int PS_DASH
```


Стиль линии, представляющий пунктир

### PS_DOT {#PS-DOT}
```
public static final int PS_DOT
```


Стиль линии, представляющий точечный.

### PS_DASHDOT {#PS-DASHDOT}
```
public static final int PS_DASHDOT
```


Стиль линии, состоящий из чередующихся тире и точек

### PS_DASHDOTDOT {#PS-DASHDOTDOT}
```
public static final int PS_DASHDOTDOT
```


Стиль линии, состоящий из тире и двойных точек.

### PS_NULL {#PS-NULL}
```
public static final int PS_NULL
```


Стиль линии, который невидим.

### PS_INSIDEFRAME {#PS-INSIDEFRAME}
```
public static final int PS_INSIDEFRAME
```


Стиль линии, представляющий сплошной цвет. Когда этот стиль указывается в записи рисования, принимающей ограничивающий прямоугольник, размеры фигуры уменьшаются так, чтобы полностью помещаться в ограничивающий прямоугольник с учётом ширины пера.

### PS_USERSTYLE {#PS-USERSTYLE}
```
public static final int PS_USERSTYLE
```


Стиль линии, определяемый массивом стилей, который задает длины тире и промежутков в линии.

### PS_ALTERNATE {#PS-ALTERNATE}
```
public static final int PS_ALTERNATE
```


Стиль линии, в которой каждый второй пиксель установлен. Этот стиль применим только к типу пера PS\_COSMETIC.

### PS_ENDCAP_SQUARE {#PS-ENDCAP-SQUARE}
```
public static final int PS_ENDCAP_SQUARE
```


Конец линии, указывающий квадратные окончания.

### PS_ENDCAP_FLAT {#PS-ENDCAP-FLAT}
```
public static final int PS_ENDCAP_FLAT
```


Конец линии, указывающий плоские окончания.

### PS_JOIN_BEVEL {#PS-JOIN-BEVEL}
```
public static final int PS_JOIN_BEVEL
```


Соединение линий, указывающее фасетные соединения.

### PS_JOIN_MITER {#PS-JOIN-MITER}
```
public static final int PS_JOIN_MITER
```


Соединение линий, указывающее на срезанные соединения, когда длина соединений находится в пределах текущего предела длины среза, установленного в контексте устройства воспроизведения. Если длина соединений превышает предел среза, указываются фасетные соединения.

### PS_GEOMETRIC {#PS-GEOMETRIC}
```
public static final int PS_GEOMETRIC
```


Тип пера, указывающий линию с шириной, измеряемой в логических единицах, и стиль, который может содержать любые атрибуты кисти.

### StyleMask {#StyleMask}
```
public static final int StyleMask
```


Маска стиля

### EndCapMask {#EndCapMask}
```
public static final int EndCapMask
```


Маска конца

### JoinMask {#JoinMask}
```
public static final int JoinMask
```


Маска соединения

### TypeMask {#TypeMask}
```
public static final int TypeMask
```


Маска типа

