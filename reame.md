
## Императивный подход

Для выполнения определенных действий вводятся определенные команды (например создание контейнера **docker run..., docker build...**)

#### Одно команда - одно действие

## Декларативный подход 

Абстрагирование от отдельных команд и создание инструкции более высокого уровня.

Нет необходимости запускать каждый контейнер по отдельности

Один конфигурационный файл, который запускает все сразу

#### Одна команда - много действий


## Преимущества Docker compose

- Декларативный подход к созданию контейнеров
- Все необходимые контейнеры запускаются одной командой
- Автоматическое создание необходимых образов на основании Dockerfile каждого приложения
- Автоматическое создание изолированной сети для взаимодействия контейнеров
- Благодаря DNS возможно взаимодействие между контейнерами, используя имена сервисов