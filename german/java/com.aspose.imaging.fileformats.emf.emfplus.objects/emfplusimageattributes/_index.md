---
title: "EmfPlusImageAttributes"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das EmfPlusImageAttributes-Objekt gibt an, wie Bitmap-Bildfarben während des Renderns manipuliert werden."
type: docs
weight: 48
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageattributes/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusImageAttributes extends EmfPlusGraphicsObjectType
```

Das EmfPlusImageAttributes-Objekt gibt an, wie Bitmap-Bildfarben während des Renderns manipuliert werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusImageAttributes()](#EmfPlusImageAttributes--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getWrapMode()](#getWrapMode--) | Liest oder setzt eine 32‑Bit‑unsigned‑Integer, die angibt, wie Randbedingungen mit einem Wert aus der WrapMode‑Aufzählung (Abschnitt 2.1.1.34) zu handhaben sind. |
| [setWrapMode(int value)](#setWrapMode-int-) | Liest oder setzt eine 32‑Bit‑unsigned‑Integer, die angibt, wie Randbedingungen mit einem Wert aus der WrapMode‑Aufzählung (Abschnitt 2.1.1.34) zu handhaben sind. |
| [getClampArgb32Color()](#getClampArgb32Color--) | Liest oder setzt das EmfPlusARGB‑Objekt (Abschnitt 2.2.2.1), das die Randfarbe angibt, die verwendet werden soll, wenn der WrapMode‑Wert WrapModeClamp ist. |
| [setClampArgb32Color(int value)](#setClampArgb32Color-int-) | Liest oder setzt das EmfPlusARGB‑Objekt (Abschnitt 2.2.2.1), das die Randfarbe angibt, die verwendet werden soll, wenn der WrapMode‑Wert WrapModeClamp ist. |
| [getObjectClamp()](#getObjectClamp--) | Liest oder setzt eine 32‑Bit‑signed‑Integer, die das Verhalten der Objektklammerung angibt. |
| [setObjectClamp(int value)](#setObjectClamp-int-) | Liest oder setzt eine 32‑Bit‑signed‑Integer, die das Verhalten der Objektklammerung angibt. |
### EmfPlusImageAttributes() {#EmfPlusImageAttributes--}
```
public EmfPlusImageAttributes()
```


### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Liest oder setzt eine 32‑Bit‑unsigned‑Integer, die angibt, wie Randbedingungen mit einem Wert aus der WrapMode‑Aufzählung (Abschnitt 2.1.1.34) zu handhaben sind.

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Liest oder setzt eine 32‑Bit‑unsigned‑Integer, die angibt, wie Randbedingungen mit einem Wert aus der WrapMode‑Aufzählung (Abschnitt 2.1.1.34) zu handhaben sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getClampArgb32Color() {#getClampArgb32Color--}
```
public int getClampArgb32Color()
```


Liest oder setzt das EmfPlusARGB‑Objekt (Abschnitt 2.2.2.1), das die Randfarbe angibt, die verwendet werden soll, wenn der WrapMode‑Wert WrapModeClamp ist. Diese Farbe ist sichtbar, wenn das von einem EmfPlusDrawImage (Abschnitt 2.3.4.8) verarbeitete Quellrechteck größer ist als das Bild selbst.

**Returns:**
int
### setClampArgb32Color(int value) {#setClampArgb32Color-int-}
```
public void setClampArgb32Color(int value)
```


Liest oder setzt das EmfPlusARGB‑Objekt (Abschnitt 2.2.2.1), das die Randfarbe angibt, die verwendet werden soll, wenn der WrapMode‑Wert WrapModeClamp ist. Diese Farbe ist sichtbar, wenn das von einem EmfPlusDrawImage (Abschnitt 2.3.4.8) verarbeitete Quellrechteck größer ist als das Bild selbst.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getObjectClamp() {#getObjectClamp--}
```
public int getObjectClamp()
```


Liest oder setzt eine 32‑Bit‑signed‑Integer, die das Verhalten der Objektklammerung angibt. Sie wird erst verwendet, wenn dieses Objekt auf ein zu zeichnendes Bild angewendet wird. Dieser Wert MUSS einer der in der folgenden Tabelle definierten Werte sein.

**Returns:**
int
### setObjectClamp(int value) {#setObjectClamp-int-}
```
public void setObjectClamp(int value)
```


Liest oder setzt eine 32‑Bit‑signed‑Integer, die das Verhalten der Objektklammerung angibt. Sie wird erst verwendet, wenn dieses Objekt auf ein zu zeichnendes Bild angewendet wird. Dieser Wert MUSS einer der in der folgenden Tabelle definierten Werte sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

