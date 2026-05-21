---
title: "EmfCreateDibPatternBrushPt"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_CREATEDIBPATTERNBRUSHPT define un pincel de patrón para operaciones gráficas."
type: docs
weight: 38
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatedibpatternbrushpt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateDibPatternBrushPt extends EmfObjectCreationRecordType
```

El registro EMR\_CREATEDIBPATTERNBRUSHPT define un pincel de patrón para operaciones gráficas. El patrón se especifica mediante un DIB.

El objeto pincel de patrón definido por este registro puede seleccionarse en el contexto del dispositivo de reproducción mediante un registro EMR\_SELECTOBJECT (sección 2.3.8.5), que especifica el pincel de patrón a usar en operaciones gráficas posteriores.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfCreateDibPatternBrushPt(EmfRecord source)](#EmfCreateDibPatternBrushPt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfCreateDibPatternBrushPt`. |
| [EmfCreateDibPatternBrushPt()](#EmfCreateDibPatternBrushPt--) | Inicializa una nueva instancia de la clase `EmfCreateDibPatternBrushPt`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getIhBrush()](#getIhBrush--) | Obtiene o establece un entero sin signo de 32 bits que especifica el índice del objeto pincel de patrón en la tabla de objetos EMF (sección 3.1.1.1). |
| [setIhBrush(int value)](#setIhBrush-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el índice del objeto pincel de patrón en la tabla de objetos EMF (sección 3.1.1.1). |
| [getUsage()](#getUsage--) | Obtiene o establece un entero sin signo de 32 bits que especifica cómo interpretar los valores en la tabla de colores del encabezado DIB. |
| [setUsage(int value)](#setUsage-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica cómo interpretar los valores en la tabla de colores del encabezado DIB. |
| [getBitmapBuffer()](#getBitmapBuffer--) | Obtiene o establece un búfer que contiene un DIB empaquetado en forma de objeto WMF DeviceIndependentBitmap ([MS-WMF] sección 2.2.2.9). |
| [setBitmapBuffer(WmfDeviceIndependentBitmap value)](#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Obtiene o establece un búfer que contiene un DIB empaquetado en forma de objeto WMF DeviceIndependentBitmap ([MS-WMF] sección 2.2.2.9). |
### EmfCreateDibPatternBrushPt(EmfRecord source) {#EmfCreateDibPatternBrushPt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateDibPatternBrushPt(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfCreateDibPatternBrushPt`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### EmfCreateDibPatternBrushPt() {#EmfCreateDibPatternBrushPt--}
```
public EmfCreateDibPatternBrushPt()
```


Inicializa una nueva instancia de la clase `EmfCreateDibPatternBrushPt`.

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el índice del objeto pincel de patrón en la tabla de objetos EMF (sección 3.1.1.1). Este índice DEBE guardarse para que este objeto pueda reutilizarse o modificarse.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el índice del objeto pincel de patrón en la tabla de objetos EMF (sección 3.1.1.1). Este índice DEBE guardarse para que este objeto pueda reutilizarse o modificarse.

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

