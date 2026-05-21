---
title: "EmfPlusStringFormatData"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto EmfPlusStringFormatData especifica tabulaciones y posiciones de caracteres para una cadena gráfica."
type: docs
weight: 75
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusStringFormatData extends EmfPlusStructureObjectType
```

El objeto EmfPlusStringFormatData especifica tabulaciones y posiciones de caracteres para una cadena gráfica.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusStringFormatData()](#EmfPlusStringFormatData--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getTabStops()](#getTabStops--) | Obtiene o establece una matriz opcional de valores de punto flotante que especifican las ubicaciones opcionales de tabulaciones para este objeto. |
| [setTabStops(float[] value)](#setTabStops-float---) | Obtiene o establece una matriz opcional de valores de punto flotante que especifican las ubicaciones opcionales de tabulaciones para este objeto. |
| [getCharRange()](#getCharRange--) | Obtiene o establece una matriz opcional de objetos RangeCount EmfPlusCharacterRange que especifican el rango de posiciones de caracteres dentro de una cadena de texto. |
| [setCharRange(EmfPlusCharacterRange[] value)](#setCharRange-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCharacterRange---) | Obtiene o establece una matriz opcional de objetos RangeCount EmfPlusCharacterRange que especifican el rango de posiciones de caracteres dentro de una cadena de texto. |
### EmfPlusStringFormatData() {#EmfPlusStringFormatData--}
```
public EmfPlusStringFormatData()
```


### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


Obtiene o establece una matriz opcional de valores de punto flotante que especifican las ubicaciones opcionales de tabulaciones para este objeto. Cada valor de tabulación representa el número de espacios entre tabulaciones o, para la primera tabulación, el número de espacios entre el comienzo de una línea de texto y la primera tabulación. Este campo DEBE estar presente si el valor del campo TabStopCount en el objeto EmfPlusStringFormat es mayor que 0.

**Returns:**
float[]
### setTabStops(float[] value) {#setTabStops-float---}
```
public void setTabStops(float[] value)
```


Obtiene o establece una matriz opcional de valores de punto flotante que especifican las ubicaciones opcionales de tabulaciones para este objeto. Cada valor de tabulación representa el número de espacios entre tabulaciones o, para la primera tabulación, el número de espacios entre el comienzo de una línea de texto y la primera tabulación. Este campo DEBE estar presente si el valor del campo TabStopCount en el objeto EmfPlusStringFormat es mayor que 0.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float[] |  |

### getCharRange() {#getCharRange--}
```
public EmfPlusCharacterRange[] getCharRange()
```


Obtiene o establece una matriz opcional de objetos RangeCount EmfPlusCharacterRange que especifican el rango de posiciones de caracteres dentro de una cadena de texto. La región delimitada se define por el área de la pantalla ocupada por un grupo de caracteres especificado por el rango de caracteres. Este campo DEBE estar presente si el valor del campo RangeCount en el objeto EmfPlusStringFormat es mayor que 0.

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCharacterRange[]
### setCharRange(EmfPlusCharacterRange[] value) {#setCharRange-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCharacterRange---}
```
public void setCharRange(EmfPlusCharacterRange[] value)
```


Obtiene o establece una matriz opcional de objetos RangeCount EmfPlusCharacterRange que especifican el rango de posiciones de caracteres dentro de una cadena de texto. La región delimitada se define por el área de la pantalla ocupada por un grupo de caracteres especificado por el rango de caracteres. Este campo DEBE estar presente si el valor del campo RangeCount en el objeto EmfPlusStringFormat es mayor que 0.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfPlusCharacterRange\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscharacterrange) |  |

