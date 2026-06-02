---
title: "WmfSetLayout"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro META_SETLAYOUT define la orientación del diseño en el contexto del dispositivo de reproducción."
type: docs
weight: 76
url: /es/java/com.aspose.imaging.fileformats.wmf.objects/wmfsetlayout/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfSetLayout extends WmfObject
```

El registro META\_SETLAYOUT define la orientación del diseño en el contexto del dispositivo de reproducción. La orientación del diseño determina la dirección en la que se dibujan el texto y los gráficos.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [WmfSetLayout()](#WmfSetLayout--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getLayoutMode()](#getLayoutMode--) | Obtiene o establece el LayoutMode. |
| [setLayoutMode(int value)](#setLayoutMode-int-) | Obtiene o establece el LayoutMode. |
### WmfSetLayout() {#WmfSetLayout--}
```
public WmfSetLayout()
```


### getLayoutMode() {#getLayoutMode--}
```
public int getLayoutMode()
```


Obtiene o establece el LayoutMode.

Valor: El diseño del texto y los gráficos. Esto DEBE ser uno de los valores en la Enumeración de Diseño (sección 2.1.1.13).

**Returns:**
int
### setLayoutMode(int value) {#setLayoutMode-int-}
```
public void setLayoutMode(int value)
```


Obtiene o establece el LayoutMode.

Valor: El diseño del texto y los gráficos. Esto DEBE ser uno de los valores en la Enumeración de Diseño (sección 2.1.1.13).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

