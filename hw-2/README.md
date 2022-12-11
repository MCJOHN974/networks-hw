- Реализован поиск минимального MTU в канале между локальным пользователем и хостом
- код обёрнут в docker контейнер
- так же присутствует возможность отдельно запустить скрипт на intel mac или ubuntu

### Тестирование:
клонируем репозиторий
```
$ git clone git@github.com:evlampiy-lavrentiev/hse-networks-hw.git
$ cd hw-2
```

сборка и запуск докер-контейнера
```
$ docker build . -f Dockerfile -t MTU-finder
$ docker run MTU-finder
```

