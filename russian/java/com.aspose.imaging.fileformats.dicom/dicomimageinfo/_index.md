---
title: "DicomImageInfo"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Содержит всю метаинформацию из заголовка файла Dicom."
type: docs
weight: 14
url: /ru/java/com.aspose.imaging.fileformats.dicom/dicomimageinfo/
---
**Inheritance:**
java.lang.Object
```
public class DicomImageInfo
```

Содержит всю метаинформацию из заголовка файла Dicom.
## Методы

| Метод | Описание |
| --- | --- |
| [getDicomHeaderInfoByBytes()](#getDicomHeaderInfoByBytes--) | Получает информацию заголовка DICOM в виде байтов. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | Получает планарную конфигурацию. |
| [getSignedImage()](#getSignedImage--) | Получает значение, указывающее, является ли "signedImage". |
| [getDicomInfo()](#getDicomInfo--) | Получает информацию заголовка DICOM‑файла. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | Получает значение "samplesPerPixel". |
| [getBitsAllocated()](#getBitsAllocated--) | Получает значение "bitsAllocated". |
| [getBitsStored()](#getBitsStored--) | Получает количество сохранённых бит. |
| [getPhotoInterpretation()](#getPhotoInterpretation--) | Получает значение "PhotoInterpretation". |
| [getWidth()](#getWidth--) | Получает ширину. |
| [getHeight()](#getHeight--) | Получает высоту. |
| [getWindowCentre()](#getWindowCentre--) | Получает центр окна. |
| [getWindowWidth()](#getWindowWidth--) | Получает ширину окна. |
| [getPixelRepresentation()](#getPixelRepresentation--) | Получает значение пикселя "pixelRepresentation". |
| [getRescaleIntercept()](#getRescaleIntercept--) | Получает значение "rescaleIntercept". |
| [getRescaleSlope()](#getRescaleSlope--) | Получает значение "rescaleSlope". |
| [getNumberOfFrames()](#getNumberOfFrames--) | Получает количество кадров. |
| [isLittleEndian()](#isLittleEndian--) | Получает значение, указывающее, является ли этот экземпляр little endian. |
| [getReds()](#getReds--) | Получает массив цветов красного. |
| [getGreens()](#getGreens--) | Получает массив цветов зеленого. |
| [getBlues()](#getBlues--) | Получает массив цветов синего. |
| [getOffset()](#getOffset--) | Получает смещение. |
| [addTag(String tagDescription, Object value)](#addTag-java.lang.String-java.lang.Object-) | Добавить новый тег Dicom. |
| [tryAddTag(String tagDescription, Object value)](#tryAddTag-java.lang.String-java.lang.Object-) | Добавить новый тег Dicom. |
| [removeTagAt(int index)](#removeTagAt-int-) | Удалить существующий тег. |
| [tryRemoveTagAt(int index)](#tryRemoveTagAt-int-) | Удалить существующий тег. |
| [updateTagAt(int index, Object newValue)](#updateTagAt-int-java.lang.Object-) | Обновить существующий тег. |
| [tryUpdateTagAt(int index, Object newValue)](#tryUpdateTagAt-int-java.lang.Object-) | Обновить существующий тег. |
### getDicomHeaderInfoByBytes() {#getDicomHeaderInfoByBytes--}
```
public byte[] getDicomHeaderInfoByBytes()
```


Получает информацию заголовка DICOM в виде байтов.

Значение: Информация заголовка DICOM в виде байтов.

**Returns:**
byte[] — информация заголовка DICOM в виде байтов.
### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


Получает планарную конфигурацию.

Значение: Планарная конфигурация.

**Returns:**
int — планарная конфигурация.
### getSignedImage() {#getSignedImage--}
```
public boolean getSignedImage()
```


Получает значение, указывающее, является ли "signedImage".

**Returns:**
boolean — значение, указывающее, является ли "signedImage".
### getDicomInfo() {#getDicomInfo--}
```
public List<String> getDicomInfo()
```


Получает информацию заголовка DICOM‑файла.

**Returns:**
java.util.List<java.lang.String> - заголовочная информация DICOM‑файла.

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
//Идентификатор UID класса Media Storage Sop: 1.2.840.10008.5.1.4.1.1.3.1
//Идентификатор UID экземпляра Media Storage Sop: 2.16.840.1.114488.0.4.123489834087.1330071425.2
//Идентификатор UID синтаксиса передачи: 1.2.840.10008.1.2.4.70
//Идентификатор UID класса реализации: 1.2.840.114236
//Набор специфических символов: ISO_IR 100
//Тип изображения: \SECONDARY\INTRAOPERATIVE
//Идентификатор UID класса Sop: 1.2.840.10008.5.1.4.1.1.3.1
//Идентификатор UID экземпляра Sop: 2.16.840.1.114488.0.4.123489834087.1330071425.2
//Дата исследования: 20110824
//Дата серии: 20110824
//Дата контента: 20110824
//Время исследования: 094836.214743984
//Время серии: 094836.214743984
//Время контента: 100451.214743816
//Модальность: US
//Производитель: Medistim
//Название учреждения: Hospital Name
//Адрес учреждения: Hospital Address or Department
//Название станции: VERIQ
//Имя выполняющего врача: CA Prof. Debus
//Модель производителя: VeriQ C
//Рекомендуемая частота кадров отображения: 1
//Имя пациента: Femoral trombenarterectomy^Case Report:
//Идентификатор пациента: Отчет о случае 1
//Пол пациента: M
//Размер пациента: 0
//Вес пациента: 0
//Комментарии пациента: Смотрите отчет о случае на www.medistim.com
//Скорость Cine: 1
//Эффективная длительность: 1
//Серийный номер устройства: 0
//Версия(и) программного обеспечения: 3.3.0 RC0 построено 02 / 23 / 12  09:50:45
//Время кадра: 1000
//UID экземпляра исследования: 2.16.840.1.114488.0.4.123489834087.1330071425.0
//UID экземпляра серии: 2.16.840.1.114488.0.4.123489834087.1330071425.1
//Номер серии: 1
//Номер экземпляра: 1
//Отсчётов на пиксель: 3
//Фотометрическая интерпретация: RGB
//Плоская конфигурация: 0
//Количество кадров: 1
//Указатель инкремента кадра:
//Строки: 768
//Столбцы: 1024
//Битов выделено: 8
//Битов сохранено: 8
//Высший бит: 7
//Представление пикселя: 0
//Сжатие изображения с потерями: 00
//Данные пикселей: 1492
```

### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


Получает значение "samplesPerPixel".

Значение: Значение "samplesPerPixel".

**Returns:**
int - значение "samplesPerPixel".
### getBitsAllocated() {#getBitsAllocated--}
```
public int getBitsAllocated()
```


Получает значение "bitsAllocated".

Значение: Значение "bitsAllocated".

**Returns:**
int - значение "bitsAllocated".
### getBitsStored() {#getBitsStored--}
```
public int getBitsStored()
```


Получает количество сохранённых бит.

**Returns:**
int - количество сохранённых бит.
### getPhotoInterpretation() {#getPhotoInterpretation--}
```
public String getPhotoInterpretation()
```


Получает значение "PhotoInterpretation".

**Returns:**
java.lang.String - значение "PhotoInterpretation".
### getWidth() {#getWidth--}
```
public int getWidth()
```


Получает ширину.

Значение: Значение ширины.

**Returns:**
int - ширина.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Получает высоту.

Значение: Значение высоты.

**Returns:**
int - высота.
### getWindowCentre() {#getWindowCentre--}
```
public double getWindowCentre()
```


Получает центр окна.

Значение: Значение центра окна.

**Returns:**
double - центр окна.
### getWindowWidth() {#getWindowWidth--}
```
public double getWindowWidth()
```


Получает ширину окна.

Значение: Ширина окна.

**Returns:**
double - ширина окна.
### getPixelRepresentation() {#getPixelRepresentation--}
```
public int getPixelRepresentation()
```


Получает значение пикселя "pixelRepresentation".

Значение: Значение "pixelRepresentation".

**Returns:**
int - значение пикселя "pixelRepresentation".
### getRescaleIntercept() {#getRescaleIntercept--}
```
public double getRescaleIntercept()
```


Получает значение "rescaleIntercept".

Значение: Значение "rescaleIntercept".

**Returns:**
double - значение "rescaleIntercept".
### getRescaleSlope() {#getRescaleSlope--}
```
public double getRescaleSlope()
```


Получает значение "rescaleSlope".

Значение: Значение "rescaleSlope".

**Returns:**
double - значение "rescaleSlope".
### getNumberOfFrames() {#getNumberOfFrames--}
```
public int getNumberOfFrames()
```


Получает количество кадров.

Значение: Количество кадров.

**Returns:**
int - количество кадров.
### isLittleEndian() {#isLittleEndian--}
```
public boolean isLittleEndian()
```


Получает значение, указывающее, является ли этот экземпляр little endian.

Значение: `true`, если этот экземпляр использует порядок little endian; иначе `false`.

**Returns:**
boolean - значение, указывающее, использует ли этот экземпляр порядок little endian.
### getReds() {#getReds--}
```
public byte[] getReds()
```


Получает массив цветов красного.

Значение: Красные.

**Returns:**
byte[] - массив цветов красного
### getGreens() {#getGreens--}
```
public byte[] getGreens()
```


Получает массив цветов зеленого.

Значение: Цвет красного.

**Returns:**
byte[] - массив цветов зелёного
### getBlues() {#getBlues--}
```
public byte[] getBlues()
```


Получает массив цветов синего.

Значение: Синий.

**Returns:**
byte[] - массив цветов синего
### getOffset() {#getOffset--}
```
public int getOffset()
```


Получает смещение.

Значение: Значение смещения.

**Returns:**
int - смещение.
### addTag(String tagDescription, Object value) {#addTag-java.lang.String-java.lang.Object-}
```
public void addTag(String tagDescription, Object value)
```


Добавить новый тег Dicom.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| tagDescription | java.lang.String | Описание тега. Не может быть null или пустой строкой. |
| value | java.lang.Object | Значение тега. Не может быть null. |

### tryAddTag(String tagDescription, Object value) {#tryAddTag-java.lang.String-java.lang.Object-}
```
public boolean tryAddTag(String tagDescription, Object value)
```


Добавить новый тег Dicom.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| tagDescription | java.lang.String | Описание тега. Не может быть null или пустой строкой. |
| value | java.lang.Object | Значение тега. Не может быть null. |

**Returns:**
boolean - результат операции.
### removeTagAt(int index) {#removeTagAt-int-}
```
public void removeTagAt(int index)
```


Удалить существующий тег.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс тега, который будет обновлён. |

### tryRemoveTagAt(int index) {#tryRemoveTagAt-int-}
```
public boolean tryRemoveTagAt(int index)
```


Удалить существующий тег.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс тега, который будет обновлён. |

**Returns:**
boolean - результат операции.
### updateTagAt(int index, Object newValue) {#updateTagAt-int-java.lang.Object-}
```
public void updateTagAt(int index, Object newValue)
```


Обновить существующий тег.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс тега, который будет обновлён. |
| newValue | java.lang.Object | Значение тега. Не может быть null. |

### tryUpdateTagAt(int index, Object newValue) {#tryUpdateTagAt-int-java.lang.Object-}
```
public boolean tryUpdateTagAt(int index, Object newValue)
```


Обновить существующий тег.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс тега, который будет обновлён. |
| newValue | java.lang.Object | Значение тега. Не может быть null. |

**Returns:**
boolean - результат операции.
