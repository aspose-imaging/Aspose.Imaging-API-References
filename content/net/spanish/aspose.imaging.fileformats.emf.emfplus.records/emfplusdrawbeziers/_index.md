---
title: EmfPlusDrawBeziers
second_title: Aspose.Imaging para la referencia de la API de .NET
description: El registro EmfPlusDrawBeziers especifica dibujar una secuencia de curvas Bezier conectadas. El orden de los puntos de datos Bezier es el punto inicial el punto de control 1 el punto de control 2 y el punto final. Para obtener más información consulte MSDN-DrawBeziers.
type: docs
weight: 5910
url: /es/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/
---
## EmfPlusDrawBeziers class

El registro EmfPlusDrawBeziers especifica dibujar una secuencia de curvas Bezier conectadas. El orden de los puntos de datos Bezier es el punto inicial, el punto de control 1, el punto de control 2 y el punto final. Para obtener más información, consulte [MSDN-DrawBeziers].

```csharp
public sealed class EmfPlusDrawBeziers : EmfPlusDrawingRecordType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmfPlusDrawBeziers](emfplusdrawbeziers)(EmfPlusRecord) | Inicializa una nueva instancia del[`EmfPlusDrawBeziers`](../emfplusdrawbeziers) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/compressed) { get; set; } | Obtiene o establece un valor que indica si PointData está comprimido. Si se establece, PointData especifica ubicaciones absolutas en el espacio de coordenadas con coordenadas enteras de 16 bits . Si está claro, PointData especifica ubicaciones absolutas en el espacio de coordenadas con coordenadas de punto flotante de 32 bits. Nota Si se establece el indicador Relativo (a continuación), este indicador no está definido y DEBE ignorarse. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado de 32 bits de bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado del registro de 12 bytes. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo se realizará la operación y sobre la estructura del registro. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/objectid) { get; set; } | Obtiene o establece el identificador del objeto. El índice de un objeto EmfPlusPen (sección 2.2.1.7) en la tabla de objetos EMF+ para dibujar las curvas Bezier. El valor DEBE ser cero a 63, inclusive. |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/pointdata) { get; set; } | Obtiene o establece el punto data Una matriz de puntos de recuento que especifican los puntos inicial, final y de control de las curvas Bezier. La coordenada final de una curva Bezier es la coordenada inicial de la siguiente. Los puntos de control se utilizan para producir el efecto Bezier. El tipo de datos en esta matriz se especifica en el campo Banderas, de la siguiente manera: Tipo de datos Significado Objeto EmfPlusPointR (sección 2.2.2.37) Si la bandera P está configurada en Banderas , los puntos especifican ubicaciones relativas. Objeto EmfPlusPointF (sección 2.2.2.36) Si los bits P y C están claros en el campo Banderas, los puntos especifican ubicaciones absolutas. Objeto EmfPlusPoint (sección 2.2.2.35) Si el bit P está claro y el bit C está establecido en el campo Banderas, los puntos especifican ubicaciones relativas. Una curva Bezier no pasa por sus puntos de control. Los puntos de control actúan como |
| [Relative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/relative) { get; set; } | Obtiene o establece un valor que indica si PointData es relativo. Si se establece, cada elemento de PointData especifica una ubicación en el espacio de coordenadas que es relativa a la ubicación especificada por el elemento anterior en la matriz. En el caso del primer elemento en PointData, se asume una ubicación previa en las coordenadas (0,0). Si está claro, PointData especifica ubicaciones absolutas según al indicador C. Nota Si se establece este indicador, el indicador C (arriba) no está definido y DEBE ignorarse. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado de 32 bits de bytes en todo el registro, incluido el encabezado del registro de 12 bytes y los datos específicos del registro. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Obtiene un entero de 16 bits sin signo que identifica el tipo de registro. |

### Ver también

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
