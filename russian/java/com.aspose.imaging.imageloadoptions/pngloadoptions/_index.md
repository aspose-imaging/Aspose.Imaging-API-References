---
title: "PngLoadOptions"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Параметры загрузки png."
type: docs
weight: 18
url: /ru/java/com.aspose.imaging.imageloadoptions/pngloadoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.LoadOptions](../../com.aspose.imaging/loadoptions)
```
public class PngLoadOptions extends LoadOptions
```

Параметры загрузки png.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PngLoadOptions()](#PngLoadOptions--) | Инициализирует новый экземпляр класса `PngLoadOptions`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getStrictMode()](#getStrictMode--) | Получает или задает значение, указывающее, включён ли [strict mode]. |
| [setStrictMode(boolean value)](#setStrictMode-boolean-) | Получает или задает значение, указывающее, включён ли [strict mode]. |
### PngLoadOptions() {#PngLoadOptions--}
```
public PngLoadOptions()
```


Инициализирует новый экземпляр класса `PngLoadOptions`.

### getStrictMode() {#getStrictMode--}
```
public boolean getStrictMode()
```


Получает или задает значение, указывающее, включён ли [strict mode].

**Returns:**
boolean - значение, указывающее, включён ли [strict mode].
### setStrictMode(boolean value) {#setStrictMode-boolean-}
```
public void setStrictMode(boolean value)
```


Получает или задает значение, указывающее, включён ли [strict mode].

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | значение, указывающее, включён ли [strict mode]. |


**Example: The following example shows how to read PNG file : a strict mode.**
В следующем примере показано, как читать PNG‑файл: строгий режим. Строгий режим позволяет находить потенциальные проблемы: PNG‑изображения, например нераспознанные блоки данных, неожиданное окончание файла. Такие файлы всё ещё могут быть открыты: режим по умолчанию (non‑strict) с помощью Aspose.Imaging и обычных просмотрщиков. Однако любые попытки открыть их: строгий режим вызывают соответствующее исключение.
``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1442\\";
String inputImage = dir + "FC5F1998104EB92469CB14070628073616BB28F9.png";
String outputImage = inputImage + ".png";

// Режим по умолчанию (non‑strict) — успешное чтение.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputImage);
try {
    image.save(outputImage, new com.aspose.imaging.imageoptions.PngOptions());
}
finally {
    image.close();
}

// Строгий режим — ImageLoadException: неожиданное окончание файла.
com.aspose.imaging.Image image2 = com.aspose.imaging.Image.load(inputImage, new com.aspose.imaging.imageloadoptions.PngLoadOptions() {{
    setStrictMode(true);
    }});
                
try {
    image2.save(outputImage, new com.aspose.imaging.imageoptions.PngOptions());
}
finally {
    image2.close();
}
```

