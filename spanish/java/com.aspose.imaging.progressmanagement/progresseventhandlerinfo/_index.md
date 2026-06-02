---
title: "ProgressEventHandlerInfo"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Esta clase representa información sobre el progreso de operaciones de carga/guardado/exportación de imágenes que puede ser utilizada en una aplicación externa para mostrar el progreso de la conversión al usuario final"
type: docs
weight: 10
url: /es/java/com.aspose.imaging.progressmanagement/progresseventhandlerinfo/
---
**Inheritance:**
java.lang.Object
```
public class ProgressEventHandlerInfo
```

Esta clase representa información sobre el progreso de las operaciones de carga/guardado/exportación de imágenes, que puede ser utilizada en una aplicación externa para mostrar el progreso de la conversión al usuario final.
## Métodos

| Método | Descripción |
| --- | --- |
| [getDescription()](#getDescription--) | Obtiene la descripción del evento |
| [getEventType()](#getEventType--) | Obtiene el tipo del evento. |
| [getMaxValue()](#getMaxValue--) | Obtiene el límite superior del valor de progreso. |
| [getValue()](#getValue--) | Obtiene el valor de progreso actual. |

## Example: The following example shows how to print information about progress events for load/export operations.

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1440\\";
String fileName = dir + "big.png";

// Ejemplo de uso de controladores de eventos de progreso de operación separados para operaciones de carga/exportación
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

// El registro STDOUT puede verse así:
//        Evento de carga Inicialización : 1/4
//        Evento de carga Preprocesamiento : 2/4
//        Evento de carga Procesamiento : 3/4
//        Evento de carga Finalización : 4/4
//        Evento de exportación Inicialización : 1/4
//        Evento de exportación Preprocesamiento : 2/4
//        Evento de exportación Procesamiento : 3/4
//        Evento de exportación ProgresoRelativo : 1/1
//        Evento de carga ProgresoRelativo : 1/1
//        Evento de exportación Finalización : 4/4
```

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Obtiene la descripción del evento

Valor: La descripción.

**Returns:**
java.lang.String - la descripción del evento
### getEventType() {#getEventType--}
```
public final EventType getEventType()
```


Obtiene el tipo del evento.

Valor: El tipo del evento.

**Returns:**
[EventType](../../com.aspose.imaging.progressmanagement/eventtype) - the type of the event.
### getMaxValue() {#getMaxValue--}
```
public final int getMaxValue()
```


Obtiene el límite superior del valor de progreso.

Valor: El límite superior del valor de progreso.

**Returns:**
int - el límite superior del valor de progreso.
### getValue() {#getValue--}
```
public final int getValue()
```


Obtiene el valor de progreso actual.

Valor: El valor de progreso.

**Returns:**
int - valor de progreso actual.
