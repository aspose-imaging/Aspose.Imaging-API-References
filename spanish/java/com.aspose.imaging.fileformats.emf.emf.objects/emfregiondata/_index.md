---
title: "EmfRegionData"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto RegionData especifica datos que definen una región compuesta por rectángulos que no se superponen."
type: docs
weight: 33
url: /es/java/com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfRegionData extends EmfObject
```

El objeto RegionData especifica los datos que definen una región, que está compuesta por rectángulos que no se superponen.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfRegionData()](#EmfRegionData--) | Inicializa una nueva instancia de la clase `EmfRegionData`. |
| [EmfRegionData(Rectangle rectangle)](#EmfRegionData-com.aspose.imaging.Rectangle-) | Inicializa una nueva instancia de la clase `EmfRegionData`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getRegionDataHeader()](#getRegionDataHeader--) | Obtiene un objeto RegionDataHeader de 256 bits que describe los datos siguientes. |
| [setRegionDataHeader(EmfRegionDataHeader value)](#setRegionDataHeader-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionDataHeader-) | Establece un objeto RegionDataHeader de 256 bits que describe los datos siguientes. |
| [getData()](#getData--) | Obtiene una matriz de objetos WMF RectL ([MS-WMF] sección 2.2.2.19); los objetos se combinan para crear la región |
| [setData(Rectangle[] value)](#setData-com.aspose.imaging.Rectangle---) | Establece una matriz de objetos WMF RectL ([MS-WMF] sección 2.2.2.19); los objetos se combinan para crear la región |
### EmfRegionData() {#EmfRegionData--}
```
public EmfRegionData()
```


Inicializa una nueva instancia de la clase `EmfRegionData`.

### EmfRegionData(Rectangle rectangle) {#EmfRegionData-com.aspose.imaging.Rectangle-}
```
public EmfRegionData(Rectangle rectangle)
```


Inicializa una nueva instancia de la clase `EmfRegionData`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo. |

### getRegionDataHeader() {#getRegionDataHeader--}
```
public EmfRegionDataHeader getRegionDataHeader()
```


Obtiene un objeto RegionDataHeader de 256 bits que describe los datos siguientes.

**Returns:**
[EmfRegionDataHeader](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader)
### setRegionDataHeader(EmfRegionDataHeader value) {#setRegionDataHeader-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionDataHeader-}
```
public void setRegionDataHeader(EmfRegionDataHeader value)
```


Establece un objeto RegionDataHeader de 256 bits que describe los datos siguientes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfRegionDataHeader](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader) |  |

### getData() {#getData--}
```
public Rectangle[] getData()
```


Obtiene una matriz de objetos WMF RectL ([MS-WMF] sección 2.2.2.19); los objetos se combinan para crear la región

**Returns:**
com.aspose.imaging.Rectangle[]
### setData(Rectangle[] value) {#setData-com.aspose.imaging.Rectangle---}
```
public void setData(Rectangle[] value)
```


Establece una matriz de objetos WMF RectL ([MS-WMF] sección 2.2.2.19); los objetos se combinan para crear la región

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.imaging/rectangle) |  |

