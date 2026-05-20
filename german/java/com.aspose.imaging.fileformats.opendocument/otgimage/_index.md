---
title: "OtgImage"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Verarbeiten Sie OpenDocument‑Template‑OTG‑Zeichnungs‑Bilddateien mit unserer API, die das OpenDocument‑XML‑Format mit Grafik‑Inhalt nutzt, um eine nahtlose Manipulation zu ermöglichen."
type: docs
weight: 13
url: /de/java/com.aspose.imaging.fileformats.opendocument/otgimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage), [com.aspose.imaging.fileformats.opendocument.OdImage](../../com.aspose.imaging.fileformats.opendocument/odimage)
```
public class OtgImage extends OdImage
```

Verarbeiten Sie OpenDocument‑Template‑(OTG)‑Zeichnungs‑Bilddateien mit unserer API, die das OpenDocument‑XML‑Format mit Grafik‑Inhalt nutzt, um eine nahtlose Manipulation zu ermöglichen. Parsen Sie Dokumente einfach, passen Sie Hintergrundfarben an und ändern Sie Seitenabmessungen, um optimale Kontrolle und Flexibilität für Ihre OTG‑Vektorgrafik‑Projekte zu gewährleisten.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [OtgImage(StreamContainer streamContainer, LoadOptions loadOptions)](#OtgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | Initialisieren Sie ein neues [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage)-Objekt, indem Sie einen Stream-Container und Ladeoptionen bereitstellen. |
| [OtgImage(StreamContainer streamContainer)](#OtgImage-com.aspose.imaging.StreamContainer-) | Erstellen Sie ein neues Objekt der Klasse [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage), indem Sie einen Stream-Container bereitstellen. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Diese Eigenschaft bietet Zugriff auf das OTG-Dateiformat und liefert wichtige Einblicke in die Art der im Bilddatei enthaltenen Daten. |
| [getPages()](#getPages--) | Ruft die Sammlung von Seiten ab, die mit dem Bild verknüpft sind, und ermöglicht Entwicklern, jede einzelne Seite effizient zuzugreifen und zu manipulieren. |
### OtgImage(StreamContainer streamContainer, LoadOptions loadOptions) {#OtgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-}
```
public OtgImage(StreamContainer streamContainer, LoadOptions loadOptions)
```


Initialisieren Sie ein neues [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage)-Objekt, indem Sie einen Stream-Container und Ladeoptionen bereitstellen. Dieser Konstruktor ermöglicht Entwicklern, OTG-Bilder effizient aus Streams zu laden und dabei benutzerdefinierte Ladekonfigurationen anzugeben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Der Stream. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Die Ladeoptionen. |

### OtgImage(StreamContainer streamContainer) {#OtgImage-com.aspose.imaging.StreamContainer-}
```
public OtgImage(StreamContainer streamContainer)
```


Erstellen Sie ein neues Objekt der Klasse [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage), indem Sie einen Stream-Container bereitstellen. Dieser Konstruktor ermöglicht Entwicklern, OTG-Bilder direkt aus Stream-Containern zu erzeugen und vereinfacht so die Arbeit mit OTG-Bilddaten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Der Stream‑Container. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Diese Eigenschaft bietet Zugriff auf das OTG-Dateiformat und liefert wichtige Einblicke in die Art der im Bilddatei enthaltenen Daten. Sie dient als zentraler Referenzpunkt für Entwickler, sodass sie OTG-Dateien in ihren Anwendungen effektiv handhaben können. Durch die Nutzung dieser Eigenschaft können Sie das spezifische Format der Bilddatei ermitteln, was eine nahtlose Integration und Manipulation von OTG-Dateien in Ihren Softwaresystemen ermöglicht.

**Returns:**
long
### getPages() {#getPages--}
```
public Image[] getPages()
```


Ruft die Sammlung von Seiten ab, die mit dem Bild verknüpft sind, und ermöglicht Entwicklern, jede einzelne Seite effizient zuzugreifen und zu manipulieren. Diese Eigenschaft erleichtert ein nahtloses Durchlaufen der Seiten für verschiedene Vorgänge und erhöht die Funktionalität und Vielseitigkeit von Bildverarbeitungsanwendungen.

**Returns:**
com.aspose.imaging.Image[] – die Seiten.
