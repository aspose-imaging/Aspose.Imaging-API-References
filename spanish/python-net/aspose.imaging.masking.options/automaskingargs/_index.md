---
title: "Clase AutoMaskingArgs"
type: docs
weight: 20
url: /es/python-net/aspose.imaging.masking.options/automaskingargs/
---

**Summary:** Represents the arguments that are specified for automated masking methods

**Module:** [aspose.imaging.masking.options](/imaging/python-net/aspose.imaging.masking.options/)

**Full Name:** aspose.imaging.masking.options.AutoMaskingArgs

**Inheritance:** IMaskingArgs

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [AutoMaskingArgs()](#AutoMaskingArgs__1) | Inicializa una nueva instancia de la clase AutoMaskingArgs |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| max_iteration_number | int | r/w | Obtiene o establece el número máximo de iteraciones. |
| number_of_objects | int | r/w | Obtiene o establece el número de objetos<br/>            para separar la imagen inicial en (opcional), el valor predeterminado es 2 (objeto y fondo). |
| objects_points | [Point[][]](/imaging/python-net/aspose.imaging/point[]/) | r/w | Obtiene o establece los puntos que pertenecen a los objetos separados (opcional)<br/>            Coordenadas NumberOfObjects que pertenecen a los objetos NumberOfObjects de la imagen inicial.<br/>            Este parámetro se usa para aumentar la precisión del método de segmentación. |
| objects_rectangles | [Rectangle[]](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtiene o establece los rectángulos de los objetos que pertenecen a objetos separados (opcional).<br/>            Este parámetro se usa para aumentar la precisión del método de segmentación. |
| orphaned_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | r/w | Obtiene o establece los puntos que ya no pertenecen a ningún objeto (opcional).<br/>            Este parámetro se usa solo en caso de resegmentación. |
| precision | float | r/w | Obtiene o establece la precisión del método de segmentación (opcional). |


### Constructor: AutoMaskingArgs() {#AutoMaskingArgs__1}


```
 AutoMaskingArgs() 
```

Inicializa una nueva instancia de la clase AutoMaskingArgs

