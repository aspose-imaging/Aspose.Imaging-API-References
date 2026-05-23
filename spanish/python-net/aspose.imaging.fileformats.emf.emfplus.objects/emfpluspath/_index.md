---
title: "Clase EmfPlusPath"
type: docs
weight: 490
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspath/
---

**Summary:** The EmfPlusPath object specifies a series of line and curve segments that form a graphics path. The<br/>            order for Bezier data points is the start point, control point 1, control point 2, and end point.For<br/>            more information see[MSDN - DrawBeziers].

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPath

**Inheritance:** EmfPlusGraphicsObjectType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusPath()](#EmfPlusPath__1) | Inicializa una nueva instancia de la clase EmfPlusPath |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| path_point_flags | [EmfPlusPathPointFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspathpointflags/) | r/w | Obtiene o establece el recuento de puntos del Path <br/>            Un entero sin signo de 32 bits que especifica cómo interpretar los puntos y los tipos de punto asociados que define este objeto |
| path_point_types | [EmfPlusBasePointType[]](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasepointtype/) | r/w | Obtiene o establece una matriz que especifica cómo se utilizan los puntos en el campo PathPoints para dibujar la ruta. <br/>            El tipo de objetos en esta matriz se especifica mediante la bandera R en el campo PathPointFlags |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Obtiene o establece una matriz de puntos de ruta<br/>            Una matriz de PathPointCount puntos que especifican la ruta. El tipo de objetos en esta matriz se especifica mediante el campo PathPointFlags, como sigue:<br/>            Si la bandera P está establecida, los puntos son ubicaciones relativas que se especifican mediante objetos EmfPlusPointR (sección 2.2.2.37).<br/>            Si la bandera P está despejada y la bandera C está establecida, los puntos son ubicaciones absolutas que se especifican mediante objetos EmfPlusPoint (sección 2.2.2.35).<br/>            Si la bandera P está despejada y la bandera C está despejada, los puntos son ubicaciones absolutas que se especifican mediante objetos EmfPlusPointF (sección 2.2.2.36). |
| version | [EmfPlusGraphicsVersion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/) | r/w | Obtiene o establece la versión. |


### Constructor: EmfPlusPath() {#EmfPlusPath__1}


```
 EmfPlusPath() 
```

Inicializa una nueva instancia de la clase EmfPlusPath

