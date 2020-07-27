##### NB! THIS FIRMWARE IS NOT FOR COMMERCIAL USE!!! DO NOT BUY ANY ESP DEVICE WITH THIS FW - IT'S 3-4 TIMES MORE EXPENSIVE THAN THE DEVICE ITSELF!!! JUST BUY ESP8266 AND FLASH IT BY YOURSELF!!! 

##### NB! ПРЕДСТАВЛЕННАЯ ЗДЕСЬ ПРОШИВКА НЕ ДЛЯ КОММЕРЧЕСКОГО ИСПОЛЬЗОВАНИЯ!!! НЕ ПОКУПАЙТЕ МОДУЛЬ С ДАННОЙ ПРОШИВКОЙ - ОН СТОИТ В 3-4 РАЗА ДОРОЖЕ, ЧЕМ САМО УСТРОЙСТВО!!! ПРОСТО КУПИТЕ ESP8266 И ПРОШЕЙТЕ ЕГО САМОСТОЯТЕЛЬНО!!!

## PS4 Payloads Host Firmware for ESP8266 (OFW 6.72)
## Прошивка ESP8266 для хоста пэйлоадов PS4 (ПО 6.72) (описание на русском смотрите ниже)

Here you can find ESP8266 custom firmware for hosting PS 4 payloads for 6.72 OFW. It is simple and light firmware without any tools like autopayload, firmware upgrade, ftp server for uploading files, etc. 

**The payloads list:**

    HEN (No HB)
    PS4JB (Sleirsgoevy)
    App2Usb
    BackUp
    Bin Loader
    Dumper
    Disable/Enable Updates
    FTP
        
*Payload version/description is indicated in "About" section*

**Cache**

Payload can be used in offline mode - just click "CACHE" and all the contents will be cached in PS4 system. Now you can turn off "Connect to the Internet" and run payloads as usually (works via user's guide/browser).


**Useful Tips:**
1. HEN is unstable in general, you should individually fit together optimal conditions for achieving system stability (waiting some minutes before payload run, closing all apps, navigating in the menu, etc.)
2. It's better to create permanent bookmark for offline mode, for example, /13.13.13.1/index.html

### COMMON    
**PS4 Wi-Fi Settings (EASY):**

    Network: PS4
    Password: qwertyuiop

*"Test internet connection" also passes successfully with such settings!*


Upload firmware in .bin format via NodeMCU-PyFlasher 3.0 (added screenshot with NodeMCU-PyFlasher settings in "release" page )

### CREDITS TO:

Al-Azif, Specter, Qwertyoruiopz, Flatz, XVortex, Sleirsgoevy, Stooged, LightningMods, Anonymous, Marcelstoer, EdiTzZ, Zer0xFF, Leeful, The Open Orbis team, SISTRo, etc.

## Прошивка ESP8266 для хоста пэйлоадов PS4 (ПО 6.72)
Данный репозиторий содержит прошивку для модуля ESP8266 с поднятием веб-сервера для хоста эксплоитов/пэйлоадов Playstation 4 с ПО 6.72. Данная прошивка отличается простым и легким интерфейсом и не содержит никаких дополнительных утилит, например, автозагрузка пэйлоада, обновление прошивки, ФТП сервер для загрузки файлов и т.д.

**Список пэйлоадов:**

    HEN (No HB)
    PS4JB (Sleirsgoevy)
    App2Usb
    BackUp
    Bin Loader
    Dumper
    Disable/Enable Updates
    FTP
    
*Версия/описание пэйлоада указано в разделе "About"*


**Кэш**

Пэйлоады можно использовать в оффлайн режиме - для этого нажмите "CACHE" и все содержимое закэшируется в консоль. Теперь Вы можете отключить "Подключить к интернету" и запускать пэйлоады как обычно (работает через руководство пользователя/браузер).


**Полезные советы для:**
1. Сам по себе HEN достаточно нестабилен, Вам самим предстоит подобрать наиболее оптимальные условия, при которых достигается общая стабильность системы (подождать пару минут перед запуском пэйлоада, закрыть все приложения, "побродить" по меню и т.д.)
2. Для использования оффлайн режима лучше создать постоянную закладку, например, /13.13.13.1/index.html


### ОБЩИЕ    
**Настройки PS4 Wi-Fi (метод подключения - ПРОСТОЙ):**

    Сеть: PS4
    Пароль: qwertyuiop

*С данными настройками так же успешно проходится тест на подключение к интернету!*

Прошивка предоставляется в формате bin для заливки в модуль с помощью NodeMCU-PyFlasher 3.0 (в разделе "релиз" добавлен скриншот с настройками NodeMCU-PyFlasher)

### ОСОБАЯ БЛАГОДАРНОСТЬ РАЗРАБОТЧИКАМ:

Al-Azif, Specter, Qwertyoruiopz, Flatz, XVortex, Sleirsgoevy, Stooged, LightningMods, Anonymous, Marcelstoer, EdiTzZ, Zer0xFF, Leeful, The Open Orbis team, SISTRo, etc.
