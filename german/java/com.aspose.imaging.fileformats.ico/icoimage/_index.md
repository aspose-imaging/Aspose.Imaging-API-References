---
title: "IcoImage"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Manipulieren Sie ICO‑Bilddateien mühelos mit unserer API, die verschiedene Dateiformate und Frame‑Typen einschließlich PNG und BMP unterstützt."
type: docs
weight: 10
url: /de/java/com.aspose.imaging.fileformats.ico/icoimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext)
```
public class IcoImage extends RasterCachedMultipageImage implements IMultipageImageExt
```

Manipulieren Sie ICO‑Bilddateien mühelos mit unserer API, die verschiedene Dateiformate und Frame‑Typen einschließlich PNG und BMP unterstützt. Passen Sie die Bits‑pro‑Pixel‑Einstellungen an und aktualisieren Sie Bildabmessungen nahtlos, um eine optimale Darstellung und Kompatibilität Ihrer Symbole auf verschiedenen Plattformen zu gewährleisten.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [IcoImage(int width, int height, IcoOptions options)](#IcoImage-int-int-com.aspose.imaging.imageoptions.IcoOptions-) | Starten Sie die ICO‑Bild-Erstellung mühelos mit der Klasse [IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage). |
| [IcoImage(Image image, IcoOptions icoOptions)](#IcoImage-com.aspose.imaging.Image-com.aspose.imaging.imageoptions.IcoOptions-) | Entwickelt für Einfachheit und Effizienz, ermöglicht Ihnen die Klasse [IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage) das einfache Erstellen von ICO‑Bildern. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Rufen Sie das Dateiformat mühelos über diese Eigenschaft ab, um eine nahtlose Integration in Ihren Arbeitsablauf zu ermöglichen. |
| [getPageCount()](#getPageCount--) | Erhalten Sie sofortigen Einblick in die Dokumentstruktur mit dieser einfachen Eigenschaft. |
| [getPages()](#getPages--) | Rufen Sie mühelos umfassende Informationen zu den Seiten des Dokuments über diese Eigenschaft ab. |
| [hasAlpha()](#hasAlpha--) | Bestimmen Sie mit dieser Eigenschaft, ob ein Alphakanal in dieser Instanz vorhanden ist. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Erweitern Sie Ihr ICO-Bild, indem Sie einen Bildseiteneintrag hinzufügen und dabei die [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) nutzen. |
| [addPage(Image page)](#addPage-com.aspose.imaging.Image-) | Bereichern Sie Ihr ICO-Bild mühelos, indem Sie einen Bildseiteneintrag mit den Standardeinstellungen von [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) einfügen. |
| [addPage(Image page, IcoOptions icoOptions)](#addPage-com.aspose.imaging.Image-com.aspose.imaging.imageoptions.IcoOptions-) | Diversifizieren Sie Ihr ICO-Bild mühelos, indem Sie einen Bildeintrag integrieren, der mit den angegebenen [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) an Ihre Bedürfnisse angepasst ist. |
| [removePage(int index)](#removePage-int-) | Feinabstimmen Sie Ihr ICO-Bild, indem Sie einen bestimmten Bildeintrag entfernen, der sich an der angegebenen `` innerhalb der Datei befindet. |
### IcoImage(int width, int height, IcoOptions options) {#IcoImage-int-int-com.aspose.imaging.imageoptions.IcoOptions-}
```
public IcoImage(int width, int height, IcoOptions options)
```


Starten Sie die Erstellung von ICO-Bildern mühelos mit der Klasse [IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage). Dieser Konstruktor ermöglicht es Ihnen, neue Instanzen von ICO-Bildern zu initialisieren, indem Sie die Parameter Breite, Höhe und Erstellungsoptionen angeben. Mit diesem einfachen Konstruktor können Sie ICO-Bilder exakt nach Ihren Vorgaben anpassen und so nahtlose Kompatibilität sowie visuelle Attraktivität auf verschiedenen Plattformen und Geräten gewährleisten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite | int | Die Breite. |
| Höhe | int | Die Höhe. |
| options | [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) | Die ICO-Erstellungsoptionen. |

### IcoImage(Image image, IcoOptions icoOptions) {#IcoImage-com.aspose.imaging.Image-com.aspose.imaging.imageoptions.IcoOptions-}
```
public IcoImage(Image image, IcoOptions icoOptions)
```


Entwickelt für Einfachheit und Effizienz, ermöglicht Ihnen die Klasse [IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage) das mühelose Erstellen von ICO-Bildern. Dieser Konstruktor initialisiert eine neue Instanz der Klasse und bietet eine solide Grundlage für Ihre Bildbearbeitungsanforderungen. Egal, ob Sie Anwendungen entwickeln oder Benutzeroberflächen verbessern, die Klasse [IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage) vereinfacht die Verwaltung von ICO-Bildern, sodass Sie sich darauf konzentrieren können, außergewöhnliche Erlebnisse zu liefern.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Das Bild. |
| icoOptions | [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) | Die ICO-Optionen. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Rufen Sie das Dateiformat mühelos über diese Eigenschaft ab, um eine nahtlose Integration in Ihren Arbeitsablauf zu ermöglichen. Durch die Verwendung dieser Eigenschaft erhalten Sie Zugriff auf wichtige Informationen zum Format Ihrer Datei, was Kompatibilität und effiziente Verarbeitung sicherstellt.

**Returns:**
long
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Erhalten Sie sofortigen Einblick in die Dokumentstruktur mit dieser einfachen Eigenschaft. Durch Aufrufen dieser Eigenschaft rufen Sie mühelos die Gesamtzahl der im Dateibereich enthaltenen Seiten ab.

**Returns:**
int – die Seitenanzahl.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Rufen Sie umfassende Informationen zu den Seiten des Dokuments mühelos über diese Eigenschaft ab. Durch den Zugriff auf diese Eigenschaft erhalten Sie eine Sammlung oder ein Array, das alle im Dokument vorhandenen Seiten enthält.

**Returns:**
com.aspose.imaging.Image[] – die Seiten.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Bestimmen Sie mit dieser Eigenschaft, ob ein Alphakanal in dieser Instanz vorhanden ist. Sie bietet eine schnelle Möglichkeit zu prüfen, ob das Bild oder Dokument einen Alphakanal enthält, was für verschiedene Bildverarbeitungs- und Rendering‑Aufgaben entscheidend ist. Ideal, um Kompatibilität sicherzustellen und Transparenzeffekte in Bildern oder Dokumenten zu handhaben.

**Returns:**
boolean – ein Wert, der angibt, ob diese Instanz Alpha hat.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public final void addPage(RasterImage page)
```


Erweitern Sie Ihr ICO-Bild, indem Sie einen Bildseiteneintrag hinzufügen und dabei die [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) nutzen. Diese Methode integriert Rasterbilder nahtlos in Ihre ICO-Datei und konvertiert sie in ein hochwertiges 32‑Bit‑PNG‑Format. Perfekt, um Ihre ICO-Dateien mit Rasterbildern zu verbessern und gleichzeitig optimale Kompatibilität und Rendering‑Qualität sicherzustellen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | Das Bild. |

### addPage(Image page) {#addPage-com.aspose.imaging.Image-}
```
public final void addPage(Image page)
```


Bereichern Sie Ihr ICO-Bild mühelos, indem Sie einen Bildseiteneintrag mit den Standardeinstellungen von [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) einfügen. Diese Methode konvertiert das eingefügte Bild bequem in ein 32‑Bit‑PNG‑Format, wodurch Kompatibilität und hochwertige Darstellung im ICO-Bild gewährleistet werden. Perfekt, um PNG‑Bilder nahtlos und effizient in Ihre ICO-Dateien zu integrieren.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| page | [Image](../../com.aspose.imaging/image) | Das Bild. |

### addPage(Image page, IcoOptions icoOptions) {#addPage-com.aspose.imaging.Image-com.aspose.imaging.imageoptions.IcoOptions-}
```
public final void addPage(Image page, IcoOptions icoOptions)
```


Diversifizieren Sie Ihr ICO-Bild mühelos, indem Sie einen Bildeintrag integrieren, der mit den angegebenen [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) an Ihre Bedürfnisse angepasst ist. Diese Methode fügt das Bild nahtlos gemäß Ihren benutzerdefinierten Optionen ein und gewährleistet Flexibilität und Präzision in Ihrer ICO-Datei.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| page | [Image](../../com.aspose.imaging/image) | Das Bild. |
| icoOptions | [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) | Die ICO-Optionen. |

### removePage(int index) {#removePage-int-}
```
public final void removePage(int index)
```


Feinabstimmen Sie Ihr ICO-Bild, indem Sie einen bestimmten Bildeintrag entfernen, der sich an der angegebenen `` innerhalb der Datei befindet. Diese Methode bietet präzise Kontrolle über Ihre Bildkomposition und ermöglicht es Ihnen, Ihre ICO-Datei mühelos zu verfeinern.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der Index. |

