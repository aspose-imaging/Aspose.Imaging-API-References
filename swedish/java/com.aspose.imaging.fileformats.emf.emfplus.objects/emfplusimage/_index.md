---
title: "EmfPlusImage"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusImage-objektet specificerar en grafikbild i form av en bitmap eller metafil."
type: docs
weight: 47
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusImage extends EmfPlusGraphicsObjectType
```

EmfPlusImage-objektet specificerar en grafikbild i form av en bitmap eller metafil.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusImage()](#EmfPlusImage--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getImageData()](#getImageData--) | Hämtar eller anger Image data variabel‑längd data som definierar bilddata specificerad i Type‑fältet. |
| [setImageData(EmfPlusBaseImageData value)](#setImageData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseImageData-) | Hämtar eller anger Image data variabel‑längd data som definierar bilddata specificerad i Type‑fältet. |
| [getType()](#getType--) | Hämtar eller anger bildtyp Ett 32‑bitars osignerat heltal som specificerar typen av data i ImageData‑fältet. |
| [setType(int value)](#setType-int-) | Hämtar eller anger bildtyp Ett 32‑bitars osignerat heltal som specificerar typen av data i ImageData‑fältet. |
### EmfPlusImage() {#EmfPlusImage--}
```
public EmfPlusImage()
```


### getImageData() {#getImageData--}
```
public EmfPlusBaseImageData getImageData()
```


Hämtar eller anger Image data variabel‑längd data som definierar bilddata specificerad i Type‑fältet. Innehållet och formatet på data kan vara olika för varje bildtyp.

**Returns:**
[EmfPlusBaseImageData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbaseimagedata)
### setImageData(EmfPlusBaseImageData value) {#setImageData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseImageData-}
```
public void setImageData(EmfPlusBaseImageData value)
```


Hämtar eller anger Image data variabel‑längd data som definierar bilddata specificerad i Type‑fältet. Innehållet och formatet på data kan vara olika för varje bildtyp.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfPlusBaseImageData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbaseimagedata) |  |

### getType() {#getType--}
```
public int getType()
```


Hämtar eller anger bildtyp A 32-bitars osignerat heltal som specificerar datatypen i ImageData-fältet. Detta värde MÅSTE vara definierat i ImageDataType‑enumerationen (avsnitt 2.1.1.15).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Hämtar eller anger bildtyp A 32-bitars osignerat heltal som specificerar datatypen i ImageData-fältet. Detta värde MÅSTE vara definierat i ImageDataType‑enumerationen (avsnitt 2.1.1.15).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

