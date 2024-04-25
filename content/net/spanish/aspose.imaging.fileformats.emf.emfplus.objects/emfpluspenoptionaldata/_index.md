---
title: EmfPlusPenOptionalData
second_title: Aspose.Imaging para la referencia de la API de .NET
description: El objeto EmfPlusPenOptionalData especifica datos opcionales para un lápiz gráfico
type: docs
weight: 5680
url: /es/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/
---
## EmfPlusPenOptionalData class

El objeto EmfPlusPenOptionalData especifica datos opcionales para un lápiz gráfico

```csharp
public sealed class EmfPlusPenOptionalData : EmfPlusStructureObjectType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmfPlusPenOptionalData](emfpluspenoptionaldata)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CompoundLineData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/compoundlinedata) { get; set; } | Obtiene o establece el objeto opcional EmfPlusCompoundLineData (sección 2.2.2.9) que especifica una matriz de valores de coma flotante que definen la línea compuesta de un bolígrafo, que se compone de líneas paralelas y espacios. Este campo DEBE estar presente si el indicador PenDataCompoundLine está establecido en el campo PenDataFlags del objeto EmfPlusPenData |
| [CustomEndCapData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/customendcapdata) { get; set; } | Obtiene o establece el objeto opcional EmfPlusCustomEndCapData (sección 2.2.2.11) que define la forma personalizada de la tapa final, que es la forma que usará al final de una línea dibujada con esta pluma. Puede ser cualquiera de varias formas, como un cuadrado, un círculo o un diamante. Este campo DEBE estar presente si el indicador PenDataCustomEndCap es establecido en el campo PenDataFlags del objeto EmfPlusPenData |
| [CustomStartCapData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/customstartcapdata) { get; set; } | Obtiene o establece el objeto opcional EmfPlusCustomStartCapData (sección 2.2.2.15) que define la forma personalizada de la tapa de inicio, que es la forma que usará al comienzo de una línea dibujada con esta pluma. Puede ser cualquier de varias formas, como un cuadrado, un círculo o un diamante. Este campo DEBE estar presente si el indicador PenDataCustomStartCap está establecido en el campo PenDataFlags del objeto EmfPlusPenData |
| [DashedLineCapType](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/dashedlinecaptype) { get; set; } | Obtiene o establece un entero opcional de 32 bits con signo que especifica la forma de en ambos extremos de cada guión en una línea discontinua. Este campo DEBE estar presente si el indicador PenDataDashedLineCap está establecido en el campo PenDataFlags del objeto EmfPlusPenData, y el valor DEBE estar definido en la enumeración de DashedLineCapType (sección 2.1.1.10). |
| [DashedLineData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/dashedlinedata) { get; set; } | Obtiene o establece el objeto opcional EmfPlusDashedLineData (sección 2.2.2.16) que especifica la longitud de los guiones y espacios en una línea discontinua personalizada. Este campo DEBE estar presente si el indicador PenDataDashedLine está establecido en el campo PenDataFlags del objeto EmfPlusPenData . |
| [DashOffset](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/dashoffset) { get; set; } | Obtiene o establece un valor de punto flotante de 32 bits opcional que especifica la distancia desde el comienzo de una línea hasta el comienzo del primer espacio en un patrón de línea discontinua. Este campo DEBE estar presente si el indicador PenDataDashedLineOffset está establecido en el campo PenDataFlags del objeto EmfPlusPenData. |
| [EndCap](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/endcap) { get; set; } | Obtiene o establece un entero opcional de 32 bits con signo que especifica la forma para el final de una línea en el campo CustomEndCapData. Este campo DEBE estar presente si el indicador PenDataEndCap está establecido en el campo PenDataFlags del objeto EmfPlusPenData, y el valor DEBE estar definido en la enumeración LineCapType |
| [Join](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/join) { get; set; } | Obtiene o establece un entero opcional de 32 bits con signo que especifica cómo unir dos líneas dibujadas por la misma pluma y cuyos extremos se encuentran. Este campo DEBE estar presente si el indicador PenDataJoin está establecido en el campo PenDataFlags del objeto EmfPlusPenData, y el valor DEBE estar definido en la enumeración LineJoinType (sección 2.1.1.19). |
| [LineStyle](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/linestyle) { get; set; } | Obtiene o establece un entero opcional de 32 bits con signo que especifica el estilo utilizado para las líneas dibujadas con este objeto de pluma. Este campo DEBE estar presente si el indicador PenDataLineStyle está establecido en el campo PenDataFlags del objeto EmfPlusPenData, y el valor DEBE estar definido en la enumeración LineStyle (sección 2.1.1.20). |
| [MiterLimit](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/miterlimit) { get; set; } | Obtiene o establece un valor de punto flotante de 32 bits opcional que especifica el límite de inglete , que es la relación máxima permitida entre la longitud del inglete y el ancho de línea . La longitud de inglete es la distancia desde la intersección de las paredes de línea en el interior de la unión hasta la intersección de las paredes de línea fuera de la unión. La longitud del inglete puede ser grande cuando el ángulo entre dos líneas es pequeño. Este campo DEBE estar presente si el indicador PenDataMiterLimit está establecido en el campo PenDataFlags del objeto EmfPlusPenData. |
| [PenAlignment](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/penalignment) { get; set; } | Obtiene o establece un entero opcional de 32 bits con signo que especifica la distribución del ancho de la pluma con respecto a las coordenadas de la línea que se está dibujando. Este campo DEBE estar presente si el indicador PenDataNonCenter está establecido en el campo PenDataFlags del objeto EmfPlusPenData, y el valor DEBE estar definido en la enumeración PenAlignment (sección 2.1.1.24). |
| [StartCap](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/startcap) { get; set; } | Obtiene o establece un entero opcional de 32 bits con signo que especifica la forma para el comienzo de una línea en el campo CustomStartCapData. Este campo DEBE estar presente si el indicador PenDataStartCap está establecido en en el campo PenDataFlags del objeto EmfPlusPenData, y el valor DEBE estar definido en la enumeración LineCapType (sección 2.1.1.18). |
| [TransformMatrix](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/transformmatrix) { get; set; } | Obtiene o establece un objeto EmfPlusTransformMatrix opcional (sección 2.2.2.47) que especifica una transformación de espacio mundial a espacio de dispositivo para el bolígrafo. Este campo DEBE estar presente si el indicador PenDataTransform está establecido en el campo PenDataFlags del objeto EmfPlusPenData . |

### Ver también

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
