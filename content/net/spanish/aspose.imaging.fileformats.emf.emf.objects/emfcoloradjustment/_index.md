---
title: EmfColorAdjustment
second_title: Aspose.Imaging para la referencia de la API de .NET
description: El objeto ColorAdjustment define valores para ajustar los colores en mapas de bits de origen en transferencias de bloques de bits.
type: docs
weight: 2930
url: /es/aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/
---
## EmfColorAdjustment class

El objeto ColorAdjustment define valores para ajustar los colores en mapas de bits de origen en transferencias de bloques de bits.

```csharp
public sealed class EmfColorAdjustment : EmfObject
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmfColorAdjustment](emfcoloradjustment)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BlueGamma](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/bluegamma) { get; set; } | Obtiene o establece un entero sin signo de 16 bits que especifica el valor de corrección gamma de potencia n-ésima para el azul primario de los colores de origen. Este valor DEBE estar en el rango de 2.500 a 65.000. Un valor de 10.000 significa que la corrección gamma NO DEBE realizarse. |
| [Brightness](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/brightness) { get; set; } | Obtiene o establece un entero de 16 bits con signo que especifica la cantidad de brillo que se aplicará al objeto de origen. Este valor DEBE estar en el rango de –100 a 100. Un valor de cero significa que NO DEBE realizarse un ajuste de brillo. |
| [Colorfullness](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/colorfullness) { get; set; } | Obtiene o establece un entero de 16 bits con signo que especifica la cantidad de colorido que se aplicará al objeto de origen. Este valor DEBE estar en el rango de –100 a 100. Un valor de cero significa que NO DEBE realizarse un ajuste de colorido |
| [Contrast](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/contrast) { get; set; } | Obtiene o establece un entero de 16 bits con signo que especifica la cantidad de contraste que se aplicará al objeto de origen. Este valor DEBE estar en el rango de –100 a 100. Un valor de cero significa que NO DEBE realizarse un ajuste de contraste. |
| [GreenGamma](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/greengamma) { get; set; } | Obtiene o establece un entero sin signo de 16 bits que especifica el valor de corrección gamma de n-ésima potencia para el verde primario de los colores de origen. Este valor DEBE estar en el rango de 2.500 a 65.000. Un valor de 10.000 significa que la corrección gamma NO DEBE realizarse. |
| [IlluminantIndex](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/illuminantindex) { get; set; } | Obtiene o establece un entero sin signo de 16 bits que especifica el tipo de fuente de luz estándar bajo la cual se ve la imagen , de la enumeración Illuminant (sección 2.1.19). |
| [RedGamma](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/redgamma) { get; set; } | Obtiene o establece un entero sin signo de 16 bits que especifica el valor de corrección gamma de potencia n-ésima para el rojo primario de los colores de origen. Este valor DEBE estar en el rango de 2,500 a 65,000. Un valor de 10,000 significa que NO DEBE realizarse la corrección gamma. |
| [RedGreenTint](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/redgreentint) { get; set; } | Obtiene o establece un entero de 16 bits con signo que especifica la cantidad de ajuste de tinte rojo o verde que se aplicará al objeto de origen. Este valor DEBE estar en el rango de –100 a 100. Los números positivos se ajustan hacia el rojo y los números negativos se ajustan hacia el verde. Un valor de cero significa que NO DEBE realizarse un ajuste de matiz |
| [ReferenceBlack](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/referenceblack) { get; set; } | Obtiene o establece un entero sin signo de 16 bits que especifica la referencia negra para los colores de origen. Cualquier color que sea más oscuro que este se tratará como negro. Este valor DEBE estar en el rango de cero a 4,000 |
| [ReferenceWhite](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/referencewhite) { get; set; } | Obtiene o establece un entero sin signo de 16 bits que especifica la referencia blanca para los colores de origen. Cualquier color que sea más claro que este se tratará como blanco. Este valor DEBE estar en el rango de 6,000 a 10,000. |
| [Size](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/size) { get; set; } | Obtiene o establece un entero sin signo de 16 bits que especifica el tamaño en bytes de este objeto. Esto DEBE ser 0x0018. |
| [Values](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/values) { get; set; } | Obtiene o establece un entero sin signo de 16 bits que especifica cómo preparar la imagen de salida. Este campo se puede establecer en NULL o en cualquier combinación de valores en la enumeración ColorAdjustment (sección 2.1.5). |

### Ver también

* class [EmfObject](../emfobject)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
