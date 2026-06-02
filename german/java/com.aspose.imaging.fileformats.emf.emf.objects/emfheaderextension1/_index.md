---
title: "EmfHeaderExtension1"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das HeaderExtension1‑Objekt definiert die erste Erweiterung des EMF‑Metadatei‑Headers."
type: docs
weight: 18
url: /de/java/com.aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderobject)
```
public final class EmfHeaderExtension1 extends EmfHeaderObject
```

Das HeaderExtension1-Objekt definiert die erste Erweiterung des EMF-Metadatei-Headers. Es fügt Unterstützung für ein PixelFormatDescriptor-Objekt (Abschnitt 2.2.22) und OpenGL [OPENGL]-Datensätze (Abschnitt 2.3.9) hinzu.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfHeaderExtension1()](#EmfHeaderExtension1--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCbPixelFormat()](#getCbPixelFormat--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe des PixelFormatDescriptor-Objekts angibt. |
| [setCbPixelFormat(int value)](#setCbPixelFormat-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe des PixelFormatDescriptor-Objekts angibt. |
| [getOffPixelFormat()](#getOffPixelFormat--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Offset zum PixelFormatDescriptor-Objekt angibt. |
| [setOffPixelFormat(int value)](#setOffPixelFormat-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Offset zum PixelFormatDescriptor-Objekt angibt. |
| [getBOpenGl()](#getBOpenGl--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die angibt, ob OpenGL‑Befehle in der Metadatei vorhanden sind. |
| [setBOpenGl(int value)](#setBOpenGl-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die angibt, ob OpenGL‑Befehle in der Metadatei vorhanden sind. |
### EmfHeaderExtension1() {#EmfHeaderExtension1--}
```
public EmfHeaderExtension1()
```


### getCbPixelFormat() {#getCbPixelFormat--}
```
public int getCbPixelFormat()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe des PixelFormatDescriptor-Objekts angibt. Dieser MUSS 0x00000000 sein, wenn kein Pixelformat festgelegt ist.

**Returns:**
int
### setCbPixelFormat(int value) {#setCbPixelFormat-int-}
```
public void setCbPixelFormat(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe des PixelFormatDescriptor-Objekts angibt. Dieser MUSS 0x00000000 sein, wenn kein Pixelformat festgelegt ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getOffPixelFormat() {#getOffPixelFormat--}
```
public int getOffPixelFormat()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Offset zum PixelFormatDescriptor-Objekt angibt. Dieser MUSS 0x00000000 sein, wenn kein Pixelformat festgelegt ist.

**Returns:**
int
### setOffPixelFormat(int value) {#setOffPixelFormat-int-}
```
public void setOffPixelFormat(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Offset zum PixelFormatDescriptor-Objekt angibt. Dieser MUSS 0x00000000 sein, wenn kein Pixelformat festgelegt ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getBOpenGl() {#getBOpenGl--}
```
public int getBOpenGl()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die angibt, ob OpenGL‑Befehle in der Metadatei vorhanden sind. 0x00000000 OpenGL‑Datensätze sind nicht in der Metadatei enthalten. 0x00000001 OpenGL‑Datensätze sind in der Metadatei enthalten.

**Returns:**
int
### setBOpenGl(int value) {#setBOpenGl-int-}
```
public void setBOpenGl(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die angibt, ob OpenGL‑Befehle in der Metadatei vorhanden sind. 0x00000000 OpenGL‑Datensätze sind nicht in der Metadatei enthalten. 0x00000001 OpenGL‑Datensätze sind in der Metadatei enthalten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

