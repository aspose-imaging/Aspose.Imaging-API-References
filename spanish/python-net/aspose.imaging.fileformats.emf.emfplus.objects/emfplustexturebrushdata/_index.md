---
title: "Clase EmfPlusTextureBrushData"
type: docs
weight: 680
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/
---

**Summary:** The EmfPlusTextureBrushData object specifies a texture image for a graphics brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTextureBrushData

**Inheritance:** EmfPlusBaseBrushData

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusTextureBrushData()](#EmfPlusTextureBrushData__1) | Inicializa una nueva instancia de la clase EmfPlusTextureBrushData |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| brush_data_flags | [EmfPlusBrushDataFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/) | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica los datos en el campo OptionalData. <br/>
            Este valor DEBE estar compuesto por los indicadores BrushData (sección 2.1.2.1). <br/>
            Los siguientes indicadores son relevantes para un pincel de textura<br/>
            BrushDataTransform<br/>
            BrushDataIsGammaCorrected<br/>
            BrushDataDoNotTransform |
| optional_data | [EmfPlusTextureBrushOptionalData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata/) | r/w | Obtiene o establece un objeto opcional EmfPlusTextureBrushOptionalData (sección 2.2.2.46) que <br/>
            especifica datos adicionales para el pincel de textura. El contenido específico de <br/>
            este campo se determina por el valor del campo BrushDataFlags |
| wrap_mode | [EmfPlusWrapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluswrapmode/) | r/w | Obtiene o establece un entero con signo de 32 bits de la enumeración WrapMode (sección 2.1.1.34) <br/>
            que especifica cómo repetir la imagen de textura a lo largo de una forma, cuando la <br/>
            imagen es más pequeña que el área a rellenar. |


### Constructor: EmfPlusTextureBrushData() {#EmfPlusTextureBrushData__1}


```
 EmfPlusTextureBrushData() 
```

Inicializa una nueva instancia de la clase EmfPlusTextureBrushData

