---
title: "EmfPlusTextureBrushOptionalData Clase"
type: docs
weight: 690
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata/
---

**Summary:** he EmfPlusTextureBrushOptionalData object specifies optional data for a texture brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTextureBrushOptionalData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusTextureBrushOptionalData()](#EmfPlusTextureBrushOptionalData__1) | Inicializa una nueva instancia de la clase EmfPlusTextureBrushOptionalData |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| image_object | [EmfPlusImage](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage/) | r/w | Obtiene o establece un objeto EmfPlusImage opcional (sección 2.2.1.4) que especifica la<br/>            textura del pincel. Este campo DEBE estar presente si el tamaño del <br/>            registro EmfPlusObject (sección 2.3.5.1) que define este pincel de textura <br/>            es lo suficientemente grande para alojar un objeto EmfPlusImage además <br/>            de los campos obligatorios del objeto EmfPlusTextureBrushData <br/>            y opcionalmente un objeto EmfPlusTransformMatrix. |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Obtiene o establece un objeto EmfPlusTransformMatrix opcional (sección 2.2.2.47) <br/>            que especifica una transformación de espacio mundial a espacio de dispositivo para el<br/>             pincel de textura. Este campo DEBE estar presente si el indicador BrushDataTransform <br/>            está establecido en el campo BrushDataFlags del objeto EmfPlusTextureBrushData. |


### Constructor: EmfPlusTextureBrushOptionalData() {#EmfPlusTextureBrushOptionalData__1}


```
 EmfPlusTextureBrushOptionalData() 
```

Inicializa una nueva instancia de la clase EmfPlusTextureBrushOptionalData

