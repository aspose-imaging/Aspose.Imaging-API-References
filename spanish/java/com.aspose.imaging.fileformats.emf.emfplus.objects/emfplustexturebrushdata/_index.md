---
title: "EmfPlusTextureBrushData"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto EmfPlusTextureBrushData especifica una imagen de textura para un pincel gráfico."
type: docs
weight: 77
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
```
public final class EmfPlusTextureBrushData extends EmfPlusBaseBrushData
```

El objeto EmfPlusTextureBrushData especifica una imagen de textura para un pincel gráfico.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusTextureBrushData()](#EmfPlusTextureBrushData--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBrushDataFlags()](#getBrushDataFlags--) | Obtiene o establece un entero sin signo de 32 bits que especifica los datos en el campo OptionalData. |
| [setBrushDataFlags(int value)](#setBrushDataFlags-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica los datos en el campo OptionalData. |
| [getWrapMode()](#getWrapMode--) | Obtiene o establece un entero con signo de 32 bits de la enumeración WrapMode (sección 2.1.1.34) que especifica cómo repetir la imagen de textura a lo largo de una forma, cuando la imagen es más pequeña que el área a rellenar. |
| [setWrapMode(int value)](#setWrapMode-int-) | Obtiene o establece un entero con signo de 32 bits de la enumeración WrapMode (sección 2.1.1.34) que especifica cómo repetir la imagen de textura a lo largo de una forma, cuando la imagen es más pequeña que el área a rellenar. |
| [getOptionalData()](#getOptionalData--) | Obtiene o establece un objeto opcional EmfPlusTextureBrushOptionalData (sección 2.2.2.46) que especifica datos adicionales para el pincel de textura. |
| [setOptionalData(EmfPlusTextureBrushOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTextureBrushOptionalData-) | Obtiene o establece un objeto opcional EmfPlusTextureBrushOptionalData (sección 2.2.2.46) que especifica datos adicionales para el pincel de textura. |
### EmfPlusTextureBrushData() {#EmfPlusTextureBrushData--}
```
public EmfPlusTextureBrushData()
```


### getBrushDataFlags() {#getBrushDataFlags--}
```
public int getBrushDataFlags()
```


Obtiene o establece un entero sin signo de 32 bits que especifica los datos en el campo OptionalData. Este valor DEBE estar compuesto por banderas BrushData (sección 2.1.2.1). Las siguientes banderas son relevantes para un pincel de textura: BrushDataTransform BrushDataIsGammaCorrected BrushDataDoNotTransform

**Returns:**
int
### setBrushDataFlags(int value) {#setBrushDataFlags-int-}
```
public void setBrushDataFlags(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica los datos en el campo OptionalData. Este valor DEBE estar compuesto por banderas BrushData (sección 2.1.2.1). Las siguientes banderas son relevantes para un pincel de textura: BrushDataTransform BrushDataIsGammaCorrected BrushDataDoNotTransform

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Obtiene o establece un entero con signo de 32 bits de la enumeración WrapMode (sección 2.1.1.34) que especifica cómo repetir la imagen de textura a lo largo de una forma, cuando la imagen es más pequeña que el área a rellenar.

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Obtiene o establece un entero con signo de 32 bits de la enumeración WrapMode (sección 2.1.1.34) que especifica cómo repetir la imagen de textura a lo largo de una forma, cuando la imagen es más pequeña que el área a rellenar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusTextureBrushOptionalData getOptionalData()
```


Obtiene o establece un objeto opcional EmfPlusTextureBrushOptionalData (sección 2.2.2.46) que especifica datos adicionales para el pincel de textura. El contenido específico de este campo se determina por el valor del campo BrushDataFlags

**Returns:**
[EmfPlusTextureBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata)
### setOptionalData(EmfPlusTextureBrushOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTextureBrushOptionalData-}
```
public void setOptionalData(EmfPlusTextureBrushOptionalData value)
```


Obtiene o establece un objeto opcional EmfPlusTextureBrushOptionalData (sección 2.2.2.46) que especifica datos adicionales para el pincel de textura. El contenido específico de este campo se determina por el valor del campo BrushDataFlags

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfPlusTextureBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata) |  |

