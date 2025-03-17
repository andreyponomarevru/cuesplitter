**RU**

CLI-приложение для разрезания аудио на отдельные треки по CUE-файлу. Формат получаемых файлов всегда FLAC.
Функционал:

* Поддерживает FLAC, APE, WV, WAV
* При разрезании, заполняет все ID3v2 теги данными из CUE
* Поддерживает CUE-файлы с кириллицей
* Обнаруживает и предупреждает, если есть проблемы с pre-gap'ом

---

**EN**

CLI app for splitting audio files based on a provided CUE sheet. The output files format is always FLAC.

* Supports FLAC, APE, WV, WAV
* Fills all ID3v2 tags with info from the CUE
* Supports CUE files with cyrillics
* Warns about pre-gap problems if any

For more info issue `cuesplitter -h`.
