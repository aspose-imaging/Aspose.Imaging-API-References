---
title: "OdgRasterizationOptions Класс"
type: docs
weight: 220
url: /ru/python-net/aspose.imaging.imageoptions/odgrasterizationoptions/
---

**Summary:** The Odg rasterization options

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.OdgRasterizationOptions

**Inheritance:** OdRasterizationOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [OdgRasterizationOptions()](#OdgRasterizationOptions__1) | Инициализирует новый экземпляр класса OdgRasterizationOptions |
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
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | Получает или задает режим сглаживания. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | Получает или задает подсказку рендеринга текста. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Создает новый объект, являющийся поверхностной копией текущего экземпляра. |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | Копирует в. |


### Constructor: OdgRasterizationOptions() {#OdgRasterizationOptions__1}


```
 OdgRasterizationOptions() 
```

Инициализирует новый экземпляр класса OdgRasterizationOptions

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

Копирует в.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | Параметры растеризации векторных изображений. |

## **Examples**
### The following example shows how to export a FODG (Flat XML ODF Template) image to PDF format. {#example_189}
``` python
from os.path import join
import aspose.pycore as aspycore
from aspose.imaging import Image, Color, SizeF
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.imageoptions import OdgRasterizationOptions, PdfOptions

dir_: str = "c:\\aspose.imaging\\issues\\net\\3635"
input_file_name: str = join(dir_, "VariousObjectsMultiPage.fodg")
output_file_name: str = input_file_name + ".pdf"
with Image.load(input_file_name) as image:
	rasterization_options = OdgRasterizationOptions()
	rasterization_options.background_color = Color.white
	rasterization_options.page_size = aspycore.cast(SizeF, image.size)
	save_options = PdfOptions()
	save_options.vector_rasterization_options = rasterization_options
	image.save(output_file_name, save_options)


```

