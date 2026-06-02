---
title: "EmfSetPolyFillMode"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_SETPOLYFILLMODE define el modo de relleno de polígonos."
type: docs
weight: 136
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetpolyfillmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetPolyFillMode extends EmfStateRecordType
```

El registro EMR\_SETPOLYFILLMODE define el modo de relleno de polígonos.

En general, los modos difieren solo en los casos en que un polígono complejo y superpuesto DEBE ser rellenado; por ejemplo, un polígono de cinco lados que forma una estrella de cinco puntas con un pentágono en el centro. En tales casos, el modo ALTERNATE DEBERÍA rellenar cada otra región encerrada dentro del polígono (los puntos de la estrella), pero el modo WINDING DEBERÍA rellenar todas las regiones (los puntos de la estrella y el pentágono). Cuando el modo de relleno es ALTERNATE, el área entre los lados impares y pares del polígono en cada línea de escaneo DEBERÍA ser rellenada. Es decir, el área entre el primer y segundo lado DEBERÍA ser rellenada, y entre el tercer y cuarto lado, y así sucesivamente. Cuando el modo de relleno es WINDING, cualquier región que tenga un valor de winding distinto de cero DEBERÍA ser rellenada. El valor de winding es el número de veces que una pluma usada para dibujar el polígono daría la vuelta a la región. La dirección de cada borde del polígono es significativa.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfSetPolyFillMode(EmfRecord source)](#EmfSetPolyFillMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfSetPolyFillMode`. |
| [EmfSetPolyFillMode()](#EmfSetPolyFillMode--) | Inicializa una nueva instancia de la clase `EmfSetPolyFillMode`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getPolygonFillMode()](#getPolygonFillMode--) | Obtiene o establece un entero sin signo de 32 bits que especifica el modo de relleno de polígonos y DEBE estar en la enumeración PolygonFillMode (sección 2.1.27). |
| [setPolygonFillMode(int value)](#setPolygonFillMode-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el modo de relleno de polígonos y DEBE estar en la enumeración PolygonFillMode (sección 2.1.27). |
### EmfSetPolyFillMode(EmfRecord source) {#EmfSetPolyFillMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetPolyFillMode(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfSetPolyFillMode`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### EmfSetPolyFillMode() {#EmfSetPolyFillMode--}
```
public EmfSetPolyFillMode()
```


Inicializa una nueva instancia de la clase `EmfSetPolyFillMode`.

### getPolygonFillMode() {#getPolygonFillMode--}
```
public int getPolygonFillMode()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el modo de relleno de polígonos y DEBE estar en la enumeración PolygonFillMode (sección 2.1.27).

**Returns:**
int
### setPolygonFillMode(int value) {#setPolygonFillMode-int-}
```
public void setPolygonFillMode(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el modo de relleno de polígonos y DEBE estar en la enumeración PolygonFillMode (sección 2.1.27).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

