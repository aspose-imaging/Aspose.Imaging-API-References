---
title: "DicomImageInfo"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Contiene toda la metainformación del encabezado del archivo Dicom."
type: docs
weight: 14
url: /es/java/com.aspose.imaging.fileformats.dicom/dicomimageinfo/
---
**Inheritance:**
java.lang.Object
```
public class DicomImageInfo
```

Contiene toda la metainformación del encabezado del archivo Dicom.
## Métodos

| Método | Descripción |
| --- | --- |
| [getDicomHeaderInfoByBytes()](#getDicomHeaderInfoByBytes--) | Obtiene la información del encabezado DICOM en bytes. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | Obtiene la configuración planar. |
| [getSignedImage()](#getSignedImage--) | Obtiene un valor que indica si "signedImage". |
| [getDicomInfo()](#getDicomInfo--) | Obtiene la información de encabezado del archivo DICOM. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | Obtiene un valor de "samplesPerPixel". |
| [getBitsAllocated()](#getBitsAllocated--) | Obtiene un valor de "bitsAllocated". |
| [getBitsStored()](#getBitsStored--) | Obtiene el número de bits almacenados. |
| [getPhotoInterpretation()](#getPhotoInterpretation--) | Obtiene un valor de "PhotoInterpretation". |
| [getWidth()](#getWidth--) | Obtiene el ancho. |
| [getHeight()](#getHeight--) | Obtiene la altura. |
| [getWindowCentre()](#getWindowCentre--) | Obtiene el centro de la ventana. |
| [getWindowWidth()](#getWindowWidth--) | Obtiene el ancho de la ventana. |
| [getPixelRepresentation()](#getPixelRepresentation--) | Obtiene un valor del píxel "pixelRepresentation". |
| [getRescaleIntercept()](#getRescaleIntercept--) | Obtiene un valor de "rescaleIntercept". |
| [getRescaleSlope()](#getRescaleSlope--) | Obtiene un valor de "rescaleSlope". |
| [getNumberOfFrames()](#getNumberOfFrames--) | Obtiene el número de fotogramas. |
| [isLittleEndian()](#isLittleEndian--) | Obtiene un valor que indica si esta instancia es little endian. |
| [getReds()](#getReds--) | Obtiene el array de colores del rojo |
| [getGreens()](#getGreens--) | Obtiene el array de colores del verde |
| [getBlues()](#getBlues--) | Obtiene el array de colores del azul |
| [getOffset()](#getOffset--) | Obtiene el desplazamiento. |
| [addTag(String tagDescription, Object value)](#addTag-java.lang.String-java.lang.Object-) | Agrega una nueva etiqueta Dicom. |
| [tryAddTag(String tagDescription, Object value)](#tryAddTag-java.lang.String-java.lang.Object-) | Agrega una nueva etiqueta Dicom. |
| [removeTagAt(int index)](#removeTagAt-int-) | Elimina una etiqueta existente. |
| [tryRemoveTagAt(int index)](#tryRemoveTagAt-int-) | Elimina una etiqueta existente. |
| [updateTagAt(int index, Object newValue)](#updateTagAt-int-java.lang.Object-) | Actualiza una etiqueta existente. |
| [tryUpdateTagAt(int index, Object newValue)](#tryUpdateTagAt-int-java.lang.Object-) | Actualiza una etiqueta existente. |
### getDicomHeaderInfoByBytes() {#getDicomHeaderInfoByBytes--}
```
public byte[] getDicomHeaderInfoByBytes()
```


Obtiene la información del encabezado DICOM en bytes.

Valor: La información de encabezado dicom en bytes.

**Returns:**
byte[] - la información de encabezado dicom en bytes.
### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


Obtiene la configuración planar.

Valor: La configuración planar.

**Returns:**
int - la configuración planar.
### getSignedImage() {#getSignedImage--}
```
public boolean getSignedImage()
```


Obtiene un valor que indica si "signedImage".

**Returns:**
boolean - un valor que indica si "signedImage".
### getDicomInfo() {#getDicomInfo--}
```
public List<String> getDicomInfo()
```


Obtiene la información de encabezado del archivo DICOM.

**Returns:**
java.util.List<java.lang.String> - la información de encabezado del archivo DICOM.

**Example: The following example shows how to read the header information of a DICOM image.**

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1489\\";
com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "ttfm.dcm");
try {
    for (String s : image.getFileInfo().getDicomInfo()) {
        System.out.println(s);
    }
}
finally {
    image.close();
}

// STDOUT:
//Identificador de clase SOP de almacenamiento de medios: 1.2.840.10008.5.1.4.1.1.3.1
//Identificador de instancia SOP de almacenamiento de medios: 2.16.840.1.114488.0.4.123489834087.1330071425.2
//Identificador de sintaxis de transferencia: 1.2.840.10008.1.2.4.70
//Identificador de clase de implementación: 1.2.840.114236
//Conjunto de caracteres específico: ISO_IR 100
//Tipo de imagen: \\SECONDARY\\INTRAOPERATIVE
//Identificador de clase SOP: 1.2.840.10008.5.1.4.1.1.3.1
//Identificador de instancia SOP: 2.16.840.1.114488.0.4.123489834087.1330071425.2
//Fecha del estudio: 20110824
//Fecha de la serie: 20110824
//Fecha del contenido: 20110824
//Hora del estudio: 094836.214743984
//Hora de la serie: 094836.214743984
//Hora del contenido: 100451.214743816
//Modalidad: US
//Fabricante: Medistim
//Nombre de la institución: Hospital Name
//Dirección de la institución: Hospital Address or Department
//Nombre de la estación: VERIQ
//Nombre del médico que realiza el procedimiento: CA Prof. Debus
//Nombre del modelo del fabricante: VeriQ C
//Frecuencia de fotogramas recomendada para visualización: 1
//Nombre del paciente: Femoral trombenarterectomy^Case Report:
//Identificación del paciente: Informe de caso 1
//Sexo del paciente: M
//Tamaño del paciente: 0
//Peso del paciente: 0
//Comentarios del paciente: Ver informe de caso en www.medistim.com
//Frecuencia de cine: 1
//Duración efectiva: 1
//Número de serie del dispositivo: 0
//Versión(es) de software: 3.3.0 RC0 compilada 02 / 23 / 12  09:50:45
//Tiempo de cuadro: 1000
//UID de instancia del estudio: 2.16.840.1.114488.0.4.123489834087.1330071425.0
//UID de instancia de la serie: 2.16.840.1.114488.0.4.123489834087.1330071425.1
//Número de serie: 1
//Número de instancia: 1
//Muestras por píxel: 3
//Interpretación fotométrica: RGB
//Configuración planar: 0
//Número de cuadros: 1
//Puntero de incremento de cuadro:
//Filas: 768
//Columnas: 1024
//Bits asignados: 8
//Bits almacenados: 8
//Bit alto: 7
//Representación de píxel: 0
//Compresión de Imagen con Pérdida: 00
//Datos de Píxel: 1492
```

### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


Obtiene un valor de "samplesPerPixel".

Valor: El valor de "samplesPerPixel".

**Returns:**
int - un valor de "samplesPerPixel".
### getBitsAllocated() {#getBitsAllocated--}
```
public int getBitsAllocated()
```


Obtiene un valor de "bitsAllocated".

Valor: El valor de "bitsAllocated".

**Returns:**
int - un valor de "bitsAllocated".
### getBitsStored() {#getBitsStored--}
```
public int getBitsStored()
```


Obtiene el número de bits almacenados.

**Returns:**
int - el número de bits almacenados.
### getPhotoInterpretation() {#getPhotoInterpretation--}
```
public String getPhotoInterpretation()
```


Obtiene un valor de "PhotoInterpretation".

**Returns:**
java.lang.String - un valor de "PhotoInterpretation".
### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtiene el ancho.

Valor: El valor del ancho.

**Returns:**
int - el ancho.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtiene la altura.

Valor: El valor de la altura.

**Returns:**
int - la altura.
### getWindowCentre() {#getWindowCentre--}
```
public double getWindowCentre()
```


Obtiene el centro de la ventana.

Valor: El valor del centro de la ventana.

**Returns:**
double - el centro de la ventana.
### getWindowWidth() {#getWindowWidth--}
```
public double getWindowWidth()
```


Obtiene el ancho de la ventana.

Valor: El ancho de la ventana.

**Returns:**
double - el ancho de la ventana.
### getPixelRepresentation() {#getPixelRepresentation--}
```
public int getPixelRepresentation()
```


Obtiene un valor del píxel "pixelRepresentation".

Valor: El valor de "pixelRepresentation".

**Returns:**
int - un valor del píxel "pixelRepresentation".
### getRescaleIntercept() {#getRescaleIntercept--}
```
public double getRescaleIntercept()
```


Obtiene un valor de "rescaleIntercept".

Valor: El valor de "rescaleIntercept".

**Returns:**
double - un valor de "rescaleIntercept".
### getRescaleSlope() {#getRescaleSlope--}
```
public double getRescaleSlope()
```


Obtiene un valor de "rescaleSlope".

Valor: El valor de "rescaleSlope".

**Returns:**
double - un valor de "rescaleSlope".
### getNumberOfFrames() {#getNumberOfFrames--}
```
public int getNumberOfFrames()
```


Obtiene el número de fotogramas.

Valor: El número de fotogramas.

**Returns:**
int - el número de fotogramas.
### isLittleEndian() {#isLittleEndian--}
```
public boolean isLittleEndian()
```


Obtiene un valor que indica si esta instancia es little endian.

Valor: `true` si esta instancia es little endian; de lo contrario, `false`.

**Returns:**
boolean - un valor que indica si esta instancia es little endian.
### getReds() {#getReds--}
```
public byte[] getReds()
```


Obtiene el array de colores del rojo

Valor: Los rojos.

**Returns:**
byte[] - la matriz de colores del rojo
### getGreens() {#getGreens--}
```
public byte[] getGreens()
```


Obtiene el array de colores del verde

Valor: El color rojo.

**Returns:**
byte[] - la matriz de colores del verde
### getBlues() {#getBlues--}
```
public byte[] getBlues()
```


Obtiene el array de colores del azul

Valor: Los azules.

**Returns:**
byte[] - la matriz de colores del azul
### getOffset() {#getOffset--}
```
public int getOffset()
```


Obtiene el desplazamiento.

Valor: El valor del desplazamiento.

**Returns:**
int - el desplazamiento.
### addTag(String tagDescription, Object value) {#addTag-java.lang.String-java.lang.Object-}
```
public void addTag(String tagDescription, Object value)
```


Agrega una nueva etiqueta Dicom.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tagDescription | java.lang.String | La descripción de la etiqueta. No puede ser nula o estar vacía. |
| valor | java.lang.Object | El valor de la etiqueta. No puede ser nulo. |

### tryAddTag(String tagDescription, Object value) {#tryAddTag-java.lang.String-java.lang.Object-}
```
public boolean tryAddTag(String tagDescription, Object value)
```


Agrega una nueva etiqueta Dicom.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tagDescription | java.lang.String | La descripción de la etiqueta. No puede ser nula o estar vacía. |
| valor | java.lang.Object | El valor de la etiqueta. No puede ser nulo. |

**Returns:**
boolean - El resultado de la operación.
### removeTagAt(int index) {#removeTagAt-int-}
```
public void removeTagAt(int index)
```


Elimina una etiqueta existente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice de la etiqueta a actualizar. |

### tryRemoveTagAt(int index) {#tryRemoveTagAt-int-}
```
public boolean tryRemoveTagAt(int index)
```


Elimina una etiqueta existente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice de la etiqueta a actualizar. |

**Returns:**
boolean - El resultado de la operación.
### updateTagAt(int index, Object newValue) {#updateTagAt-int-java.lang.Object-}
```
public void updateTagAt(int index, Object newValue)
```


Actualiza una etiqueta existente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice de la etiqueta a actualizar. |
| newValue | java.lang.Object | El valor de la etiqueta. No puede ser nulo. |

### tryUpdateTagAt(int index, Object newValue) {#tryUpdateTagAt-int-java.lang.Object-}
```
public boolean tryUpdateTagAt(int index, Object newValue)
```


Actualiza una etiqueta existente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice de la etiqueta a actualizar. |
| newValue | java.lang.Object | El valor de la etiqueta. No puede ser nulo. |

**Returns:**
boolean - El resultado de la operación.
