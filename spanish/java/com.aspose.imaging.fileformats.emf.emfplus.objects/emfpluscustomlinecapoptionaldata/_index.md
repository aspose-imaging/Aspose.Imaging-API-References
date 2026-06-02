---
title: "EmfPlusCustomLineCapOptionalData"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto EmfPlusCustomLineCapOptionalData especifica datos opcionales de relleno y contorno para una tapa de línea personalizada."
type: docs
weight: 37
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusCustomLineCapOptionalData extends EmfPlusStructureObjectType
```

El objeto EmfPlusCustomLineCapOptionalData especifica datos opcionales de relleno y contorno para una tapa de línea personalizada.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusCustomLineCapOptionalData()](#EmfPlusCustomLineCapOptionalData--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFillData()](#getFillData--) | Obtiene o establece el objeto opcional EmfPlusFillPath (sección 2.2.2.17) que especifica la ruta para rellenar una tapa de línea gráfica personalizada. |
| [setFillData(EmfPlusFillPath value)](#setFillData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusFillPath-) | Obtiene o establece el objeto opcional EmfPlusFillPath (sección 2.2.2.17) que especifica la ruta para rellenar una tapa de línea gráfica personalizada. |
| [getOutlineData()](#getOutlineData--) | Obtiene o establece el objeto opcional EmfPlusLinePath (sección 2.2.26) que especifica la ruta para delinear una tapa de línea gráfica personalizada. |
| [setOutlineData(EmfPlusLinePath value)](#setOutlineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinePath-) | Obtiene o establece el objeto opcional EmfPlusLinePath (sección 2.2.26) que especifica la ruta para delinear una tapa de línea gráfica personalizada. |
### EmfPlusCustomLineCapOptionalData() {#EmfPlusCustomLineCapOptionalData--}
```
public EmfPlusCustomLineCapOptionalData()
```


### getFillData() {#getFillData--}
```
public EmfPlusFillPath getFillData()
```


Obtiene o establece el objeto opcional EmfPlusFillPath (sección 2.2.17) que especifica la ruta para rellenar una tapa de línea gráfica personalizada. Este campo DEBE estar presente si la bandera CustomLineCapDataFillPath está establecida en el campo CustomLineCapDataFlags del objeto EmfPlusCustomLineCapData.

**Returns:**
[EmfPlusFillPath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfillpath)
### setFillData(EmfPlusFillPath value) {#setFillData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusFillPath-}
```
public void setFillData(EmfPlusFillPath value)
```


Obtiene o establece el objeto opcional EmfPlusFillPath (sección 2.2.17) que especifica la ruta para rellenar una tapa de línea gráfica personalizada. Este campo DEBE estar presente si la bandera CustomLineCapDataFillPath está establecida en el campo CustomLineCapDataFlags del objeto EmfPlusCustomLineCapData.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfPlusFillPath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfillpath) |  |

### getOutlineData() {#getOutlineData--}
```
public EmfPlusLinePath getOutlineData()
```


Obtiene o establece el objeto opcional EmfPlusLinePath (sección 2.2.26) que especifica la ruta para delinear una tapa de línea gráfica personalizada. Este campo DEBE estar presente si la bandera CustomLineCapDataLinePath está establecida en el campo CustomLineCapDataFlags del objeto EmfPlusCustomLineCapData.

**Returns:**
[EmfPlusLinePath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslinepath)
### setOutlineData(EmfPlusLinePath value) {#setOutlineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinePath-}
```
public void setOutlineData(EmfPlusLinePath value)
```


Obtiene o establece el objeto opcional EmfPlusLinePath (sección 2.2.26) que especifica la ruta para delinear una tapa de línea gráfica personalizada. Este campo DEBE estar presente si la bandera CustomLineCapDataLinePath está establecida en el campo CustomLineCapDataFlags del objeto EmfPlusCustomLineCapData.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfPlusLinePath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslinepath) |  |

