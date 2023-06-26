# MelTake
> десктопное приложение для проигрывания и визуализации музыки

**Возможности пользователя:** 
- Использование базовых возможностей музыкального плеера (play, stop, повторение трека/плейлиста, следующий/предыдущий трек, изменение громкости)
- Встроенная визуализация музыки
- Создание собственных плейлистов
- Использование горячих клавиш для базовых функций

![ghost_icon](https://github.com/B-E-D-A/audio-app-MelTake/assets/112130616/96c7d71a-d39c-4777-8bf6-d56edbb25ed7)

# Инструкция по сборке

1) Установить Qt 5.15.2 вместе с модулем Qt Multimedia
1) Скачать и скомпилировать библиотеки taglib 1.13 и fftw 3.3.10
1) В qmake_project.pro файле указать пути до файлов библиотек:
	- `TAGLIB_LIB_PATH` - путь до папки с .dll.a файлами библиотеки
	- `FFTW_LIB_PATH` - путь до папки с .dll файлами библиотеки
	- `TAGLIB_INCLUDE_PATH`, `FFTW_INCLUDE_PATH` - пути до папок с заголовочными файлами соответствующих библиотек
1) В `PATH` добавить пути до .dll файлов библиотек, либо скопировать их в папку, гле будет лежать скомпилированная программа
1) Компилируем проект либо в Qt Creator, либо в командной строке:
	```
	qmake
	make
	```
# Вид приложения

 ![image](https://github.com/B-E-D-A/audio-app-MelTake/assets/112130616/49c3dd5d-c366-402b-9c7c-544f5561094d) 
 ![image](https://github.com/B-E-D-A/audio-app-MelTake/assets/112130616/d827d023-f691-4508-8539-83600a85d687) 

 
