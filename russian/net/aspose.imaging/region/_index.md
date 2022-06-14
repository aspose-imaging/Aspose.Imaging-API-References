---
title: Region
second_title: Справочник по Aspose.Imaging for .NET API
description: Описывает внутреннюю часть графической фигуры состоящей из прямоугольников и путей. Этот класс не может быть унаследован.
type: docs
weight: 10860
url: /ru/net/aspose.imaging/region/
---
## Region class

Описывает внутреннюю часть графической фигуры, состоящей из прямоугольников и путей. Этот класс не может быть унаследован.

```csharp
public sealed class Region
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Region](region#constructor)() | Инициализирует новую[`Region`](../region). |
| [Region](region#constructor_1)(GraphicsPath) | Инициализирует новую[`Region`](../region)с указанным[`GraphicsPath`](../graphicspath). |
| [Region](region#constructor_2)(Rectangle) | Инициализирует новую[`Region`](../region)из указанной[`Rectangle`](../rectangle)структура. |
| [Region](region#constructor_3)(RectangleF) | Инициализирует новую[`Region`](../region)из указанной[`RectangleF`](../rectanglef)структура. |

## Методы

| Имя | Описание |
| --- | --- |
| [Complement](../../aspose.imaging/region/complement#complement)(GraphicsPath) | Обновляет этот[`Region`](../region), чтобы он содержал часть указанного[`GraphicsPath`](../graphicspath)который не пересекается с этим[`Region`](../region). |
| [Complement](../../aspose.imaging/region/complement#complement_1)(Rectangle) | Обновляет этот[`Region`](../region), чтобы он содержал часть указанногоСтруктураRectangle, которая не пересекается с этой[`Region`](../region). |
| [Complement](../../aspose.imaging/region/complement#complement_2)(RectangleF) | Обновляет этот[`Region`](../region), чтобы он содержал часть указанногоСтруктураRectangleF, которая не пересекается с этой[`Region`](../region). |
| [Complement](../../aspose.imaging/region/complement#complement_3)(Region) | Обновляет этот[`Region`](../region), чтобы он содержал часть указанного[`Region`](../region)который не пересекается с этим[`Region`](../region). |
| [DeepClone](../../aspose.imaging/region/deepclone)() | Создает точную глубокую копию этого[`Region`](../region). |
| [Equals](../../aspose.imaging/region/equals#equals)(Region, Graphics) | Проверяет, идентичен ли указанный[`Region`](../region)этому[`Region`](../region)на указанной поверхности рисования. |
| [Exclude](../../aspose.imaging/region/exclude#exclude)(GraphicsPath) | Обновляет этот[`Region`](../region), чтобы он содержал только ту часть его внутренней части, которая не пересекается с указанным[`GraphicsPath`](../graphicspath). |
| [Exclude](../../aspose.imaging/region/exclude#exclude_1)(Rectangle) | Обновляет этот[`Region`](../region), чтобы он содержал только ту часть его внутренней части, которая не пересекается с указанным[`Rectangle`](../rectangle)структура. |
| [Exclude](../../aspose.imaging/region/exclude#exclude_2)(RectangleF) | Обновляет этот[`Region`](../region), чтобы он содержал только ту часть его внутренней части, которая не пересекается с указанным[`RectangleF`](../rectanglef)структура. |
| [Exclude](../../aspose.imaging/region/exclude#exclude_3)(Region) | Обновляет этот[`Region`](../region), чтобы он содержал только ту часть его внутренней части, которая не пересекается с указанным[`Region`](../region). |
| [Intersect](../../aspose.imaging/region/intersect#intersect)(GraphicsPath) | Обновляет этот[`Region`](../region)до пересечения себя с указаннымПутькграфике. |
| [Intersect](../../aspose.imaging/region/intersect#intersect_1)(Rectangle) | Обновляет этот[`Region`](../region)до пересечения себя с указанным[`Rectangle`](../rectangle)структура. |
| [Intersect](../../aspose.imaging/region/intersect#intersect_2)(RectangleF) | Обновляет этот[`Region`](../region)до пересечения себя с указанным[`RectangleF`](../rectanglef)структура. |
| [Intersect](../../aspose.imaging/region/intersect#intersect_3)(Region) | Обновляет этот[`Region`](../region)до пересечения себя с указаннымОбласть,край. |
| [IsEmpty](../../aspose.imaging/region/isempty)(Graphics) | Проверяет, имеет ли этот[`Region`](../region)пустую внутреннюю часть на указанной поверхности рисования. |
| [IsInfinite](../../aspose.imaging/region/isinfinite)(Graphics) | Проверяет, имеет ли этот[`Region`](../region)бесконечный внутренний объем на указанной поверхности рисования. |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible)(Point) | Проверяет, содержится ли указанная структура[`Point`](../point)в этомОбласть,край. |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_2)(PointF) | Проверяет, содержится ли указанная структура[`PointF`](../pointf)в этомОбласть,край. |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_4)(Rectangle) | Проверяет, содержится ли какая-либо часть указанной структуры[`Rectangle`](../rectangle)внутри этойРегион. |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_6)(RectangleF) | Проверяет, содержится ли какая-либо часть указанной структуры[`RectangleF`](../rectanglef)внутри этойРегион. |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_11)(float, float) | Проверяет, содержится ли указанная точка в этом[`Region`](../region). |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_1)(Point, Graphics) | Проверяет, содержится ли указанная структура[`Point`](../point)в этом[`Region`](../region)при рисовании с использованием указанного[`Graphics`](../graphics). |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_3)(PointF, Graphics) | Проверяет, содержится ли указанная структура[`PointF`](../pointf)в этом[`Region`](../region)при рисовании с использованием указанного[`Graphics`](../graphics). |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_5)(Rectangle, Graphics) | Проверяет, содержится ли какая-либо часть указанной структуры[`Rectangle`](../rectangle)внутри этой[`Region`](../region)при рисовании с использованием указанного[`Graphics`](../graphics). |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_7)(RectangleF, Graphics) | Проверяет, содержится ли какая-либо часть указанной структуры[`RectangleF`](../rectanglef)внутри этой[`Region`](../region)при рисовании с использованием указанного[`Graphics`](../graphics). |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_12)(float, float, Graphics) | Проверяет, содержится ли указанная точка в этом[`Region`](../region)при рисовании с использованием указанного[`Graphics`](../graphics). |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_8)(int, int, Graphics) | Проверяет, содержится ли указанная точка в этом объекте[`Region`](../region)при рисовании с использованием указанного[`Graphics`](../graphics)объект. |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_13)(float, float, float, float) | Проверяет, содержится ли какая-либо часть указанного прямоугольника в этом[`Region`](../region). |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_9)(int, int, int, int) | Проверяет, содержится ли какая-либо часть указанного прямоугольника в этом[`Region`](../region). |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_14)(float, float, float, float, Graphics) | Проверяет, содержится ли какая-либо часть указанного прямоугольника в этом[`Region`](../region)при рисовании с использованием указанного[`Graphics`](../graphics). |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_10)(int, int, int, int, Graphics) | Проверяет, содержится ли какая-либо часть указанного прямоугольника в этом[`Region`](../region)при рисовании с использованием указанного[`Graphics`](../graphics). |
| [MakeEmpty](../../aspose.imaging/region/makeempty)() | Инициализирует это[`Region`](../region)пустым внутренним пространством. |
| [MakeInfinite](../../aspose.imaging/region/makeinfinite)() | Инициализирует этот[`Region`](../region)объект бесконечной внутренней частью. |
| [Transform](../../aspose.imaging/region/transform)(Matrix) | Преобразует это[`Region`](../region)по указанному[`Matrix`](../matrix). |
| [Translate](../../aspose.imaging/region/translate#translate_1)(float, float) | Смещает координаты этого[`Region`](../region)на указанную величину. |
| [Translate](../../aspose.imaging/region/translate#translate)(int, int) | Смещает координаты этого[`Region`](../region)на указанную величину. |
| [Union](../../aspose.imaging/region/union#union)(GraphicsPath) | Обновляет этот[`Region`](../region)до объединения самого себя и указанногоПутькграфике. |
| [Union](../../aspose.imaging/region/union#union_1)(Rectangle) | Обновляет этот[`Region`](../region)до объединения самого себя и указанного[`Rectangle`](../rectangle)структура. |
| [Union](../../aspose.imaging/region/union#union_2)(RectangleF) | Обновляет этот[`Region`](../region)до объединения самого себя и указанного[`RectangleF`](../rectanglef)структура. |
| [Union](../../aspose.imaging/region/union#union_3)(Region) | Обновляет этот[`Region`](../region)до объединения самого себя и указанногоОбласть,край. |
| [Xor](../../aspose.imaging/region/xor#xor)(GraphicsPath) | Обновляет этот[`Region`](../region)до объединения минус пересечение самого себя с указанным[`GraphicsPath`](../graphicspath). |
| [Xor](../../aspose.imaging/region/xor#xor_1)(Rectangle) | Обновляет этот[`Region`](../region)до объединения минус пересечение самого себя с указанным[`Rectangle`](../rectangle)структура. |
| [Xor](../../aspose.imaging/region/xor#xor_2)(RectangleF) | Обновляет этот[`Region`](../region)до объединения минус пересечение самого себя с указанным[`RectangleF`](../rectanglef)структура. |
| [Xor](../../aspose.imaging/region/xor#xor_3)(Region) | Обновляет этот[`Region`](../region)до объединения минус пересечение самого себя с указанным[`Region`](../region). |

### Смотрите также

* пространство имен [Aspose.Imaging](../../aspose.imaging)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
