---
title: WmfPenStyle
second_title: Справочник по Aspose.Imaging for .NET API
description: 16-битное перечисление PenStyle используется для указания различных типов перьев которые можно использовать в графических операциях.
type: docs
weight: 8270
url: /ru/net/aspose.imaging.fileformats.wmf.consts/wmfpenstyle/
---
## WmfPenStyle enumeration

16-битное перечисление PenStyle используется для указания различных типов перьев, которые можно использовать в графических операциях.

```csharp
public enum WmfPenStyle : short
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| Cosmetic | `0` | Косметика |
| EndcapRound | `0` | Концы строк круглые. |
| JoinRound | `0` | Соединения строк круглые. |
| Solid | `0` | Перо твердое. |
| Dash | `1` | Перо заштриховано. |
| Dot | `2` | Перо с точками. |
| Dashdot | `3` | На ручке чередуются тире и точки. |
| Dashdotdot | `4` | Перо имеет тире и двойные точки. |
| Null | `5` | Перо невидимо. |
| Insideframe | `6` | Перо твердое. Когда это перо используется в любой записи чертежа, которая принимает ограничивающий прямоугольник, размеры фигуры уменьшаются так, чтобы она полностью помещалась в ограничивающий прямоугольник с учетом ширины пера. |
| Userstyle | `7` | Перо использует массив стилей, предоставленный пользователем. |
| Alternate | `8` | Перо устанавливает каждый второй пиксель (этот стиль применим только для косметических перьев). |
| EndcapSquare | `256` | Концы строк квадратные. |
| EndcapFlat | `512` | Концы строк плоские. |
| JoinBevel | `4096` | Соединения линий скошены. |
| JoinMiter | `8192` | Соединения строк обрезаются, когда они находятся в пределах текущего предела , установленного записью SETMITERLIMIT META_ESCAPE. Соединение скошено, если оно превысит предел. |

### Смотрите также

* пространство имен [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
