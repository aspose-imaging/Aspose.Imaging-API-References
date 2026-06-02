---
title: "WmfSetTextCharExtra"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro META_SETTEXTCHAREXTRA define el espaciado entre caracteres para la justificación de texto en el contexto del dispositivo de reproducción."
type: docs
weight: 86
url: /es/java/com.aspose.imaging.fileformats.wmf.objects/wmfsettextcharextra/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfSetTextCharExtra extends WmfObject
```

El registro META\_SETTEXTCHAREXTRA define el espaciado entre caracteres para la justificación de texto en el contexto del dispositivo de reproducción. El espaciado se añade al espacio en blanco entre cada carácter, incluidos los caracteres `` , cuando se genera una línea de texto justificado.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [WmfSetTextCharExtra()](#WmfSetTextCharExtra--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getCharExtra()](#getCharExtra--) | Obtiene o establece el extra de carácter. |
| [setCharExtra(int value)](#setCharExtra-int-) | Obtiene o establece el extra de carácter. |
### WmfSetTextCharExtra() {#WmfSetTextCharExtra--}
```
public WmfSetTextCharExtra()
```


### getCharExtra() {#getCharExtra--}
```
public int getCharExtra()
```


Obtiene o establece el extra de carácter.

Valor: La cantidad de espacio adicional, en unidades lógicas, que se añadirá a cada carácter. Si el modo de mapeo actual no es MM\_TEXT, este valor se transforma y redondea al píxel más cercano. Para obtener detalles sobre la configuración del modo de mapeo, consulte META\_SETMAPMODE (sección 2.3.5.17).

**Returns:**
int
### setCharExtra(int value) {#setCharExtra-int-}
```
public void setCharExtra(int value)
```


Obtiene o establece el extra de carácter.

Valor: La cantidad de espacio adicional, en unidades lógicas, que se añadirá a cada carácter. Si el modo de mapeo actual no es MM\_TEXT, este valor se transforma y redondea al píxel más cercano. Para obtener detalles sobre la configuración del modo de mapeo, consulte META\_SETMAPMODE (sección 2.3.5.17).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

