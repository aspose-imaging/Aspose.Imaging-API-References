---
title: "EmfPlusMetafile"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto EmfPlusMetafileData especifica un metafichero que contiene una imagen gráfica."
type: docs
weight: 55
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusmetafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseImageData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbaseimagedata)
```
public final class EmfPlusMetafile extends EmfPlusBaseImageData
```

El objeto EmfPlusMetafileData especifica un metafichero que contiene una imagen gráfica.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusMetafile()](#EmfPlusMetafile--) | Inicializa una nueva instancia de la clase `EmfPlusMetafile`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getType()](#getType--) | Obtiene o establece un entero sin signo de 32 bits que especifica el tipo de metafile que está incrustado en el campo MetafileData. |
| [setType(int value)](#setType-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el tipo de metafile que está incrustado en el campo MetafileData. |
| [getMetafileDataSize()](#getMetafileDataSize--) | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño en bytes de los datos del metafile en el campo MetafileData. |
| [setMetafileDataSize(int value)](#setMetafileDataSize-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño en bytes de los datos del metafile en el campo MetafileData. |
| [getMetafileData()](#getMetafileData--) | Obtiene o establece datos de longitud variable que especifican el metafile incrustado. |
| [setMetafileData(byte[] value)](#setMetafileData-byte---) | Obtiene o establece datos de longitud variable que especifican el metafile incrustado. |
### EmfPlusMetafile() {#EmfPlusMetafile--}
```
public EmfPlusMetafile()
```


Inicializa una nueva instancia de la clase `EmfPlusMetafile`.

### getType() {#getType--}
```
public int getType()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el tipo de metafile que está incrustado en el campo MetafileData. Este valor DEBE estar definido en la enumeración MetafileDataType (sección 2.1.1.21).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el tipo de metafile que está incrustado en el campo MetafileData. Este valor DEBE estar definido en la enumeración MetafileDataType (sección 2.1.1.21).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getMetafileDataSize() {#getMetafileDataSize--}
```
public int getMetafileDataSize()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño en bytes de los datos del metafile en el campo MetafileData.

**Returns:**
int
### setMetafileDataSize(int value) {#setMetafileDataSize-int-}
```
public void setMetafileDataSize(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño en bytes de los datos del metafile en el campo MetafileData.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getMetafileData() {#getMetafileData--}
```
public byte[] getMetafileData()
```


Obtiene o establece datos de longitud variable que especifican el metafile incrustado. El contenido y formato de los datos pueden ser diferentes para cada tipo de metafile.

Las imágenes gráficas se especifican mediante objetos EmfPlusImage (sección 2.2.1.4). Un objeto EmfPlusMetafile DEBE estar presente en el campo ImageData de un objeto EmfPlusImage si ImageTypeMetafile está especificado en su campo Type. Este objeto es genérico y se utiliza para diferentes tipos de datos, incluyendo: un metafile WMF [MS-WMF]; metafile WMF que puede ser colocado; un metafile EMF [MS-EMF]; un metafile EMF+ que especifica operaciones gráficas solo con registros EMF+; y un metafile EMF+ que especifica operaciones gráficas con registros EMF+ y EMF. Consulte la sección 2.2.2 para la especificación de objetos estructurales adicionales.

**Returns:**
byte[]
### setMetafileData(byte[] value) {#setMetafileData-byte---}
```
public void setMetafileData(byte[] value)
```


Obtiene o establece datos de longitud variable que especifican el metafile incrustado. El contenido y formato de los datos pueden ser diferentes para cada tipo de metafile.

Las imágenes gráficas se especifican mediante objetos EmfPlusImage (sección 2.2.1.4). Un objeto EmfPlusMetafile DEBE estar presente en el campo ImageData de un objeto EmfPlusImage si ImageTypeMetafile está especificado en su campo Type. Este objeto es genérico y se utiliza para diferentes tipos de datos, incluyendo: un metafile WMF [MS-WMF]; metafile WMF que puede ser colocado; un metafile EMF [MS-EMF]; un metafile EMF+ que especifica operaciones gráficas solo con registros EMF+; y un metafile EMF+ que especifica operaciones gráficas con registros EMF+ y EMF. Consulte la sección 2.2.2 para la especificación de objetos estructurales adicionales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

