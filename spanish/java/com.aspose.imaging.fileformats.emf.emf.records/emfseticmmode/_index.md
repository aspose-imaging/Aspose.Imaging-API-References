---
title: "EmfSetIcmMode"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_SETICMMODE especifica el modo de Gestión de Color de Imagen ICM para operaciones gráficas."
type: docs
weight: 125
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfseticmmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetIcmMode extends EmfStateRecordType
```

El registro EMR\_SETICMMODE especifica el modo de Gestión de Color de Imagen (ICM) para operaciones gráficas.

Cuando el modo ICM está habilitado, los colores especificados en los registros EMF DEBERÍAN coincidir en color, mientras que el perfil de color predeterminado en el contexto del dispositivo de reproducción DEBERÍA usarse cuando se realiza una transferencia de bloques de bits. Si no se desea el perfil de color predeterminado, el modo ICM DEBERÍA desactivarse antes de realizar la transferencia de bloques de bits.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfSetIcmMode(EmfRecord source)](#EmfSetIcmMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfSetIcmMode`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getIcmMode()](#getIcmMode--) | Obtiene o establece un entero sin signo de 32 bits que especifica si habilitar o deshabilitar ICM, a partir de la enumeración ICMMode (sección 2.1.18). |
| [setIcmMode(int value)](#setIcmMode-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica si habilitar o deshabilitar ICM, a partir de la enumeración ICMMode (sección 2.1.18). |
### EmfSetIcmMode(EmfRecord source) {#EmfSetIcmMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetIcmMode(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfSetIcmMode`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### getIcmMode() {#getIcmMode--}
```
public int getIcmMode()
```


Obtiene o establece un entero sin signo de 32 bits que especifica si habilitar o deshabilitar ICM, a partir de la enumeración ICMMode (sección 2.1.18). Este valor forma parte del estado del contexto del dispositivo de reproducción.

**Returns:**
int
### setIcmMode(int value) {#setIcmMode-int-}
```
public void setIcmMode(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica si habilitar o deshabilitar ICM, a partir de la enumeración ICMMode (sección 2.1.18). Este valor forma parte del estado del contexto del dispositivo de reproducción.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

