---
title: FileStreamContainer
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Asistente para procesamiento de flujo de archivos.
type: docs
weight: 9300
url: /es/aspose.imaging/filestreamcontainer/
---
## FileStreamContainer class

Asistente para procesamiento de flujo de archivos.

```csharp
public sealed class FileStreamContainer : StreamContainer
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| virtual [CanRead](../../aspose.imaging/streamcontainer/canread) { get; } | Obtiene un valor que indica si la secuencia admite la lectura. |
| virtual [CanSeek](../../aspose.imaging/streamcontainer/canseek) { get; } | Obtiene un valor que indica si la secuencia admite la búsqueda. |
| virtual [CanWrite](../../aspose.imaging/streamcontainer/canwrite) { get; } | Obtiene un valor que indica si la secuencia admite escritura. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtiene un valor que indica si esta instancia se desecha. |
| [FilePath](../../aspose.imaging/filestreamcontainer/filepath) { get; } | Obtiene la ruta del archivo. |
| [IsCreated](../../aspose.imaging/filestreamcontainer/iscreated) { get; } | Obtiene un valor que indica si la secuencia se creó explícitamente. |
| virtual [IsStreamDisposedOnClose](../../aspose.imaging/streamcontainer/isstreamdisposedonclose) { get; } | Obtiene un valor que indica si esta secuencia se elimina al cerrar. |
| [IsTemporal](../../aspose.imaging/filestreamcontainer/istemporal) { get; set; } | Obtiene o establece un valor que indica si el flujo es temporal. |
| virtual [Length](../../aspose.imaging/streamcontainer/length) { get; set; } | Obtiene o establece la longitud del flujo en bytes. Este valor es menor que elLength por la posición inicial de flujo pasada en el constructor StreamContainer. |
| virtual [Position](../../aspose.imaging/streamcontainer/position) { get; set; } | Obtiene o establece la posición actual dentro de la secuencia. Este valor representa el desplazamiento desde la posición inicial de la secuencia pasada en el constructor StreamContainer. |
| virtual [Stream](../../aspose.imaging/streamcontainer/stream) { get; } | Obtiene el flujo de datos. |
| [SyncRoot](../../aspose.imaging/streamcontainer/syncroot) { get; } | Obtiene un objeto que se puede usar para sincronizar el acceso al recurso sincronizado. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [CreateFileStream](../../aspose.imaging/filestreamcontainer/createfilestream)(string, bool) | Crea una nueva secuencia de archivos. |
| static [OpenFileStream](../../aspose.imaging/filestreamcontainer/openfilestream)(string) | Abre un flujo de archivos existente. Si el flujo de archivos no existe, se lanza la excepción apropiada. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Elimina la instancia actual. |
| virtual [Flush](../../aspose.imaging/streamcontainer/flush)() | Borra todos los búferes de esta transmisión y hace que los datos almacenados en el búfer se escriban en el dispositivo subyacente. |
| virtual [Read](../../aspose.imaging/streamcontainer/read)(byte[]) | Lee bytes para llenar el búfer de bytes especificado. |
| virtual [Read](../../aspose.imaging/streamcontainer/read)(byte[], int, int) | Lee una secuencia de bytes del flujo actual y avanza la posición dentro del flujo según el número de bytes leídos. |
| virtual [ReadByte](../../aspose.imaging/streamcontainer/readbyte)() | Lee un byte de la secuencia y avanza la posición dentro de la secuencia en un byte, o devuelve -1 si está al final de la secuencia. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(Stream) | Guarda (copia) los datos del flujo en el flujo especificado. Utiliza el tamaño de búfer predeterminado[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount) y corriente[`Length`](../streamcontainer/length) valor. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string) | Guarda (copia) los datos del flujo en el flujo especificado. Utiliza el tamaño de búfer predeterminado[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount) y corriente[`Length`](../streamcontainer/length) valor. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(Stream, int) | Guarda (copia) todos los datos del flujo en el flujo especificado. corriente de usos[`Length`](../streamcontainer/length) valor. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string, int) | Guarda (copia) los datos del flujo en el flujo especificado. corriente de usos[`Length`](../streamcontainer/length) valor. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(Stream, int, long) | Guarda (copia) los datos del flujo en el flujo especificado. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string, int, long) | Guarda (copia) los datos del flujo en el flujo especificado. |
| virtual [Seek](../../aspose.imaging/streamcontainer/seek)(long, SeekOrigin) | Establece la posición dentro de la secuencia actual. |
| virtual [SeekBegin](../../aspose.imaging/streamcontainer/seekbegin)() | Establece la posición de la transmisión al comienzo de la transmisión. Este valor representa el desplazamiento desde la posición inicial de la secuencia pasada en el constructor StreamContainer. |
| virtual [ToBytes](../../aspose.imaging/streamcontainer/tobytes)() | Convierte los datos de flujo alByte matriz. |
| virtual [ToBytes](../../aspose.imaging/streamcontainer/tobytes)(long, long) | Convierte los datos de flujo alByte matriz. |
| virtual [Write](../../aspose.imaging/streamcontainer/write)(byte[]) | Escribe todos los bytes especificados en la secuencia. |
| virtual [Write](../../aspose.imaging/streamcontainer/write)(byte[], int, int) | Escribe una secuencia de bytes en el flujo actual y avanza la posición actual dentro de este flujo según el número de bytes escritos. |
| virtual [WriteByte](../../aspose.imaging/streamcontainer/writebyte)(byte) | Escribe un byte en la posición actual en la secuencia y avanza la posición dentro de la secuencia en un byte. |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto)(StreamContainer) | Copia los datos contenidos a otro[`StreamContainer`](../streamcontainer) . |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto)(StreamContainer, long) | Copia los datos contenidos a otro[`StreamContainer`](../streamcontainer) . |
| [explicit operator](../../aspose.imaging/filestreamcontainer/op_explicit#op_explicit_1) | Realiza una conversión explícita de[`FileStreamContainer`](../filestreamcontainer) aStream . (2 operators) |

### Ver también

* class [StreamContainer](../streamcontainer)
* espacio de nombres [Aspose.Imaging](../../aspose.imaging)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
