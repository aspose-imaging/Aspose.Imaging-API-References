---
title: "ProgressEventHandlerInfo"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Questa classe rappresenta le informazioni sul progresso delle operazioni di caricamento/salvataggio/esportazione delle immagini che possono essere utilizzate in un'applicazione esterna per mostrare all'utente finale lo stato di avanzamento della conversione"
type: docs
weight: 10
url: /it/java/com.aspose.imaging.progressmanagement/progresseventhandlerinfo/
---
**Inheritance:**
java.lang.Object
```
public class ProgressEventHandlerInfo
```

Questa classe rappresenta le informazioni sul progresso delle operazioni di caricamento/salvataggio/esportazione delle immagini, che possono essere utilizzate in un'applicazione esterna per mostrare il progresso della conversione all'utente finale.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getDescription()](#getDescription--) | Ottiene la descrizione dell'evento |
| [getEventType()](#getEventType--) | Ottiene il tipo dell'evento. |
| [getMaxValue()](#getMaxValue--) | Ottiene il limite superiore del valore di avanzamento. |
| [getValue()](#getValue--) | Ottiene il valore di avanzamento corrente. |

## Example: The following example shows how to print information about progress events for load/export operations.

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1440\\";
String fileName = dir + "big.png";

// Esempio di utilizzo di gestori di eventi di avanzamento dell'operazione separati per le operazioni di caricamento/esportazione
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

// Il registro STDOUT può apparire così:
//        Evento di caricamento Inizializzazione : 1/4
//        Evento di caricamento Preelaborazione : 2/4
//        Evento di caricamento Elaborazione : 3/4
//        Evento di caricamento Finalizzazione : 4/4
//        Evento di esportazione Inizializzazione : 1/4
//        Evento di esportazione Preelaborazione : 2/4
//        Evento di esportazione Elaborazione : 3/4
//        Evento di esportazione ProgressoRelativo : 1/1
//        Evento di caricamento ProgressoRelativo : 1/1
//        Evento di esportazione Finalizzazione : 4/4
```

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Ottiene la descrizione dell'evento

Valore: La descrizione.

**Returns:**
java.lang.String - la descrizione dell'evento
### getEventType() {#getEventType--}
```
public final EventType getEventType()
```


Ottiene il tipo dell'evento.

Valore: Il tipo dell'evento.

**Returns:**
[EventType](../../com.aspose.imaging.progressmanagement/eventtype) - the type of the event.
### getMaxValue() {#getMaxValue--}
```
public final int getMaxValue()
```


Ottiene il limite superiore del valore di avanzamento.

Valore: Il limite superiore del valore di avanzamento.

**Returns:**
int - il limite superiore del valore di avanzamento.
### getValue() {#getValue--}
```
public final int getValue()
```


Ottiene il valore di avanzamento corrente.

Valore: Il valore di avanzamento.

**Returns:**
int - valore di avanzamento corrente.
