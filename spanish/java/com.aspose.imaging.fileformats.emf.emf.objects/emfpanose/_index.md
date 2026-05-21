---
title: "EmfPanose"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto Panose describe los valores de clasificación de fuentes PANOSE para una fuente TrueType."
type: docs
weight: 30
url: /es/java/com.aspose.imaging.fileformats.emf.emf.objects/emfpanose/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfPanose extends EmfObject
```

El objeto Panose describe los valores de clasificación de fuentes PANOSE para una fuente TrueType. Estas características se utilizan para asociar la fuente con otras fuentes de apariencia similar pero con nombres diferentes.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPanose()](#EmfPanose--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFamilyType()](#getFamilyType--) | Obtiene o establece un entero sin signo de 8 bits que especifica el tipo de familia. |
| [setFamilyType(byte value)](#setFamilyType-byte-) | Obtiene o establece un entero sin signo de 8 bits que especifica el tipo de familia. |
| [getSerifStyle()](#getSerifStyle--) | Obtiene o establece un entero sin signo de 8 bits que especifica el estilo de serif. |
| [setSerifStyle(byte value)](#setSerifStyle-byte-) | Obtiene o establece un entero sin signo de 8 bits que especifica el estilo de serif. |
| [getWeight()](#getWeight--) | Obtiene o establece un entero sin signo de 8 bits que especifica el peso de la fuente. |
| [setWeight(byte value)](#setWeight-byte-) | Obtiene o establece un entero sin signo de 8 bits que especifica el peso de la fuente. |
| [getProportion()](#getProportion--) | Obtiene o establece un entero sin signo de 8 bits que especifica la proporción de la fuente. |
| [setProportion(byte value)](#setProportion-byte-) | Obtiene o establece un entero sin signo de 8 bits que especifica la proporción de la fuente. |
| [getContrast()](#getContrast--) | Obtiene o establece un entero sin signo de 8 bits que especifica el contraste de la fuente. |
| [setContrast(byte value)](#setContrast-byte-) | Obtiene o establece un entero sin signo de 8 bits que especifica el contraste de la fuente. |
| [getStrokeVariation()](#getStrokeVariation--) | Obtiene o establece un entero sin signo de 8 bits que especifica la variación del trazo para la fuente. |
| [setStrokeVariation(byte value)](#setStrokeVariation-byte-) | Obtiene o establece un entero sin signo de 8 bits que especifica la variación del trazo para la fuente. |
| [getArmStyle()](#getArmStyle--) | Obtiene o establece un entero sin signo de 8 bits que especifica el estilo del brazo de la fuente. |
| [setArmStyle(byte value)](#setArmStyle-byte-) | Obtiene o establece un entero sin signo de 8 bits que especifica el estilo del brazo de la fuente. |
| [getLetterform()](#getLetterform--) | Obtiene o establece un entero sin signo de 8 bits que especifica la forma de la letra de la fuente. |
| [setLetterform(byte value)](#setLetterform-byte-) | Obtiene o establece un entero sin signo de 8 bits que especifica la forma de la letra de la fuente. |
| [getMidline()](#getMidline--) | Obtiene o establece un entero sin signo de 8 bits que especifica la línea media de la fuente. |
| [setMidline(byte value)](#setMidline-byte-) | Obtiene o establece un entero sin signo de 8 bits que especifica la línea media de la fuente. |
| [getXHeight()](#getXHeight--) | Obtiene o establece un entero sin signo de 8 bits que especifica la altura x de la fuente. |
| [setXHeight(byte value)](#setXHeight-byte-) | Obtiene o establece un entero sin signo de 8 bits que especifica la altura x de la fuente. |
### EmfPanose() {#EmfPanose--}
```
public EmfPanose()
```


### getFamilyType() {#getFamilyType--}
```
public byte getFamilyType()
```


Obtiene o establece un entero sin signo de 8 bits que especifica el tipo de familia. El valor DEBE estar en la tabla de enumeración FamilyType (sección 2.1.12).

**Returns:**
byte
### setFamilyType(byte value) {#setFamilyType-byte-}
```
public void setFamilyType(byte value)
```


Obtiene o establece un entero sin signo de 8 bits que especifica el tipo de familia. El valor DEBE estar en la tabla de enumeración FamilyType (sección 2.1.12).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getSerifStyle() {#getSerifStyle--}
```
public byte getSerifStyle()
```


Obtiene o establece un entero sin signo de 8 bits que especifica el estilo de serifa. El valor DEBE estar en la tabla de enumeración SerifType (sección 2.1.30).

**Returns:**
byte
### setSerifStyle(byte value) {#setSerifStyle-byte-}
```
public void setSerifStyle(byte value)
```


Obtiene o establece un entero sin signo de 8 bits que especifica el estilo de serifa. El valor DEBE estar en la tabla de enumeración SerifType (sección 2.1.30).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getWeight() {#getWeight--}
```
public byte getWeight()
```


Obtiene o establece un entero sin signo de 8 bits que especifica el peso de la fuente. El valor DEBE estar en la tabla de enumeración Weight (sección 2.1.34).

**Returns:**
byte
### setWeight(byte value) {#setWeight-byte-}
```
public void setWeight(byte value)
```


Obtiene o establece un entero sin signo de 8 bits que especifica el peso de la fuente. El valor DEBE estar en la tabla de enumeración Weight (sección 2.1.34).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getProportion() {#getProportion--}
```
public byte getProportion()
```


Obtiene o establece un entero sin signo de 8 bits que especifica la proporción de la fuente. El valor DEBE estar en la tabla de enumeración Proportion (sección 2.1.28).

**Returns:**
byte
### setProportion(byte value) {#setProportion-byte-}
```
public void setProportion(byte value)
```


Obtiene o establece un entero sin signo de 8 bits que especifica la proporción de la fuente. El valor DEBE estar en la tabla de enumeración Proportion (sección 2.1.28).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getContrast() {#getContrast--}
```
public byte getContrast()
```


Obtiene o establece un entero sin signo de 8 bits que especifica el contraste de la fuente. El valor DEBE estar en la tabla de enumeración Contrast (sección 2.1.8).

**Returns:**
byte
### setContrast(byte value) {#setContrast-byte-}
```
public void setContrast(byte value)
```


Obtiene o establece un entero sin signo de 8 bits que especifica el contraste de la fuente. El valor DEBE estar en la tabla de enumeración Contrast (sección 2.1.8).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getStrokeVariation() {#getStrokeVariation--}
```
public byte getStrokeVariation()
```


Obtiene o establece un entero sin signo de 8 bits que especifica la variación del trazo para la fuente. El valor DEBE estar en la tabla de enumeración StrokeVariation (sección 2.1.33).

**Returns:**
byte
### setStrokeVariation(byte value) {#setStrokeVariation-byte-}
```
public void setStrokeVariation(byte value)
```


Obtiene o establece un entero sin signo de 8 bits que especifica la variación del trazo para la fuente. El valor DEBE estar en la tabla de enumeración StrokeVariation (sección 2.1.33).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getArmStyle() {#getArmStyle--}
```
public byte getArmStyle()
```


Obtiene o establece un entero sin signo de 8 bits que especifica el estilo del brazo de la fuente. El valor DEBE estar en la tabla de enumeración ArmStyle (sección 2.1.3).

**Returns:**
byte
### setArmStyle(byte value) {#setArmStyle-byte-}
```
public void setArmStyle(byte value)
```


Obtiene o establece un entero sin signo de 8 bits que especifica el estilo del brazo de la fuente. El valor DEBE estar en la tabla de enumeración ArmStyle (sección 2.1.3).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getLetterform() {#getLetterform--}
```
public byte getLetterform()
```


Obtiene o establece un entero sin signo de 8 bits que especifica la forma de la letra de la fuente. El valor DEBE estar en la tabla de enumeración Letterform (sección 2.1.20).

**Returns:**
byte
### setLetterform(byte value) {#setLetterform-byte-}
```
public void setLetterform(byte value)
```


Obtiene o establece un entero sin signo de 8 bits que especifica la forma de la letra de la fuente. El valor DEBE estar en la tabla de enumeración Letterform (sección 2.1.20).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getMidline() {#getMidline--}
```
public byte getMidline()
```


Obtiene o establece un entero sin signo de 8 bits que especifica la línea media de la fuente. El valor DEBE estar en la tabla de enumeración MidLine (sección 2.1.23).

**Returns:**
byte
### setMidline(byte value) {#setMidline-byte-}
```
public void setMidline(byte value)
```


Obtiene o establece un entero sin signo de 8 bits que especifica la línea media de la fuente. El valor DEBE estar en la tabla de enumeración MidLine (sección 2.1.23).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getXHeight() {#getXHeight--}
```
public byte getXHeight()
```


Obtiene o establece un entero sin signo de 8 bits que especifica la altura x de la fuente. El valor DEBE estar en la tabla de enumeración XHeight (sección 2.1.35).

**Returns:**
byte
### setXHeight(byte value) {#setXHeight-byte-}
```
public void setXHeight(byte value)
```


Obtiene o establece un entero sin signo de 8 bits que especifica la altura x de la fuente. El valor DEBE estar en la tabla de enumeración XHeight (sección 2.1.35).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

