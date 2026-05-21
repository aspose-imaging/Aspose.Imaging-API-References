---
title: "WmfSetMapperFlags"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro META_SETMAPPERFLAGS define el algoritmo que el asignador de fuentes utiliza al mapear fuentes lógicas a fuentes físicas."
type: docs
weight: 78
url: /es/java/com.aspose.imaging.fileformats.wmf.objects/wmfsetmapperflags/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfSetMapperFlags extends WmfObject
```

El registro META\_SETMAPPERFLAGS define el algoritmo que el asignador de fuentes utiliza al mapear fuentes lógicas a fuentes físicas.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [WmfSetMapperFlags()](#WmfSetMapperFlags--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getMapperValues()](#getMapperValues--) | Obtiene o establece los valores del asignador. |
| [setMapperValues(int value)](#setMapperValues-int-) | Obtiene o establece los valores del asignador. |
### WmfSetMapperFlags() {#WmfSetMapperFlags--}
```
public WmfSetMapperFlags()
```


### getMapperValues() {#getMapperValues--}
```
public int getMapperValues()
```


Obtiene o establece los valores del asignador.

Valor: El asignador de fuentes intenta coincidir la relación de aspecto de una fuente con la relación de aspecto del dispositivo actual. Si el bit cero está activado, el asignador selecciona solo fuentes coincidentes.

**Returns:**
int
### setMapperValues(int value) {#setMapperValues-int-}
```
public void setMapperValues(int value)
```


Obtiene o establece los valores del asignador.

Valor: El asignador de fuentes intenta coincidir la relación de aspecto de una fuente con la relación de aspecto del dispositivo actual. Si el bit cero está activado, el asignador selecciona solo fuentes coincidentes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

