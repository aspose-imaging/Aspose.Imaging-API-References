---
title: EmfPlusDrawImagePoints
second_title: Aspose.Imaging para la referencia de la API de .NET
description: El registro EmfPlusDrawImagePoints especifica dibujar una imagen a escala dentro de un paralelogramo.
type: docs
weight: 5970
url: /es/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/
---
## EmfPlusDrawImagePoints class

El registro EmfPlusDrawImagePoints especifica dibujar una imagen a escala dentro de un paralelogramo.

```csharp
public sealed class EmfPlusDrawImagePoints : EmfPlusDrawingRecordType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmfPlusDrawImagePoints](emfplusdrawimagepoints)(EmfPlusRecord) | Inicializa una nueva instancia del[`EmfPlusDrawImagePoints`](../emfplusdrawimagepoints) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ApplyingAnEffect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/applyinganeffect) { get; set; } | Obtiene o establece un valor que indica si [aplica un efecto]. Este bit indica que la representación de la imagen incluye la aplicación de un efecto. Si se establece, un objeto de la clase Effect DEBE haberse especificado en un registro anterior EmfPlusSerializableObject (sección 2.3.5.2). |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/compressed) { get; set; } | Obtiene o establece un valor que indica si PointData está comprimido. Este bit indica si el campo PointData especifica datos comprimidos. Si se establece, PointData especifica ubicaciones absolutas en el espacio de coordenadas con coordenadas de entero de 16 bits. Si está claro, PointData especifica ubicaciones absolutas en el espacio de coordenadas con coordenadas de coma flotante de 32 bits. Nota Si se establece el indicador P (a continuación), este indicador no está definido y DEBE ignorarse. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado de 32 bits de bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado del registro de 12 bytes. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo se realizará la operación y sobre la estructura del registro. |
| [ImageAttributesId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/imageattributesid) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que contiene el índice del objeto opcional EmfPlusImageAttributes (sección 2.2.1.5) en la tabla de objetos EMF+. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/objectid) { get; set; } | Obtiene o establece el identificador del objeto. El índice de un objeto EmfPlusImage (sección 2.2.1.4) en la tabla de objetos EMF+ , que especifica la imagen a representar. El valor DEBE ser cero a 63, inclusive. |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/pointdata) { get; set; } | Obtiene o establece una matriz de puntos Count que especifican tres puntos de un paralelogramo. Los tres puntos representan las esquinas superior izquierda, superior derecha e inferior izquierda del paralelogramo . El cuarto punto del paralelogramo se extrapola de los tres primeros. La porción de la imagen especificada por el campo SrcRect DEBERÍA tener aplicadas transformaciones de escalado y corte si es necesario para caber dentro del paralelogramo. |
| [Relative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/relative) { get; set; } | Obtiene o establece un valor que indica si este[`EmfPlusDrawImagePoints`](../emfplusdrawimagepoints)es relativo. Este bit indica si el campo PointData especifica ubicaciones relativas o absolutas. Si se establece, cada elemento en PointData especifica una ubicación en el espacio de coordenadas que es relativa a la ubicación especificada por el elemento anterior en la matriz. En el caso del primer elemento en PointData, se asume una ubicación anterior en las coordenadas (0,0). Si está claro, PointData especifica ubicaciones absolutas de acuerdo con el indicador C. Nota Si este indicador está establecido, el indicador C (arriba) no está definido y DEBE ignorarse. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado de 32 bits de bytes en todo el registro, incluido el encabezado del registro de 12 bytes y los datos específicos del registro. |
| [SrcRect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/srcrect) { get; set; } | Obtiene o establece un objeto EmfPlusRectF (sección 2.2.2.39) que define una porción de la imagen a renderizar. |
| [SrcUnit](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/srcunit) { get; set; } | Obtiene o establece un entero de 32 bits con signo que define las unidades del campo SrcRect. DEBE ser el valor UnitPixel de la enumeración UnitType (sección 2.1.1.33). |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Obtiene un entero de 16 bits sin signo que identifica el tipo de registro. |

### Observaciones

Una EmfPlusImage puede especificar un mapa de bits o un metarchivo. Los colores de una imagen se pueden manipular durante la renderización. Se pueden corregir, oscurecer, aclarar y eliminar.

### Ver también

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
