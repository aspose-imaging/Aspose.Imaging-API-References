---
title: "EmfPlusGraphicsVersion"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das EmfPlusGraphicsVersion‑Objekt gibt die Version der Betriebssystemgrafik an, die zum Erstellen einer EMF‑Metadatei verwendet wird."
type: docs
weight: 44
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusGraphicsVersion extends EmfPlusStructureObjectType
```

Das EmfPlusGraphicsVersion-Objekt gibt die Version der Betriebssystemgrafik an, die zum Erstellen einer EMF+-Metadatei verwendet wird.

Grafikversionen sind herstellererweiterbar; jedoch MUSS jede solche Erweiterung zur Gewährleistung der Interoperabilität sowohl in Clients als auch in Servern von EMF+‑Metadateien implementiert werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusGraphicsVersion()](#EmfPlusGraphicsVersion--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getMetafileSignature()](#getMetafileSignature--) | Liest eine MetafileSignature (20 Bit): Ein Wert, der den Typ der Metadatei identifiziert. |
| [setMetafileSignature(int value)](#setMetafileSignature-int-) | Liest eine MetafileSignature (20 Bit): Ein Wert, der den Typ der Metadatei identifiziert. |
| [getGraphicsVersion()](#getGraphicsVersion--) | Liest eine GraphicsVersion (12 Bit): Die Version der Betriebssystemgrafik. |
| [setGraphicsVersion(int value)](#setGraphicsVersion-int-) | Liest eine GraphicsVersion (12 Bit): Die Version der Betriebssystemgrafik. |
### EmfPlusGraphicsVersion() {#EmfPlusGraphicsVersion--}
```
public EmfPlusGraphicsVersion()
```


### getMetafileSignature() {#getMetafileSignature--}
```
public int getMetafileSignature()
```


Liest eine MetafileSignature (20 Bit): Ein Wert, der den Typ der Metadatei identifiziert. Der Wert für eine EMF+‑Metadatei ist 0xDBC01.

**Returns:**
int
### setMetafileSignature(int value) {#setMetafileSignature-int-}
```
public void setMetafileSignature(int value)
```


Liest eine MetafileSignature (20 Bit): Ein Wert, der den Typ der Metadatei identifiziert. Der Wert für eine EMF+‑Metadatei ist 0xDBC01.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getGraphicsVersion() {#getGraphicsVersion--}
```
public int getGraphicsVersion()
```


Liest eine GraphicsVersion (12 Bit): Die Version der Betriebssystemgrafik. Dieser Wert MUSS in der `EmfPlusGraphicsVersion`‑Aufzählung definiert sein

**Returns:**
int
### setGraphicsVersion(int value) {#setGraphicsVersion-int-}
```
public void setGraphicsVersion(int value)
```


Liest eine GraphicsVersion (12 Bit): Die Version der Betriebssystemgrafik. Dieser Wert MUSS in der `EmfPlusGraphicsVersion`‑Aufzählung definiert sein

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

