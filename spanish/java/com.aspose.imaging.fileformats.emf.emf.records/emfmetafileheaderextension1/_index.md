---
title: "EmfMetafileHeaderExtension1"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfMetafileHeaderExtension1 es el registro de encabezado utilizado en la primera extensión de los metarchivos EMF."
type: docs
weight: 71
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader)
```
public class EmfMetafileHeaderExtension1 extends EmfMetafileHeader
```

El registro EmfMetafileHeaderExtension1 es el registro de encabezado utilizado en la primera extensión de los metarchivos EMF. Después del campo EmfHeaderExtension1, los campos restantes son opcionales y pueden aparecer en cualquier orden.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfMetafileHeaderExtension1(EmfMetafileHeader header)](#EmfMetafileHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-) | Inicializa una nueva instancia de la clase `EmfMetafileHeaderExtension1`. |
| [EmfMetafileHeaderExtension1(EmfMetafileHeaderExtension1 header)](#EmfMetafileHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeaderExtension1-) | Inicializa una nueva instancia de la clase `EmfMetafileHeaderExtension1`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getEmfHeaderExtension1()](#getEmfHeaderExtension1--) | Obtiene o establece un objeto HeaderExtension1, que especifica información adicional sobre la imagen en el metarchivo. |
| [setEmfHeaderExtension1(EmfHeaderExtension1 value)](#setEmfHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderExtension1-) | Obtiene o establece un objeto HeaderExtension1, que especifica información adicional sobre la imagen en el metarchivo. |
| [getEmfPixelFormatBuffer()](#getEmfPixelFormatBuffer--) | Obtiene o establece una matriz opcional de bytes que contiene el descriptor de formato de píxel EMF, que no es necesario que sea contigua con la porción fija del registro EmfMetafileHeaderExtension1 o con la cadena de descripción EMF. |
| [setEmfPixelFormatBuffer(byte[] value)](#setEmfPixelFormatBuffer-byte---) | Obtiene o establece una matriz opcional de bytes que contiene el descriptor de formato de píxel EMF, que no es necesario que sea contigua con la porción fija del registro EmfMetafileHeaderExtension1 o con la cadena de descripción EMF. |
### EmfMetafileHeaderExtension1(EmfMetafileHeader header) {#EmfMetafileHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-}
```
public EmfMetafileHeaderExtension1(EmfMetafileHeader header)
```


Inicializa una nueva instancia de la clase `EmfMetafileHeaderExtension1`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| header | [EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) | El encabezado. |

### EmfMetafileHeaderExtension1(EmfMetafileHeaderExtension1 header) {#EmfMetafileHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeaderExtension1-}
```
public EmfMetafileHeaderExtension1(EmfMetafileHeaderExtension1 header)
```


Inicializa una nueva instancia de la clase `EmfMetafileHeaderExtension1`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| header | [EmfMetafileHeaderExtension1](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1) | El encabezado. |

### getEmfHeaderExtension1() {#getEmfHeaderExtension1--}
```
public EmfHeaderExtension1 getEmfHeaderExtension1()
```


Obtiene o establece un objeto HeaderExtension1, que especifica información adicional sobre la imagen en el metarchivo.

**Returns:**
[EmfHeaderExtension1](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1)
### setEmfHeaderExtension1(EmfHeaderExtension1 value) {#setEmfHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderExtension1-}
```
public void setEmfHeaderExtension1(EmfHeaderExtension1 value)
```


Obtiene o establece un objeto HeaderExtension1, que especifica información adicional sobre la imagen en el metarchivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfHeaderExtension1](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1) |  |

### getEmfPixelFormatBuffer() {#getEmfPixelFormatBuffer--}
```
public byte[] getEmfPixelFormatBuffer()
```


Obtiene o establece una matriz opcional de bytes que contiene el descriptor de formato de píxel EMF, que no es necesario que sea contigua con la porción fija del registro EmfMetafileHeaderExtension1 o con la cadena de descripción EMF. En consecuencia, el campo en este búfer etiquetado como "UndefinedSpace" es opcional y DEBE ser ignorado.

**Returns:**
byte[]
### setEmfPixelFormatBuffer(byte[] value) {#setEmfPixelFormatBuffer-byte---}
```
public void setEmfPixelFormatBuffer(byte[] value)
```


Obtiene o establece una matriz opcional de bytes que contiene el descriptor de formato de píxel EMF, que no es necesario que sea contigua con la porción fija del registro EmfMetafileHeaderExtension1 o con la cadena de descripción EMF. En consecuencia, el campo en este búfer etiquetado como "UndefinedSpace" es opcional y DEBE ser ignorado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

