---
title: "EmfBeginPath"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Este registro abre un corchete de ruta en el contexto del dispositivo de reproducción actual."
type: docs
weight: 15
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfbeginpath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPathBracketRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfpathbracketrecordtype)
```
public final class EmfBeginPath extends EmfPathBracketRecordType
```

Este registro abre un corchete de ruta en el contexto de dispositivo de reproducción actual. Después de que el corchete de ruta está abierto, una aplicación puede comenzar a procesar registros para definir los puntos que pertenecen a la ruta. Una aplicación DEBE cerrar un corchete de ruta abierto procesando el registro EMR\_ENDPATH. Cuando una aplicación procesa el registro EMR\_BEGINPATH, todas las rutas anteriores DEBEN descartarse del contexto de dispositivo de reproducción.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfBeginPath()](#EmfBeginPath--) | Inicializa una nueva instancia de la clase `EmfBeginPath`. |
### EmfBeginPath() {#EmfBeginPath--}
```
public EmfBeginPath()
```


Inicializa una nueva instancia de la clase `EmfBeginPath`.

