Скрипт автоматически обновляет нужную вкладку в браузере каждые 5 секунд (при желании можно посылать эмуляцию нужных клавиш и в другие программы).
Для использования скрипта потребуется AHK, можно скачать на официальном сайте https://www.autohotkey.com/.
1. Чтобы нужная вкладка в браузере обновлялась автоматически, нужно указать её название в коде, в качестве примера указана «Новая вкладка — Google Chrome».
<img src="https://github.com/f1eshDK/F5/blob/main/screenshots/ahk_code.png">
Название можно узнать с помощью скрипта «Window Spy», устанавливается вместе с AHK, найти его можно в папке, где установлен AHK. <img src="https://github.com/f1eshDK/F5/blob/main/screenshots/WinSpy_AHK.png">
Запускаем скрипт «Window Spy» и переходим на нужную вкладку <img src="https://github.com/f1eshDK/F5/blob/main/screenshots/browser.png">
После чего смотрим, какое название у вкладки в скрипте «Window Spy» <img src="https://github.com/f1eshDK/F5/blob/main/screenshots/WinSpy_1.png">
И заменяем в коде «Новая вкладка — Google Chrome» на полученное название <img src="https://github.com/f1eshDK/F5/blob/main/screenshots/WinSpy_1.png">

3. Чтобы изменить время, через сколько будет обновляться страница, указываем нужное значение в миллисекундах (1000 — это 1 секунда) в «Sleep».
4. Чтобы изменить клавишу остановки скрипта, указываем перед «::Pause» название клавиши (название клавиши можно посмотреть тут https://ahk-wiki.ru/keylist).
