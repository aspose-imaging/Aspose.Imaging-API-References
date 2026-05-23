---
title: "Класс WmfRasterizationOptions"
type: docs
weight: 380
url: /ru/python-net/aspose.imaging.imageoptions/wmfrasterizationoptions/
---

**Summary:** The Wmf rasterization options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.WmfRasterizationOptions

**Inheritance:** MetafileRasterizationOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [WmfRasterizationOptions()](#WmfRasterizationOptions__1) | Инициализирует новый экземпляр класса [WmfRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/wmfrasterizationoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Получает или задаёт цвет фона. |
| border_x | float | r/w | Получает или задает границу X. |
| border_y | float | r/w | Получает или задает границу Y. |
| center_drawing | bool | r/w | Получает или задает значение, указывающее, включено ли центрирование рисования. |
| draw_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Получает или задает цвет переднего плана. |
| page_height | float | r/w | Получает или задает высоту страницы.<br/>            Если значение равно 0, соотношение сторон исходного изображения будет сохранено. |
| page_size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r/w | Получает или задает размер страницы.<br/>            Если одно из измерений [SizeF](/imaging/python-net/aspose.imaging/sizef/) равно 0, соотношение сторон исходного изображения будет сохранено. |
| page_width | float | r/w | Получает или задает ширину страницы.<br/>            Если значение равно 0, соотношение сторон исходного изображения будет сохранено. |
| positioning | [PositioningTypes](/imaging/python-net/aspose.imaging.imageoptions/positioningtypes/) | r/w | Получает или задает позиционирование. |
| [render_mode](#render_mode1) | [WmfRenderMode](/imaging/python-net/aspose.imaging.fileformats.wmf/wmfrendermode/) | r/w | Получает или задает режим рендеринга WMF. |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | Получает или задает режим сглаживания. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | Получает или задает подсказку рендеринга текста. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Создает новый объект, являющийся поверхностной копией текущего экземпляра. |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | Копирует это в _vectorRasterizationOptions_. |


### Constructor: WmfRasterizationOptions() {#WmfRasterizationOptions__1}


```
 WmfRasterizationOptions() 
```

Инициализирует новый экземпляр класса [WmfRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/wmfrasterizationoptions/).

### Property: render_mode {#render_mode1}

Получает или задает режим рендеринга WMF.

**See also:**

**[Example # 1](#example_173)**: This example shows how to load a WMF image from a file and convert it to SVG ...


### Method: clone() {#clone__1}


```
 clone() 
```

Создает новый объект, являющийся поверхностной копией текущего экземпляра.

**Returns**

| Тип | Описание |
| :- | :- |
| System.Object | Новый объект, являющийся поверхностной копией этого экземпляра. |


### Method: copy_to(vector_rasterization_options) {#copy_to_vector_rasterization_options_2}


```
 copy_to(vector_rasterization_options) 
```

Копирует это в _vectorRasterizationOptions_.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | vectorRasterizationOptions |

## **Examples**
### This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions. {#example_173}
``` python

from aspose.pycore import as_of, cast
from aspose.imaging import Image, Color, SizeF
from aspose.imaging.fileformats.wmf import WmfImage, WmfRenderMode
from aspose.imaging.imageoptions import SvgOptions, WmfRasterizationOptions

# Использование Aspose.Imaging.Image.Load — единый способ загрузки всех типов изображений, включая WMF.
with as_of(Image.load("test.wmf") as image:
	saveOptions = SvgOptions()
	# Текст будет преобразован в фигуры.
	saveOptions.text_as_shapes = True
	rasterizationOptions = WmfRasterizationOptions()
	# Цвет фона поверхности рисования.
	rasterizationOptions.background_color = Color.white_smoke
	# Размер страницы.
	rasterizationOptions.page_size = cast(SizeF, wmfImage.size)
	# Если встроенный emf существует, то рендерить emf; иначе рендерить wmf.
	rasterizationOptions.render_mode = WmfRenderMode.AUTO
	saveOptions.vector_rasterization_options = rasterizationOptions
	wmfImage.save("test.output.svg", saveOptions)


```

