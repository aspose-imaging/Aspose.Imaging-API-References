---
title: "EmfLogFontPanose"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto LogFontPanose especifica las características PANOSE de una fuente lógica."
type: docs
weight: 25
url: /es/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont)
```
public final class EmfLogFontPanose extends EmfLogFont
```

El objeto LogFontPanose especifica las características PANOSE de una fuente lógica.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfLogFontPanose(EmfLogFont emfLogFont)](#EmfLogFontPanose-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-) | Inicializa una nueva instancia de la clase `EmfLogFontPanose`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFullName()](#getFullName--) | Obtiene o establece una cadena de 64 caracteres Unicode que define el nombre completo de la fuente. |
| [setFullName(String value)](#setFullName-java.lang.String-) | Obtiene o establece una cadena de 64 caracteres Unicode que define el nombre completo de la fuente. |
| [getStyle()](#getStyle--) | Obtiene o establece una cadena de 32 caracteres Unicode que define el estilo de la fuente. |
| [setStyle(String value)](#setStyle-java.lang.String-) | Obtiene o establece una cadena de 32 caracteres Unicode que define el estilo de la fuente. |
| [getVersion()](#getVersion--) | Obtiene o establece Este campo DEBE ser ignorado. |
| [setVersion(int value)](#setVersion-int-) | Obtiene o establece Este campo DEBE ser ignorado. |
| [getStyleSize()](#getStyleSize--) | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño de punto en el que se realiza el ajuste de fuentes. |
| [setStyleSize(int value)](#setStyleSize-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño de punto en el que se realiza el ajuste de fuentes. |
| [getMatch()](#getMatch--) | Obtiene o establece Este campo DEBE ser ignorado. |
| [setMatch(int value)](#setMatch-int-) | Obtiene o establece Este campo DEBE ser ignorado. |
| [getVendorId()](#getVendorId--) | Obtiene o establece Este campo DEBE ser ignorado. |
| [setVendorId(int value)](#setVendorId-int-) | Obtiene o establece Este campo DEBE ser ignorado. |
| [getCulture()](#getCulture--) | Obtiene o establece un entero sin signo de 32 bits que DEBE establecerse a cero y DEBE ser ignorado. |
| [setCulture(int value)](#setCulture-int-) | Obtiene o establece un entero sin signo de 32 bits que DEBE establecerse a cero y DEBE ser ignorado. |
| [getPanose()](#getPanose--) | Obtiene o establece un objeto Panose (sección 2.2.21) que especifica las características PANOSE de la fuente lógica. |
| [setPanose(EmfPanose value)](#setPanose-com.aspose.imaging.fileformats.emf.emf.objects.EmfPanose-) | Obtiene o establece un objeto Panose (sección 2.2.21) que especifica las características PANOSE de la fuente lógica. |
| [getPadding()](#getPadding--) | Obtiene o establece un campo que existe solo para garantizar la alineación de 32 bits de esta estructura. |
| [setPadding(short value)](#setPadding-short-) | Obtiene o establece un campo que existe solo para garantizar la alineación de 32 bits de esta estructura. |
### EmfLogFontPanose(EmfLogFont emfLogFont) {#EmfLogFontPanose-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-}
```
public EmfLogFontPanose(EmfLogFont emfLogFont)
```


Inicializa una nueva instancia de la clase `EmfLogFontPanose`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| emfLogFont | [EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont) | La fuente de registro base. |

### getFullName() {#getFullName--}
```
public String getFullName()
```


Obtiene o establece una cadena de 64 caracteres Unicode que define el nombre completo de la fuente. Si la longitud de esta cadena es inferior a 64 caracteres, debe estar presente un NULL terminador, después del cual el resto de este campo DEBE ser ignorado.

**Returns:**
java.lang.String
### setFullName(String value) {#setFullName-java.lang.String-}
```
public void setFullName(String value)
```


Obtiene o establece una cadena de 64 caracteres Unicode que define el nombre completo de la fuente. Si la longitud de esta cadena es inferior a 64 caracteres, debe estar presente un NULL terminador, después del cual el resto de este campo DEBE ser ignorado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getStyle() {#getStyle--}
```
public String getStyle()
```


Obtiene o establece una cadena de 32 caracteres Unicode que define el estilo de la fuente. Si la longitud de esta cadena es menor que 32 caracteres, DEBE estar presente un NULL terminador, después del cual el resto de este campo DEBE ser ignorado.

**Returns:**
java.lang.String
### setStyle(String value) {#setStyle-java.lang.String-}
```
public void setStyle(String value)
```


Obtiene o establece una cadena de 32 caracteres Unicode que define el estilo de la fuente. Si la longitud de esta cadena es menor que 32 caracteres, DEBE estar presente un NULL terminador, después del cual el resto de este campo DEBE ser ignorado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Obtiene o establece Este campo DEBE ser ignorado.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Obtiene o establece Este campo DEBE ser ignorado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getStyleSize() {#getStyleSize--}
```
public int getStyleSize()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño de punto en el que se realiza el ajuste de fuentes. Si se establece a cero, el ajuste de fuentes se realiza en el tamaño de punto correspondiente al campo Height del objeto LogFont en el campo LogFont.

**Returns:**
int
### setStyleSize(int value) {#setStyleSize-int-}
```
public void setStyleSize(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño de punto en el que se realiza el ajuste de fuentes. Si se establece a cero, el ajuste de fuentes se realiza en el tamaño de punto correspondiente al campo Height del objeto LogFont en el campo LogFont.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getMatch() {#getMatch--}
```
public int getMatch()
```


Obtiene o establece Este campo DEBE ser ignorado.

**Returns:**
int
### setMatch(int value) {#setMatch-int-}
```
public void setMatch(int value)
```


Obtiene o establece Este campo DEBE ser ignorado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getVendorId() {#getVendorId--}
```
public int getVendorId()
```


Obtiene o establece Este campo DEBE ser ignorado.

**Returns:**
int
### setVendorId(int value) {#setVendorId-int-}
```
public void setVendorId(int value)
```


Obtiene o establece Este campo DEBE ser ignorado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getCulture() {#getCulture--}
```
public int getCulture()
```


Obtiene o establece un entero sin signo de 32 bits que DEBE establecerse a cero y DEBE ser ignorado.

**Returns:**
int
### setCulture(int value) {#setCulture-int-}
```
public void setCulture(int value)
```


Obtiene o establece un entero sin signo de 32 bits que DEBE establecerse a cero y DEBE ser ignorado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getPanose() {#getPanose--}
```
public EmfPanose getPanose()
```


Obtiene o establece un objeto Panose (sección 2.2.21) que especifica las características PANOSE de la fuente lógica. Si todos los campos de este objeto son cero, DEBE ser ignorado.

**Returns:**
[EmfPanose](../../com.aspose.imaging.fileformats.emf.emf.objects/emfpanose)
### setPanose(EmfPanose value) {#setPanose-com.aspose.imaging.fileformats.emf.emf.objects.EmfPanose-}
```
public void setPanose(EmfPanose value)
```


Obtiene o establece un objeto Panose (sección 2.2.21) que especifica las características PANOSE de la fuente lógica. Si todos los campos de este objeto son cero, DEBE ser ignorado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfPanose](../../com.aspose.imaging.fileformats.emf.emf.objects/emfpanose) |  |

### getPadding() {#getPadding--}
```
public short getPadding()
```


Obtiene o establece un campo que existe solo para garantizar la alineación de 32 bits de esta estructura. DEBE ser ignorado

**Returns:**
short
### setPadding(short value) {#setPadding-short-}
```
public void setPadding(short value)
```


Obtiene o establece un campo que existe solo para garantizar la alineación de 32 bits de esta estructura. DEBE ser ignorado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

