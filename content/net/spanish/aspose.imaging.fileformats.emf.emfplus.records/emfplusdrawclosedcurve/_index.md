---
title: EmfPlusDrawClosedCurve
second_title: Aspose.Imaging para la referencia de la API de .NET
description: El registro EmfPlusDrawClosedCurve especifica dibujar una spline cardinal cerrada
type: docs
weight: 5920
url: /es/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/
---
## EmfPlusDrawClosedCurve class

El registro EmfPlusDrawClosedCurve especifica dibujar una spline cardinal cerrada

```csharp
public sealed class EmfPlusDrawClosedCurve : EmfPlusDrawingRecordType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmfPlusDrawClosedCurve](emfplusdrawclosedcurve)(EmfPlusRecord) | Inicializa una nueva instancia del[`EmfPlusDrawClosedCurve`](../emfplusdrawclosedcurve) class. RecordType: un entero de 16 bits sin signo que identifica este tipo de registro como EmfPlusDrawClosedCurve de la enumeración RecordType (sección 2.1.1.1). El valor DEBE ser 0x4017. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/compressed) { get; set; } | Obtiene o establece un valor que indica si este[`EmfPlusDrawClosedCurve`](../emfplusdrawclosedcurve)está comprimido. Este bit indica si el campo PointData especifica datos comprimidos. Si se establece, PointData especifica ubicaciones absolutas en el espacio de coordenadas con coordenadas enteras de 16 bits. Si está claro, PointData especifica ubicaciones absolutas en el espacio de coordenadas con coordenadas de coma flotante de 32 bits Nota Si se establece el indicador Relativo (a continuación), este indicador no está definido y DEBE ignorarse |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado de 32 bits de bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado del registro de 12 bytes. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo se realizará la operación y sobre la estructura del registro. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/objectid) { get; set; } | Obtiene o establece el identificador del objeto. El índice de un objeto EmfPlusPen (sección 2.2.1.7) en la tabla de objetos EMF+ para dibujar la curva cerrada. El valor DEBE ser cero a 63, inclusive. |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/pointdata) { get; set; } | Obtiene o establece el punto data Una matriz de puntos de recuento que especifican los extremos de las líneas que definen la spline. En una spline cardinal cerrada, la curva continúa hasta el último punto de la matriz PointData y se conecta con el primer punto de la matriz. El tipo de datos de esta matriz se especifica en el campo Flags, de la siguiente manera: Tipo de datos Significado EmfPlusPointR objeto (sección 2.2.2.37) Si el indicador P está configurado en Banderas, los puntos especifican ubicaciones relativas. EmfPlusPointF objeto (sección 2.2.2.36) Si los bits P y C están configurados en el campo Banderas, los puntos ubicaciones absolutas. Objeto EmfPlusPoint (sección 2.2.2.35) Si el bit P está limpio y el bit C está configurado en el campo Banderas, los puntos especifican ubicaciones relativas. |
| [Relative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/relative) { get; set; } | Obtiene o establece un valor que indica si este[`EmfPlusDrawClosedCurve`](../emfplusdrawclosedcurve)es relativo. Este bit indica si el campo PointData especifica ubicaciones relativas o absolutas. Si se establece, cada elemento en PointData especifica una ubicación en el espacio de coordenadas que es relativa a la ubicación especificada por el elemento anterior en la matriz. En el caso del primer elemento en PointData, se asume una ubicación anterior en las coordenadas (0,0). Si está claro, PointData especifica ubicaciones absolutas de acuerdo con el indicador C. Nota Si se establece este indicador, el indicador comprimido (arriba) no está definido y DEBE ignorarse |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado de 32 bits de bytes en todo el registro, incluido el encabezado del registro de 12 bytes y los datos específicos del registro. |
| [Tension](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/tension) { get; set; } | Obtiene o establece la tensión Un número de coma flotante de 32 bits que especifica la fuerza con la que se dobla la spline al pasar por los puntos. Un valor de 0 especifica que la spline es una secuencia de líneas rectas. A medida que aumenta el valor, la curva se vuelve más redondeada. Para obtener más información, consulte [SPLINE77] y [PETZOLD]. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Obtiene un entero de 16 bits sin signo que identifica el tipo de registro. |

### Ver también

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
