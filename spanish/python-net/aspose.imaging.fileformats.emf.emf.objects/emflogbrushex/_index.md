---
title: "Clase EmfLogBrushEx"
type: docs
weight: 120
url: /es/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogbrushex/
---

**Summary:** The LogBrushEx object defines the style, color, and pattern of a device-independent brush.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfLogBrushEx

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfLogBrushEx()](#EmfLogBrushEx__1) | Inicializa una nueva instancia de la clase EmfLogBrushEx |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| argb_32_color_ref | int | r/w | Obtiene o establece un objeto WMF ColorRef de 32 bits ([MS-WMF] sección 2.2.2.8) que especifica un<br/>            color. La interpretación de este campo depende del valor de BrushStyle, como se explica en la<br/>            tabla siguiente. |
| brush_hatch | [EmfHatchStyle](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfhatchstyle/) | r/w | Obtiene o establece un campo sin signo de 32 bits que contiene los datos de trama del pincel. Su <br/>            interpretación depende del valor de BrushStyle, |
| brush_style | [WmfBrushStyle](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfbrushstyle/) | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el estilo del pincel. El valor DEBE <br/>            ser una enumeración de la enumeración WMF BrushStyle ([MS-WMF] sección 2.1.1.4). Los valores de estilo <br/>            que son compatibles con esta estructura se enumeran más adelante en esta sección. El estilo BS_NULL <br/>            DEBERÍA usarse para especificar un pincel que no tiene efecto. |


### Constructor: EmfLogBrushEx() {#EmfLogBrushEx__1}


```
 EmfLogBrushEx() 
```

Inicializa una nueva instancia de la clase EmfLogBrushEx

