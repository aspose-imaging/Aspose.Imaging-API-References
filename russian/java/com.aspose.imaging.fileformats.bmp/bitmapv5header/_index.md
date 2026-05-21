---
title: "BitmapV5Header"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Структура BitmapV5Header является файлом заголовка информации о битмапе."
type: docs
weight: 14
url: /ru/java/com.aspose.imaging.fileformats.bmp/bitmapv5header/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.bmp.BitmapCoreHeader](../../com.aspose.imaging.fileformats.bmp/bitmapcoreheader), [com.aspose.imaging.fileformats.bmp.BitmapInfoHeader](../../com.aspose.imaging.fileformats.bmp/bitmapinfoheader), [com.aspose.imaging.fileformats.bmp.BitmapV4Header](../../com.aspose.imaging.fileformats.bmp/bitmapv4header)
```
public class BitmapV5Header extends BitmapV4Header
```

Структура BitmapV5Header является файлом заголовка информации битмапа. Это расширенная версия структуры BITMAPINFOHEADER.

Если bV5Height отрицателен, указывая на DIB с верх‑вниз ориентацией, bV5Compression должен быть либо BI\\_RGB, либо BI\\_BITFIELDS. DIB с верх‑вниз ориентацией нельзя сжимать. Интерфейс Independent Color Management (ICM) 2.0 позволяет профилям цветов International Color Consortium (ICC) быть связанными или встроенными в DIB (DIB). См. Using Structures для получения дополнительной информации. Когда DIB загружается в память, данные профиля (если они присутствуют) должны следовать за таблицей цветов, и bV5ProfileData должен указывать смещение данных профиля от начала структуры BITMAPV5HEADER. Значение, хранящееся в bV5ProfileData, будет отличаться от значения, возвращаемого оператором sizeof для аргумента BITMAPV5HEADER, поскольку bV5ProfileData — это смещение в байтах от начала структуры BITMAPV5HEADER до начала данных профиля. (Биты битмапа не следуют за таблицей цветов в памяти). Приложения должны изменять член bV5ProfileData после загрузки DIB в память. Для упакованных DIB данные профиля должны следовать за битами битмапа аналогично файловому формату. Член bV5ProfileData всё равно должен указывать смещение данных профиля от начала BITMAPV5HEADER. Приложения должны обращаться к данным профиля только когда bV5Size равно размеру BITMAPV5HEADER и bV5CSType равно PROFILE\\_EMBEDDED или PROFILE\\_LINKED.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [BitmapV5Header()](#BitmapV5Header--) | Инициализирует новый экземпляр класса `BitmapV5Header`. |
| [BitmapV5Header(byte[] bytes)](#BitmapV5Header-byte---) | Инициализирует новый экземпляр класса `BitmapV5Header`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getIntent()](#getIntent--) | Получает цель рендеринга для битмапа. |
| [setIntent(long value)](#setIntent-long-) | Задаёт цель рендеринга для битмапа. |
| [getProfileData()](#getProfileData--) | Получает данные профиля. |
| [setProfileData(long value)](#setProfileData-long-) | Задаёт данные профиля. |
| [getProfileSize()](#getProfileSize--) | Получает размер профиля. |
| [setProfileSize(long value)](#setProfileSize-long-) | Задаёт размер профиля. |
| [getReserved()](#getReserved--) | Получает зарезервированный член. |
| [setReserved(long value)](#setReserved-long-) | Задаёт зарезервированный член. |
### BitmapV5Header() {#BitmapV5Header--}
```
public BitmapV5Header()
```


Инициализирует новый экземпляр класса `BitmapV5Header`.

### BitmapV5Header(byte[] bytes) {#BitmapV5Header-byte---}
```
public BitmapV5Header(byte[] bytes)
```


Инициализирует новый экземпляр класса `BitmapV5Header`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| байты | byte[] | Байты. |

### getIntent() {#getIntent--}
```
public long getIntent()
```


Получает цель рендеринга для битмапа.

**Returns:**
long - цель.
### setIntent(long value) {#setIntent-long-}
```
public void setIntent(long value)
```


Задаёт цель рендеринга для битмапа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long | Цель. |

### getProfileData() {#getProfileData--}
```
public long getProfileData()
```


Получает данные профиля.

**Returns:**
long - Данные профиля.
### setProfileData(long value) {#setProfileData-long-}
```
public void setProfileData(long value)
```


Задаёт данные профиля.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long | Данные профиля. |

### getProfileSize() {#getProfileSize--}
```
public long getProfileSize()
```


Получает размер профиля.

**Returns:**
long - Размер профиля.
### setProfileSize(long value) {#setProfileSize-long-}
```
public void setProfileSize(long value)
```


Задаёт размер профиля.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long | Размер профиля. |

### getReserved() {#getReserved--}
```
public long getReserved()
```


Получает зарезервированный член.

**Returns:**
long - Зарезервированное значение.
### setReserved(long value) {#setReserved-long-}
```
public void setReserved(long value)
```


Задаёт зарезервированный член.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long | Зарезервированное значение. |

