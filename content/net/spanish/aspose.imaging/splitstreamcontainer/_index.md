---
title: SplitStreamContainer
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Representa el contenedor de flujo dividido que contiene el flujo y proporciona rutinas de procesamiento de flujo.
type: docs
weight: 11120
url: /es/aspose.imaging/splitstreamcontainer/
---
## SplitStreamContainer class

Representa el contenedor de flujo dividido que contiene el flujo y proporciona rutinas de procesamiento de flujo.

```csharp
public class SplitStreamContainer : StreamContainer
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SplitStreamContainer](splitstreamcontainer#constructor_1)(Stream) | Inicializa una nueva instancia del[`SplitStreamContainer`](../splitstreamcontainer) clase. |
| [SplitStreamContainer](splitstreamcontainer#constructor_2)(Stream, bool) | Inicializa una nueva instancia del[`SplitStreamContainer`](../splitstreamcontainer) clase. |
| [SplitStreamContainer](splitstreamcontainer#constructor)(StreamContainer, bool) | Inicializa una nueva instancia del[`SplitStreamContainer`](../splitstreamcontainer) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| override [CanRead](../../aspose.imaging/splitstreamcontainer/canread) { get; } | Obtiene un valor que indica si la secuencia admite la lectura. |
| override [CanSeek](../../aspose.imaging/splitstreamcontainer/canseek) { get; } | Obtiene un valor que indica si la secuencia admite la búsqueda. |
| override [CanWrite](../../aspose.imaging/splitstreamcontainer/canwrite) { get; } | Obtiene un valor que indica si la secuencia admite escritura. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtiene un valor que indica si esta instancia se desecha. |
| virtual [IsStreamDisposedOnClose](../../aspose.imaging/streamcontainer/isstreamdisposedonclose) { get; } | Obtiene un valor que indica si esta secuencia se elimina al cerrar. |
| override [Length](../../aspose.imaging/splitstreamcontainer/length) { get; set; } | Obtiene o establece la longitud del flujo en bytes. Este valor es menor que elLength por la posición inicial de flujo pasada en el constructor StreamContainer. |
| override [Position](../../aspose.imaging/splitstreamcontainer/position) { get; set; } | Obtiene o establece la posición actual dentro de la secuencia. Este valor representa el desplazamiento desde la posición inicial de la secuencia pasada en el constructor StreamContainer. |
| override [Stream](../../aspose.imaging/splitstreamcontainer/stream) { get; } | Obtiene el flujo de datos. |
| [SyncRoot](../../aspose.imaging/splitstreamcontainer/syncroot) { get; } | Obtiene un objeto que se puede usar para sincronizar el acceso al recurso sincronizado. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Elimina la instancia actual. |
| override [Flush](../../aspose.imaging/splitstreamcontainer/flush)() | Borra todos los búferes de esta transmisión y hace que los datos almacenados en el búfer se escriban en el dispositivo subyacente. |
| [Insert](../../aspose.imaging/splitstreamcontainer/insert)(int, StreamContainer, bool) | Inserta el contenedor de flujo en la posición especificada. |
| override [Read](../../aspose.imaging/splitstreamcontainer/read#read)(byte[]) | Lee bytes para llenar el búfer de bytes especificado. |
| override [Read](../../aspose.imaging/splitstreamcontainer/read#read_1)(byte[], int, int) | Lee una secuencia de bytes del flujo actual y avanza la posición dentro del flujo según el número de bytes leídos. |
| override [ReadByte](../../aspose.imaging/splitstreamcontainer/readbyte)() | Lee un byte de la secuencia y avanza la posición dentro de la secuencia en un byte, o devuelve -1 si está al final de la secuencia. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(Stream) | Guarda (copia) los datos del flujo en el flujo especificado. Utiliza el tamaño de búfer predeterminado[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount) y corriente[`Length`](../streamcontainer/length) valor. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string) | Guarda (copia) los datos del flujo en el flujo especificado. Utiliza el tamaño de búfer predeterminado[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount) y corriente[`Length`](../streamcontainer/length) valor. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(Stream, int) | Guarda (copia) todos los datos del flujo en el flujo especificado. corriente de usos[`Length`](../streamcontainer/length) valor. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string, int) | Guarda (copia) los datos del flujo en el flujo especificado. corriente de usos[`Length`](../streamcontainer/length) valor. |
| override [Save](../../aspose.imaging/splitstreamcontainer/save#save_2)(Stream, int, long) | Guarda (copia) los datos del flujo en el flujo especificado. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string, int, long) | Guarda (copia) los datos del flujo en el flujo especificado. |
| override [Seek](../../aspose.imaging/splitstreamcontainer/seek)(long, SeekOrigin) | Establece la posición dentro de la secuencia actual. |
| override [SeekBegin](../../aspose.imaging/splitstreamcontainer/seekbegin)() | Establece la posición de la transmisión al comienzo de la transmisión. Este valor representa el desplazamiento desde la posición inicial de la secuencia pasada en el constructor StreamContainer. |
| override [ToBytes](../../aspose.imaging/splitstreamcontainer/tobytes#tobytes)() | Convierte los datos de flujo alByte matriz. |
| override [ToBytes](../../aspose.imaging/splitstreamcontainer/tobytes#tobytes_1)(long, long) | Convierte los datos de flujo alByte matriz. |
| override [Write](../../aspose.imaging/splitstreamcontainer/write#write)(byte[]) | Escribe todos los bytes especificados en la secuencia. |
| override [Write](../../aspose.imaging/splitstreamcontainer/write#write_1)(byte[], int, int) | Escribe una secuencia de bytes en el flujo actual y avanza la posición actual dentro de este flujo según el número de bytes escritos. |
| override [WriteByte](../../aspose.imaging/splitstreamcontainer/writebyte)(byte) | Escribe un byte en la posición actual en la secuencia y avanza la posición dentro de la secuencia en un byte. |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto)(StreamContainer) | Copia los datos contenidos a otro[`StreamContainer`](../streamcontainer) . |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto)(StreamContainer, long) | Copia los datos contenidos a otro[`StreamContainer`](../streamcontainer) . |

### Ver también

* class [StreamContainer](../streamcontainer)
* espacio de nombres [Aspose.Imaging](../../aspose.imaging)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
