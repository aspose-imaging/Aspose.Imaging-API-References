---
title: "ProgressEventHandlerInfo"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Diese Klasse repräsentiert Informationen über den Fortschritt von Bild‑Lade‑/Speicher‑/Export‑Operationen, die in einer externen Anwendung verwendet werden können, um dem Endbenutzer den Konvertierungsfortschritt anzuzeigen."
type: docs
weight: 10
url: /de/java/com.aspose.imaging.progressmanagement/progresseventhandlerinfo/
---
**Inheritance:**
java.lang.Object
```
public class ProgressEventHandlerInfo
```

Diese Klasse stellt Informationen über den Fortschritt von Bild‑Lade‑/Speicher‑/Export‑Operationen bereit, die in einer externen Anwendung verwendet werden können, um dem Endbenutzer den Konvertierungsfortschritt anzuzeigen
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDescription()](#getDescription--) | Ruft die Beschreibung des Ereignisses ab |
| [getEventType()](#getEventType--) | Ruft den Typ des Ereignisses ab. |
| [getMaxValue()](#getMaxValue--) | Gibt die obere Fortschrittswertgrenze zurück. |
| [getValue()](#getValue--) | Gibt den aktuellen Fortschrittswert zurück. |

## Example: The following example shows how to print information about progress events for load/export operations.

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1440\\";
String fileName = dir + "big.png";

// Beispiel für die Verwendung separater Fortschrittsereignis-Handler für Lade-/Exportvorgänge
final com.aspose.imaging.ProgressEventHandler loadHandler = new com.aspose.imaging.ProgressEventHandler() {
    @Override
    public void invoke(com.aspose.imaging.progressmanagement.ProgressEventHandlerInfo info) {
        System.out.format("Load event %s : %d/%d\n", com.aspose.imaging.progressmanagement.EventType.toString(com.aspose.imaging.progressmanagement.EventType.class, info.getEventType()), info.getValue(), info.getMaxValue());
    }
};

final com.aspose.imaging.ProgressEventHandler exportHandler = new com.aspose.imaging.ProgressEventHandler() {
    @Override
    public void invoke(com.aspose.imaging.progressmanagement.ProgressEventHandlerInfo info) {
        System.out.format("Export event %s : %d/%d\n", com.aspose.imaging.progressmanagement.EventType.toString(com.aspose.imaging.progressmanagement.EventType.class, info.getEventType()), info.getValue(), info.getMaxValue());
    }
};

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName, new com.aspose.imaging.LoadOptions() {{ setProgressEventHandler(loadHandler); }} );
try {
    image.save(fileName + ".psd",
            new com.aspose.imaging.imageoptions.PsdOptions() {{ setProgressEventHandler( exportHandler); }});
}
finally {
    image.close();
}

// Das STDOUT-Protokoll kann folgendermaßen aussehen:
//        Ladeereignis Initialisierung : 1/4
//        Ladeereignis Vorverarbeitung : 2/4
//        Ladeereignis Verarbeitung : 3/4
//        Ladeereignis Finalisierung : 4/4
//        Exportereignis Initialisierung : 1/4
//        Exportereignis Vorverarbeitung : 2/4
//        Exportereignis Verarbeitung : 3/4
//        Exportereignis Relativer Fortschritt : 1/1
//        Ladeereignis Relativer Fortschritt : 1/1
//        Exportereignis Finalisierung : 4/4
```

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Ruft die Beschreibung des Ereignisses ab

Wert: Die Beschreibung.

**Returns:**
java.lang.String - die Beschreibung des Ereignisses
### getEventType() {#getEventType--}
```
public final EventType getEventType()
```


Ruft den Typ des Ereignisses ab.

Wert: Der Typ des Ereignisses.

**Returns:**
[EventType](../../com.aspose.imaging.progressmanagement/eventtype) - the type of the event.
### getMaxValue() {#getMaxValue--}
```
public final int getMaxValue()
```


Gibt die obere Fortschrittswertgrenze zurück.

Wert: Die obere Fortschrittswertgrenze.

**Returns:**
int - die obere Fortschrittswertgrenze.
### getValue() {#getValue--}
```
public final int getValue()
```


Gibt den aktuellen Fortschrittswert zurück.

Wert: Der Fortschrittswert.

**Returns:**
int - aktueller Fortschrittswert.
