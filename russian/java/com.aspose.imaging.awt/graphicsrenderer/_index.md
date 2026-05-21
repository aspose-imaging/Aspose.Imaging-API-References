---
title: "GraphicsRenderer"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Класс обрабатывает отрисовку com.aspose.imaging.Image непосредственно на java.awt.Graphic2D."
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.awt/graphicsrenderer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)
```
public class GraphicsRenderer extends DisposableObject
```

Класс обрабатывает отрисовку com.aspose.imaging.Image непосредственно на java.awt.Graphic2D. Используя этот класс, можно избежать множественных выделений памяти и копирования пикселей между буферами com.aspose.Imaging и java.awt.BufferImage в случае VectorImage.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [GraphicsRenderer(Image image)](#GraphicsRenderer-com.aspose.imaging.Image-) | Создаёт новый рендер. |
| [GraphicsRenderer(Image image, ImageOptionsBase exportOptions)](#GraphicsRenderer-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-) | Создаёт новый рендер. |
| [GraphicsRenderer(Image image, Color backgroundColor, int smoothingMode, int textRendering)](#GraphicsRenderer-com.aspose.imaging.Image-com.aspose.imaging.Color-int-int-) | Создаёт новый рендер. |
## Методы

| Метод | Описание |
| --- | --- |
| [render(Graphics2D graphics)](#render-java.awt.Graphics2D-) | Выполняет рендеринг на заданном `graphics` с коэффициентом масштабирования 1.0. |
| [render(Graphics2D graphics, float scaleFactor)](#render-java.awt.Graphics2D-float-) | Выполняет рендеринг на заданном `graphics`. |
### GraphicsRenderer(Image image) {#GraphicsRenderer-com.aspose.imaging.Image-}
```
public GraphicsRenderer(Image image)
```


Создаёт новый рендер. По умолчанию рендер будет выполнен с использованием [SmoothingMode.HighQuality](../../com.aspose.imaging/smoothingmode\\#HighQuality), [TextRenderingHint.ClearTypeGridFit](../../com.aspose.imaging/textrenderinghint\\#ClearTypeGridFit) и с белым цветом фона.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Изображение, которое будет отрисовано на java.awt.Graphics2D |

### GraphicsRenderer(Image image, ImageOptionsBase exportOptions) {#GraphicsRenderer-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-}
```
public GraphicsRenderer(Image image, ImageOptionsBase exportOptions)
```


Создаёт новый рендер.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Изображение, которое будет отрисовано на java.awt.Graphics2D |
| exportOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Параметры экспорта для настройки экспортируемого изображения. |

### GraphicsRenderer(Image image, Color backgroundColor, int smoothingMode, int textRendering) {#GraphicsRenderer-com.aspose.imaging.Image-com.aspose.imaging.Color-int-int-}
```
public GraphicsRenderer(Image image, Color backgroundColor, int smoothingMode, int textRendering)
```


Создаёт новый рендер.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Изображение, которое будет отрисовано на java.awt.Graphics2D |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Фоновый цвет. |
| smoothingMode | int | Режим сглаживания. |
| textRendering | int | Режим отображения текста. |

### render(Graphics2D graphics) {#render-java.awt.Graphics2D-}
```
public void render(Graphics2D graphics)
```


Выполняет рендеринг на заданном `graphics` с коэффициентом масштабирования 1.0.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| graphics | java.awt.Graphics2D | Графика для рисования. |

### render(Graphics2D graphics, float scaleFactor) {#render-java.awt.Graphics2D-float-}
```
public void render(Graphics2D graphics, float scaleFactor)
```


Выполняет рендеринг на заданном `graphics`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| graphics | java.awt.Graphics2D | Графика для рисования. |
| scaleFactor | float | Коэффициент масштабирования. |

