---
title: "Clase EmfPlusImageAttributes"
type: docs
weight: 390
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageattributes/
---

**Summary:** The EmfPlusImageAttributes object specifies how bitmap image<br/>            colors are manipulated during rendering.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageAttributes

**Inheritance:** EmfPlusGraphicsObjectType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusImageAttributes()](#EmfPlusImageAttributes__1) | Inicializa una nueva instancia de la clase EmfPlusImageAttributes |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| clamp_argb_32_color | int | r/w | Obtiene o establece el objeto EmfPlusARGB (sección 2.2.2.1) que especifica el color de borde a usar <br/>            cuando el valor WrapMode es WrapModeClamp. Este color es visible cuando el <br/>            rectángulo de origen procesado por un registro EmfPlusDrawImage (sección 2.3.4.8)<br/>            es más grande que la propia imagen. |
| object_clamp | [EmfPlusObjectClamp](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusobjectclamp/) | r/w | Obtiene o establece un entero con signo de 32 bits que especifica el comportamiento de sujeción del objeto.<br/>            No se utiliza hasta que este objeto se aplique a una imagen que está <br/>            siendo dibujada. Este valor DEBE ser uno de los valores definidos en la <br/>            tabla siguiente. |
| version | [EmfPlusGraphicsVersion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/) | r/w | Obtiene o establece la versión. |
| wrap_mode | [EmfPlusWrapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluswrapmode/) | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica cómo manejar las condiciones de borde con <br/>            un valor de la enumeración WrapMode (sección 2.1.1.34). |


### Constructor: EmfPlusImageAttributes() {#EmfPlusImageAttributes__1}


```
 EmfPlusImageAttributes() 
```

Inicializa una nueva instancia de la clase EmfPlusImageAttributes

