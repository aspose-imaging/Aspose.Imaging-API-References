---
title: "EmfPlusImage"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das EmfPlusImage-Objekt gibt ein Grafikbild in Form einer Bitmap oder Metadatei an."
type: docs
weight: 47
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusImage extends EmfPlusGraphicsObjectType
```

Das EmfPlusImage-Objekt gibt ein Grafikbild in Form einer Bitmap oder Metadatei an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusImage()](#EmfPlusImage--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getImageData()](#getImageData--) | Liest oder setzt die Bilddaten (Variable‑Länge‑Daten), die die im Typ‑Feld angegebenen Bilddaten definieren. |
| [setImageData(EmfPlusBaseImageData value)](#setImageData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseImageData-) | Liest oder setzt die Bilddaten (Variable‑Länge‑Daten), die die im Typ‑Feld angegebenen Bilddaten definieren. |
| [getType()](#getType--) | Liest oder setzt den Bildtyp. Ein 32‑Bit vorzeichenloser Integer, der den Typ der Daten im ImageData‑Feld angibt. |
| [setType(int value)](#setType-int-) | Liest oder setzt den Bildtyp. Ein 32‑Bit vorzeichenloser Integer, der den Typ der Daten im ImageData‑Feld angibt. |
### EmfPlusImage() {#EmfPlusImage--}
```
public EmfPlusImage()
```


### getImageData() {#getImageData--}
```
public EmfPlusBaseImageData getImageData()
```


Liest oder setzt die Bilddaten (Variable‑Länge‑Daten), die die im Typ‑Feld angegebenen Bilddaten definieren. Der Inhalt und das Format der Daten können je nach Bildtyp unterschiedlich sein.

**Returns:**
[EmfPlusBaseImageData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbaseimagedata)
### setImageData(EmfPlusBaseImageData value) {#setImageData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseImageData-}
```
public void setImageData(EmfPlusBaseImageData value)
```


Liest oder setzt die Bilddaten (Variable‑Länge‑Daten), die die im Typ‑Feld angegebenen Bilddaten definieren. Der Inhalt und das Format der Daten können je nach Bildtyp unterschiedlich sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfPlusBaseImageData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbaseimagedata) |  |

### getType() {#getType--}
```
public int getType()
```


Liest oder setzt den Bildtyp, ein 32‑Bit‑vorzeichenloser Integer, der den Typ der Daten im Feld ImageData angibt. Dieser Wert MUSS in der Aufzählung ImageDataType definiert sein (Abschnitt 2.1.1.15).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Liest oder setzt den Bildtyp, ein 32‑Bit‑vorzeichenloser Integer, der den Typ der Daten im Feld ImageData angibt. Dieser Wert MUSS in der Aufzählung ImageDataType definiert sein (Abschnitt 2.1.1.15).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

