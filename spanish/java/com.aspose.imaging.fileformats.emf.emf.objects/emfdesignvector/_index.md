---
title: "EmfDesignVector"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto DesignVector de la sección 2.2.3 define el vector de diseño que especifica valores para los ejes de fuente de una fuente de varios maestros."
type: docs
weight: 13
url: /es/java/com.aspose.imaging.fileformats.emf.emf.objects/emfdesignvector/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfDesignVector extends EmfObject
```

El objeto DesignVector (sección 2.2.3) define el vector de diseño, que especifica valores para los ejes de fuente de una fuente maestra múltiple.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfDesignVector()](#EmfDesignVector--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getSignature()](#getSignature--) | Obtiene o establece un entero sin signo de 32 bits que DEBE establecerse al valor 0x08007664. |
| [setSignature(int value)](#setSignature-int-) | Obtiene o establece un entero sin signo de 32 bits que DEBE establecerse al valor 0x08007664. |
| [getNumAxes()](#getNumAxes--) | Obtiene o establece un entero sin signo de 32 bits que especifica el número de elementos en la matriz Values. |
| [setNumAxes(int value)](#setNumAxes-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el número de elementos en la matriz Values. |
| [getValues()](#getValues--) | Obtiene o establece una matriz opcional de enteros con signo de 32 bits que especifica los valores de los ejes de fuente de una fuente OpenType de varios maestros. |
| [setValues(int[] value)](#setValues-int---) | Obtiene o establece una matriz opcional de enteros con signo de 32 bits que especifica los valores de los ejes de fuente de una fuente OpenType de varios maestros. |
### EmfDesignVector() {#EmfDesignVector--}
```
public EmfDesignVector()
```


### getSignature() {#getSignature--}
```
public int getSignature()
```


Obtiene o establece un entero sin signo de 32 bits que DEBE establecerse al valor 0x08007664.

**Returns:**
int
### setSignature(int value) {#setSignature-int-}
```
public void setSignature(int value)
```


Obtiene o establece un entero sin signo de 32 bits que DEBE establecerse al valor 0x08007664.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getNumAxes() {#getNumAxes--}
```
public int getNumAxes()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el número de elementos en la matriz Values. DEBE estar en el rango de 0 a 16, inclusive.

**Returns:**
int
### setNumAxes(int value) {#setNumAxes-int-}
```
public void setNumAxes(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el número de elementos en la matriz Values. DEBE estar en el rango de 0 a 16, inclusive.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getValues() {#getValues--}
```
public int[] getValues()
```


Obtiene o establece una matriz opcional de enteros con signo de 32 bits que especifica los valores de los ejes de fuente de una fuente OpenType de varios maestros. El número máximo de valores en la matriz es 16.

**Returns:**
int[]
### setValues(int[] value) {#setValues-int---}
```
public void setValues(int[] value)
```


Obtiene o establece una matriz opcional de enteros con signo de 32 bits que especifica los valores de los ejes de fuente de una fuente OpenType de varios maestros. El número máximo de valores en la matriz es 16.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] |  |

