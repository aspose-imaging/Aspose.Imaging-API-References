---
title: "MetafileRasterizationOptions Класс"
type: docs
weight: 180
url: /ru/python-net/aspose.imaging.imageoptions/metafilerasterizationoptions/
---

**Summary:** The metafile rasterization options

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.MetafileRasterizationOptions

**Inheritance:** VectorRasterizationOptions

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

