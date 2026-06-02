---
title: "Класс AutoMaskingArgs"
type: docs
weight: 20
url: /ru/python-net/aspose.imaging.masking.options/automaskingargs/
---

**Summary:** Represents the arguments that are specified for automated masking methods

**Module:** [aspose.imaging.masking.options](/imaging/python-net/aspose.imaging.masking.options/)

**Full Name:** aspose.imaging.masking.options.AutoMaskingArgs

**Inheritance:** IMaskingArgs

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [AutoMaskingArgs()](#AutoMaskingArgs__1) | Инициализирует новый экземпляр класса AutoMaskingArgs |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| max_iteration_number | int | r/w | Получает или задает максимальное количество итераций. |
| number_of_objects | int | r/w | Получает или задает количество объектов<br/>            для разделения исходного изображения (необязательно), значение по умолчанию — 2 (объект и фон). |
| objects_points | [Point[][]](/imaging/python-net/aspose.imaging/point[]/) | r/w | Получает или задает точки, принадлежащие разделенным объектам (необязательно)<br/>            координаты NumberOfObjects, принадлежащие объектам NumberOfObjects исходного изображения.<br/>            Этот параметр используется для повышения точности метода сегментации. |
| objects_rectangles | [Rectangle[]](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Получает или задает прямоугольники объектов, принадлежащие разделенным объектам (необязательно).<br/>            Этот параметр используется для повышения точности метода сегментации. |
| orphaned_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | r/w | Получает или задает точки, которые больше не принадлежат ни одному объекту (необязательно).<br/>            Этот параметр используется только в случае повторной сегментации. |
| precision | float | r/w | Получает или задает точность метода сегментации (необязательно). |


### Constructor: AutoMaskingArgs() {#AutoMaskingArgs__1}


```
 AutoMaskingArgs() 
```

Инициализирует новый экземпляр класса AutoMaskingArgs

