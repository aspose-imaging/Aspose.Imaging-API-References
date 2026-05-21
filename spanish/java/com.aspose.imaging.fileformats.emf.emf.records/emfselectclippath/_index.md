---
title: "EmfSelectClipPath"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_SELECTCLIPPATH especifica la ruta actual como una región de recorte para un contexto de dispositivo de reproducción, combinando la nueva región con cualquier región de recorte existente mediante el modo especificado."
type: docs
weight: 115
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfselectclippath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfSelectClipPath extends EmfClippingRecordType
```

El registro EMR\_SELECTCLIPPATH especifica la ruta actual como una región de recorte para un contexto de dispositivo de reproducción, combinando la nueva región con cualquier región de recorte existente usando el modo especificado.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfSelectClipPath(EmfRecord source)](#EmfSelectClipPath-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfSelectClipPath`. |
| [EmfSelectClipPath()](#EmfSelectClipPath--) | Inicializa una nueva instancia de la clase `EmfSelectClipPath`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getRegionMode()](#getRegionMode--) | Obtiene o establece un entero sin signo de 32 bits que especifica la forma de usar la ruta. |
| [setRegionMode(int value)](#setRegionMode-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica la forma de usar la ruta. |
### EmfSelectClipPath(EmfRecord source) {#EmfSelectClipPath-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSelectClipPath(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfSelectClipPath`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### EmfSelectClipPath() {#EmfSelectClipPath--}
```
public EmfSelectClipPath()
```


Inicializa una nueva instancia de la clase `EmfSelectClipPath`.

### getRegionMode() {#getRegionMode--}
```
public int getRegionMode()
```


Obtiene o establece un entero sin signo de 32 bits que especifica la forma de usar la ruta. El valor DEBE estar en la enumeración RegionMode (sección 2.1.29).

**Returns:**
int
### setRegionMode(int value) {#setRegionMode-int-}
```
public void setRegionMode(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica la forma de usar la ruta. El valor DEBE estar en la enumeración RegionMode (sección 2.1.29).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

