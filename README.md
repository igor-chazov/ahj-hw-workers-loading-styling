# WebWorkers, ServiceWorkers

[![Build status](https://ci.appveyor.com/api/projects/status/10hvh5cibnoapu4y?svg=true)](https://ci.appveyor.com/project/igor-chazov/ahj-hw-workers-loading-styling) [[Github Pages](https://igor-chazov.github.io/ahj-hw-workers-loading-styling)]

---

### Loading Styling

#### Легенда

Сейчас модно показывать интерфейсы загрузки вроде следующего:

![](./pic/loading.png)

#### Описание

Реализуйте подобный интерфейс, закешировав статические ресурсы и показывая данный внешний вид до момента загрузки данных.

Обратите внимание, даже если у пользователя нет подключения, страница всё равно должна отображаться, но в режиме "загрузки" и после неудачной попытки соединения переходить в режим:

![](./pic/loading-2.png)

Для эмуляции задержки можете самостоятельно написать middleware для koa, или посмотреть на существующие вроде [koa-slow](https://github.com/bahmutov/koa-slow)

Напоминаем, что для кэширования вы можете воспользоваться плагином Workbox.

---