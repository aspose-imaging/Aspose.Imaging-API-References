---
title: "EmfBlendFunction"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Une structure qui spécifie les opérations de fusion pour les bitmaps source et destination."
type: docs
weight: 18
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class EmfBlendFunction extends Struct<EmfBlendFunction>
```

Une structure qui spécifie les opérations de fusion pour les bitmaps source et destination.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfBlendFunction()](#EmfBlendFunction--) |  |
| [EmfBlendFunction(int dwordData)](#EmfBlendFunction-int-) | Initialise une nouvelle instance de la classe `EmfBlendFunction`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBlendOperation()](#getBlendOperation--) | Obtient le code d'opération de mélange. |
| [getBlendFlags()](#getBlendFlags--) | Obtient les indicateurs de mélange. |
| [getSrcConstantAlpha()](#getSrcConstantAlpha--) | Obtient un entier non signé de 8 bits qui spécifie la transparence alpha, laquelle détermine le mélange des images source et destination. |
| [getAlphaFormat()](#getAlphaFormat--) | Obtient une structure qui spécifie comment les pixels source et destination sont interprétés par rapport à la transparence alpha. |
| [toInt()](#toInt--) | Convertit la représentation sous forme de chaîne d'un nombre en entier. |
| [CloneTo(EmfBlendFunction that)](#CloneTo-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-) |  |
| [Clone()](#Clone--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
| [isEquals(EmfBlendFunction obj1, EmfBlendFunction obj2)](#isEquals-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-) |  |
### EmfBlendFunction() {#EmfBlendFunction--}
```
public EmfBlendFunction()
```


### EmfBlendFunction(int dwordData) {#EmfBlendFunction-int-}
```
public EmfBlendFunction(int dwordData)
```


Initialise une nouvelle instance de la classe `EmfBlendFunction`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dwordData | int | Les données dword. |

### getBlendOperation() {#getBlendOperation--}
```
public byte getBlendOperation()
```


Obtient le code d'opération de mélange. La seule opération de mélange source et destination qui a été définie est 0x00, qui spécifie que l'image source DOIT être combinée avec l'image destination en fonction des valeurs de transparence alpha des pixels source. Voir les équations suivantes pour plus de détails.

**Returns:**
byte
### getBlendFlags() {#getBlendFlags--}
```
public byte getBlendFlags()
```


Obtient les indicateurs de mélange. Cette valeur DOIT être 0x00 et DOIT être ignorée.

**Returns:**
byte
### getSrcConstantAlpha() {#getSrcConstantAlpha--}
```
public byte getSrcConstantAlpha()
```


Obtient un entier non signé de 8 bits qui spécifie la transparence alpha, laquelle détermine le mélange des images source et destination. Cette valeur DOIT être utilisée sur l'ensemble de l'image source. La valeur minimale de transparence alpha, zéro, correspond à totalement transparent ; la valeur maximale, 0xFF, correspond à totalement opaque. En pratique, une valeur de 0xFF indique que les valeurs alpha par pixel déterminent le mélange des images source et destination. Voir les équations plus loin dans cette section pour plus de détails.

**Returns:**
byte
### getAlphaFormat() {#getAlphaFormat--}
```
public byte getAlphaFormat()
```


Obtient une structure qui spécifie comment les pixels source et destination sont interprétés par rapport à la transparence alpha.

**Returns:**
byte
### toInt() {#toInt--}
```
public int toInt()
```


Convertit la représentation sous forme de chaîne d'un nombre en entier.

**Returns:**
int - La valeur DWORD de la structure.
### CloneTo(EmfBlendFunction that) {#CloneTo-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-}
```
public void CloneTo(EmfBlendFunction that)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| that | [EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction) |  |

### Clone() {#Clone--}
```
public EmfBlendFunction Clone()
```




**Returns:**
[EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### isEquals(EmfBlendFunction obj1, EmfBlendFunction obj2) {#isEquals-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-}
```
public static boolean isEquals(EmfBlendFunction obj1, EmfBlendFunction obj2)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj1 | [EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction) |  |
| obj2 | [EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction) |  |

**Returns:**
boolean
