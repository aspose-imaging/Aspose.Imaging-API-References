---
title: "Region"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Описывает внутреннюю часть графической формы, состоящей из прямоугольников и путей."
type: docs
weight: 95
url: /ru/java/com.aspose.imaging/region/
---
**Inheritance:**
java.lang.Object
```
public final class Region
```

Описывает внутреннюю часть графической формы, состоящей из прямоугольников и путей. Этот класс не может быть унаследован.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Region()](#Region--) | Инициализирует новый объект Region. |
| [Region(RectangleF rect)](#Region-com.aspose.imaging.RectangleF-) | Инициализирует новый `T:Aspose.Imaging.Region` из указанной структуры `T:Aspose.Imaging.RectangleF`. |
| [Region(Rectangle rect)](#Region-com.aspose.imaging.Rectangle-) | Инициализирует новый `T:Aspose.Imaging.Region` из указанной структуры `T:Aspose.Imaging.Rectangle`. |
| [Region(GraphicsPath path)](#Region-com.aspose.imaging.GraphicsPath-) | Инициализирует новый `T:Aspose.Imaging.Region` с указанным `T:Aspose.Imaging.GraphicsPath`. |
## Методы

| Метод | Описание |
| --- | --- |
| [deepClone()](#deepClone--) | Создаёт точную глубокую копию этого `com.aspose.imaging.region`. |
| [makeInfinite()](#makeInfinite--) | Инициализирует объект `com.aspose.imaging.Region` бесконечным внутренним пространством. |
| [makeEmpty()](#makeEmpty--) | Инициализирует `com.aspose.imaging.Region` пустым внутренним пространством. |
| [intersect(RectangleF rect)](#intersect-com.aspose.imaging.RectangleF-) | Обновляет этот `com.aspose.imaging.Region`, устанавливая его пересечение с указанной структурой `com.aspose.imaging.RectangleF`. |
| [intersect(Rectangle rect)](#intersect-com.aspose.imaging.Rectangle-) | Обновляет этот `com.aspose.imaging.Region`, устанавливая его пересечение с указанной структурой `com.aspose.imaging.Rectangle`. |
| [intersect(GraphicsPath path)](#intersect-com.aspose.imaging.GraphicsPath-) | Обновляет этот `com.aspose.imaging.Region`, устанавливая его пересечение с указанным `com.aspose.imaging.graphicsPath`. |
| [intersect(Region region)](#intersect-com.aspose.imaging.Region-) | Обновляет этот `com.aspose.imaging.Region`, устанавливая его пересечение с указанным `com.aspose.imaging.region`. |
| [union(RectangleF rect)](#union-com.aspose.imaging.RectangleF-) | Обновляет этот `com.aspose.imaging.Region`, устанавливая его объединение с указанной структурой `com.aspose.imaging.RectangleF`. |
| [union(Rectangle rect)](#union-com.aspose.imaging.Rectangle-) | Обновляет этот `com.aspose.imaging.Region`, устанавливая его объединение с указанной структурой `com.aspose.imaging.Rectangle`. |
| [union(GraphicsPath path)](#union-com.aspose.imaging.GraphicsPath-) | Обновляет этот `com.aspose.imaging.Region`, устанавливая его объединение с указанным `com.aspose.imaging.graphicsPath`. |
| [union(Region region)](#union-com.aspose.imaging.Region-) | Обновляет этот `com.aspose.imaging.Region`, устанавливая его объединение с указанным `com.aspose.imaging.region`. |
| [xor(RectangleF rect)](#xor-com.aspose.imaging.RectangleF-) | Обновляет этот `com.aspose.imaging.Region`, устанавливая его объединение за вычетом пересечения с указанной структурой `com.aspose.imaging.RectangleF`. |
| [xor(Rectangle rect)](#xor-com.aspose.imaging.Rectangle-) | Обновляет этот `com.aspose.imaging.Region`, приводя его к объединению минус пересечение с указанной структурой `com.aspose.imaging.Rectangle`. |
| [xor(GraphicsPath path)](#xor-com.aspose.imaging.GraphicsPath-) | Обновляет этот `com.aspose.imaging.Region`, приводя его к объединению минус пересечение с указанным `com.aspose.imaging.graphicsPath`. |
| [xor(Region region)](#xor-com.aspose.imaging.Region-) | Обновляет этот `com.aspose.imaging.Region`, приводя его к объединению минус пересечение с указанным `com.aspose.imaging.region`. |
| [exclude(RectangleF rect)](#exclude-com.aspose.imaging.RectangleF-) | Обновляет этот `com.aspose.imaging.Region`, оставляя только ту часть его внутренней области, которая не пересекается с указанной структурой `com.aspose.imaging.RectangleF`. |
| [exclude(Rectangle rect)](#exclude-com.aspose.imaging.Rectangle-) | Обновляет этот `com.aspose.imaging.Region`, оставляя только ту часть его внутренней области, которая не пересекается с указанной структурой `com.aspose.imaging.Rectangle`. |
| [exclude(GraphicsPath path)](#exclude-com.aspose.imaging.GraphicsPath-) | Обновляет этот `com.aspose.imaging.Region`, оставляя только ту часть его внутренней области, которая не пересекается с указанным `com.aspose.imaging.graphicsPath`. |
| [exclude(Region region)](#exclude-com.aspose.imaging.Region-) | Обновляет этот `com.aspose.imaging.Region`, оставляя только ту часть его внутренней области, которая не пересекается с указанным `com.aspose.imaging.region`. |
| [complement(RectangleF rect)](#complement-com.aspose.imaging.RectangleF-) | Обновляет этот `com.aspose.imaging.Region`, оставляя часть указанной структуры `com.aspose.imaging.RectangleF`, которая не пересекается с этим `com.aspose.imaging.region`. |
| [complement(Rectangle rect)](#complement-com.aspose.imaging.Rectangle-) | Обновляет этот `com.aspose.imaging.Region`, оставляя часть указанной структуры `com.aspose.imaging.Rectangle`, которая не пересекается с этим `com.aspose.imaging.region`. |
| [complement(GraphicsPath path)](#complement-com.aspose.imaging.GraphicsPath-) | Обновляет этот `com.aspose.imaging.Region`, оставляя часть указанного `com.aspose.imaging.GraphicsPath`, которая не пересекается с этим `com.aspose.imaging.region`. |
| [complement(Region region)](#complement-com.aspose.imaging.Region-) | Обновляет этот `com.aspose.imaging.Region`, оставляя часть указанного `com.aspose.imaging.Region`, которая не пересекается с этим `com.aspose.imaging.region`. |
| [translate(float dx, float dy)](#translate-float-float-) | Смещает координаты этого `com.aspose.imaging.Region` на указанную величину. |
| [translate(int dx, int dy)](#translate-int-int-) | Смещает координаты этого `com.aspose.imaging.Region` на указанную величину. |
| [transform(Matrix matrix)](#transform-com.aspose.imaging.Matrix-) | Преобразует этот `com.aspose.imaging.Region` с помощью указанной `com.aspose.imaging.matrix`. |
| [isEmpty(Graphics g)](#isEmpty-com.aspose.imaging.Graphics-) | Проверяет, имеет ли этот `com.aspose.imaging.Region` пустую внутреннюю область на указанной поверхности рисования. |
| [isInfinite(Graphics g)](#isInfinite-com.aspose.imaging.Graphics-) | Проверяет, имеет ли этот `com.aspose.imaging.Region` бесконечную внутреннюю область на указанной поверхности рисования. |
| [isEquals(Region region, Graphics g)](#isEquals-com.aspose.imaging.Region-com.aspose.imaging.Graphics-) | Проверяет, идентичен ли указанный `com.aspose.imaging.Region` этому `com.aspose.imaging.Region` на указанной поверхности рисования. |
| [isVisible(float x, float y)](#isVisible-float-float-) | Проверяет, содержится ли указанная точка внутри этого `com.aspose.imaging.region`. |
| [isVisible(PointF point)](#isVisible-com.aspose.imaging.PointF-) | Проверяет, содержится ли указанная структура `com.aspose.imaging.PointF` внутри этого `com.aspose.imaging.region`. |
| [isVisible(float x, float y, Graphics g)](#isVisible-float-float-com.aspose.imaging.Graphics-) | Проверяет, содержится ли указанная точка внутри этого `com.aspose.imaging.Region`, когда он отрисован с использованием указанного `com.aspose.imaging.graphics`. |
| [isVisible(PointF point, Graphics g)](#isVisible-com.aspose.imaging.PointF-com.aspose.imaging.Graphics-) | Проверяет, содержится ли указанная структура `com.aspose.imaging.PointF` внутри этого `com.aspose.imaging.Region`, когда он отрисован с использованием указанного `com.aspose.imaging.graphics`. |
| [isVisible(float x, float y, float width, float height)](#isVisible-float-float-float-float-) | Проверяет, содержится ли какая-либо часть указанного прямоугольника внутри этого `com.aspose.imaging.region`. |
| [isVisible(RectangleF rect)](#isVisible-com.aspose.imaging.RectangleF-) | Проверяет, содержится ли какая-либо часть указанной структуры `com.aspose.imaging.RectangleF` внутри этого `com.aspose.imaging.region`. |
| [isVisible(float x, float y, float width, float height, Graphics g)](#isVisible-float-float-float-float-com.aspose.imaging.Graphics-) | Проверяет, содержится ли какая-либо часть указанного прямоугольника внутри этого `com.aspose.imaging.Region`, когда он отрисован с использованием указанного `com.aspose.imaging.graphics`. |
| [isVisible(RectangleF rect, Graphics g)](#isVisible-com.aspose.imaging.RectangleF-com.aspose.imaging.Graphics-) | Проверяет, содержится ли какая-либо часть указанной структуры `com.aspose.imaging.RectangleF` внутри этого `com.aspose.imaging.Region`, когда он отрисован с использованием указанного `com.aspose.imaging.graphics`. |
| [isVisible(int x, int y, Graphics g)](#isVisible-int-int-com.aspose.imaging.Graphics-) | Проверяет, содержится ли указанная точка внутри этого объекта `com.aspose.imaging.Region`, когда он отрисован с использованием указанного объекта `com.aspose.imaging.Graphics`. |
| [isVisible(Point point)](#isVisible-com.aspose.imaging.Point-) | Проверяет, содержится ли указанная структура `com.aspose.imaging.Point` в данном `com.aspose.imaging.region`. |
| [isVisible(Point point, Graphics g)](#isVisible-com.aspose.imaging.Point-com.aspose.imaging.Graphics-) | Проверяет, содержится ли указанная структура `com.aspose.imaging.Point` в данном `com.aspose.imaging.Region`, когда она отрисована с использованием указанного `com.aspose.imaging.graphics`. |
| [isVisible(int x, int y, int width, int height)](#isVisible-int-int-int-int-) | Проверяет, содержится ли какая-либо часть указанного прямоугольника внутри этого `com.aspose.imaging.region`. |
| [isVisible(Rectangle rect)](#isVisible-com.aspose.imaging.Rectangle-) | Проверяет, содержится ли какая-либо часть указанной структуры `com.aspose.imaging.Rectangle` в данном `com.aspose.imaging.region`. |
| [isVisible(int x, int y, int width, int height, Graphics g)](#isVisible-int-int-int-int-com.aspose.imaging.Graphics-) | Проверяет, содержится ли какая-либо часть указанного прямоугольника внутри этого `com.aspose.imaging.Region`, когда он отрисован с использованием указанного `com.aspose.imaging.graphics`. |
| [isVisible(Rectangle rect, Graphics g)](#isVisible-com.aspose.imaging.Rectangle-com.aspose.imaging.Graphics-) | Проверяет, содержится ли какая-либо часть указанной структуры `com.aspose.imaging.Rectangle` в данном `com.aspose.imaging.Region`, когда она отрисована с использованием указанного `com.aspose.imaging.graphics`. |
| [equals(Object o)](#equals-java.lang.Object-) | Проверяет, равны ли объекты. |
| [hashCode()](#hashCode--) | Получает хеш‑код текущего объекта. |
### Region() {#Region--}
```
public Region()
```


Инициализирует новый объект Region.

### Region(RectangleF rect) {#Region-com.aspose.imaging.RectangleF-}
```
public Region(RectangleF rect)
```


Инициализирует новый `T:Aspose.Imaging.Region` из указанной структуры `T:Aspose.Imaging.RectangleF`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Структура `T:Aspose.Imaging.RectangleF`, определяющая внутреннюю часть нового `T:Aspose.Imaging.Region`. |

### Region(Rectangle rect) {#Region-com.aspose.imaging.Rectangle-}
```
public Region(Rectangle rect)
```


Инициализирует новый `T:Aspose.Imaging.Region` из указанной структуры `T:Aspose.Imaging.Rectangle`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Структура `T:Aspose.Imaging.Rectangle`, определяющая внутреннюю часть нового `T:Aspose.Imaging.Region`. |

### Region(GraphicsPath path) {#Region-com.aspose.imaging.GraphicsPath-}
```
public Region(GraphicsPath path)
```


Инициализирует новый `T:Aspose.Imaging.Region` с указанным `T:Aspose.Imaging.GraphicsPath`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Объект `T:Aspose.Imaging.GraphicsPath`, определяющий новый `T:Aspose.Imaging.Region`. |

### deepClone() {#deepClone--}
```
public Region deepClone()
```


Создаёт точную глубокую копию этого `com.aspose.imaging.region`.

**Returns:**
[Region](../../com.aspose.imaging/region) - The `com.aspose.imaging.Region` that this method creates.
### makeInfinite() {#makeInfinite--}
```
public void makeInfinite()
```


Инициализирует объект `com.aspose.imaging.Region` бесконечным внутренним пространством.

### makeEmpty() {#makeEmpty--}
```
public void makeEmpty()
```


Инициализирует `com.aspose.imaging.Region` пустым внутренним пространством.

### intersect(RectangleF rect) {#intersect-com.aspose.imaging.RectangleF-}
```
public void intersect(RectangleF rect)
```


Обновляет этот `com.aspose.imaging.Region`, устанавливая его пересечение с указанной структурой `com.aspose.imaging.RectangleF`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Структура `com.aspose.imaging.RectangleF` для пересечения с этим `com.aspose.imaging.region`. |

### intersect(Rectangle rect) {#intersect-com.aspose.imaging.Rectangle-}
```
public void intersect(Rectangle rect)
```


Обновляет этот `com.aspose.imaging.Region`, устанавливая его пересечение с указанной структурой `com.aspose.imaging.Rectangle`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Структура `com.aspose.imaging.Rectangle` для пересечения с этим `com.aspose.imaging.region`. |

### intersect(GraphicsPath path) {#intersect-com.aspose.imaging.GraphicsPath-}
```
public void intersect(GraphicsPath path)
```


Обновляет этот `com.aspose.imaging.Region`, устанавливая его пересечение с указанным `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Объект `com.aspose.imaging.GraphicsPath` для пересечения с этим `com.aspose.imaging.region`. |

### intersect(Region region) {#intersect-com.aspose.imaging.Region-}
```
public void intersect(Region region)
```


Обновляет этот `com.aspose.imaging.Region`, устанавливая его пересечение с указанным `com.aspose.imaging.region`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Объект `com.aspose.imaging.Region` для пересечения с этим `com.aspose.imaging.region`. |

### union(RectangleF rect) {#union-com.aspose.imaging.RectangleF-}
```
public void union(RectangleF rect)
```


Обновляет этот `com.aspose.imaging.Region`, устанавливая его объединение с указанной структурой `com.aspose.imaging.RectangleF`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Структура `com.aspose.imaging.RectangleF` для объединения с этим `com.aspose.imaging.region`. |

### union(Rectangle rect) {#union-com.aspose.imaging.Rectangle-}
```
public void union(Rectangle rect)
```


Обновляет этот `com.aspose.imaging.Region`, устанавливая его объединение с указанной структурой `com.aspose.imaging.Rectangle`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Структура `com.aspose.imaging.Rectangle` для объединения с этим `com.aspose.imaging.region`. |

### union(GraphicsPath path) {#union-com.aspose.imaging.GraphicsPath-}
```
public void union(GraphicsPath path)
```


Обновляет этот `com.aspose.imaging.Region`, устанавливая его объединение с указанным `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Объект `com.aspose.imaging.GraphicsPath` для объединения с этим `com.aspose.imaging.region`. |

### union(Region region) {#union-com.aspose.imaging.Region-}
```
public void union(Region region)
```


Обновляет этот `com.aspose.imaging.Region`, устанавливая его объединение с указанным `com.aspose.imaging.region`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Объект `com.aspose.imaging.Region` для объединения с этим `com.aspose.imaging.region`. |

### xor(RectangleF rect) {#xor-com.aspose.imaging.RectangleF-}
```
public void xor(RectangleF rect)
```


Обновляет этот `com.aspose.imaging.Region`, устанавливая его объединение за вычетом пересечения с указанной структурой `com.aspose.imaging.RectangleF`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Структура `com.aspose.imaging.RectangleF` для XOR с этим `com.aspose.imaging.region`. |

### xor(Rectangle rect) {#xor-com.aspose.imaging.Rectangle-}
```
public void xor(Rectangle rect)
```


Обновляет этот `com.aspose.imaging.Region`, приводя его к объединению минус пересечение с указанной структурой `com.aspose.imaging.Rectangle`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Структура `com.aspose.imaging.Rectangle` для XOR с этим `com.aspose.imaging.region`. |

### xor(GraphicsPath path) {#xor-com.aspose.imaging.GraphicsPath-}
```
public void xor(GraphicsPath path)
```


Обновляет этот `com.aspose.imaging.Region`, приводя его к объединению минус пересечение с указанным `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Объект `com.aspose.imaging.GraphicsPath` для XOR с этим `com.aspose.imaging.region`. |

### xor(Region region) {#xor-com.aspose.imaging.Region-}
```
public void xor(Region region)
```


Обновляет этот `com.aspose.imaging.Region`, приводя его к объединению минус пересечение с указанным `com.aspose.imaging.region`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Объект `com.aspose.imaging.Region` для XOR с этим `com.aspose.imaging.region`. |

### exclude(RectangleF rect) {#exclude-com.aspose.imaging.RectangleF-}
```
public void exclude(RectangleF rect)
```


Обновляет этот `com.aspose.imaging.Region`, оставляя только ту часть его внутренней области, которая не пересекается с указанной структурой `com.aspose.imaging.RectangleF`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Структура `com.aspose.imaging.RectangleF` для исключения из этого `com.aspose.imaging.region`. |

### exclude(Rectangle rect) {#exclude-com.aspose.imaging.Rectangle-}
```
public void exclude(Rectangle rect)
```


Обновляет этот `com.aspose.imaging.Region`, оставляя только ту часть его внутренней области, которая не пересекается с указанной структурой `com.aspose.imaging.Rectangle`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Структура `com.aspose.imaging.Rectangle` для исключения из этого `com.aspose.imaging.region`. |

### exclude(GraphicsPath path) {#exclude-com.aspose.imaging.GraphicsPath-}
```
public void exclude(GraphicsPath path)
```


Обновляет этот `com.aspose.imaging.Region`, оставляя только ту часть его внутренней области, которая не пересекается с указанным `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Объект `com.aspose.imaging.GraphicsPath` для исключения из этого `com.aspose.imaging.region`. |

### exclude(Region region) {#exclude-com.aspose.imaging.Region-}
```
public void exclude(Region region)
```


Обновляет этот `com.aspose.imaging.Region`, оставляя только ту часть его внутренней области, которая не пересекается с указанным `com.aspose.imaging.region`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Объект `com.aspose.imaging.Region` для исключения из этого `com.aspose.imaging.region`. |

### complement(RectangleF rect) {#complement-com.aspose.imaging.RectangleF-}
```
public void complement(RectangleF rect)
```


Обновляет этот `com.aspose.imaging.Region`, оставляя часть указанной структуры `com.aspose.imaging.RectangleF`, которая не пересекается с этим `com.aspose.imaging.region`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Структура `com.aspose.imaging.RectangleF` для дополнения этого `com.aspose.imaging.region`. |

### complement(Rectangle rect) {#complement-com.aspose.imaging.Rectangle-}
```
public void complement(Rectangle rect)
```


Обновляет этот `com.aspose.imaging.Region`, оставляя часть указанной структуры `com.aspose.imaging.Rectangle`, которая не пересекается с этим `com.aspose.imaging.region`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Структура `com.aspose.imaging.Rectangle` для дополнения этого `com.aspose.imaging.region`. |

### complement(GraphicsPath path) {#complement-com.aspose.imaging.GraphicsPath-}
```
public void complement(GraphicsPath path)
```


Обновляет этот `com.aspose.imaging.Region`, оставляя часть указанного `com.aspose.imaging.GraphicsPath`, которая не пересекается с этим `com.aspose.imaging.region`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Объект `com.aspose.imaging.GraphicsPath`, дополняющий этот `com.aspose.imaging.region`. |

### complement(Region region) {#complement-com.aspose.imaging.Region-}
```
public void complement(Region region)
```


Обновляет этот `com.aspose.imaging.Region`, оставляя часть указанного `com.aspose.imaging.Region`, которая не пересекается с этим `com.aspose.imaging.region`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Объект `com.aspose.imaging.Region`, дополняющий этот объект `com.aspose.imaging.Region`. |

### translate(float dx, float dy) {#translate-float-float-}
```
public void translate(float dx, float dy)
```


Смещает координаты этого `com.aspose.imaging.Region` на указанную величину.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dx | float | Величина смещения этого `com.aspose.imaging.Region` по горизонтали. |
| dy | float | Величина смещения этого `com.aspose.imaging.Region` по вертикали. |

### translate(int dx, int dy) {#translate-int-int-}
```
public void translate(int dx, int dy)
```


Смещает координаты этого `com.aspose.imaging.Region` на указанную величину.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dx | int | Величина смещения этого `com.aspose.imaging.Region` по горизонтали. |
| dy | int | Величина смещения этого `com.aspose.imaging.Region` по вертикали. |

### transform(Matrix matrix) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix matrix)
```


Преобразует этот `com.aspose.imaging.Region` с помощью указанной `com.aspose.imaging.matrix`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Объект `com.aspose.imaging.Matrix`, с помощью которого преобразуется этот `com.aspose.imaging.region`. |

### isEmpty(Graphics g) {#isEmpty-com.aspose.imaging.Graphics-}
```
public boolean isEmpty(Graphics g)
```


Проверяет, имеет ли этот `com.aspose.imaging.Region` пустую внутреннюю область на указанной поверхности рисования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.imaging/graphics) | `com.aspose.imaging.Graphics`, представляющий поверхность рисования. |

**Returns:**
boolean — true, если внутреннее пространство этого `com.aspose.imaging.Region` пусто при применении преобразования, связанного с `g`; иначе — false.
### isInfinite(Graphics g) {#isInfinite-com.aspose.imaging.Graphics-}
```
public boolean isInfinite(Graphics g)
```


Проверяет, имеет ли этот `com.aspose.imaging.Region` бесконечную внутреннюю область на указанной поверхности рисования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.imaging/graphics) | `com.aspose.imaging.Graphics`, представляющий поверхность рисования. |

**Returns:**
boolean — true, если внутреннее пространство этого `com.aspose.imaging.Region` бесконечно при применении преобразования, связанного с `g`; иначе — false.
### isEquals(Region region, Graphics g) {#isEquals-com.aspose.imaging.Region-com.aspose.imaging.Graphics-}
```
public boolean isEquals(Region region, Graphics g)
```


Проверяет, идентичен ли указанный `com.aspose.imaging.Region` этому `com.aspose.imaging.Region` на указанной поверхности рисования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | `com.aspose.imaging.Region` для тестирования. |
| g | [Graphics](../../com.aspose.imaging/graphics) | `com.aspose.imaging.Graphics`, представляющий поверхность рисования. |

**Returns:**
boolean — True, если внутреннее пространство региона идентично внутреннему пространству этого региона при применении преобразования, связанного с параметром `g`; иначе — false.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Проверяет, содержится ли указанная точка внутри этого `com.aspose.imaging.region`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата x проверяемой точки. |
| y | float | Координата y проверяемой точки. |

**Returns:**
boolean — True, когда указанная точка находится внутри этого `com.aspose.imaging.Region`; иначе — false.
### isVisible(PointF point) {#isVisible-com.aspose.imaging.PointF-}
```
public boolean isVisible(PointF point)
```


Проверяет, содержится ли указанная структура `com.aspose.imaging.PointF` внутри этого `com.aspose.imaging.region`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Структура `com.aspose.imaging.PointF` для тестирования. |

**Returns:**
boolean — true, когда `point` находится внутри этого `com.aspose.imaging.Region`; иначе — false.
### isVisible(float x, float y, Graphics g) {#isVisible-float-float-com.aspose.imaging.Graphics-}
```
public boolean isVisible(float x, float y, Graphics g)
```


Проверяет, содержится ли указанная точка внутри этого `com.aspose.imaging.Region`, когда он отрисован с использованием указанного `com.aspose.imaging.graphics`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата x проверяемой точки. |
| y | float | Координата y проверяемой точки. |
| g | [Graphics](../../com.aspose.imaging/graphics) | `com.aspose.imaging.Graphics`, представляющий графический контекст. |

**Returns:**
boolean — True, когда указанная точка находится внутри этого `com.aspose.imaging.Region`; иначе — false.
### isVisible(PointF point, Graphics g) {#isVisible-com.aspose.imaging.PointF-com.aspose.imaging.Graphics-}
```
public boolean isVisible(PointF point, Graphics g)
```


Проверяет, содержится ли указанная структура `com.aspose.imaging.PointF` внутри этого `com.aspose.imaging.Region`, когда он отрисован с использованием указанного `com.aspose.imaging.graphics`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Структура `com.aspose.imaging.PointF` для тестирования. |
| g | [Graphics](../../com.aspose.imaging/graphics) | `com.aspose.imaging.Graphics`, представляющий графический контекст. |

**Returns:**
boolean — true, когда `point` находится внутри этого `com.aspose.imaging.Region`; иначе — false.
### isVisible(float x, float y, float width, float height) {#isVisible-float-float-float-float-}
```
public boolean isVisible(float x, float y, float width, float height)
```


Проверяет, содержится ли какая-либо часть указанного прямоугольника внутри этого `com.aspose.imaging.region`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата x левого верхнего угла прямоугольника для тестирования. |
| y | float | Координата y левого верхнего угла прямоугольника для тестирования. |
| width | float | Ширина прямоугольника для тестирования. |
| height | float | Высота прямоугольника для тестирования. |

**Returns:**
boolean — true, когда любая часть указанного прямоугольника находится внутри этого объекта `com.aspose.imaging.Region`; иначе — false.
### isVisible(RectangleF rect) {#isVisible-com.aspose.imaging.RectangleF-}
```
public boolean isVisible(RectangleF rect)
```


Проверяет, содержится ли какая-либо часть указанной структуры `com.aspose.imaging.RectangleF` внутри этого `com.aspose.imaging.region`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Структура `com.aspose.imaging.RectangleF` для тестирования. |

**Returns:**
boolean — true, когда любая часть `rect` находится внутри этого `com.aspose.imaging.Region`; иначе — false.
### isVisible(float x, float y, float width, float height, Graphics g) {#isVisible-float-float-float-float-com.aspose.imaging.Graphics-}
```
public boolean isVisible(float x, float y, float width, float height, Graphics g)
```


Проверяет, содержится ли какая-либо часть указанного прямоугольника внутри этого `com.aspose.imaging.Region`, когда он отрисован с использованием указанного `com.aspose.imaging.graphics`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата x левого верхнего угла прямоугольника для тестирования. |
| y | float | Координата y левого верхнего угла прямоугольника для тестирования. |
| width | float | Ширина прямоугольника для тестирования. |
| height | float | Высота прямоугольника для тестирования. |
| g | [Graphics](../../com.aspose.imaging/graphics) | `com.aspose.imaging.Graphics`, представляющий графический контекст. |

**Returns:**
boolean — true, когда любая часть указанного прямоугольника находится внутри этого `com.aspose.imaging.Region`; иначе — false.
### isVisible(RectangleF rect, Graphics g) {#isVisible-com.aspose.imaging.RectangleF-com.aspose.imaging.Graphics-}
```
public boolean isVisible(RectangleF rect, Graphics g)
```


Проверяет, содержится ли какая-либо часть указанной структуры `com.aspose.imaging.RectangleF` внутри этого `com.aspose.imaging.Region`, когда он отрисован с использованием указанного `com.aspose.imaging.graphics`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Структура `com.aspose.imaging.RectangleF` для тестирования. |
| g | [Graphics](../../com.aspose.imaging/graphics) | `com.aspose.imaging.Graphics`, представляющий графический контекст. |

**Returns:**
boolean — true, когда `rect` находится внутри этого `com.aspose.imaging.Region`; иначе — false.
### isVisible(int x, int y, Graphics g) {#isVisible-int-int-com.aspose.imaging.Graphics-}
```
public boolean isVisible(int x, int y, Graphics g)
```


Проверяет, содержится ли указанная точка внутри этого объекта `com.aspose.imaging.Region`, когда он отрисован с использованием указанного объекта `com.aspose.imaging.Graphics`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Координата x проверяемой точки. |
| y | int | Координата y проверяемой точки. |
| g | [Graphics](../../com.aspose.imaging/graphics) | `com.aspose.imaging.Graphics`, представляющий графический контекст. |

**Returns:**
boolean - true, когда указанная точка находится внутри этого `com.aspose.imaging.Region`; в противном случае — false.
### isVisible(Point point) {#isVisible-com.aspose.imaging.Point-}
```
public boolean isVisible(Point point)
```


Проверяет, содержится ли указанная структура `com.aspose.imaging.Point` в данном `com.aspose.imaging.region`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Структура `com.aspose.imaging.Point` для тестирования. |

**Returns:**
boolean — true, когда `point` находится внутри этого `com.aspose.imaging.Region`; иначе — false.
### isVisible(Point point, Graphics g) {#isVisible-com.aspose.imaging.Point-com.aspose.imaging.Graphics-}
```
public boolean isVisible(Point point, Graphics g)
```


Проверяет, содержится ли указанная структура `com.aspose.imaging.Point` в данном `com.aspose.imaging.Region`, когда она отрисована с использованием указанного `com.aspose.imaging.graphics`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Структура `com.aspose.imaging.Point` для тестирования. |
| g | [Graphics](../../com.aspose.imaging/graphics) | `com.aspose.imaging.Graphics`, представляющий графический контекст. |

**Returns:**
boolean — true, когда `point` находится внутри этого `com.aspose.imaging.Region`; иначе — false.
### isVisible(int x, int y, int width, int height) {#isVisible-int-int-int-int-}
```
public boolean isVisible(int x, int y, int width, int height)
```


Проверяет, содержится ли какая-либо часть указанного прямоугольника внутри этого `com.aspose.imaging.region`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Координата x левого верхнего угла прямоугольника для тестирования. |
| y | int | Координата y левого верхнего угла прямоугольника для тестирования. |
| width | int | Ширина прямоугольника для тестирования. |
| height | int | Высота прямоугольника для тестирования. |

**Returns:**
boolean — true, когда любая часть указанного прямоугольника находится внутри этого `com.aspose.imaging.Region`; иначе — false.
### isVisible(Rectangle rect) {#isVisible-com.aspose.imaging.Rectangle-}
```
public boolean isVisible(Rectangle rect)
```


Проверяет, содержится ли какая-либо часть указанной структуры `com.aspose.imaging.Rectangle` в данном `com.aspose.imaging.region`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Структура `com.aspose.imaging.Rectangle` для тестирования. |

**Returns:**
boolean - Этот метод возвращает true, когда любая часть `rect` находится внутри этого `com.aspose.imaging.Region`; в противном случае — false.
### isVisible(int x, int y, int width, int height, Graphics g) {#isVisible-int-int-int-int-com.aspose.imaging.Graphics-}
```
public boolean isVisible(int x, int y, int width, int height, Graphics g)
```


Проверяет, содержится ли какая-либо часть указанного прямоугольника внутри этого `com.aspose.imaging.Region`, когда он отрисован с использованием указанного `com.aspose.imaging.graphics`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Координата x левого верхнего угла прямоугольника для тестирования. |
| y | int | Координата y левого верхнего угла прямоугольника для тестирования. |
| width | int | Ширина прямоугольника для тестирования. |
| height | int | Высота прямоугольника для тестирования. |
| g | [Graphics](../../com.aspose.imaging/graphics) | `com.aspose.imaging.Graphics`, представляющий графический контекст. |

**Returns:**
boolean — true, когда любая часть указанного прямоугольника находится внутри этого `com.aspose.imaging.Region`; иначе — false.
### isVisible(Rectangle rect, Graphics g) {#isVisible-com.aspose.imaging.Rectangle-com.aspose.imaging.Graphics-}
```
public boolean isVisible(Rectangle rect, Graphics g)
```


Проверяет, содержится ли какая-либо часть указанной структуры `com.aspose.imaging.Rectangle` в данном `com.aspose.imaging.Region`, когда она отрисована с использованием указанного `com.aspose.imaging.graphics`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Структура `com.aspose.imaging.Rectangle` для тестирования. |
| g | [Graphics](../../com.aspose.imaging/graphics) | `com.aspose.imaging.Graphics`, представляющий графический контекст. |

**Returns:**
boolean - true, когда любая часть `rect` находится внутри этого `com.aspose.imaging.Region`; в противном случае — false.
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Проверяет, равны ли объекты.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| o | java.lang.Object | Другой объект. |

**Returns:**
boolean - Результат сравнения на равенство.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Получает хеш‑код текущего объекта.

**Returns:**
int - Хеш-код.
