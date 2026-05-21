---
title: "EmfColorMatchToTargetW"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_COLORMATCHTOTargetW определяет, следует ли выполнять сопоставление цветов с профилем цвета, указанным в файле, имя которого состоит из символов Unicode."
type: docs
weight: 24
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfColorMatchToTargetW extends EmfStateRecordType
```

Запись EMR\_COLORMATCHTOTargetW определяет, следует ли выполнять сопоставление цветов с цветовым профилем, указанным в файле, имя которого состоит из символов Unicode.

Запись EMR\_COLORMATCHTOTargetW может использоваться для управления тем, применять ли текущую цветовую трансформацию в контексте устройства воспроизведения. Если значение dwAction равно CS\_ENABLE, сопоставление цветов включено, и текущая цветовая трансформация ДОЛЖНА применяться к последующим графическим операциям. Если dwAction установлено в CS\_DISABLE, цветовая трансформация НЕ ДОЛЖНА применяться. Пока сопоставление цветов с целью включено значением dwAction CS\_ENABLE, изменения цветового пространства или сопоставления цветового охвата не применяются. Однако эти изменения ДОЛЖНЫ вступить в силу, когда сопоставление цветов с целью отключено. Поле dwAction НЕ ДОЛЖНО быть установлено в CS\_DELETE\_TRANSFORM, если только управление цветом уже не было включено записью EMR\_SETICMMODE (раздел 2.3.11.14).
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfColorMatchToTargetW(EmfRecord source)](#EmfColorMatchToTargetW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfColorMatchToTargetW`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getDwAction()](#getDwAction--) | Получает или задаёт 32‑битное беззнаковое целое, которое указывает значение из перечисления ColorSpace (раздел 2.1.7). |
| [setDwAction(int value)](#setDwAction-int-) | Получает или задаёт 32‑битное беззнаковое целое, которое указывает значение из перечисления ColorSpace (раздел 2.1.7). |
| [getDwFlags()](#getDwFlags--) | Получает или задаёт 32‑битное беззнаковое целое, которое указывает значение из перечисления ColorMatchToTarget (раздел 2.1.6). |
| [setDwFlags(int value)](#setDwFlags-int-) | Получает или задаёт 32‑битное беззнаковое целое, которое указывает значение из перечисления ColorMatchToTarget (раздел 2.1.6). |
| [getCbName()](#getCbName--) | Получает или задаёт 32‑битное беззнаковое целое, которое указывает количество байт в имени профиля цвета в кодировке Unicode UTF16-LE. |
| [setCbName(int value)](#setCbName-int-) | Получает или задаёт 32‑битное беззнаковое целое, которое указывает количество байт в имени профиля цвета в кодировке Unicode UTF16-LE. |
| [getCbData()](#getCbData--) | Получает или задаёт 32‑битное беззнаковое целое, которое указывает размер необработанных данных целевого профиля цвета, если они содержатся в поле Data. |
| [setCbData(int value)](#setCbData-int-) | Получает или задаёт 32‑битное беззнаковое целое, которое указывает размер необработанных данных целевого профиля цвета, если они содержатся в поле Data. |
| [getData()](#getData--) | Получает или задает массив размером (cbName + cbData) в байтах, который указывает имя в кодировке UTF16-LE и необработанные данные желаемого цветового профиля. |
| [setData(byte[] value)](#setData-byte---) | Получает или задает массив размером (cbName + cbData) в байтах, который указывает имя в кодировке UTF16-LE и необработанные данные желаемого цветового профиля. |
| [getName()](#getName--) | Получает имя |
| [getRawData()](#getRawData--) | Получает необработанные данные |
### EmfColorMatchToTargetW(EmfRecord source) {#EmfColorMatchToTargetW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfColorMatchToTargetW(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfColorMatchToTargetW`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### getDwAction() {#getDwAction--}
```
public int getDwAction()
```


Получает или задаёт 32‑битное беззнаковое целое, которое указывает значение из перечисления ColorSpace (раздел 2.1.7).

**Returns:**
int
### setDwAction(int value) {#setDwAction-int-}
```
public void setDwAction(int value)
```


Получает или задаёт 32‑битное беззнаковое целое, которое указывает значение из перечисления ColorSpace (раздел 2.1.7).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getDwFlags() {#getDwFlags--}
```
public int getDwFlags()
```


Получает или задаёт 32‑битное беззнаковое целое, которое указывает значение из перечисления ColorMatchToTarget (раздел 2.1.6).

**Returns:**
int
### setDwFlags(int value) {#setDwFlags-int-}
```
public void setDwFlags(int value)
```


Получает или задаёт 32‑битное беззнаковое целое, которое указывает значение из перечисления ColorMatchToTarget (раздел 2.1.6).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getCbName() {#getCbName--}
```
public int getCbName()
```


Получает или задаёт 32‑битное беззнаковое целое, которое указывает количество байт в имени профиля цвета в кодировке Unicode UTF16-LE.

**Returns:**
int
### setCbName(int value) {#setCbName-int-}
```
public void setCbName(int value)
```


Получает или задаёт 32‑битное беззнаковое целое, которое указывает количество байт в имени профиля цвета в кодировке Unicode UTF16-LE.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getCbData() {#getCbData--}
```
public int getCbData()
```


Получает или задаёт 32‑битное беззнаковое целое, которое указывает размер необработанных данных целевого профиля цвета, если они содержатся в поле Data.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


Получает или задаёт 32‑битное беззнаковое целое, которое указывает размер необработанных данных целевого профиля цвета, если они содержатся в поле Data.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Получает или задает массив размером (cbName + cbData) в байтах, который указывает имя в кодировке UTF16-LE и необработанные данные желаемого цветового профиля.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Получает или задает массив размером (cbName + cbData) в байтах, который указывает имя в кодировке UTF16-LE и необработанные данные желаемого цветового профиля.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

### getName() {#getName--}
```
public String getName()
```


Получает имя

**Returns:**
java.lang.String
### getRawData() {#getRawData--}
```
public byte[] getRawData()
```


Получает необработанные данные

**Returns:**
byte[]
