<p align="center">
  <img src="https://i.imgur.com/ZcxzsEg.png" width="281.5" height="103"/>
</p>

[![Swift 4.0](https://img.shields.io/badge/Swift-4.0-orange.svg)](https://swift.org)
[![Build Status](https://travis-ci.org/alfa-laboratory/YARCH-Examples.svg?branch=master)](https://travis-ci.org/alfa-laboratory/YARCH-Examples)
[![codecov](https://codecov.io/gh/alfa-laboratory/YARCH-Examples/branch/master/graph/badge.svg)](https://codecov.io/gh/alfa-laboratory/YARCH-Examples)

YARCH – это архитектурный паттерн для iOS, созданный в Альфа-Банке. Все вопросы можно задать в [Telegram](https://t.me/yarch_ios).

## Общая схема
![](YARCH-scheme.png)

Прочитать про компоненты YARCH можно [здесь](https://github.com/alfa-laboratory/YARCH-Examples/blob/master/GUIDE-rus.md).

## Создание нового модуля
Для генерации модулей используется [generamba](https://github.com/rambler-digital-solutions/Generamba). Каталог шаблонов:
```
https://github.com/alfa-laboratory/YARCH-Template
```

Перед первым созданием модуля необходимо установить шаблоны:
```
generamba template install
```

Для создания нового модуля нужно воспользоваться командой:
```
generamba gen [MODULE_NAME] yarch --description 'Предназначение вашего модуля в одном предложении.'
```

Лицензия
--------

© 2017 Альфа-Банк. Код лицензирован MIT.
