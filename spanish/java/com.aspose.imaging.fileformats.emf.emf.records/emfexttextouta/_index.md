---
title: "EmfExtTextOutA"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_EXTTEXTOUTA dibuja una cadena de texto ASCII usando la fuente actual y los colores del texto."
type: docs
weight: 56
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfexttextouta/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfExtTextOutA extends EmfDrawingRecordType
```

El registro EMR\_EXTTEXTOUTA dibuja una cadena de texto ASCII usando la fuente actual y los colores de texto.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfExtTextOutA(EmfRecord source)](#EmfExtTextOutA-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfExtTextOutA`. |
| [EmfExtTextOutA()](#EmfExtTextOutA--) | Inicializa una nueva instancia de la clase [EmfExtTextOutA](../../com.aspose.imaging.fileformats.emf.emf.records/emfexttextouta). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBounds()](#getBounds--) | Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19). |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19). |
| [getIGraphicsMode()](#getIGraphicsMode--) | Obtiene o establece un entero sin signo de 32 bits que especifica el modo gráfico de la enumeración GraphicsMode (sección 2.1.16). |
| [setIGraphicsMode(int value)](#setIGraphicsMode-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el modo gráfico de la enumeración GraphicsMode (sección 2.1.16). |
| [getExScale()](#getExScale--) | Obtiene o establece un valor de punto flotante de 32 bits que especifica el factor de escala a aplicar a lo largo del eje X para convertir de unidades de espacio de página a unidades de .01 mm. |
| [setExScale(float value)](#setExScale-float-) | Obtiene o establece un valor de punto flotante de 32 bits que especifica el factor de escala a aplicar a lo largo del eje X para convertir de unidades de espacio de página a unidades de .01 mm. |
| [getEyScale()](#getEyScale--) | Obtiene o establece un valor de punto flotante de 32 bits que especifica el factor de escala a aplicar a lo largo del eje Y para convertir de unidades de espacio de página a unidades de .01 mm. |
| [setEyScale(float value)](#setEyScale-float-) | Obtiene o establece un valor de punto flotante de 32 bits que especifica el factor de escala a aplicar a lo largo del eje Y para convertir de unidades de espacio de página a unidades de .01 mm. |
| [getAEmrText()](#getAEmrText--) | Obtiene o establece un objeto EmrText (sección 2.2.5) que especifica la cadena de salida en caracteres ASCII de 8 bits, atributos de texto y valores de espaciado. |
| [setAEmrText(EmfText value)](#setAEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText-) | Obtiene o establece un objeto EmrText (sección 2.2.5) que especifica la cadena de salida en caracteres ASCII de 8 bits, atributos de texto y valores de espaciado. |
### EmfExtTextOutA(EmfRecord source) {#EmfExtTextOutA-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtTextOutA(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfExtTextOutA`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### EmfExtTextOutA() {#EmfExtTextOutA--}
```
public EmfExtTextOutA()
```


Inicializa una nueva instancia de la clase [EmfExtTextOutA](../../com.aspose.imaging.fileformats.emf.emf.records/emfexttextouta).

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19). No se utiliza y DEBE ignorarse al recibirlo.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19). No se utiliza y DEBE ignorarse al recibirlo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getIGraphicsMode() {#getIGraphicsMode--}
```
public int getIGraphicsMode()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el modo gráfico de la enumeración GraphicsMode (sección 2.1.16).

**Returns:**
int
### setIGraphicsMode(int value) {#setIGraphicsMode-int-}
```
public void setIGraphicsMode(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el modo gráfico de la enumeración GraphicsMode (sección 2.1.16).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getExScale() {#getExScale--}
```
public float getExScale()
```


Obtiene o establece un valor de punto flotante de 32 bits que especifica el factor de escala a aplicar a lo largo del eje X para convertir de unidades de espacio de página a unidades de .01 mm. Esto DEBERÍA usarse solo si el modo gráfico especificado por iGraphicsMode es GM\_COMPATIBLE.

**Returns:**
float
### setExScale(float value) {#setExScale-float-}
```
public void setExScale(float value)
```


Obtiene o establece un valor de punto flotante de 32 bits que especifica el factor de escala a aplicar a lo largo del eje X para convertir de unidades de espacio de página a unidades de .01 mm. Esto DEBERÍA usarse solo si el modo gráfico especificado por iGraphicsMode es GM\_COMPATIBLE.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getEyScale() {#getEyScale--}
```
public float getEyScale()
```


Obtiene o establece un valor de punto flotante de 32 bits que especifica el factor de escala a aplicar a lo largo del eje Y para convertir de unidades de espacio de página a unidades de .01 mm. Esto DEBERÍA usarse solo si el modo gráfico especificado por iGraphicsMode es GM\_COMPATIBLE.

**Returns:**
float
### setEyScale(float value) {#setEyScale-float-}
```
public void setEyScale(float value)
```


Obtiene o establece un valor de punto flotante de 32 bits que especifica el factor de escala a aplicar a lo largo del eje Y para convertir de unidades de espacio de página a unidades de .01 mm. Esto DEBERÍA usarse solo si el modo gráfico especificado por iGraphicsMode es GM\_COMPATIBLE.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getAEmrText() {#getAEmrText--}
```
public EmfText getAEmrText()
```


Obtiene o establece un objeto EmrText (sección 2.2.5) que especifica la cadena de salida en caracteres ASCII de 8 bits, atributos de texto y valores de espaciado.

**Returns:**
[EmfText](../../com.aspose.imaging.fileformats.emf.emf.objects/emftext)
### setAEmrText(EmfText value) {#setAEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText-}
```
public void setAEmrText(EmfText value)
```


Obtiene o establece un objeto EmrText (sección 2.2.5) que especifica la cadena de salida en caracteres ASCII de 8 bits, atributos de texto y valores de espaciado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfText](../../com.aspose.imaging.fileformats.emf.emf.objects/emftext) |  |

