---
title: "EmfPlusTextureBrushData"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das EmfPlusTextureBrushData-Objekt gibt ein Texturbild für einen Grafikpinsel an."
type: docs
weight: 77
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
```
public final class EmfPlusTextureBrushData extends EmfPlusBaseBrushData
```

Das EmfPlusTextureBrushData-Objekt gibt ein Texturbild für einen Grafikpinsel an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusTextureBrushData()](#EmfPlusTextureBrushData--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBrushDataFlags()](#getBrushDataFlags--) | Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der die Daten im Feld OptionalData angibt. |
| [setBrushDataFlags(int value)](#setBrushDataFlags-int-) | Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der die Daten im Feld OptionalData angibt. |
| [getWrapMode()](#getWrapMode--) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer aus der Aufzählung WrapMode (Abschnitt 2.1.1.34), der angibt, wie das Texturbild über eine Form wiederholt wird, wenn das Bild kleiner ist als der zu füllende Bereich. |
| [setWrapMode(int value)](#setWrapMode-int-) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer aus der Aufzählung WrapMode (Abschnitt 2.1.1.34), der angibt, wie das Texturbild über eine Form wiederholt wird, wenn das Bild kleiner ist als der zu füllende Bereich. |
| [getOptionalData()](#getOptionalData--) | Liest oder setzt ein optionales EmfPlusTextureBrushOptionalData‑Objekt (Abschnitt 2.2.2.46), das zusätzliche Daten für den Texturpinsel angibt. |
| [setOptionalData(EmfPlusTextureBrushOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTextureBrushOptionalData-) | Liest oder setzt ein optionales EmfPlusTextureBrushOptionalData‑Objekt (Abschnitt 2.2.2.46), das zusätzliche Daten für den Texturpinsel angibt. |
### EmfPlusTextureBrushData() {#EmfPlusTextureBrushData--}
```
public EmfPlusTextureBrushData()
```


### getBrushDataFlags() {#getBrushDataFlags--}
```
public int getBrushDataFlags()
```


Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der die Daten im Feld OptionalData angibt. Dieser Wert MUSS aus BrushData‑Flags bestehen (Abschnitt 2.1.2.1). Die folgenden Flags sind für einen Texturpinsel relevant: BrushDataTransform, BrushDataIsGammaCorrected, BrushDataDoNotTransform

**Returns:**
int
### setBrushDataFlags(int value) {#setBrushDataFlags-int-}
```
public void setBrushDataFlags(int value)
```


Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der die Daten im Feld OptionalData angibt. Dieser Wert MUSS aus BrushData‑Flags bestehen (Abschnitt 2.1.2.1). Die folgenden Flags sind für einen Texturpinsel relevant: BrushDataTransform, BrushDataIsGammaCorrected, BrushDataDoNotTransform

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer aus der Aufzählung WrapMode (Abschnitt 2.1.1.34), der angibt, wie das Texturbild über eine Form wiederholt wird, wenn das Bild kleiner ist als der zu füllende Bereich.

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer aus der Aufzählung WrapMode (Abschnitt 2.1.1.34), der angibt, wie das Texturbild über eine Form wiederholt wird, wenn das Bild kleiner ist als der zu füllende Bereich.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusTextureBrushOptionalData getOptionalData()
```


Liest oder setzt ein optionales EmfPlusTextureBrushOptionalData‑Objekt (Abschnitt 2.2.2.46), das zusätzliche Daten für den Texturpinsel angibt. Der genaue Inhalt dieses Feldes wird durch den Wert des BrushDataFlags‑Feldes bestimmt.

**Returns:**
[EmfPlusTextureBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata)
### setOptionalData(EmfPlusTextureBrushOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTextureBrushOptionalData-}
```
public void setOptionalData(EmfPlusTextureBrushOptionalData value)
```


Liest oder setzt ein optionales EmfPlusTextureBrushOptionalData‑Objekt (Abschnitt 2.2.2.46), das zusätzliche Daten für den Texturpinsel angibt. Der genaue Inhalt dieses Feldes wird durch den Wert des BrushDataFlags‑Feldes bestimmt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfPlusTextureBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata) |  |

