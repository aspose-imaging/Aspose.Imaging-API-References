---
title: "Класс EmfPlusPath"
type: docs
weight: 490
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspath/
---

**Summary:** The EmfPlusPath object specifies a series of line and curve segments that form a graphics path. The<br/>            order for Bezier data points is the start point, control point 1, control point 2, and end point.For<br/>            more information see[MSDN - DrawBeziers].

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPath

**Inheritance:** EmfPlusGraphicsObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusPath()](#EmfPlusPath__1) | Инициализирует новый экземпляр класса EmfPlusPath |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| path_point_flags | [EmfPlusPathPointFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspathpointflags/) | r/w | Получает или задает количество точек пути <br/>            32‑битное беззнаковое целое, которое определяет, как интерпретировать точки и связанные типы точек, определённые этим объектом |
| path_point_types | [EmfPlusBasePointType[]](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasepointtype/) | r/w | Получает или задает массив, который определяет, как точки в поле PathPoints используются для построения пути. <br/>            Тип объектов в этом массиве задаётся флагом R в поле PathPointFlags. |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Получает или задает массив точек пути<br/>            Массив из PathPointCount точек, определяющих путь. Тип объектов в этом массиве задаётся полем PathPointFlags следующим образом:<br/>            Если установлен флаг P, точки являются относительными координатами, задаваемыми объектами EmfPlusPointR (section 2.2.2.37).<br/>            Если флаг P сброшен и установлен флаг C, точки являются абсолютными координатами, задаваемыми объектами EmfPlusPoint (section 2.2.2.35).<br/>            Если флаг P и флаг C сброшены, точки являются абсолютными координатами, задаваемыми объектами EmfPlusPointF (section 2.2.2.36). |
| version | [EmfPlusGraphicsVersion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/) | r/w | Получает или задает версию. |


### Constructor: EmfPlusPath() {#EmfPlusPath__1}


```
 EmfPlusPath() 
```

Инициализирует новый экземпляр класса EmfPlusPath

