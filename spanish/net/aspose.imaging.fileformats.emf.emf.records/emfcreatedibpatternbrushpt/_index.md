---
title: EmfCreateDibPatternBrushPt
second_title: Aspose.Imaging para la referencia de la API de .NET
description: El registro EMR_CREATEDIBPATTERNBRUSHPT define un pincel de motivo para operaciones gráficas. El patrón está especificado por un DIB.
type: docs
weight: 3490
url: /es/net/aspose.imaging.fileformats.emf.emf.records/emfcreatedibpatternbrushpt/
---
## EmfCreateDibPatternBrushPt class

El registro EMR_CREATEDIBPATTERNBRUSHPT define un pincel de motivo para operaciones gráficas. El patrón está especificado por un DIB.

```csharp
public sealed class EmfCreateDibPatternBrushPt : EmfObjectCreationRecordType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmfCreateDibPatternBrushPt](emfcreatedibpatternbrushpt#constructor)() | Inicializa una nueva instancia del[`EmfCreateDibPatternBrushPt`](../emfcreatedibpatternbrushpt) clase. |
| [EmfCreateDibPatternBrushPt](emfcreatedibpatternbrushpt#constructor_1)(EmfRecord) | Inicializa una nueva instancia del[`EmfCreateDibPatternBrushPt`](../emfcreatedibpatternbrushpt) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BitmapBuffer](../../aspose.imaging.fileformats.emf.emf.records/emfcreatedibpatternbrushpt/bitmapbuffer) { get; set; } | Obtiene o establece un búfer que contiene un DIB empaquetado en forma de objeto WMF DeviceIndependentBitmap ([MS-WMF] sección 2.2.2.9). No es necesario que sea contiguo a la parte fija del registro EMR_CREATEDIBPATTERNBRUSHPT. |
| [IhBrush](../../aspose.imaging.fileformats.emf.emf.records/emfcreatedibpatternbrushpt/ihbrush) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica el índice del objeto patrón brush en la tabla de objetos EMF (sección 3.1.1.1). Este índice DEBE guardarse para que este objeto pueda reutilizarse o modificarse. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Obtiene o establece el tamaño del registro |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Obtiene o establece el tipo. |
| [Usage](../../aspose.imaging.fileformats.emf.emf.records/emfcreatedibpatternbrushpt/usage) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica cómo interpretar los valores en la tabla color en el encabezado DIB. Este valor DEBE estar en la enumeración DIBColors (sección 2.1.9). |

### Observaciones

El objeto de pincel de motivo definido por este registro se puede seleccionar en el contexto del dispositivo de reproducción mediante un registro EMR_SELECTOBJECT (sección 2.3.8.5), que especifica el pincel de motivo que se usará en operaciones gráficas subsiguientes.

### Ver también

* class [EmfObjectCreationRecordType](../emfobjectcreationrecordtype)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->