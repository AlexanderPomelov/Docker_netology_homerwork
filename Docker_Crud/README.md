## Сборка образа

```docker build --tag [IMAGE] [PATH] ```

Данная команда собирает образ контейнера.

В **[IMAGE]** подставить свое название образа.

В **[PATH]** указать путь до файла Dockerfile 

## Запуск контейнера 

```docker run -d -p 9000:8000  --name=[CONTAIER] [IMAGE]```

Данная команда запускает контейнер. 

В **[CONTAIER]** подставить имя контейнера.

В **[IMAGE]** подставить имя которое указали при создании образа.