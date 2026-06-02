---
title: "EmfPlusPathPointTypeRle Класс"
type: docs
weight: 530
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/
---

**Summary:** The EmfPlusPathPointTypeRle object specifies type values associated with points on a graphics path using RLE compression.<br/>             0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1<br/>             B|1|RunCount   | PointType       |<br/>            B (1 bit): If set, the path points are on a Bezier curve.<br/>            If clear, the path points are on a graphics line.<br/>            RunCount (6 bits): The run count, which is the number of path points to be associated with the type in the PointType field.<br/>            PointType (1 byte): An EmfPlusPathPointType object (section 2.2.2.31) that specifies the type to associate with the path points.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathPointTypeRle

**Inheritance:** EmfPlusBasePointType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusPathPointTypeRle()](#EmfPlusPathPointTypeRle__1) | Инициализирует новый экземпляр класса EmfPlusPathPointTypeRle |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bezier | bool | r/w | Получает или задает значение, указывающее, является ли этот [EmfPlusPathPointTypeRle](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/) безье.<br/>            Если установлено, точки пути находятся на кривой Безье.<br/>            Если сброшено, точки пути находятся на графической линии. |
| данные | int | r/w | Получает или задает данные. |
| point_type | [EmfPlusPathPointType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtype/) | r/w | Получает или задает тип точки.<br/>            PointType (1 байт): объект EmfPlusPathPointType<br/>            (section 2.2.2.31), который определяет тип, связываемый с точками пути. |
| run_count | System.Byte | r/w | Получает или задает количество запусков.<br/>            RunCount (6 бит): количество запусков, которое представляет число точек пути <br/>            связанных с типом в поле PointType. |


### Constructor: EmfPlusPathPointTypeRle() {#EmfPlusPathPointTypeRle__1}


```
 EmfPlusPathPointTypeRle() 
```

Инициализирует новый экземпляр класса EmfPlusPathPointTypeRle

