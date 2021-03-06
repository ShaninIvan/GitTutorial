## Что такое Git и GitHub

[Содержание](./readme.md)
[Вперед -->](./2_Install_Git.md)

---

**Система контроля версий** — специальное программное обеспечение, которое записывает изменения в файлы в течение времени, 
позволяет работать с разными их версиями, в том числе нескольким людям одновременно. 

Система контроля версий может быть:
* Локальная — файлы хранятся на одном компьютере. Примером такой системы может быть резервное хранилище Windows, из которого система в
случае ошибки может восстановить прежние версии файлов.

* Централизованная — этот вид СКВ возник от необходимости разработчиков взаимодействовать друг с другом. При этом подходе все файлы
хранятся на центральном сервере, а клиенты (разработчики) получают все файлы от него и сохраняют на нем же. Опасность такого подхода
состоит в том, что при выходе сервера из строя, доступ к файлам теряют все. 

* Распределенная — при таком подходе клиенты получают не просто снимок (состояние файлов на определённый момент времени), а копируют
репозиторий целиком. Даже если какой-то сервер отключится, работа может быть продолжена только на репозиториях клиентов. Самой
популярной распределенной СКВ является *Git*.

**Git** — распределённая система управления версиями. Проект был создан Линусом Торвальдсом для управления разработкой ядра Linux,
 первая версия выпущена 7 апреля 2005 года. На сегодняшний день его поддерживает Джунио Хамано.
На сегодняшний день, GIT — это одна из самых известных систем контроля версий с открытым исходным кодом, 
на которую полагаются миллионы проектов по всем миру. Кроме локальных СКВ существуют глобальные хостинги, выполняющие такие же функции,
наример *GitHub*.

**GitHub** — сервис онлайн-хостинга репозиториев, обладающий всеми функциями распределённого контроля версий и функциональностью 
управления исходным кодом — всё, что поддерживает Git и даже больше. Обычно он используется вместе с Git и даёт разработчикам 
возможность сохранять их код онлайн, а затем взаимодействовать с другими разработчиками в разных проектах.

---
[Содержание](./readme.md)
[Вперед -->](./2_Install_Git.md)

