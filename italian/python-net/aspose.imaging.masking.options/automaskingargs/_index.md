---
title: "AutoMaskingArgs Classe"
type: docs
weight: 20
url: /it/python-net/aspose.imaging.masking.options/automaskingargs/
---

**Summary:** Represents the arguments that are specified for automated masking methods

**Module:** [aspose.imaging.masking.options](/imaging/python-net/aspose.imaging.masking.options/)

**Full Name:** aspose.imaging.masking.options.AutoMaskingArgs

**Inheritance:** IMaskingArgs

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [AutoMaskingArgs()](#AutoMaskingArgs__1) | Inizializza una nuova istanza della classe AutoMaskingArgs |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| max_iteration_number | int | r/w | Ottiene o imposta il numero massimo di iterazioni. |
| number_of_objects | int | r/w | Ottiene o imposta il numero di oggetti<br/>            per separare l'immagine iniziale in (opzionale), il valore predefinito è 2 (oggetto e sfondo). |
| objects_points | [Point[][]](/imaging/python-net/aspose.imaging/point[]/) | r/w | Ottiene o imposta i punti che appartengono agli oggetti separati (opzionale)<br/>            coordinate NumberOfObjects che appartengono a NumberOfObjects oggetti dell'immagine iniziale.<br/>            Questo parametro è usato per aumentare la precisione del metodo di segmentazione. |
| objects_rectangles | [Rectangle[]](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Ottiene o imposta i rettangoli degli oggetti che appartengono a oggetti separati (opzionale).<br/>            Questo parametro è usato per aumentare la precisione del metodo di segmentazione. |
| orphaned_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | r/w | Ottiene o imposta i punti che non appartengono più a nessun oggetto (opzionale).<br/>            Questo parametro è usato solo in caso di ri-segmentazione. |
| precision | float | r/w | Ottiene o imposta la precisione del metodo di segmentazione (opzionale). |


### Constructor: AutoMaskingArgs() {#AutoMaskingArgs__1}


```
 AutoMaskingArgs() 
```

Inizializza una nuova istanza della classe AutoMaskingArgs

