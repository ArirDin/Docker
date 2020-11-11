# Запуск
1. Переходим в папку в которую хотим установить и скачиваем файлы:
    
    git clone https://github.com/ArirDin/Docker.git
    
2. В проекте перезодим в папку apache.

3. Собираем контейнер.

    docker-compose build

4. Запускаем контейнер.

    docker-compose up
    
5. Заходим в браузер по внешнему адресу 80 порта терминала.

# Выход

1. Нажимаем в консоли Ctrl+C и останавливаем контейнер.

    docker-compose stop

2. Удаляем.

    docker-compose rm
