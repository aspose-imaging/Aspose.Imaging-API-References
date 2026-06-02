---
title: "ProgressEventHandlerInfo"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Cette classe représente des informations sur la progression des opérations de chargement/enregistrement/export d'images qui peuvent être utilisées dans une application externe pour afficher la progression de la conversion à l'utilisateur final"
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.progressmanagement/progresseventhandlerinfo/
---
**Inheritance:**
java.lang.Object
```
public class ProgressEventHandlerInfo
```

Cette classe représente les informations sur la progression des opérations de chargement/enregistrement/exportation d'images, qui peuvent être utilisées dans une application externe pour afficher la progression de la conversion à l'utilisateur final.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getDescription()](#getDescription--) | Obtient la description de l'événement |
| [getEventType()](#getEventType--) | Obtient le type de l'événement. |
| [getMaxValue()](#getMaxValue--) | Obtient la limite supérieure de la valeur de progression. |
| [getValue()](#getValue--) | Obtient la valeur de progression actuelle. |

## Example: The following example shows how to print information about progress events for load/export operations.

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1440\\";
String fileName = dir + "big.png";

// Exemple d'utilisation de gestionnaires d'événements de progression d'opération séparés pour les opérations de chargement/exportation
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

// Le journal STDOUT peut ressembler à ceci :
//        Événement de chargement Initialisation : 1/4
//        Événement de chargement Prétraitement : 2/4
//        Événement de chargement Traitement : 3/4
//        Événement de chargement Finalisation : 4/4
//        Événement d'exportation Initialisation : 1/4
//        Événement d'exportation Prétraitement : 2/4
//        Événement d'exportation Traitement : 3/4
//        Événement d'exportation RelativeProgress : 1/1
//        Événement de chargement RelativeProgress : 1/1
//        Événement d'exportation Finalisation : 4/4
```

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Obtient la description de l'événement

Valeur : La description.

**Returns:**
java.lang.String - la description de l'événement
### getEventType() {#getEventType--}
```
public final EventType getEventType()
```


Obtient le type de l'événement.

Valeur : Le type de l'événement.

**Returns:**
[EventType](../../com.aspose.imaging.progressmanagement/eventtype) - the type of the event.
### getMaxValue() {#getMaxValue--}
```
public final int getMaxValue()
```


Obtient la limite supérieure de la valeur de progression.

Valeur : La limite supérieure de la valeur de progression.

**Returns:**
int - la limite supérieure de la valeur de progression.
### getValue() {#getValue--}
```
public final int getValue()
```


Obtient la valeur de progression actuelle.

Valeur : La valeur de progression.

**Returns:**
int - valeur de progression actuelle.
