---
title: "EmfExtCreatePen"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_EXTCREATEPEN define una pluma lógica extendida para operaciones gráficas."
type: docs
weight: 52
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfExtCreatePen extends EmfObjectCreationRecordType
```

El registro EMR\_EXTCREATEPEN define una pluma lógica extendida para operaciones gráficas. Se puede especificar un DIB opcional para usar como estilo de línea.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfExtCreatePen(EmfRecord record)](#EmfExtCreatePen-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfExtCreatePen`. |
| [EmfExtCreatePen()](#EmfExtCreatePen--) | Inicializa una nueva instancia de la clase `EmfExtCreatePen`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getIhPen()](#getIhPen--) | Obtiene o establece un entero sin signo de 32 bits que especifica el índice del objeto de lápiz lógico extendido en la EMF Object Table (sección 3.1.1.1). |
| [setIhPen(int value)](#setIhPen-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el índice del objeto de lápiz lógico extendido en la EMF Object Table (sección 3.1.1.1). |
| [getElp()](#getElp--) | Obtiene o establece un objeto LogPenEx (sección 2.2.20) que especifica un lápiz lógico extendido con atributos que incluyen una matriz opcional de estilos de línea. |
| [setElp(EmfLogPenEx value)](#setElp-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPenEx-) | Obtiene o establece un objeto LogPenEx (sección 2.2.20) que especifica un lápiz lógico extendido con atributos que incluyen una matriz opcional de estilos de línea. |
| [getBitmapBuffer()](#getBitmapBuffer--) | Obtiene o establece un búfer opcional que contiene un DIB empaquetado en forma de objeto WMF DeviceIndependentBitmap ([MS-WMF] sección 2.2.2.9). |
| [setBitmapBuffer(WmfDeviceIndependentBitmap value)](#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Obtiene o establece un búfer opcional que contiene un DIB empaquetado en forma de objeto WMF DeviceIndependentBitmap ([MS-WMF] sección 2.2.2.9). |
### EmfExtCreatePen(EmfRecord record) {#EmfExtCreatePen-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtCreatePen(EmfRecord record)
```


Inicializa una nueva instancia de la clase `EmfExtCreatePen`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El registro. |

### EmfExtCreatePen() {#EmfExtCreatePen--}
```
public EmfExtCreatePen()
```


Inicializa una nueva instancia de la clase `EmfExtCreatePen`.

### getIhPen() {#getIhPen--}
```
public int getIhPen()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el índice del objeto de lápiz lógico extendido en la EMF Object Table (sección 3.1.1.1). Este índice DEBE guardarse para que este objeto pueda reutilizarse o modificarse.

**Returns:**
int
### setIhPen(int value) {#setIhPen-int-}
```
public void setIhPen(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el índice del objeto de lápiz lógico extendido en la EMF Object Table (sección 3.1.1.1). Este índice DEBE guardarse para que este objeto pueda reutilizarse o modificarse.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getElp() {#getElp--}
```
public EmfLogPenEx getElp()
```


Obtiene o establece un objeto LogPenEx (sección 2.2.20) que especifica un lápiz lógico extendido con atributos que incluyen una matriz opcional de estilos de línea.

**Returns:**
[EmfLogPenEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpenex)
### setElp(EmfLogPenEx value) {#setElp-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPenEx-}
```
public void setElp(EmfLogPenEx value)
```


Obtiene o establece un objeto LogPenEx (sección 2.2.20) que especifica un lápiz lógico extendido con atributos que incluyen una matriz opcional de estilos de línea.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfLogPenEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpenex) |  |

### getBitmapBuffer() {#getBitmapBuffer--}
```
public WmfDeviceIndependentBitmap getBitmapBuffer()
```


Obtiene o establece un búfer opcional que contiene un DIB empaquetado en forma de objeto WMF DeviceIndependentBitmap ([MS-WMF] sección 2.2.2.9). No es necesario que sea contiguo con la porción fija del registro EMR\_EXTCREATEPEN.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setBitmapBuffer(WmfDeviceIndependentBitmap value) {#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setBitmapBuffer(WmfDeviceIndependentBitmap value)
```


Obtiene o establece un búfer opcional que contiene un DIB empaquetado en forma de objeto WMF DeviceIndependentBitmap ([MS-WMF] sección 2.2.2.9). No es necesario que sea contiguo con la porción fija del registro EMR\_EXTCREATEPEN.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

