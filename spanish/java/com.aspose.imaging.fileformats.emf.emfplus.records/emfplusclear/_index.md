---
title: "EmfPlusClear"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfPlusClear borra el espacio de coordenadas de salida y lo inicializa con un color de fondo y transparencia."
type: docs
weight: 12
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusclear/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusClear extends EmfPlusDrawingRecordType
```

El registro EmfPlusClear borra el espacio de coordenadas de salida y lo inicializa con un color de fondo y transparencia.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusClear(EmfPlusRecord source)](#EmfPlusClear-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusClear`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getArgb32Color()](#getArgb32Color--) | Obtiene o establece el color. |
| [setArgb32Color(int value)](#setArgb32Color-int-) | Obtiene o establece el color. |
### EmfPlusClear(EmfPlusRecord source) {#EmfPlusClear-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusClear(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusClear`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | El origen. |

### getArgb32Color() {#getArgb32Color--}
```
public int getArgb32Color()
```


Obtiene o establece el color. Un objeto EmfPlusARGB (sección 2.2.2.1) que define el color para pintar la pantalla. Todos los colores se especifican en [IEC-RGB], a menos que se indique lo contrario.

Valor: El color.

**Returns:**
int
### setArgb32Color(int value) {#setArgb32Color-int-}
```
public void setArgb32Color(int value)
```


Obtiene o establece el color. Un objeto EmfPlusARGB (sección 2.2.2.1) que define el color para pintar la pantalla. Todos los colores se especifican en [IEC-RGB], a menos que se indique lo contrario.

Valor: El color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

