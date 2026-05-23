---
title: "Класс EmfVertexData"
type: docs
weight: 1460
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfvertexdata/
---

**Summary:** Objects that specify the vertexes of either rectangles or triangles and <br/>            the colors that correspond to them.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfVertexData

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfVertexData()](#EmfVertexData__1) | Инициализирует новый экземпляр класса EmfVertexData |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| vertex_indexes | [EmfGradientRectangle[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfgradientrectangle/) | r/w | Получает или задает массив из nTri объектов GradientRectangle (раздел 2.2.7) или <br/>            объектов GradientTriangle (раздел 2.2.8), в зависимости от значения поля ulMode. <br/>            Каждый объект указывает индексы в массиве объектов TriVertex в поле VertexObjects. |
| vertex_objects | [EmfTriVertex[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emftrivertex/) | r/w | Получает или задает массив из nVer объектов TriVertex (раздел 2.2.26). Каждый <br/>            объект указывает позицию и цвет вершины прямоугольника или треугольника, <br/>            в зависимости от значения поля ulMode. |
| vertex_padding | System.Byte | r/w | Получает или задает необязательный массив переменной длины, состоящий из nTri элементов по четыре байта каждый <br/>            который ДОЛЖЕН присутствовать, если значение поля ulMode указывает на объекты GradientRectangle <br/>            (раздел 2.2.7). Если значение поля ulMode указывает на объекты GradientTriangle <br/>            (раздел 2.2.8), массив VertexPadding отсутствует. Это поле ДОЛЖНО игнорироваться. |


### Constructor: EmfVertexData() {#EmfVertexData__1}


```
 EmfVertexData() 
```

Инициализирует новый экземпляр класса EmfVertexData

