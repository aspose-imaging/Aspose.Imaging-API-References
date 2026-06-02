---
title: "EmfCreateMonoBrush"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_CREATEMONOBRUSH define un pincel de patrón monocromo para operaciones gráficas."
type: docs
weight: 39
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatemonobrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateMonoBrush extends EmfObjectCreationRecordType
```

El registro EMR\\_CREATEMONOBRUSH define un pincel de patrón monocromo para operaciones gráficas. El patrón se especifica mediante un DIB monocromo.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfCreateMonoBrush(EmfRecord source)](#EmfCreateMonoBrush-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfCreateMonoBrush`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getIhBrush()](#getIhBrush--) | Obtiene o establece un entero sin signo de 32 bits que especifica el índice del objeto de pincel de patrón monocromo en la tabla de objetos EMF (sección 3.1.1.1). |
| [setIhBrush(int value)](#setIhBrush-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el índice del objeto de pincel de patrón monocromo en la tabla de objetos EMF (sección 3.1.1.1). |
| [getUsage()](#getUsage--) | Obtiene o establece un entero sin signo de 32 bits que especifica cómo interpretar los valores en la tabla de colores del encabezado DIB. |
| [setUsage(int value)](#setUsage-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica cómo interpretar los valores en la tabla de colores del encabezado DIB. |
| [getBitmapBuffer()](#getBitmapBuffer--) | Obtiene o establece un búfer que contiene un DIB empaquetado en forma de objeto WMF DeviceIndependentBitmap ([MS-WMF] sección 2.2.2.9). |
| [setBitmapBuffer(WmfDeviceIndependentBitmap value)](#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Obtiene o establece un búfer que contiene un DIB empaquetado en forma de objeto WMF DeviceIndependentBitmap ([MS-WMF] sección 2.2.2.9). |
### EmfCreateMonoBrush(EmfRecord source) {#EmfCreateMonoBrush-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateMonoBrush(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfCreateMonoBrush`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el índice del objeto de pincel de patrón monocromo en la tabla de objetos EMF (sección 3.1.1.1). Este índice DEBE guardarse para que este objeto pueda reutilizarse o modificarse.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el índice del objeto de pincel de patrón monocromo en la tabla de objetos EMF (sección 3.1.1.1). Este índice DEBE guardarse para que este objeto pueda reutilizarse o modificarse.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getUsage() {#getUsage--}
```
public int getUsage()
```


Obtiene o establece un entero sin signo de 32 bits que especifica cómo interpretar los valores en la tabla de colores en el encabezado DIB. Este valor DEBE estar en la enumeración DIBColors (sección 2.1.9).

**Returns:**
int
### setUsage(int value) {#setUsage-int-}
```
public void setUsage(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica cómo interpretar los valores en la tabla de colores en el encabezado DIB. Este valor DEBE estar en la enumeración DIBColors (sección 2.1.9).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getBitmapBuffer() {#getBitmapBuffer--}
```
public WmfDeviceIndependentBitmap getBitmapBuffer()
```


Obtiene o establece un búfer que contiene un DIB empaquetado en forma de un objeto WMF DeviceIndependentBitmap ([MS-WMF] sección 2.2.2.9). No es necesario que sea contiguo con la parte fija del registro EMR\_CREATEDIBPATTERNBRUSHPT.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setBitmapBuffer(WmfDeviceIndependentBitmap value) {#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setBitmapBuffer(WmfDeviceIndependentBitmap value)
```


Obtiene o establece un búfer que contiene un DIB empaquetado en forma de un objeto WMF DeviceIndependentBitmap ([MS-WMF] sección 2.2.2.9). No es necesario que sea contiguo con la parte fija del registro EMR\_CREATEDIBPATTERNBRUSHPT.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

