---
title: "EmfPolyTextOutW"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_POLYTEXTOUTW dibuja una o más cadenas de texto Unicode usando la fuente y los colores de texto actuales."
type: docs
weight: 98
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPolyTextOutW extends EmfDrawingRecordType
```

El registro EMR\_POLYTEXTOUTW dibuja una o más cadenas de texto Unicode usando la fuente y los colores de texto actuales.

La fuente y los colores de texto utilizados para la salida se especifican mediante propiedades en el estado actual del contexto del dispositivo de reproducción. EMR\_POLYTEXTOUTW DEBERÍA emularse con una serie de registros EMR\_EXTTEXTOUTW (sección 2.3.5.7), uno por cadena.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPolyTextOutW(EmfRecord source)](#EmfPolyTextOutW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfPolyTextOutW`. |
| [EmfPolyTextOutW()](#EmfPolyTextOutW--) | Inicializa una nueva instancia de la clase `EmfPolyTextOutW`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBounds()](#getBounds--) | Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19), que especifica el rectángulo delimitador en unidades del dispositivo. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19), que especifica el rectángulo delimitador en unidades del dispositivo. |
| [getIGraphicsMode()](#getIGraphicsMode--) | Obtiene o establece un entero sin signo de 32 bits que especifica el modo gráfico actual, de la enumeración GraphicsMode (sección 2.1.16). |
| [setIGraphicsMode(int value)](#setIGraphicsMode-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el modo gráfico actual, de la enumeración GraphicsMode (sección 2.1.16). |
| [getExScale()](#getExScale--) | Obtiene o establece un valor de punto flotante de 32 bits que especifica la escala X de unidades de página a unidades de .01 mm si el modo gráfico es GM\_COMPATIBLE. |
| [setExScale(float value)](#setExScale-float-) | Obtiene o establece un valor de punto flotante de 32 bits que especifica la escala X de unidades de página a unidades de .01 mm si el modo gráfico es GM\_COMPATIBLE. |
| [getEyScale()](#getEyScale--) | Obtiene o establece un valor de punto flotante de 32 bits que especifica la escala Y de unidades de página a unidades de .01 mm si el modo gráfico es GM\_COMPATIBLE. |
| [setEyScale(float value)](#setEyScale-float-) | Obtiene o establece un valor de punto flotante de 32 bits que especifica la escala Y de unidades de página a unidades de .01 mm si el modo gráfico es GM\_COMPATIBLE. |
| [getWEmrText()](#getWEmrText--) | Obtiene o establece una matriz de objetos EmrText (sección 2.2.5) que especifican las cadenas de salida en caracteres Unicode UTF16-LE de 16 bits, con atributos de texto y valores de espaciado. |
| [setWEmrText(EmfText[] value)](#setWEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText---) | Obtiene o establece una matriz de objetos EmrText (sección 2.2.5) que especifican las cadenas de salida en caracteres Unicode UTF16-LE de 16 bits, con atributos de texto y valores de espaciado. |
### EmfPolyTextOutW(EmfRecord source) {#EmfPolyTextOutW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyTextOutW(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfPolyTextOutW`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### EmfPolyTextOutW() {#EmfPolyTextOutW--}
```
public EmfPolyTextOutW()
```


Inicializa una nueva instancia de la clase `EmfPolyTextOutW`.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19), que especifica el rectángulo delimitador en unidades del dispositivo.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19), que especifica el rectángulo delimitador en unidades del dispositivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getIGraphicsMode() {#getIGraphicsMode--}
```
public int getIGraphicsMode()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el modo gráfico actual, de la enumeración GraphicsMode (sección 2.1.16).

**Returns:**
int
### setIGraphicsMode(int value) {#setIGraphicsMode-int-}
```
public void setIGraphicsMode(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el modo gráfico actual, de la enumeración GraphicsMode (sección 2.1.16).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getExScale() {#getExScale--}
```
public float getExScale()
```


Obtiene o establece un valor de punto flotante de 32 bits que especifica la escala X de unidades de página a unidades de .01 mm si el modo gráfico es GM\_COMPATIBLE.

**Returns:**
float
### setExScale(float value) {#setExScale-float-}
```
public void setExScale(float value)
```


Obtiene o establece un valor de punto flotante de 32 bits que especifica la escala X de unidades de página a unidades de .01 mm si el modo gráfico es GM\_COMPATIBLE.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getEyScale() {#getEyScale--}
```
public float getEyScale()
```


Obtiene o establece un valor de punto flotante de 32 bits que especifica la escala Y de unidades de página a unidades de .01 mm si el modo gráfico es GM\_COMPATIBLE.

**Returns:**
float
### setEyScale(float value) {#setEyScale-float-}
```
public void setEyScale(float value)
```


Obtiene o establece un valor de punto flotante de 32 bits que especifica la escala Y de unidades de página a unidades de .01 mm si el modo gráfico es GM\_COMPATIBLE.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getWEmrText() {#getWEmrText--}
```
public EmfText[] getWEmrText()
```


Obtiene o establece una matriz de objetos EmrText (sección 2.2.5) que especifican las cadenas de salida en caracteres Unicode UTF16-LE de 16 bits, con atributos de texto y valores de espaciado. El número de objetos EmrText se especifica mediante cStrings.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfText[]
### setWEmrText(EmfText[] value) {#setWEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText---}
```
public void setWEmrText(EmfText[] value)
```


Obtiene o establece una matriz de objetos EmrText (sección 2.2.5) que especifican las cadenas de salida en caracteres Unicode UTF16-LE de 16 bits, con atributos de texto y valores de espaciado. El número de objetos EmrText se especifica mediante cStrings.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfText\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emftext) |  |

