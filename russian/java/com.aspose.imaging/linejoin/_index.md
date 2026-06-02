---
title: "LineJoin"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Указывает, как соединять последовательные отрезки линий или кривых в подпути фигуры, содержащейся в объекте GraphicsPath."
type: docs
weight: 69
url: /ru/java/com.aspose.imaging/linejoin/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LineJoin extends System.Enum
```

Указывает, как соединять последовательные отрезки линий или кривых в фигуре (подпути), содержащейся в объекте `GraphicsPath`.
## Поля

| Поле | Описание |
| --- | --- |
| [Miter](#Miter) | Указывает соединение в виде косого среза. |
| [Bevel](#Bevel) | Указывает соединение с фаской. |
| [Round](#Round) | Указывает соединение по окружности. |
| [MiterClipped](#MiterClipped) | Указывает соединение в виде косого среза. |
### Miter {#Miter}
```
public static final int Miter
```


Указывает соединение в виде косого среза. Это создает острую или обрезанную вершину, в зависимости от того, превышает ли длина среза предел среза.

### Bevel {#Bevel}
```
public static final int Bevel
```


Указывает соединение с фаской. Это создает диагональный угол.

### Round {#Round}
```
public static final int Round
```


Указывает соединение по окружности. Это создает плавную круглую дугу между линиями.

### MiterClipped {#MiterClipped}
```
public static final int MiterClipped
```


Указывает соединение с срезом. Это создаёт острый угол или скруглённый угол, в зависимости от того, превышает ли длина среза предел среза.

