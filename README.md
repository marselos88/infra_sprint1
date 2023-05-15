# Kittygram — социальная сеть для обмена фотографиями любимых питомцев. Это полностью рабочий проект, который состоит из бэкенд-приложения на Django и фронтенд-приложения на React.

Используя приложение можно сохранять информацию о домашних питомцах, загружать фотографии. Приложение имеет вэб-интерфейс и API. 

Запуск проекта backend:
1. Клонируйте проект с github по ssh *git clone git@github.com/marselos88/infra_sprint1.git*
2. При необходимости установите и активируйте виртуально окружение в директории проекта *python3 -m venv venv source venv/bin/activate*
3. Установите зависимости *pip install -r requirements.txt*
4. Произведите миграции *python manage.py migrate*
5. Запуск backend осуществляется командой *python manage.py runserver*

Запуск проекта frontend:
1. Установите пакетный менеджер npm
2. Установите зависимости для фронтенд-приложения, для этого нужно перейти в директорию frontend/ и дать команду *npm i*
3. Запуск frontend осуществляется командой *npm run start*

Для взаимодействия с приложением через API предусмотрены следующие методы:
1.
2.
