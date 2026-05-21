---
title: "EmfPlusHeader"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfPlusHeader especifica el inicio de los datos EMF en el metafichero."
type: docs
weight: 40
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusControlRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfpluscontrolrecordtype)
```
public final class EmfPlusHeader extends EmfPlusControlRecordType
```

El registro EmfPlusHeader especifica el inicio de los datos EMF+ en el metafile. El registro EmfPlusHeader DEBE estar incrustado en un registro EMF EMR\_COMMENT\_EMFPLUS, que DEBE ser el registro que sigue inmediatamente al encabezado EMF en el metafile. El registro EMR\_COMMENT\_EMFPLUS se especifica en la sección 2.3.3.2 de [MS-EMF].
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusHeader(EmfPlusRecord source)](#EmfPlusHeader-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusHeader`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getDualMode()](#getDualMode--) | Obtiene o establece un valor que indica si está en [dual mode]. |
| [setDualMode(boolean value)](#setDualMode-boolean-) | Obtiene o establece un valor que indica si está en [dual mode]. |
| [getVideoDisplay()](#getVideoDisplay--) | Obtiene o establece un valor que indica si hay visualización de video. |
| [setVideoDisplay(boolean value)](#setVideoDisplay-boolean-) | Obtiene o establece un valor que indica si hay visualización de video. |
| [getEmfPlusFlags()](#getEmfPlusFlags--) | Obtiene o establece las banderas EMF plus. |
| [setEmfPlusFlags(int value)](#setEmfPlusFlags-int-) | Obtiene o establece las banderas EMF plus. |
| [getLogicalDpiX()](#getLogicalDpiX--) | Obtiene o establece el dpi lógico x. |
| [setLogicalDpiX(int value)](#setLogicalDpiX-int-) | Obtiene o establece el dpi lógico x. |
| [getLogicalDpiY()](#getLogicalDpiY--) | Obtiene o establece el dpi lógico y. |
| [setLogicalDpiY(int value)](#setLogicalDpiY-int-) | Obtiene o establece el dpi lógico y. |
| [getVersion()](#getVersion--) | Obtiene o establece la versión. |
| [setVersion(EmfPlusGraphicsVersion value)](#setVersion-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsVersion-) | Obtiene o establece la versión. |
| [isValid()](#isValid--) | Obtiene un valor que indica si esta instancia es válida. |
### EmfPlusHeader(EmfPlusRecord source) {#EmfPlusHeader-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusHeader(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusHeader`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | El origen. |

### getDualMode() {#getDualMode--}
```
public boolean getDualMode()
```


Obtiene o establece un valor que indica si está en [dual mode]. Si se establece, esta bandera indica que este metafile está en "dual-mode", lo que significa que contiene dos conjuntos de registros, cada uno de los cuales especifica completamente el contenido gráfico. Si se borra, el contenido gráfico se especifica mediante registros EMF+, y posiblemente registros EMF que son precedidos por un registro EmfPlusGetDC. Si esta bandera está establecida, los registros EMF por sí solos DEBERÍAN ser suficientes para definir el contenido gráfico. Observe que, tanto si la bandera "dual-mode" está establecida como si no, siempre están presentes algunos registros EMF, a saber, los registros de control EMF y los registros EMF que contienen registros EMF+. Los registros de control EMF se especifican en la sección 2.3.4 de [MS-EMF].

Valor: `true` si [dual mode]; de lo contrario, `false`.

**Returns:**
boolean
### setDualMode(boolean value) {#setDualMode-boolean-}
```
public void setDualMode(boolean value)
```


Obtiene o establece un valor que indica si está en [dual mode]. Si se establece, esta bandera indica que este metafile está en "dual-mode", lo que significa que contiene dos conjuntos de registros, cada uno de los cuales especifica completamente el contenido gráfico. Si se borra, el contenido gráfico se especifica mediante registros EMF+, y posiblemente registros EMF que son precedidos por un registro EmfPlusGetDC. Si esta bandera está establecida, los registros EMF por sí solos DEBERÍAN ser suficientes para definir el contenido gráfico. Observe que, tanto si la bandera "dual-mode" está establecida como si no, siempre están presentes algunos registros EMF, a saber, los registros de control EMF y los registros EMF que contienen registros EMF+. Los registros de control EMF se especifican en la sección 2.3.4 de [MS-EMF].

Valor: `true` si [dual mode]; de lo contrario, `false`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getVideoDisplay() {#getVideoDisplay--}
```
public boolean getVideoDisplay()
```


Obtiene o establece un valor que indica si hay visualización de video. Si se establece, esta bandera indica que el metafile se grabó con un contexto de dispositivo de referencia para una visualización de video. Si se borra, el metafile se grabó con un contexto de dispositivo de referencia para una impresora.

Valor: `true` si [video display]; de lo contrario, `false`.

**Returns:**
boolean
### setVideoDisplay(boolean value) {#setVideoDisplay-boolean-}
```
public void setVideoDisplay(boolean value)
```


Obtiene o establece un valor que indica si hay visualización de video. Si se establece, esta bandera indica que el metafile se grabó con un contexto de dispositivo de referencia para una visualización de video. Si se borra, el metafile se grabó con un contexto de dispositivo de referencia para una impresora.

Valor: `true` si [video display]; de lo contrario, `false`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getEmfPlusFlags() {#getEmfPlusFlags--}
```
public int getEmfPlusFlags()
```


Obtiene o establece las banderas EMF plus. Un entero sin signo de 32 bits que contiene información sobre cómo se grabó este metafile. Si el bit 31 del campo está establecido, esta bandera indica que el metafile se grabó con un contexto de dispositivo de referencia para una visualización de video. Si se borra, el metafile se grabó con un contexto de dispositivo de referencia para una impresora.

Valor: Las banderas EMF plus.

**Returns:**
int
### setEmfPlusFlags(int value) {#setEmfPlusFlags-int-}
```
public void setEmfPlusFlags(int value)
```


Obtiene o establece las banderas EMF plus. Un entero sin signo de 32 bits que contiene información sobre cómo se grabó este metafile. Si el bit 31 del campo está establecido, esta bandera indica que el metafile se grabó con un contexto de dispositivo de referencia para una visualización de video. Si se borra, el metafile se grabó con un contexto de dispositivo de referencia para una impresora.

Valor: Las banderas EMF plus.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getLogicalDpiX() {#getLogicalDpiX--}
```
public int getLogicalDpiX()
```


Obtiene o establece el dpi lógico x. Un entero sin signo de 32 bits que especifica la resolución horizontal para la cual se grabó el metafile, en unidades de píxeles por pulgada.

Valor: El dpi lógico x.

**Returns:**
int
### setLogicalDpiX(int value) {#setLogicalDpiX-int-}
```
public void setLogicalDpiX(int value)
```


Obtiene o establece el dpi lógico x. Un entero sin signo de 32 bits que especifica la resolución horizontal para la cual se grabó el metafile, en unidades de píxeles por pulgada.

Valor: El dpi lógico x.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getLogicalDpiY() {#getLogicalDpiY--}
```
public int getLogicalDpiY()
```


Obtiene o establece el dpi lógico y. Un entero sin signo de 32 bits que especifica la resolución vertical para la cual se grabó el metafile, en unidades de líneas por pulgada.

Valor: El dpi lógico y.

**Returns:**
int
### setLogicalDpiY(int value) {#setLogicalDpiY-int-}
```
public void setLogicalDpiY(int value)
```


Obtiene o establece el dpi lógico y. Un entero sin signo de 32 bits que especifica la resolución vertical para la cual se grabó el metafile, en unidades de líneas por pulgada.

Valor: El dpi lógico y.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getVersion() {#getVersion--}
```
public EmfPlusGraphicsVersion getVersion()
```


Obtiene o establece la versión. Un objeto EmfPlusGraphicsVersion (sección 2.2.2.19) que especifica la versión de los gráficos del sistema operativo que se utilizó para crear este metafile.

Valor: La versión.

**Returns:**
[EmfPlusGraphicsVersion](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion)
### setVersion(EmfPlusGraphicsVersion value) {#setVersion-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsVersion-}
```
public void setVersion(EmfPlusGraphicsVersion value)
```


Obtiene o establece la versión. Un objeto EmfPlusGraphicsVersion (sección 2.2.2.19) que especifica la versión de los gráficos del sistema operativo que se utilizó para crear este metafile.

Valor: La versión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfPlusGraphicsVersion](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion) |  |

### isValid() {#isValid--}
```
public boolean isValid()
```


Obtiene un valor que indica si esta instancia es válida.

Valor: `true` si esta instancia es válida; de lo contrario, `false`.

**Returns:**
boolean
