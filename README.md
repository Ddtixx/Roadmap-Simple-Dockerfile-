Создание образа для простого Dockerfile, содержащего минимально-необходимое окружение alpine, а также команду 'echo' в EXEC формате, поскольку не запускает лишний shell
Для создания образа необходимо ввести:
```bash
   docker build -t hello-captain . 
   ```
Для запуска контейнера по заданному образу:
```basj 
   docker run --rm hello-captain
   ```
Ожидаемый вывод:
```bash
   Hello, Captain!
   ```
URL Project: https://roadmap.sh/projects/basic-dockerfile
