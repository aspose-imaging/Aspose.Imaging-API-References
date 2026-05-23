---
title: "Clase EmfPlusFillClosedCurve"
type: docs
weight: 230
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/
---

**Summary:** The EmfPlusFillClosedCurve record specifies filling the interior of a closed cardinal spline

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillClosedCurve

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusFillClosedCurve(source)](#EmfPlusFillClosedCurve_source_1) | Inicializa una nueva instancia de la clase [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Obtiene o establece el identificador del pincel<br/> Un entero sin signo de 32 bits que especifica el EmfPlusBrush, cuyo contenido está <br/> determinado por el bit S en el campo Flags. Este pincel se usa para rellenar el interior <br/> de la spline cardinal cerrada. |
| compressed | bool | r/w | Obtiene o establece un valor que indica si este [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/) está comprimido.<br/> Este bit indica si el campo PointData especifica datos comprimidos.<br/> Si se establece, PointData especifica ubicaciones absolutas en el espacio de coordenadas con coordenadas enteras de 16 bits. Si se borra, PointData especifica ubicaciones absolutas en el espacio de coordenadas con coordenadas de punto flotante de 32 bits.<br/> ----------------------<br/> Una operación de relleno "winding" llena áreas según la regla de "paridad impar-par". <br/> Según esta regla, se puede determinar si un punto de prueba está dentro o fuera de una <br/> curva cerrada de la siguiente manera: Dibuje una línea desde el punto de prueba a un punto que esté alejado <br/> de la curva. Si esa línea cruza la curva un número impar de veces, el punto de prueba está dentro de la curva; de lo contrario, el punto de prueba está fuera de la curva.<br/> ---------------------<br/> Una operación de relleno "alternate" llena áreas según la regla "non-zero".<br/> Según esta regla, se puede determinar si un punto de prueba está dentro o fuera de <br/> una curva cerrada de la siguiente manera: Dibuje una línea desde un punto de prueba a un punto que esté <br/> alejado de la curva. Cuente cuántas veces la curva cruza la línea de prueba de izquierda a derecha, y cuántas veces la curva cruza la línea de prueba de derecha a izquierda. Si esos dos números son iguales, el punto de prueba <br/> está fuera de la curva; de lo contrario, el punto de prueba está dentro de la curva. |
| data_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado a 32 bits de<br/>            bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado de registro de 12 bytes. |
| banderas | int | r/w | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo<br/>            se debe realizar la operación y sobre la estructura del registro. |
| is_color | bool | r/w | Obtiene o establece un valor que indica si esta instancia es de color.<br/>            Si está establecido, BrushId especifica un color como un objeto EmfPlusARGB (sección 2.2.2.1).<br/>            Si no está establecido, BrushId contiene el índice de un objeto EmfPlusBrush <br/>            (sección 2.2.1.1) en la tabla de objetos EMF+. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Obtiene o establece los datos de puntos<br/> Una matriz de puntos Count que especifican los extremos de las líneas que definen la spline. <br/> En una spline cardinal cerrada, la curva continúa a través del último punto en el PointData <br/> y se conecta con el primer punto de la matriz. |
| relative | bool | r/w | Obtiene o establece un valor que indica si este [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/) es relativo.<br/> Este bit indica si el campo PointData especifica ubicaciones relativas o absolutas.<br/> Si se establece, cada elemento en PointData especifica una ubicación en el espacio de coordenadas que es<br/> relativa a la ubicación especificada por el elemento anterior en la matriz. En el caso <br/> del primer elemento en PointData, se asume una ubicación previa en las coordenadas (0,0). <br/> Si se borra, PointData especifica ubicaciones absolutas según la bandera C.<br/> Nota: Si esta bandera está establecida, la bandera C (arriba) es indefinida y DEBE ser ignorada. |
| tamaño | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado a 32 bits de bytes<br/>            en todo el registro, incluyendo el encabezado de registro de 12 bytes y los datos específicos del registro. |
| tensión | float | r/w | Obtiene o establece la tensión<br/> Un valor de punto flotante de 32 bits que especifica cuán estrechamente se curva la spline al pasar <br/> por los puntos. Un valor de 0.0 indica que la spline es una secuencia de líneas rectas. A medida que el valor aumenta, la curva se vuelve más redondeada. Para más información, <br/> vea [SPLINE77] y [PETZOLD]. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtiene un entero sin signo de 16 bits que identifica el tipo de registro. |
| winding | bool | r/w | Obtiene o establece un valor que indica si este [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/) es "winding".<br/> Este bit indica cómo realizar la operación de relleno.<br/> Si se establece, el relleno es un relleno "winding". Si se borra, el relleno es un relleno "alternate". |


### Constructor: EmfPlusFillClosedCurve(source) {#EmfPlusFillClosedCurve_source_1}


```
 EmfPlusFillClosedCurve(source) 
```

Inicializa una nueva instancia de la clase [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La fuente. |

