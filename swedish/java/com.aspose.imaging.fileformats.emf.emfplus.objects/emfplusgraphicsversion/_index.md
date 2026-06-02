---
title: "EmfPlusGraphicsVersion"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusGraphicsVersion‑objektet specificerar versionen av operativsystemets grafik som används för att skapa en EMF‑metafil."
type: docs
weight: 44
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusGraphicsVersion extends EmfPlusStructureObjectType
```

EmfPlusGraphicsVersion-objektet specificerar versionen av operativsystemets grafik som används för att skapa en EMF+-metafil.

Grafikversioner är leverantörsutbyggbara; dock måste alla sådana tillägg implementeras i både klienter och servrar för EMF+-metafiler för att säkerställa interoperabilitet.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusGraphicsVersion()](#EmfPlusGraphicsVersion--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getMetafileSignature()](#getMetafileSignature--) | Hämtar en MetafileSignature (20 bitar): Ett värde som identifierar typen av metafil. |
| [setMetafileSignature(int value)](#setMetafileSignature-int-) | Hämtar en MetafileSignature (20 bitar): Ett värde som identifierar typen av metafil. |
| [getGraphicsVersion()](#getGraphicsVersion--) | Hämtar en GraphicsVersion (12 bitar): Versionen av operativsystemets grafik. |
| [setGraphicsVersion(int value)](#setGraphicsVersion-int-) | Hämtar en GraphicsVersion (12 bitar): Versionen av operativsystemets grafik. |
### EmfPlusGraphicsVersion() {#EmfPlusGraphicsVersion--}
```
public EmfPlusGraphicsVersion()
```


### getMetafileSignature() {#getMetafileSignature--}
```
public int getMetafileSignature()
```


Hämtar en MetafileSignature (20 bitar): Ett värde som identifierar typen av metafil. Värdet för en EMF+-metafil är 0xDBC01.

**Returns:**
int
### setMetafileSignature(int value) {#setMetafileSignature-int-}
```
public void setMetafileSignature(int value)
```


Hämtar en MetafileSignature (20 bitar): Ett värde som identifierar typen av metafil. Värdet för en EMF+-metafil är 0xDBC01.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getGraphicsVersion() {#getGraphicsVersion--}
```
public int getGraphicsVersion()
```


Hämtar en GraphicsVersion (12 bitar): Versionen av operativsystemets grafik. Detta värde MÅSTE vara definierat i `EmfPlusGraphicsVersion`‑enumerationen

**Returns:**
int
### setGraphicsVersion(int value) {#setGraphicsVersion-int-}
```
public void setGraphicsVersion(int value)
```


Hämtar en GraphicsVersion (12 bitar): Versionen av operativsystemets grafik. Detta värde MÅSTE vara definierat i `EmfPlusGraphicsVersion`‑enumerationen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

