---
title: "Clase EmfPlusPathGradientBrushData"
type: docs
weight: 500
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/
---

**Summary:** The EmfPlusPathGradientBrushData object specifies a path gradient for a graphics brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushData

**Inheritance:** EmfPlusBaseBrushData

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusPathGradientBrushData()](#EmfPlusPathGradientBrushData__1) | Inicializa una nueva instancia de la clase EmfPlusPathGradientBrushData |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| boundary_data | [EmfPlusBoundaryBase](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarybase/) | r/w | Obtiene o establece el contorno del pincel de degradado de trayectoria, que se especifica mediante una ruta o una spline cardinal cerrada. <br/>            Si el indicador BrushDataPath está establecido en el campo BrushDataFlags, este campo DEBE contener un objeto EmfPlusBoundaryPathData (sección 2.2.2.6); <br/>            de lo contrario, este campo DEBE contener un objeto EmfPlusBoundaryPointData (sección 2.2.2.7). |
| brush_data_flags | [EmfPlusBrushDataFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/) | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica los datos en el campo OptionalData.<br/>            Este valor DEBE estar compuesto por indicadores BrushData (sección 2.1.2.1). Los siguientes indicadores son relevantes para un pincel de degradado de trayectoria: |
| center_argb_32_color | int | r/w | Obtiene o establece un objeto EmfPlusARGB (sección 2.2.2.1) que especifica el color central del <br/>            pincel de degradado de trayectoria, que es el color que aparece en el punto central del pincel. <br/>            El color del pincel cambia gradualmente del color del contorno <br/>            al color central a medida que se desplaza del contorno al punto central. |
| center_point_f | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Obtiene o establece un objeto EmfPlusARGB (sección 2.2.1) que especifica el color central del pincel de degradado de trayectoria, <br/>            que es el color que aparece en el punto central del pincel. El color del<br/>            pincel cambia gradualmente del color del contorno al color central a medida que se desplaza<br/>            del contorno al punto central. |
| optional_data | [EmfPlusPathGradientBrushOptionalData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/) | r/w | Obtiene o establece un objeto opcional EmfPlusPathGradientBrushOptionalData (sección 2.2.2.30) que <br/>            especifica datos adicionales para el pincel de degradado de trayectoria. <br/>            El contenido específico de este campo se determina por el valor del campo BrushDataFlags. |
| surrounding_argb_32_colors | int[] | r/w | Obtiene o establece una matriz de objetos EmfPlusARGB SurroundingColorCount <br/>            que especifican los colores para puntos discretos en el contorno del pincel. |
| wrap_mode | [EmfPlusWrapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluswrapmode/) | r/w | Obtiene o establece un entero con signo de 32 bits de la enumeración WrapMode (sección 2.1.1.34) que especifica<br/>            si se debe pintar el área fuera del contorno del pincel. Al pintar <br/>            fuera del contorno, el modo de ajuste especifica cómo se repite el degradado de color |


### Constructor: EmfPlusPathGradientBrushData() {#EmfPlusPathGradientBrushData__1}


```
 EmfPlusPathGradientBrushData() 
```

Inicializa una nueva instancia de la clase EmfPlusPathGradientBrushData

