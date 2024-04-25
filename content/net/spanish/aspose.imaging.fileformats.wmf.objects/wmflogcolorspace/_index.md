---
title: WmfLogColorSpace
second_title: Aspose.Imaging para la referencia de la API de .NET
description: El objeto LogColorSpace especifica un espacio de color lógico para el contexto del dispositivo de reproducción  que puede ser el nombre de un perfil de color en caracteres ASCII.
type: docs
weight: 8750
url: /es/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/
---
## WmfLogColorSpace class

El objeto LogColorSpace especifica un espacio de color lógico para el contexto del dispositivo de reproducción , que puede ser el nombre de un perfil de color en caracteres ASCII.

```csharp
public class WmfLogColorSpace : MetaObject
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [WmfLogColorSpace](wmflogcolorspace)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ColorSpaceType](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/colorspacetype) { get; set; } | Obtiene o establece un entero de 32 bits con signo que especifica el tipo de espacio de color . DEBE definirse en LogicalColorSpace enumeration (sección 2.1.1.14). Si este valor es LCS_sRGB o LCS_WINDOWS_COLOR_SPACE, DEBE usarse el espacio de color sRGB. |
| [Endpoints](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/endpoints) { get; set; } | Obtiene o establece un objeto CIEXYZTriple (sección 2.2.2.7) que define las coordenadas x, y y z de cromaticidad CIE de los tres colores que corresponden al RGBendpoints para el espacio de color logical asociado con el mapa de bits. Si el [`ColorSpaceType`](./colorspacetype) el campo no especifica LCS_CALIBRADO_RGB, este campo DEBE ignorarse. |
| [Filename](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/filename) { get; set; } | Obtiene o establece una cadena de caracteres ASCII opcional que especifica el nombre de un archivo que contiene un perfil de color. Si se especifica un nombre de archivo y el[`ColorSpaceType`](./colorspacetype) está establecido en LCS_CALIBRADO_RGB, los otros campos de esta estructura DEBERÍAN ser ignorados. |
| [GammaBlue](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/gammablue) { get; set; } | Obtiene o establece un valor de punto fijo de 32 bits que define la curva de respuesta toned para el azul. Si el[`ColorSpaceType`](./colorspacetype) field no especifica LCS_CALIBRATE_RGB, este campo DEBE ignorarse. |
| [GammaGreen](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/gammagreen) { get; set; } | Obtiene o establece un valor de punto fijo de 32 bits que define la curva de respuesta toned para el verde. Si el[`ColorSpaceType`](./colorspacetype) field no especifica LCS_CALIBRATE_RGB, este campo DEBE ignorarse. |
| [GammaRed](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/gammared) { get; set; } | Obtiene o establece un valor de punto fijo de 32 bits que define la curva de respuesta toned para el rojo. Si el[`ColorSpaceType`](./colorspacetype) field no especifica LCS_CALIBRATE_RGB, este campo DEBE ignorarse. |
| [Intent](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/intent) { get; set; } | Obtiene o establece un entero con signo de 32 bits que define la intención de asignación de gama . DEBE definirse en la enumeración GamutMappingIntent (sección 2.1.1.11). |
| [Signature](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/signature) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica el signature de objetos del espacio de color; DEBE establecerse en el valor 0x50534F43, que es la codificación ASCII de la cadena "PSOC". |
| [Size](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/size) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que define el size de este objeto, en bytes. |
| [Version](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/version) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que define a version número; DEBE ser 0x00000400. |

### Observaciones

Los campos Endpoints, GammaRed, GammaGreen y GammaBlue se utilizan para especificar un espacio de color lógico. El campo Puntos finales es un objeto CIEXYZTriple que contiene los valores x, y y z del punto final RGB del espacio de color . La relación entre los valores de triestímulo X,Y,Z y los valores de cromaticidad x,y,z se expresa de la siguiente manera. x = X/(X+Y+Z) y = Y/(X+Y+Z) z = Z/(X+Y+Z) Los campos GammaRed, GammaGreen y GammaBlue contienen valores en "8.8 punto fijo" format, que es una técnica para que representa números no enteros. Cada valor consta de una magnitud de 8 bits zeroextended seguida de una fracción de 8 bits, con los 16 bits combinados desplazados a la izquierda en 8 bits. Así, en 32 bits, el valor real NF es 00000000nnnnnnnnffffffff00000000, donde "nnnnnnnn" y "ffffffff" son representaciones binarias de N y F, respectivamente. Por ejemplo, para The_ Real Number 10.5, nnnnnnnnn sería 00001010 (binario 10) y fffffffff sería 00000101 (binario 5), y el valor binario completo de 32 bits Will Be 00000000000000100000000100000000, que es el valor Hexadecimal 0x0a505050

### Ver también

* class [MetaObject](../../aspose.imaging.fileformats.emf/metaobject)
* espacio de nombres [Aspose.Imaging.FileFormats.Wmf.Objects](../../aspose.imaging.fileformats.wmf.objects)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
