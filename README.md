## Распознование лиц

Данный скрипт позволит пользователю подключить веб камеру и разпознать лицо.

## Как установить

- Скачайте программу себе на компьютер.
- Создайте [виртуальное окружение](https://python-scripts.com/virtualenv) для проекта.
- Если вы используете macos, то обновите setup-tools перед установкой зависимостей.
```sh
pip3 install -U pip setuptools
```
- Установите зависимости.
```sh
pip install -r requirements.txt
```
- Если установка не получилась, попробуйте:
```sh
python3 -m pip install opencv-python --user
```
- Запустите скрипт.
```bash
python run.py
```
- Дайте доступ к вашей вебкамере. 

## Функционал

Позволяет распознать лица в вебкамере. Рисует квадрат при использовании вебкамеры, если распознает лицо.
Если вебкамера не найдена, то выдаст ошибку "Вэб камера не найдена ".

## Цель проекта

Код написан в образовательных целях на онлайн-курсе  для веб-разработчиков [Devman](https://dvmn.org).