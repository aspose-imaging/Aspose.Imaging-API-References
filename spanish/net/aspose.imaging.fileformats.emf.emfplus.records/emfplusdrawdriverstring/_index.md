---
title: EmfPlusDrawDriverString
second_title: Aspose.Imaging para la referencia de la API de .NET
description: El registro EmfPlusDrawDriverString especifica la salida de texto con posiciones de caracteres.
type: docs
weight: 5940
url: /es/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/
---
## EmfPlusDrawDriverString class

El registro EmfPlusDrawDriverString especifica la salida de texto con posiciones de caracteres.

```csharp
public sealed class EmfPlusDrawDriverString : EmfPlusDrawingRecordType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmfPlusDrawDriverString](emfplusdrawdriverstring)(EmfPlusRecord) | Inicializa una nueva instancia del[`EmfPlusDrawDriverString`](../emfplusdrawdriverstring) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/brushid) { get; set; } | Obtiene o establece el identificador de pincel Un entero de 32 bits sin signo que especifica el color de primer plano del texto o un pincel de gráficos, dependiendo del valor de la bandera S en Flags |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado de 32 bits de bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado del registro de 12 bytes. |
| [DriverStringOptionsFlags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/driverstringoptionsflags) { get; set; } | Obtiene o establece las opciones de cadena del controlador flags Un entero de 32 bits sin signo que especifica el espaciado, la orientación y la calidad de representación de la cadena. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo se realizará la operación y sobre la estructura del registro. |
| [GlyphCount](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/glyphcount) { get; set; } | Obtiene o establece el recuento de glifos Un entero de 32 bits sin signo que especifica el número de glifos en la cadena |
| [GlyphPos](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/glyphpos) { get; set; } | Obtiene o establece las posiciones de los glifos array Una matriz de objetos EmfPlusPointF (sección 2.2.2.36) que especifican la posición de salida de cada glifo de carácter. DEBE haber elementos GlyphCount, que tienen una correspondencia uno a uno con los elementos en el Matriz de glifos. Las posiciones de los glifos se calculan a partir de la posición del primer glifo si se establece el indicador DriverStringOptionsRealizedAdvance en los indicadores de DriverStringOptions. En este caso, GlyphPos especifica la posición del primer glifo únicamente. |
| [Glyphs](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/glyphs) { get; set; } | Obtiene o establece la matriz de glifos Una matriz de valores de 16 bits que define la cadena de texto que se va a dibujar. Si se establece el indicador DriverStringOptionsCmapLookup en el campo DriverStringOptionsFlags, cada valor en esta matriz especifica un carácter Unicode. De lo contrario, cada valor especifica un índice para un glifo de carácter en el objeto EmfPlusFont especificado por el valor ObjectId en el campo Flags. |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/iscolor) { get; set; } | Obtiene o establece un valor que indica si esta instancia es color. Este bit indica el tipo de datos en el campo BrushId. Si se establece, BrushId especifica el valor de color en un objeto EmfPlusARGB (sección 2.2.2.1). Si está claro, BrushId contiene el índice EMF+ Object Table de un objeto EmfPlusBrush (sección 2.2.1.1). |
| [MatrixPresent](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/matrixpresent) { get; set; } | Obtiene o establece si la matriz presenta flag Un entero de 32 bits sin signo que especifica si una matriz de transformación está presente en el campo TransformMatrix 0 - sin matriz presente. 1 - la matriz de transformación está en TransformMatrix field |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/objectid) { get; set; } | Obtiene o establece el identificador de objeto. El índice de la tabla de objetos EMF+ de un[EmfPlusFont](EmfPlusFont) object (section 2.2.1.3) para representar el texto. El valor DEBE ser cero a 63, inclusive. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado de 32 bits de bytes en todo el registro, incluido el encabezado del registro de 12 bytes y los datos específicos del registro. |
| [TransformMatrix](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/transformmatrix) { get; set; } | Obtiene o establece la matriz de transformación Un objeto opcional EmfPlusTransformMatrix (sección 2.2.2.47) que especifica la transformación que se aplicará a cada valor en la matriz de texto. La presencia de estos datos se determina a partir del campo MatrixPresent. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Obtiene un entero de 16 bits sin signo que identifica el tipo de registro. |

### Ver también

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
