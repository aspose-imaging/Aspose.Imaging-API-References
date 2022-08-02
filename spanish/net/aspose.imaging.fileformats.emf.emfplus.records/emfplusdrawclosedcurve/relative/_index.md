---
title: Relative
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Obtiene o establece un valor que indica si esteEmfPlusDrawClosedCurveaspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurvees relativo. Este bit indica si el campo PointData especifica ubicaciones relativas o absolutas. Si se establece cada elemento en PointData especifica una ubicación en el espacio de coordenadas que es relativa a la ubicación especificada por el elemento anterior en la matriz. En el caso del primer elemento en PointData se asume una ubicación anterior en las coordenadas 00. Si está claro PointData especifica ubicaciones absolutas de acuerdo con el indicador C. Nota Si se establece este indicador el indicador comprimido arriba no está definido y DEBE ignorarse
type: docs
weight: 50
url: /es/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/relative/
---
## EmfPlusDrawClosedCurve.Relative property

Obtiene o establece un valor que indica si este[`EmfPlusDrawClosedCurve`](../../emfplusdrawclosedcurve)es relativo. Este bit indica si el campo PointData especifica ubicaciones relativas o absolutas. Si se establece, cada elemento en PointData especifica una ubicación en el espacio de coordenadas que es relativa a la ubicación especificada por el elemento anterior en la matriz. En el caso del primer elemento en PointData, se asume una ubicación anterior en las coordenadas (0,0). Si está claro, PointData especifica ubicaciones absolutas de acuerdo con el indicador C. Nota Si se establece este indicador, el indicador comprimido (arriba) no está definido y DEBE ignorarse

```csharp
public bool Relative { get; set; }
```

### El valor de la propiedad

`verdadero` si es relativo; de lo contrario,`falso` .

### Ver también

* class [EmfPlusDrawClosedCurve](../../emfplusdrawclosedcurve)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../emfplusdrawclosedcurve)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->