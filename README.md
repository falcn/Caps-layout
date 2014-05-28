Caps-layout
===========

Переключение между русской и английской раскладками клавишей Caps Lock в Mac OS X  

## Установка

[Скачать v1.0](https://github.com/falcn/Caps-layout/releases/download/v1.0/Caps-layout.dmg)

1. Скопировать `Lipton_u.bundle` в `/Library/Keyboard Layouts/`
2. Включить раскладку `Lipton_u` в настройках клавиатуры
3. Скопировать `Capster.app` и `Caps Lock fix.app` в `/Applications`
4. Добавить два вышеуказанных приложения в автозагрузку

## Содержимое

* `Lipton_u.bundle` - клавиатурная раскладка для Caps Lock
* `Capster.app` служит заменой системного индикатора раскладки, показывая, какая раскладка активна
* `Caps Lock fix.app` отключает защиту от случайных нажатий для клавиши Caps Lock


## Раскладка

В дополнение к стандартным добавлены украинские буквы

* `alt`-`и` for `і`
* `alt`-`й` for `ї`
* `alt`-`э` for `є`

## Иконки

По-умолчанию `Capster.app` идёт с парой затемнённых российской и американской иконок в наборе _Black App Icons_, которые хорошо смотрятся с 
[Obsidian menu bar](http://www.obsidianmenubar.com)  

`Shift`+`Caps` - вызвать опции Capster  
![Capster settings](img/capster_settings2.png)

![us](img/us.png)  
  
![ru](img/ru.png)  

Альтернативные иконки для кириллицы (необходимо заменить `Capster.app/Contents/Resources/capster_mini.png`)

![ua](img/ua.png)

![ua_](img/ua_.png)


## Прочее

Для защиты от случайных срабатываний кнопка Caps Lock имеет задержку на переключение режима.
Если в опциях клавиатуры выставить "Caps Lock key" в None, нажать "Ok", после чего снова выставить "Caps Lock key" в "Caps Lock", "Ok", задержка исчезает. Эффект держится до перезагрузки.  
`Caps Lock fix.app` делает это автоматически.

## Ссылки

Сделано на основе раскладки [Lipton](http://azaitsev.com/avt/caps_switch_macos.html)  
*Отличия: убраны growl уведомления, заменены иконки (+retina), добавлена двуязычная кириллическая раскладка.*

Использована иконка и идея из [bandera-layout](https://github.com/muromec/bandera-layout)
