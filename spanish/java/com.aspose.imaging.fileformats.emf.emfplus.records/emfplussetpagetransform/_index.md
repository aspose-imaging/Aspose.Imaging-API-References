---
title: "EmfPlusSetPageTransform"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfPlusSetPageTransform especifica los factores de escala y unidades para convertir coordenadas del espacio de página a coordenadas del espacio del dispositivo."
type: docs
weight: 61
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetpagetransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusSetPageTransform extends EmfPlusTerminalServerRecordType
```

El registro EmfPlusSetPageTransform especifica los factores de escala y unidades para convertir coordenadas del espacio de página a coordenadas del espacio del dispositivo.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusSetPageTransform(EmfPlusRecord source)](#EmfPlusSetPageTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusSetPageTransform`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getPageUnit()](#getPageUnit--) | Obtiene la unidad de medida para las coordenadas del espacio de página, a partir de la enumeración UnitType (sección 2.1.1.33). |
| [getPageScale()](#getPageScale--) | Obtiene o establece un valor de punto flotante de 32 bits que especifica el factor de escala para convertir coordenadas del espacio de página a coordenadas del espacio del dispositivo. |
| [setPageScale(float value)](#setPageScale-float-) | Obtiene o establece un valor de punto flotante de 32 bits que especifica el factor de escala para convertir coordenadas del espacio de página a coordenadas del espacio del dispositivo. |
### EmfPlusSetPageTransform(EmfPlusRecord source) {#EmfPlusSetPageTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetPageTransform(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusSetPageTransform`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | El origen. |

### getPageUnit() {#getPageUnit--}
```
public int getPageUnit()
```


Obtiene la unidad de medida para las coordenadas del espacio de página, a partir de la enumeración UnitType (sección 2.1.1.33). Este valor NO DEBERÍA ser UnitTypeDisplay ni UnitTypeWorld.

Valor: La unidad de página.

**Returns:**
int
### getPageScale() {#getPageScale--}
```
public float getPageScale()
```


Obtiene o establece un valor de punto flotante de 32 bits que especifica el factor de escala para convertir coordenadas del espacio de página a coordenadas del espacio del dispositivo.

Valor: La escala de página.

**Returns:**
float
### setPageScale(float value) {#setPageScale-float-}
```
public void setPageScale(float value)
```


Obtiene o establece un valor de punto flotante de 32 bits que especifica el factor de escala para convertir coordenadas del espacio de página a coordenadas del espacio del dispositivo.

Valor: La escala de página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

