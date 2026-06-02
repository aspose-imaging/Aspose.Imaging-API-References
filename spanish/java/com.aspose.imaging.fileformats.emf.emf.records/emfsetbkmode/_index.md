---
title: "EmfSetBkMode"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_SETBKMODE especifica el modo de mezcla de fondo del contexto del dispositivo de reproducción."
type: docs
weight: 120
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetbkmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetBkMode extends EmfStateRecordType
```

El registro EMR\_SETBKMODE especifica el modo de mezcla de fondo del contexto del dispositivo de reproducción. El modo de mezcla de fondo se utiliza con texto, pinceles tramados y estilos de lápiz que no son líneas sólidas.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfSetBkMode(EmfRecord source)](#EmfSetBkMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfSetBkMode`. |
| [EmfSetBkMode()](#EmfSetBkMode--) | Inicializa una nueva instancia de la clase `EmfSetBkMode`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBackgroundMode()](#getBackgroundMode--) | Obtiene o establece un entero sin signo de 32 bits que especifica el modo de fondo y DEBE estar en la enumeración BackgroundMode (sección 2.1.4). |
| [setBackgroundMode(int value)](#setBackgroundMode-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el modo de fondo y DEBE estar en la enumeración BackgroundMode (sección 2.1.4). |
### EmfSetBkMode(EmfRecord source) {#EmfSetBkMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetBkMode(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfSetBkMode`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### EmfSetBkMode() {#EmfSetBkMode--}
```
public EmfSetBkMode()
```


Inicializa una nueva instancia de la clase `EmfSetBkMode`.

### getBackgroundMode() {#getBackgroundMode--}
```
public int getBackgroundMode()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el modo de fondo y DEBE estar en la enumeración BackgroundMode (sección 2.1.4).

**Returns:**
int
### setBackgroundMode(int value) {#setBackgroundMode-int-}
```
public void setBackgroundMode(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el modo de fondo y DEBE estar en la enumeración BackgroundMode (sección 2.1.4).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

