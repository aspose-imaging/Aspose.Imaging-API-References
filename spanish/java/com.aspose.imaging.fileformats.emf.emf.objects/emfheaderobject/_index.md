---
title: "EmfHeaderObject"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto Header define el encabezado del metarchivo EMF."
type: docs
weight: 20
url: /es/java/com.aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public class EmfHeaderObject extends EmfObject
```

El objeto Header define el encabezado del metafichero EMF. Especifica las propiedades del dispositivo en el que se creó la imagen del metafichero.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfHeaderObject()](#EmfHeaderObject--) | Inicializa una nueva instancia de la clase `EmfHeaderObject`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBounds()](#getBounds--) | Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que especifica los límites rectangulares inclusivo-inclusivo en unidades del dispositivo del rectángulo más pequeño que se puede dibujar alrededor de la imagen almacenada en el metafichero |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que especifica los límites rectangulares inclusivo-inclusivo en unidades del dispositivo del rectángulo más pequeño que se puede dibujar alrededor de la imagen almacenada en el metafichero |
| [getFrame()](#getFrame--) | Obtiene o establece un objeto WMF RectL que especifica las dimensiones rectangulares inclusivo-inclusivo, en unidades de 0,01 milímetros, de un rectángulo que rodea la imagen almacenada en el metafichero |
| [setFrame(Rectangle value)](#setFrame-com.aspose.imaging.Rectangle-) | Obtiene o establece un objeto WMF RectL que especifica las dimensiones rectangulares inclusivo-inclusivo, en unidades de 0,01 milímetros, de un rectángulo que rodea la imagen almacenada en el metafichero |
| [getRecordSignature()](#getRecordSignature--) | Obtiene o establece un entero sin signo de 32 bits que especifica la firma del registro. |
| [setRecordSignature(int value)](#setRecordSignature-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica la firma del registro. |
| [getVersion()](#getVersion--) | Obtiene o establece Version (4 bytes): Un entero sin signo de 32 bits que especifica la interoperabilidad del metafichero EMF. |
| [setVersion(int value)](#setVersion-int-) | Obtiene o establece Version (4 bytes): Un entero sin signo de 32 bits que especifica la interoperabilidad del metafichero EMF. |
| [getBytes()](#getBytes--) | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño del metafichero, en bytes. |
| [setBytes(int value)](#setBytes-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño del metafichero, en bytes. |
| [getRecords()](#getRecords--) | Obtiene o establece un entero sin signo de 32 bits que especifica el número de registros en el metafichero |
| [setRecords(int value)](#setRecords-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el número de registros en el metafichero |
| [getHandles()](#getHandles--) | Obtiene o establece un entero sin signo de 16 bits que especifica el número de objetos gráficos que se utilizarán durante el procesamiento del metafichero |
| [setHandles(short value)](#setHandles-short-) | Obtiene o establece un entero sin signo de 16 bits que especifica el número de objetos gráficos que se utilizarán durante el procesamiento del metafichero |
| [getReserved()](#getReserved--) | Obtiene o establece un entero sin signo de 16 bits que DEBE ser 0x0000 y DEBE ser ignorado |
| [setReserved(short value)](#setReserved-short-) | Obtiene o establece un entero sin signo de 16 bits que DEBE ser 0x0000 y DEBE ser ignorado |
| [getNDesription()](#getNDesription--) | Obtiene o establece un entero sin signo de 32 bits que especifica el número de caracteres en la matriz que contiene la descripción del contenido del metafichero. |
| [setNDesription(int value)](#setNDesription-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el número de caracteres en la matriz que contiene la descripción del contenido del metafichero. |
| [getOffDescription()](#getOffDescription--) | Obtiene o establece un entero sin signo de 32 bits que especifica el desplazamiento desde el inicio de este registro hasta la matriz que contiene la descripción del contenido del metafichero |
| [setOffDescription(int value)](#setOffDescription-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el desplazamiento desde el inicio de este registro hasta la matriz que contiene la descripción del contenido del metafichero |
| [getNPalEntries()](#getNPalEntries--) | Obtiene o establece un entero sin signo de 32 bits que especifica el número de entradas en la paleta del metafichero. |
| [setNPalEntries(int value)](#setNPalEntries-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el número de entradas en la paleta del metafichero. |
| [getDevice()](#getDevice--) | Obtiene o establece un objeto WMF SizeL ([MS-WMF] sección 2.2.2.22) que especifica el tamaño del dispositivo de referencia, en píxeles |
| [setDevice(Size value)](#setDevice-com.aspose.imaging.Size-) | Obtiene o establece un objeto WMF SizeL ([MS-WMF] sección 2.2.2.22) que especifica el tamaño del dispositivo de referencia, en píxeles |
| [getMillimeters()](#getMillimeters--) | Obtiene o establece un objeto WMF SizeL que especifica el tamaño del dispositivo de referencia, en milímetros |
| [setMillimeters(Size value)](#setMillimeters-com.aspose.imaging.Size-) | Obtiene o establece un objeto WMF SizeL que especifica el tamaño del dispositivo de referencia, en milímetros |
| [getValid()](#getValid--) | Obtiene un valor que indica si este `EmfHeaderObject` es válido. |
### EmfHeaderObject() {#EmfHeaderObject--}
```
public EmfHeaderObject()
```


Inicializa una nueva instancia de la clase `EmfHeaderObject`.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que especifica los límites rectangulares inclusivo-inclusivo en unidades del dispositivo del rectángulo más pequeño que se puede dibujar alrededor de la imagen almacenada en el metafichero

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que especifica los límites rectangulares inclusivo-inclusivo en unidades del dispositivo del rectángulo más pequeño que se puede dibujar alrededor de la imagen almacenada en el metafichero

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getFrame() {#getFrame--}
```
public Rectangle getFrame()
```


Obtiene o establece un objeto WMF RectL que especifica las dimensiones rectangulares inclusivo-inclusivo, en unidades de 0,01 milímetros, de un rectángulo que rodea la imagen almacenada en el metafichero

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setFrame(Rectangle value) {#setFrame-com.aspose.imaging.Rectangle-}
```
public void setFrame(Rectangle value)
```


Obtiene o establece un objeto WMF RectL que especifica las dimensiones rectangulares inclusivo-inclusivo, en unidades de 0,01 milímetros, de un rectángulo que rodea la imagen almacenada en el metafichero

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getRecordSignature() {#getRecordSignature--}
```
public int getRecordSignature()
```


Obtiene o establece un entero sin signo de 32 bits que especifica la firma del registro. Esto DEBE ser ENHMETA\_SIGNATURE, de la enumeración FormatSignature (sección 2.1.14).

**Returns:**
int
### setRecordSignature(int value) {#setRecordSignature-int-}
```
public void setRecordSignature(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica la firma del registro. Esto DEBE ser ENHMETA\_SIGNATURE, de la enumeración FormatSignature (sección 2.1.14).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Obtiene o establece Version (4 bytes): Un entero sin signo de 32 bits que especifica la interoperabilidad del metafichero EMF. Esto DEBERÍA ser 0x00010000

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Obtiene o establece Version (4 bytes): Un entero sin signo de 32 bits que especifica la interoperabilidad del metafichero EMF. Esto DEBERÍA ser 0x00010000

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getBytes() {#getBytes--}
```
public int getBytes()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño del metafichero, en bytes.

**Returns:**
int
### setBytes(int value) {#setBytes-int-}
```
public void setBytes(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño del metafichero, en bytes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getRecords() {#getRecords--}
```
public int getRecords()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el número de registros en el metafichero

**Returns:**
int
### setRecords(int value) {#setRecords-int-}
```
public void setRecords(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el número de registros en el metafichero

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getHandles() {#getHandles--}
```
public short getHandles()
```


Obtiene o establece un entero sin signo de 16 bits que especifica el número de objetos gráficos que se utilizarán durante el procesamiento del metafichero

**Returns:**
short
### setHandles(short value) {#setHandles-short-}
```
public void setHandles(short value)
```


Obtiene o establece un entero sin signo de 16 bits que especifica el número de objetos gráficos que se utilizarán durante el procesamiento del metafichero

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### getReserved() {#getReserved--}
```
public short getReserved()
```


Obtiene o establece un entero sin signo de 16 bits que DEBE ser 0x0000 y DEBE ser ignorado

**Returns:**
short
### setReserved(short value) {#setReserved-short-}
```
public void setReserved(short value)
```


Obtiene o establece un entero sin signo de 16 bits que DEBE ser 0x0000 y DEBE ser ignorado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### getNDesription() {#getNDesription--}
```
public int getNDesription()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el número de caracteres en la matriz que contiene la descripción del contenido del metafichero. Esto es cero si no hay cadena de descripción.

**Returns:**
int
### setNDesription(int value) {#setNDesription-int-}
```
public void setNDesription(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el número de caracteres en la matriz que contiene la descripción del contenido del metafichero. Esto es cero si no hay cadena de descripción.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getOffDescription() {#getOffDescription--}
```
public int getOffDescription()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el desplazamiento desde el inicio de este registro hasta la matriz que contiene la descripción del contenido del metafichero

**Returns:**
int
### setOffDescription(int value) {#setOffDescription-int-}
```
public void setOffDescription(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el desplazamiento desde el inicio de este registro hasta la matriz que contiene la descripción del contenido del metafichero

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getNPalEntries() {#getNPalEntries--}
```
public int getNPalEntries()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el número de entradas en la paleta del metafichero. La paleta se encuentra en el registro EMR\_EOF

**Returns:**
int
### setNPalEntries(int value) {#setNPalEntries-int-}
```
public void setNPalEntries(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el número de entradas en la paleta del metafichero. La paleta se encuentra en el registro EMR\_EOF

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getDevice() {#getDevice--}
```
public Size getDevice()
```


Obtiene o establece un objeto WMF SizeL ([MS-WMF] sección 2.2.2.22) que especifica el tamaño del dispositivo de referencia, en píxeles

**Returns:**
[Size](../../com.aspose.imaging/size)
### setDevice(Size value) {#setDevice-com.aspose.imaging.Size-}
```
public void setDevice(Size value)
```


Obtiene o establece un objeto WMF SizeL ([MS-WMF] sección 2.2.2.22) que especifica el tamaño del dispositivo de referencia, en píxeles

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Size](../../com.aspose.imaging/size) |  |

### getMillimeters() {#getMillimeters--}
```
public Size getMillimeters()
```


Obtiene o establece un objeto WMF SizeL que especifica el tamaño del dispositivo de referencia, en milímetros

**Returns:**
[Size](../../com.aspose.imaging/size)
### setMillimeters(Size value) {#setMillimeters-com.aspose.imaging.Size-}
```
public void setMillimeters(Size value)
```


Obtiene o establece un objeto WMF SizeL que especifica el tamaño del dispositivo de referencia, en milímetros

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Size](../../com.aspose.imaging/size) |  |

### getValid() {#getValid--}
```
public boolean getValid()
```


Obtiene un valor que indica si este `EmfHeaderObject` es válido.

Valor: `true` si es válido; de lo contrario, `false`.

**Returns:**
boolean
