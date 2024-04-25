---
title: EmfPlusFillClosedCurve
second_title: Aspose.Imaging para la referencia de la API de .NET
description: El registro EmfPlusFillClosedCurve especifica el relleno del interior de una spline cardinal cerrada
type: docs
weight: 6060
url: /es/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/
---
## EmfPlusFillClosedCurve class

El registro EmfPlusFillClosedCurve especifica el relleno del interior de una spline cardinal cerrada

```csharp
public sealed class EmfPlusFillClosedCurve : EmfPlusDrawingRecordType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmfPlusFillClosedCurve](emfplusfillclosedcurve)(EmfPlusRecord) | Inicializa una nueva instancia del[`EmfPlusFillClosedCurve`](../emfplusfillclosedcurve) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/brushid) { get; set; } | Obtiene o establece el identificador de pincel Un entero de 32 bits sin signo que especifica el EmfPlusBrush, cuyo contenido es determinado por el bit S en el campo Flags. Este pincel se utiliza para rellenar el interior de la spline cardinal cerrada. |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/compressed) { get; set; } | Obtiene o establece un valor que indica si este[`EmfPlusFillClosedCurve`](../emfplusfillclosedcurve)está comprimido. Este bit indica si el campo PointData especifica datos comprimidos. Si se establece, PointData especifica ubicaciones absolutas en el espacio de coordenadas con coordenadas enteras de 16 bits . Si está claro, PointData especifica ubicaciones absolutas en el espacio de coordenadas con coordenadas de punto flotante de 32 bits. ---------------------- Un relleno "sinuoso" La operación llena áreas de acuerdo con la regla de "paridad par-impar". De acuerdo con esta regla, se puede determinar que un punto de prueba está dentro o fuera de una curva cerrada de la siguiente manera: Dibuje una línea desde el punto de prueba hasta un punto que esté distante de la curva. Si esa línea cruza la curva un número impar de veces, el punto de prueba está dentro de la curva; de lo contrario, el punto de prueba está fuera de la curva. ---------------------Una operación de relleno "alternativa" llena áreas de acuerdo con la regla "distinta de cero" . De acuerdo con esta regla, se puede determinar si un punto de prueba está dentro o fuera de una curva cerrada de la siguiente manera: Dibuje una línea desde un punto de prueba hasta un punto que esté distante de la curva. Cuente el número de veces que la curva cruza la línea de prueba de izquierda a derecha y cuente el número de veces que la curva cruza la línea de prueba de derecha a izquierda. Si esos dos números son iguales, el punto de prueba está fuera de la curva; de lo contrario, el punto de prueba está dentro de la curva. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado de 32 bits de bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado del registro de 12 bytes. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo se realizará la operación y sobre la estructura del registro. |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/iscolor) { get; set; } | Obtiene o establece un valor que indica si esta instancia es color. Si se establece, BrushId especifica un color como un objeto EmfPlusARGB (sección 2.2.2.1). Si está claro, BrushId contiene el índice de un objeto EmfPlusBrush (sección 2.2.1.1 ) en la tabla de objetos EMF+. |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/pointdata) { get; set; } | Obtiene o establece el punto data Una matriz de puntos de recuento que especifican los extremos de las líneas que definen la spline. En una spline cardinal cerrada, la curva continúa hasta el último punto de la matriz PointData y se conecta con el primer punto de la matriz |
| [Relative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/relative) { get; set; } | Obtiene o establece un valor que indica si este[`EmfPlusFillClosedCurve`](../emfplusfillclosedcurve) es relativo. Este bit indica si el campo PointData especifica ubicaciones relativas o absolutas. Si se establece, cada elemento en PointData especifica una ubicación en el espacio de coordenadas que es relativa a la ubicación especificada por el elemento anterior en la matriz. En el caso del primer elemento en PointData, se asume una ubicación anterior en las coordenadas (0,0). Si está claro, PointData especifica ubicaciones absolutas de acuerdo con el indicador C. Nota Si este indicador está establecido, el indicador C (arriba) no está definido y DEBE ignorarse. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado de 32 bits de bytes en todo el registro, incluido el encabezado del registro de 12 bytes y los datos específicos del registro. |
| [Tension](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/tension) { get; set; } | Obtiene o establece la tensión Un valor de coma flotante de 32 bits que especifica la fuerza con la que se dobla la spline cuando pasa a través de los puntos. Un valor de 0.0 especifica que la spline es una secuencia de líneas rectas . A medida que aumenta el valor, la curva se vuelve más redondeada. Para obtener más información, consulte [SPLINE77] y [PETZOLD]. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Obtiene un entero de 16 bits sin signo que identifica el tipo de registro. |
| [Winding](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/winding) { get; set; } | Obtiene o establece un valor que indica si este[`EmfPlusFillClosedCurve`](../emfplusfillclosedcurve)es sinuoso. Este bit indica cómo realizar la operación de llenado. Si se establece, el llenado es un llenado "sinuoso". Si está claro, el relleno es un relleno "alternativo". |

### Ver también

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
