---
title: "EmfCloseFigure"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Este registro cierra una figura abierta en una ruta."
type: docs
weight: 22
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfclosefigure/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPathBracketRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfpathbracketrecordtype)
```
public final class EmfCloseFigure extends EmfPathBracketRecordType
```

Este registro cierra una figura abierta en una ruta. El procesamiento del registro EMR\_CLOSEFIGURE MUST cerrar la figura dibujando una línea desde la posición actual hasta el primer punto de la figura, y luego MUST conectar las líneas usando el estilo de unión de líneas. Si una figura se cierra procesando el registro EMR\_LINETO en lugar del registro EMR\_CLOSEFIGURE, se utilizan extremos para crear la esquina en lugar de una unión. EMR\_LINETO se especifica en la sección 2.3.5.13. El registro EMR\_CLOSEFIGURE SHOULD solo usarse si hay un corchete de ruta abierto en el contexto del dispositivo de reproducción. Una figura en una ruta está abierta a menos que se cierre explícitamente procesando este registro.

Nota: Una figura puede estar abierta incluso si el punto actual y el punto de inicio de la figura son los mismos. Después de procesar el registro EMR\_CLOSEFIGURE, agregar una línea o curva a la ruta MUST iniciar una nueva figura.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfCloseFigure()](#EmfCloseFigure--) | Inicializa una nueva instancia de la clase `EmfCloseFigure`. |
### EmfCloseFigure() {#EmfCloseFigure--}
```
public EmfCloseFigure()
```


Inicializa una nueva instancia de la clase `EmfCloseFigure`.

