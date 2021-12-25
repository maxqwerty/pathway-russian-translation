# Pathway Russian Translation

Перевод на русский игры Pathway

https://store.steampowered.com/app/546430/Pathway/

Отказ от прав:

Pathway принадлежит [Robotality](http://robotality.com/blog/about/)

Этот перевод не принадлежить никому.

* * *

Rusian translation for Pathway game

https://store.steampowered.com/app/546430/Pathway/

Disclaimer:

[Robotality](http://robotality.com/blog/about/) owns Pathway

No one owns this translation.

# Как установить

Папку ru-RU поместить в папке с игрой по пути:
<ПУТЬ_К_ПАПКЕ_ИГРЫ>/i18n/

В этой же папке есть дургие переводы:
- de-DE
- en-US
- fr-FR
- ja-JP
- zh-CN

Предположительно, сейчас у вас стоит английский язык, поэтому следующей нах достаточно проделать только для файла в папке **en-US**:

- открываем файл GameUI.json
- ищем строку, в которой есть **GameOptions_Language_en-us**
- после блока фигурных скобок вставляем информацию о русском языке так, чтобы получилось примерно так:
```
	{
		"id": "GameOptions_Language_en-us",
		"text": "English"
	},
	{
		"id": "GameOptions_Language_ru-ru",
		"text": "Русский"
	},
	{
		"id": "GameOptions_Language_de-de",
		"text": "Deutsch"
	},
```
- следим, чтобы все запятые были на месте!

Теперь можно запускать игру и в настройках выбирать язык "Русский".
