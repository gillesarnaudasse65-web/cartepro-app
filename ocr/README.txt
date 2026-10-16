CartePro local text recognition

The French (fra) and English (eng) LSTM models come from:
https://github.com/tesseract-ocr/tessdata_fast
https://raw.githubusercontent.com/tesseract-ocr/tessdata_fast/main/fra.traineddata
https://raw.githubusercontent.com/tesseract-ocr/tessdata_fast/main/eng.traineddata
Downloaded 2026-10-16. Distributed under Apache License 2.0.
Models are gzip-compressed for delivery, decoded by Tesseract.js.

The build copies the worker from pinned tesseract.js and the WebAssembly
runtime from the lockfile-pinned tesseract.js-core installation.
Recognition runs on the user's device; card images are not sent to an OCR API.
