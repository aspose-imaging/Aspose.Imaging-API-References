---
title: "EmfPlusFont"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto EmfPlusFont specifica le proprietà che determinano l'aspetto del testo, inclusi la dimensione e lo stile del carattere."
type: docs
weight: 42
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfont/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusFont extends EmfPlusGraphicsObjectType
```

L'oggetto EmfPlusFont specifica le proprietà che determinano l'aspetto del testo, inclusi il tipo di carattere, la dimensione e lo stile.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusFont()](#EmfPlusFont--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Ottiene o imposta una stringa di caratteri Unicode di lunghezza Length che contiene il nome della famiglia di caratteri |
| [setFamilyName(String value)](#setFamilyName-java.lang.String-) | Ottiene o imposta una stringa di caratteri Unicode di lunghezza Length che contiene il nome della famiglia di caratteri |
| [getFontStyleFlags()](#getFontStyleFlags--) | Ottiene o imposta un intero con segno a 32 bit che specifica gli attributi dei glifi dei caratteri che influenzano l'aspetto del font, come grassetto e corsivo. |
| [setFontStyleFlags(int value)](#setFontStyleFlags-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica gli attributi dei glifi dei caratteri che influenzano l'aspetto del font, come grassetto e corsivo. |
| [getSizeUnit()](#getSizeUnit--) | Ottiene o imposta un intero senza segno a 32 bit che specifica le unità utilizzate per il campo EmSize. |
| [setSizeUnit(int value)](#setSizeUnit-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica le unità utilizzate per il campo EmSize. |
| [getEmSize()](#getEmSize--) | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica la dimensione em del font nelle unità specificate dal campo SizeUnit. |
| [setEmSize(float value)](#setEmSize-float-) | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica la dimensione em del font nelle unità specificate dal campo SizeUnit. |
### EmfPlusFont() {#EmfPlusFont--}
```
public EmfPlusFont()
```


### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Ottiene o imposta una stringa di caratteri Unicode di lunghezza Length che contiene il nome della famiglia di caratteri

**Returns:**
java.lang.String
### setFamilyName(String value) {#setFamilyName-java.lang.String-}
```
public void setFamilyName(String value)
```


Ottiene o imposta una stringa di caratteri Unicode di lunghezza Length che contiene il nome della famiglia di caratteri

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getFontStyleFlags() {#getFontStyleFlags--}
```
public int getFontStyleFlags()
```


Ottiene o imposta un intero con segno a 32 bit che specifica gli attributi dei glifi dei caratteri che influenzano l'aspetto del font, come grassetto e corsivo. Questo valore DEVE essere composto da flag FontStyle (sezione 2.1.2.4).

**Returns:**
int
### setFontStyleFlags(int value) {#setFontStyleFlags-int-}
```
public void setFontStyleFlags(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica gli attributi dei glifi dei caratteri che influenzano l'aspetto del font, come grassetto e corsivo. Questo valore DEVE essere composto da flag FontStyle (sezione 2.1.2.4).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getSizeUnit() {#getSizeUnit--}
```
public int getSizeUnit()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica le unità utilizzate per il campo EmSize. Queste sono tipicamente le unità impiegate durante la progettazione del carattere. Il valore DEVE appartenere all'enumerazione UnitType (sezione 2.1.1.33).

**Returns:**
int
### setSizeUnit(int value) {#setSizeUnit-int-}
```
public void setSizeUnit(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica le unità utilizzate per il campo EmSize. Queste sono tipicamente le unità impiegate durante la progettazione del carattere. Il valore DEVE appartenere all'enumerazione UnitType (sezione 2.1.1.33).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getEmSize() {#getEmSize--}
```
public float getEmSize()
```


Ottiene o imposta un valore a virgola mobile a 32 bit che specifica la dimensione em del font nelle unità specificate dal campo SizeUnit.

**Returns:**
float
### setEmSize(float value) {#setEmSize-float-}
```
public void setEmSize(float value)
```


Ottiene o imposta un valore a virgola mobile a 32 bit che specifica la dimensione em del font nelle unità specificate dal campo SizeUnit.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

