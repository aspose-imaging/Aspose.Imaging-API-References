---
title: "EmfSmallTextOut"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_SMALLTEXTOUT produce una cadena."
type: docs
weight: 147
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfSmallTextOut extends EmfDrawingRecordType
```

El registro EMR\_SMALLTEXTOUT genera una cadena.

Si ETO\_SMALL\_CHARS está establecido en el campo fuOptions, TextString contiene códigos de 8 bits para los caracteres, derivados de los bytes bajos de los códigos de caracteres Unicode UTF16-LE de 16 bits, donde se asume que el byte alto es 0. Si ETO\_NO\_RECT está establecido en el campo fuOptions, el campo Bounds no se incluye en el registro.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfSmallTextOut(EmfRecord source)](#EmfSmallTextOut-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfSmallTextOut`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getX()](#getX--) | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada x de donde colocar la cadena. |
| [setX(int value)](#setX-int-) | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada x de donde colocar la cadena. |
| [getY()](#getY--) | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada y de donde colocar la cadena. |
| [setY(int value)](#setY-int-) | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada y de donde colocar la cadena. |
| [getCChars()](#getCChars--) | Obtiene o establece un entero sin signo de 32 bits que especifica el número de caracteres de 16 bits en la cadena. |
| [setCChars(int value)](#setCChars-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el número de caracteres de 16 bits en la cadena. |
| [getFuOptions()](#getFuOptions--) | Obtiene o establece un entero sin signo de 32 bits que especifica las opciones de salida de texto a usar. |
| [setFuOptions(int value)](#setFuOptions-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica las opciones de salida de texto a usar. |
| [getIGraphicsMode()](#getIGraphicsMode--) | Obtiene o establece un entero sin signo de 32 bits que especifica el modo gráfico, de la enumeración GraphicsMode (sección 2.1.16). |
| [setIGraphicsMode(int value)](#setIGraphicsMode-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el modo gráfico, de la enumeración GraphicsMode (sección 2.1.16). |
| [getExScale()](#getExScale--) | Obtiene o establece un valor de punto flotante de 32 bits que especifica cuánto escalar el texto en la dirección x. |
| [setExScale(float value)](#setExScale-float-) | Obtiene o establece un valor de punto flotante de 32 bits que especifica cuánto escalar el texto en la dirección x. |
| [getEyScale()](#getEyScale--) | Obtiene o establece un valor de punto flotante de 32 bits que especifica cuánto escalar el texto en la dirección y. |
| [setEyScale(float value)](#setEyScale-float-) | Obtiene o establece un valor de punto flotante de 32 bits que especifica cuánto escalar el texto en la dirección y. |
| [getBounds()](#getBounds--) | Obtiene o establece un objeto WMF RectL opcional de 128 bits ([MS-WMF] sección 2.2.2.19) que especifica el rectángulo delimitador en unidades de dispositivo. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Obtiene o establece un objeto WMF RectL opcional de 128 bits ([MS-WMF] sección 2.2.2.19) que especifica el rectángulo delimitador en unidades de dispositivo. |
| [getTextString()](#getTextString--) | Obtiene o establece una cadena de longitud variable que contiene la cadena de texto a dibujar, ya sea en códigos de caracteres de 8 bits o de 16 bits, según el valor del campo fuOptions. |
| [setTextString(String value)](#setTextString-java.lang.String-) | Obtiene o establece una cadena de longitud variable que contiene la cadena de texto a dibujar, ya sea en códigos de caracteres de 8 bits o de 16 bits, según el valor del campo fuOptions. |
### EmfSmallTextOut(EmfRecord source) {#EmfSmallTextOut-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSmallTextOut(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfSmallTextOut`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### getX() {#getX--}
```
public int getX()
```


Obtiene o establece un entero con signo de 32 bits que especifica la coordenada x de donde colocar la cadena.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica la coordenada x de donde colocar la cadena.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getY() {#getY--}
```
public int getY()
```


Obtiene o establece un entero con signo de 32 bits que especifica la coordenada y de donde colocar la cadena.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica la coordenada y de donde colocar la cadena.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getCChars() {#getCChars--}
```
public int getCChars()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el número de caracteres de 16 bits en la cadena. La cadena NO está terminada en nulo.

**Returns:**
int
### setCChars(int value) {#setCChars-int-}
```
public void setCChars(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el número de caracteres de 16 bits en la cadena. La cadena NO está terminada en nulo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getFuOptions() {#getFuOptions--}
```
public int getFuOptions()
```


Obtiene o establece un entero sin signo de 32 bits que especifica las opciones de salida de texto a usar. Estas opciones se especifican mediante uno o una combinación de valores de la enumeración ExtTextOutOptions (sección 2.1.11).

**Returns:**
int
### setFuOptions(int value) {#setFuOptions-int-}
```
public void setFuOptions(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica las opciones de salida de texto a usar. Estas opciones se especifican mediante uno o una combinación de valores de la enumeración ExtTextOutOptions (sección 2.1.11).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getIGraphicsMode() {#getIGraphicsMode--}
```
public int getIGraphicsMode()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el modo gráfico, de la enumeración GraphicsMode (sección 2.1.16).

**Returns:**
int
### setIGraphicsMode(int value) {#setIGraphicsMode-int-}
```
public void setIGraphicsMode(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el modo gráfico, de la enumeración GraphicsMode (sección 2.1.16).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getExScale() {#getExScale--}
```
public float getExScale()
```


Obtiene o establece un valor de punto flotante de 32 bits que especifica cuánto escalar el texto en la dirección x.

**Returns:**
float
### setExScale(float value) {#setExScale-float-}
```
public void setExScale(float value)
```


Obtiene o establece un valor de punto flotante de 32 bits que especifica cuánto escalar el texto en la dirección x.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getEyScale() {#getEyScale--}
```
public float getEyScale()
```


Obtiene o establece un valor de punto flotante de 32 bits que especifica cuánto escalar el texto en la dirección y.

**Returns:**
float
### setEyScale(float value) {#setEyScale-float-}
```
public void setEyScale(float value)
```


Obtiene o establece un valor de punto flotante de 32 bits que especifica cuánto escalar el texto en la dirección y.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Obtiene o establece un objeto WMF RectL opcional de 128 bits ([MS-WMF] sección 2.2.2.19) que especifica el rectángulo delimitador en unidades de dispositivo.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Obtiene o establece un objeto WMF RectL opcional de 128 bits ([MS-WMF] sección 2.2.2.19) que especifica el rectángulo delimitador en unidades de dispositivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getTextString() {#getTextString--}
```
public String getTextString()
```


Obtiene o establece una cadena de longitud variable que contiene la cadena de texto a dibujar, ya sea en códigos de caracteres de 8 bits o de 16 bits, según el valor del campo fuOptions.

**Returns:**
java.lang.String
### setTextString(String value) {#setTextString-java.lang.String-}
```
public void setTextString(String value)
```


Obtiene o establece una cadena de longitud variable que contiene la cadena de texto a dibujar, ya sea en códigos de caracteres de 8 bits o de 16 bits, según el valor del campo fuOptions.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

