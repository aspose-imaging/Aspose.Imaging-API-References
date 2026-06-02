---
title: "EmfPlusCustomLineCapOptionalData Clase"
type: docs
weight: 280
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata/
---

**Summary:** The EmfPlusCustomLineCapOptionalData object specifies optional fill and outline data for a custom line cap.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomLineCapOptionalData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusCustomLineCapOptionalData()](#EmfPlusCustomLineCapOptionalData__1) | Inicializa una nueva instancia de la clase EmfPlusCustomLineCapOptionalData |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| fill_data | [EmfPlusFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusfillpath/) | r/w | Obtiene o establece el objeto opcional EmfPlusFillPath (sección 2.2.2.17) que especifica la ruta para rellenar una cap de línea gráfica personalizada.<br/>            Este campo DEBE estar presente si la bandera CustomLineCapDataFillPath está establecida en los CustomLineCapDataFlags<br/>            campo del objeto EmfPlusCustomLineCapData. |
| outline_data | [EmfPlusLinePath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslinepath/) | r/w | Obtiene o establece el objeto opcional EmfPlusLinePath (sección 2.2.2.26) <br/>            que especifica la ruta para delinear una cap de línea gráfica personalizada. Este campo DEBE estar presente si la bandera CustomLineCapDataLinePath está establecida en los CustomLineCapDataFlags <br/>            campo del objeto EmfPlusCustomLineCapData. |


### Constructor: EmfPlusCustomLineCapOptionalData() {#EmfPlusCustomLineCapOptionalData__1}


```
 EmfPlusCustomLineCapOptionalData() 
```

Inicializa una nueva instancia de la clase EmfPlusCustomLineCapOptionalData

