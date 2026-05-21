---
title: "Timecode"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Représente la valeur du timecode dans la vidéo."
type: docs
weight: 16
url: /fr/java/com.aspose.imaging.xmp.schemas.xmpdm/timecode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public final class Timecode extends XmpTypeBase implements System.IEquatable<Timecode>
```

Représente la valeur du timecode dans la vidéo.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Timecode(TimeFormat format, String timeValue)](#Timecode-com.aspose.imaging.xmp.schemas.xmpdm.TimeFormat-java.lang.String-) | Initialise une nouvelle instance de la classe `Timecode`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFormat()](#getFormat--) | Obtient ou définit le format utilisé dans le `TimeValue`. |
| [setFormat(TimeFormat value)](#setFormat-com.aspose.imaging.xmp.schemas.xmpdm.TimeFormat-) | Obtient ou définit le format utilisé dans le `TimeValue`. |
| [getTimeValue()](#getTimeValue--) | Obtient ou définit la valeur temporelle dans le format spécifié. |
| [setTimeValue(String value)](#setTimeValue-java.lang.String-) | Obtient ou définit la valeur temporelle dans le format spécifié. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Renvoie la valeur de chaîne contenue au format XMP. |
| [isEquals(Timecode other)](#isEquals-com.aspose.imaging.xmp.schemas.xmpdm.Timecode-) | Indique si l'objet actuel est égal à un autre objet du même type. |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si le `System.Object` spécifié est égal à cette instance. |
| [hashCode()](#hashCode--) | Renvoie un code de hachage pour cette instance. |
### Timecode(TimeFormat format, String timeValue) {#Timecode-com.aspose.imaging.xmp.schemas.xmpdm.TimeFormat-java.lang.String-}
```
public Timecode(TimeFormat format, String timeValue)
```


Initialise une nouvelle instance de la classe `Timecode`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| format | [TimeFormat](../../com.aspose.imaging.xmp.schemas.xmpdm/timeformat) | Le format temporel. |
| timeValue | java.lang.String | La valeur temporelle. |

### getFormat() {#getFormat--}
```
public TimeFormat getFormat()
```


Obtient ou définit le format utilisé dans le `TimeValue`.

Valeur : Le format utilisé dans le `TimeValue`.

**Returns:**
[TimeFormat](../../com.aspose.imaging.xmp.schemas.xmpdm/timeformat)
### setFormat(TimeFormat value) {#setFormat-com.aspose.imaging.xmp.schemas.xmpdm.TimeFormat-}
```
public void setFormat(TimeFormat value)
```


Obtient ou définit le format utilisé dans le `TimeValue`.

Valeur : Le format utilisé dans le `TimeValue`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TimeFormat](../../com.aspose.imaging.xmp.schemas.xmpdm/timeformat) |  |

### getTimeValue() {#getTimeValue--}
```
public String getTimeValue()
```


Obtient ou définit la valeur temporelle dans le format spécifié.

Valeur : La valeur temporelle dans le format spécifié.

**Returns:**
java.lang.String
### setTimeValue(String value) {#setTimeValue-java.lang.String-}
```
public void setTimeValue(String value)
```


Obtient ou définit la valeur temporelle dans le format spécifié.

Valeur : La valeur temporelle dans le format spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Renvoie la valeur de chaîne contenue au format XMP.

**Returns:**
java.lang.String - Renvoie la chaîne contenant la représentation xmp.
### isEquals(Timecode other) {#isEquals-com.aspose.imaging.xmp.schemas.xmpdm.Timecode-}
```
public boolean isEquals(Timecode other)
```


Indique si l'objet actuel est égal à un autre objet du même type.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| other | [Timecode](../../com.aspose.imaging.xmp.schemas.xmpdm/timecode) | Un objet à comparer avec cet objet. |

**Returns:**
boolean - vrai si l'objet actuel est égal au paramètre `other` ; sinon, faux.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si le `System.Object` spécifié est égal à cette instance.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Le `System.Object` à comparer avec cette instance. |

**Returns:**
boolean - `true` si le `System.Object` spécifié est égal à cette instance; sinon, `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie un code de hachage pour cette instance.

**Returns:**
int - Un code de hachage pour cette instance, adapté à une utilisation dans les algorithmes de hachage et les structures de données comme une table de hachage.
