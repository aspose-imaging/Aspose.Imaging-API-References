---
title: "EmfPlusSetTsGraphics"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EmfPlusSetTSGraphics указывает состояние контекста графического устройства для терминального сервера."
type: docs
weight: 67
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusSetTsGraphics extends EmfPlusTerminalServerRecordType
```

Запись EmfPlusSetTSGraphics указывает состояние контекста графического устройства для терминального сервера.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusSetTsGraphics(EmfPlusRecord source)](#EmfPlusSetTsGraphics-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Инициализирует новый экземпляр класса `EmfPlusSetTsGraphics`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getBasicVgaColors()](#getBasicVgaColors--) | Получает значение, указывающее, есть ли [basic vga colors]. |
| [getHavePalette()](#getHavePalette--) | Получает значение, указывающее, есть ли [have palette]. |
| [getAntiAliasMode()](#getAntiAliasMode--) | Получает или задает 8‑разрядное беззнаковое целое, определяющее качество отрисовки линий, включая тип сглаживания линий. |
| [setAntiAliasMode(byte value)](#setAntiAliasMode-byte-) | Получает или задает 8‑разрядное беззнаковое целое, определяющее качество отрисовки линий, включая тип сглаживания линий. |
| [getTextRenderHint()](#getTextRenderHint--) | Получает или задает 8‑разрядное беззнаковое целое, определяющее качество отрисовки текста, включая тип сглаживания текста. |
| [setTextRenderHint(byte value)](#setTextRenderHint-byte-) | Получает или задает 8‑разрядное беззнаковое целое, определяющее качество отрисовки текста, включая тип сглаживания текста. |
| [getCompositingMode()](#getCompositingMode--) | Получает или задает 8‑разрядное беззнаковое целое, определяющее способ комбинирования исходных цветов с фоновыми цветами. |
| [setCompositingMode(byte value)](#setCompositingMode-byte-) | Получает или задает 8‑разрядное беззнаковое целое, определяющее способ комбинирования исходных цветов с фоновыми цветами. |
| [getCompositingQuality()](#getCompositingQuality--) | Получает или задает 8‑разрядное беззнаковое целое, определяющее степень сглаживания, применяемую к линиям, кривым и краям заполненных областей, чтобы они выглядели более непрерывными или чётко определёнными. |
| [setCompositingQuality(byte value)](#setCompositingQuality-byte-) | Получает или задает 8‑разрядное беззнаковое целое, определяющее степень сглаживания, применяемую к линиям, кривым и краям заполненных областей, чтобы они выглядели более непрерывными или чётко определёнными. |
| [getRenderOriginX()](#getRenderOriginX--) | Получает или задает 16‑разрядное знаковое целое, представляющее горизонтальную координату начала для отрисовки полутоновых и дискретизирующих матриц. |
| [setRenderOriginX(short value)](#setRenderOriginX-short-) | Получает или задает 16‑разрядное знаковое целое, представляющее горизонтальную координату начала для отрисовки полутоновых и дискретизирующих матриц. |
| [getRenderOriginY()](#getRenderOriginY--) | Получает или задает 16‑разрядное знаковое целое, представляющее вертикальную координату начала для отрисовки полутоновых и дискретизирующих матриц. |
| [setRenderOriginY(short value)](#setRenderOriginY-short-) | Получает или задает 16‑разрядное знаковое целое, представляющее вертикальную координату начала для отрисовки полутоновых и дискретизирующих матриц. |
| [getTextContrast()](#getTextContrast--) | Получает или задает 16‑разрядное беззнаковое целое, определяющее значение гамма‑коррекции, используемое при отрисовке сглаженного и ClearType текста. |
| [setTextContrast(short value)](#setTextContrast-short-) | Получает или задает 16‑разрядное беззнаковое целое, определяющее значение гамма‑коррекции, используемое при отрисовке сглаженного и ClearType текста. |
| [getFilterType()](#getFilterType--) | Получает или задает 8‑разрядное беззнаковое целое, определяющее способ выполнения масштабирования, включая растягивание и сжатие. |
| [setFilterType(byte value)](#setFilterType-byte-) | Получает или задает 8‑разрядное беззнаковое целое, определяющее способ выполнения масштабирования, включая растягивание и сжатие. |
| [getPixelOffset()](#getPixelOffset--) | Получает или задает 8‑битное беззнаковое целое, которое определяет общее качество изображения и процесса отображения текста. |
| [setPixelOffset(byte value)](#setPixelOffset-byte-) | Получает или задает 8‑битное беззнаковое целое, которое определяет общее качество изображения и процесса отображения текста. |
| [getWorldToDevice()](#getWorldToDevice--) | Получает или задает 192‑битный объект EmfPlusTransformMatrix (раздел 2.2.2.47), который определяет преобразования из мирового пространства в пространство устройства. |
| [setWorldToDevice(Matrix value)](#setWorldToDevice-com.aspose.imaging.Matrix-) | Получает или задает 192‑битный объект EmfPlusTransformMatrix (раздел 2.2.2.47), который определяет преобразования из мирового пространства в пространство устройства. |
| [getPalette()](#getPalette--) | Получает или задает необязательный объект EmfPlusPalette. |
| [setPalette(EmfPlusPalette value)](#setPalette-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPalette-) | Получает или задает необязательный объект EmfPlusPalette. |
### EmfPlusSetTsGraphics(EmfPlusRecord source) {#EmfPlusSetTsGraphics-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetTsGraphics(EmfPlusRecord source)
```


Инициализирует новый экземпляр класса `EmfPlusSetTsGraphics`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Источник. |

### getBasicVgaColors() {#getBasicVgaColors--}
```
public boolean getBasicVgaColors()
```


Получает значение, указывающее, [basic vga colors]. Если установлено, палитра содержит только базовые цвета VGA.

Значение: `true`, если [basic vga colors]; иначе `false`.

**Returns:**
boolean
### getHavePalette() {#getHavePalette--}
```
public boolean getHavePalette()
```


Получает значение, указывающее, [have palette]. Если установлено, эта запись содержит объект EmfPlusPalette (раздел 2.2.2.28) в поле Palette после данных состояния графики.

Значение: `true`, если [have palette]; иначе `false`.

**Returns:**
boolean
### getAntiAliasMode() {#getAntiAliasMode--}
```
public byte getAntiAliasMode()
```


Получает или задает 8‑битное беззнаковое целое, которое определяет качество отрисовки линий, включая тип сглаживания линий. Оно ДОЛЖНО быть определено в перечислении SmoothingMode (раздел 2.1.1.28).

Значение: режим антиалиасинга.

**Returns:**
byte
### setAntiAliasMode(byte value) {#setAntiAliasMode-byte-}
```
public void setAntiAliasMode(byte value)
```


Получает или задает 8‑битное беззнаковое целое, которое определяет качество отрисовки линий, включая тип сглаживания линий. Оно ДОЛЖНО быть определено в перечислении SmoothingMode (раздел 2.1.1.28).

Значение: режим антиалиасинга.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getTextRenderHint() {#getTextRenderHint--}
```
public byte getTextRenderHint()
```


Получает или задает 8‑битное беззнаковое целое, которое определяет качество отображения текста, включая тип антиалиасинга текста. Оно ДОЛЖНО быть определено в перечислении TextRenderingHint (раздел 2.1.1.32).

Значение: подсказка рендеринга текста.

**Returns:**
byte
### setTextRenderHint(byte value) {#setTextRenderHint-byte-}
```
public void setTextRenderHint(byte value)
```


Получает или задает 8‑битное беззнаковое целое, которое определяет качество отображения текста, включая тип антиалиасинга текста. Оно ДОЛЖНО быть определено в перечислении TextRenderingHint (раздел 2.1.1.32).

Значение: подсказка рендеринга текста.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getCompositingMode() {#getCompositingMode--}
```
public byte getCompositingMode()
```


Получает или задает 8‑битное беззнаковое целое, которое определяет, как исходные цвета комбинируются с цветами фона. Оно ДОЛЖНО быть значением из перечисления CompositingMode (раздел 2.1.1.5).

Значение: режим композитинга.

**Returns:**
byte
### setCompositingMode(byte value) {#setCompositingMode-byte-}
```
public void setCompositingMode(byte value)
```


Получает или задает 8‑битное беззнаковое целое, которое определяет, как исходные цвета комбинируются с цветами фона. Оно ДОЛЖНО быть значением из перечисления CompositingMode (раздел 2.1.1.5).

Значение: режим композитинга.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getCompositingQuality() {#getCompositingQuality--}
```
public byte getCompositingQuality()
```


Получает или задает 8‑битное беззнаковое целое, которое определяет степень сглаживания, применяемую к линиям, кривым и краям заполненных областей, чтобы они выглядели более непрерывными или чётко определёнными. Оно ДОЛЖНО быть значением из перечисления CompositingQuality (раздел 2.1.1.6).

Значение: качество композитинга.

**Returns:**
byte
### setCompositingQuality(byte value) {#setCompositingQuality-byte-}
```
public void setCompositingQuality(byte value)
```


Получает или задает 8‑битное беззнаковое целое, которое определяет степень сглаживания, применяемую к линиям, кривым и краям заполненных областей, чтобы они выглядели более непрерывными или чётко определёнными. Оно ДОЛЖНО быть значением из перечисления CompositingQuality (раздел 2.1.1.6).

Значение: качество композитинга.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getRenderOriginX() {#getRenderOriginX--}
```
public short getRenderOriginX()
```


Получает или задает 16‑разрядное знаковое целое, представляющее горизонтальную координату начала для отрисовки полутоновых и дискретизирующих матриц.

Значение: координата x начала рендеринга.

**Returns:**
short
### setRenderOriginX(short value) {#setRenderOriginX-short-}
```
public void setRenderOriginX(short value)
```


Получает или задает 16‑разрядное знаковое целое, представляющее горизонтальную координату начала для отрисовки полутоновых и дискретизирующих матриц.

Значение: координата x начала рендеринга.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |

### getRenderOriginY() {#getRenderOriginY--}
```
public short getRenderOriginY()
```


Получает или задает 16‑разрядное знаковое целое, представляющее вертикальную координату начала для отрисовки полутоновых и дискретизирующих матриц.

Значение: координата y начала рендеринга.

**Returns:**
short
### setRenderOriginY(short value) {#setRenderOriginY-short-}
```
public void setRenderOriginY(short value)
```


Получает или задает 16‑разрядное знаковое целое, представляющее вертикальную координату начала для отрисовки полутоновых и дискретизирующих матриц.

Значение: координата y начала рендеринга.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |

### getTextContrast() {#getTextContrast--}
```
public short getTextContrast()
```


Получает или задает 16‑битное беззнаковое целое, которое определяет значение гамма‑коррекции, используемое при отрисовке антиалиасированного и ClearType текста. Это значение ДОЛЖНО находиться в диапазоне от 0 до 12 включительно.

Значение: контраст текста.

**Returns:**
short
### setTextContrast(short value) {#setTextContrast-short-}
```
public void setTextContrast(short value)
```


Получает или задает 16‑битное беззнаковое целое, которое определяет значение гамма‑коррекции, используемое при отрисовке антиалиасированного и ClearType текста. Это значение ДОЛЖНО находиться в диапазоне от 0 до 12 включительно.

Значение: контраст текста.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |

### getFilterType() {#getFilterType--}
```
public byte getFilterType()
```


Получает или задает 8‑битное беззнаковое целое, которое определяет, как выполняется масштабирование, включая растягивание и сжатие. Оно ДОЛЖНО быть значением из перечисления FilterType (раздел 2.1.1.11).

Значение: тип фильтра.

**Returns:**
byte
### setFilterType(byte value) {#setFilterType-byte-}
```
public void setFilterType(byte value)
```


Получает или задает 8‑битное беззнаковое целое, которое определяет, как выполняется масштабирование, включая растягивание и сжатие. Оно ДОЛЖНО быть значением из перечисления FilterType (раздел 2.1.1.11).

Значение: тип фильтра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getPixelOffset() {#getPixelOffset--}
```
public byte getPixelOffset()
```


Получает или задает 8‑битное беззнаковое целое, которое определяет общее качество изображения и процесса отображения текста. Оно ДОЛЖНО быть значением из перечисления PixelOffsetMode (раздел 2.1.1.26).

Значение: смещение пикселя.

**Returns:**
byte
### setPixelOffset(byte value) {#setPixelOffset-byte-}
```
public void setPixelOffset(byte value)
```


Получает или задает 8‑битное беззнаковое целое, которое определяет общее качество изображения и процесса отображения текста. Оно ДОЛЖНО быть значением из перечисления PixelOffsetMode (раздел 2.1.1.26).

Значение: смещение пикселя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getWorldToDevice() {#getWorldToDevice--}
```
public Matrix getWorldToDevice()
```


Получает или задает 192‑битный объект EmfPlusTransformMatrix (раздел 2.2.2.47), который определяет преобразования из мирового пространства в пространство устройства.

Значение: преобразование из мирового пространства в устройство.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setWorldToDevice(Matrix value) {#setWorldToDevice-com.aspose.imaging.Matrix-}
```
public void setWorldToDevice(Matrix value)
```


Получает или задает 192‑битный объект EmfPlusTransformMatrix (раздел 2.2.2.47), который определяет преобразования из мирового пространства в пространство устройства.

Значение: преобразование из мирового пространства в устройство.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getPalette() {#getPalette--}
```
public EmfPlusPalette getPalette()
```


Получает или задает необязательный объект EmfPlusPalette.

Значение: палитра.

**Returns:**
[EmfPlusPalette](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette)
### setPalette(EmfPlusPalette value) {#setPalette-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPalette-}
```
public void setPalette(EmfPlusPalette value)
```


Получает или задает необязательный объект EmfPlusPalette.

Значение: палитра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfPlusPalette](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette) |  |

