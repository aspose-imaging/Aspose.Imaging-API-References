---
title: "AutoMaskingArgs-klass"
type: docs
weight: 20
url: /sv/python-net/aspose.imaging.masking.options/automaskingargs/
---

**Summary:** Represents the arguments that are specified for automated masking methods

**Module:** [aspose.imaging.masking.options](/imaging/python-net/aspose.imaging.masking.options/)

**Full Name:** aspose.imaging.masking.options.AutoMaskingArgs

**Inheritance:** IMaskingArgs

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [AutoMaskingArgs()](#AutoMaskingArgs__1) | Initierar en ny instans av AutoMaskingArgs-klassen |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| max_iteration_number | int | r/w | Hämtar eller anger det maximala antalet iterationer. |
| number_of_objects | int | r/w | Hämtar eller anger antalet objekt<br/>            att separera den ursprungliga bilden i (valfritt), standardvärdet är 2 (objekt och bakgrund). |
| objects_points | [Point[][]](/imaging/python-net/aspose.imaging/point[]/) | r/w | Hämtar eller anger punkterna som tillhör separerade objekt (valfritt)<br/>            NumberOfObjects-koordinater som tillhör NumberOfObjects-objekt i den ursprungliga bilden.<br/>            Denna parameter används för att öka segmenteringsmetodens precision. |
| objects_rectangles | [Rectangle[]](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Hämtar eller anger rektanglarna för objekten som tillhör separerade objekt (valfritt).<br/>            Denna parameter används för att öka segmenteringsmetodens precision. |
| orphaned_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | r/w | Hämtar eller anger punkterna som inte längre tillhör något objekt (valfritt).<br/>            Denna parameter används endast vid resegmentering. |
| precision | float | r/w | Hämtar eller anger precisionen för segmenteringsmetoden (valfritt). |


### Constructor: AutoMaskingArgs() {#AutoMaskingArgs__1}


```
 AutoMaskingArgs() 
```

Initierar en ny instans av AutoMaskingArgs-klassen

