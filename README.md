<img width="373" height="681" alt="{FFA72CB8-CCB1-44D1-B11F-2ECC0D5778BA}" src="https://github.com/user-attachments/assets/7b125101-9b98-4f48-9635-9fe5583be8ad" />

# OCRApp — распознавание русского текста

Android-приложение для распознавания русского текста с изображения с помощью **Tesseract OCR**.

## Возможности

- выбор изображения из галереи;
- фото через камеру;
- распознавание русского текста;
- вывод результата на экран;
- работа офлайн.

## Зависимость

В `app/build.gradle`:

```gradle
implementation 'cz.adaptech.tesseract4android:tesseract4android:4.9.0'
