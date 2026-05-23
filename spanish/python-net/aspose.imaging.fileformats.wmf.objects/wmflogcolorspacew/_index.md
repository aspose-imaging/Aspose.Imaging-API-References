---
title: "Clase WmfLogColorSpaceW"
type: docs
weight: 390
url: /es/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/
---

**Summary:** The LogColorSpaceW object specifies a logical color space, which can be<br/>                defined by a color profile file with a name consisting of Unicode 16-bit<br/>                characters.

**Module:** [aspose.imaging.fileformats.wmf.objects](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/)

**Full Name:** aspose.imaging.fileformats.wmf.objects.WmfLogColorSpaceW

**Inheritance:** MetaObject

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [WmfLogColorSpaceW()](#WmfLogColorSpaceW__1) | Inicializa una nueva instancia de la clase WmfLogColorSpaceW |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| color_space_type | [WmfLogicalColorSpaceEnum](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmflogicalcolorspaceenum/) | r/w | Obtiene o establece un entero con signo de 32 bits que especifica el espacio de color<br/>                tipo. DEBE estar definido en la enumeración LogicalColorSpace<br/>                (sección 2.1.1.14). Si este valor es LCS_sRGB o<br/>                LCS_WINDOWS_COLOR_SPACE, el espacio de color sRGB DEBE ser usado. |
| endpoints | [WmfCieXyzTriple](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfciexyztriple/) | r/w | Obtiene o establece un objeto CIEXYZTriple (sección 2.2.2.7) que define<br/>                las coordenadas de cromaticidad CIE x, y, z de los tres colores<br/>                que corresponden al RGB [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) para el espacio de color lógico<br/>                asociado con el mapa de bits. Si el<br/>                [WmfLogColorSpaceW.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) campo no especifica<br/>                LCS_CALIBRATED_RGB, este campo DEBE ser ignorado. |
| filename | string | r/w | Obtiene o establece una cadena de caracteres Unicode UTF16-LE opcional, terminada en nulo<br/>                que especifica el nombre de un archivo que contiene un perfil de color. Si se especifica un nombre de archivo, y el<br/>                [WmfLogColorSpaceW.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) campo está configurado a LCS_CALIBRATED_RGB, los<br/>                demás campos de esta estructura DEBERÁN ser ignorados. |
| gamma_blue | int | r/w | Obtiene o establece un valor de punto fijo de 32 bits que define la curva tonal<br/>                de respuesta para azul. Si el campo [WmfLogColorSpaceW.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) no especifica LCS_CALIBRATED_RGB, este campo DEBE ser ignorado. |
| gamma_green | int | r/w | Obtiene o establece un valor de punto fijo de 32 bits que define la curva tonal<br/>                de respuesta para verde. Si el campo [WmfLogColorSpaceW.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) no especifica LCS_CALIBRATED_RGB, este campo DEBE ser ignorado. |
| gamma_red | int | r/w | Obtiene o establece un valor de punto fijo de 32 bits que define la curva tonal<br/>                de respuesta para rojo. Si el campo [WmfLogColorSpaceW.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) no especifica LCS_CALIBRATED_RGB, este campo DEBE ser ignorado. |
| intent | [WmfGamutMappingIntent](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfgamutmappingintent/) | r/w | Obtiene o establece un entero con signo de 32 bits que define la intención de mapeo de gamut<br/>                . DEBE estar definido en la enumeración GamutMappingIntent<br/>                (sección 2.1.1.11). |
| signature | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) de objetos de espacio de color; DEBE establecerse en<br/>                el valor 0x50534F43, que es la codificación ASCII de la cadena<br/>                "PSOC". |
| size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que define el<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) de este objeto, en bytes. |
| version | int | r/w | Obtiene o establece un entero sin signo de 32 bits que define un<br/>                número [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) ; DEBE ser 0x00000400. |


### Constructor: WmfLogColorSpaceW() {#WmfLogColorSpaceW__1}


```
 WmfLogColorSpaceW() 
```

Inicializa una nueva instancia de la clase WmfLogColorSpaceW

