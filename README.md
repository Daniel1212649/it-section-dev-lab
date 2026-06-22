# IT Section Developer Growth Lab

Публичный репозиторий с практическими заданиями по backend-разработке.

Здесь теория закрепляется руками: через отдельные ветки, небольшие коммиты,
эксперименты и собственные выводы. Условия заданий хранятся в `main`, а решения
каждого участника — в его Fork.

## Что изучаем

- Linux и инструменты разработчика
- Git и командная работа
- API и взаимодействие сервисов
- TCP, UDP, HTTP и TLS
- REST, gRPC и WebSocket
- базы данных и транзакции
- тестирование, Docker и CI/CD
- брокеры сообщений, кеширование и observability
- Kubernetes и распределенные системы

Текущий прогресс находится в [ROADMAP.md](ROADMAP.md).

## Практические задания

| № | Тема | Задание |
|---:|---|---|
| 01 | Linux и работа с файлами | [Открыть](tasks/01-linux/README.md) |
| 02 | Git: конфликты и безопасная работа с историей | [Открыть](tasks/02-git/README.md) |
| 03 | Основы API | [Открыть](tasks/03-api/README.md) |

Все задания находятся в директории [tasks](tasks/README.md).

## Как начать

1. Сделайте Fork репозитория.
2. Клонируйте свой Fork.
3. Выберите задание в `tasks/`.
4. Создайте ветку `practice/<номер>-<тема>`.
5. Создайте директорию решения в `solutions/<номер>-<тема>`.
6. Выполните задание и сохраните процесс небольшими коммитами.
7. Отправьте ветку в свой Fork и поделитесь ссылкой.

```bash
git clone https://github.com/<ваш-username>/it-section-dev-lab.git
cd it-section-dev-lab
git switch -c practice/01-linux
mkdir -p solutions/01-linux
```

Подробная инструкция: [PRACTICE_GUIDE.md](PRACTICE_GUIDE.md).

> Не отправляйте личные решения Pull Request в основной репозиторий. Каждый
> участник хранит свою работу и историю коммитов в собственном Fork.

## Когда нужен Pull Request

Pull Request в основной репозиторий нужен, если вы:

- исправляете ошибку или неточность;
- улучшаете документацию;
- предлагаете новое задание;
- добавляете тесты;
- улучшаете общий код проекта.

Перед участием прочитайте [CONTRIBUTING.md](CONTRIBUTING.md).

## Навигация

| Файл | Назначение |
|---|---|
| [ROADMAP.md](ROADMAP.md) | Темы и прогресс |
| [PRACTICE_GUIDE.md](PRACTICE_GUIDE.md) | Как выполнять задания |
| [CONTRIBUTING.md](CONTRIBUTING.md) | Правила Pull Requests |
| [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) | Правила общения |
| [SECURITY.md](SECURITY.md) | Безопасность и секреты |

## Автор и материалы

- Telegram: [IT Section](https://t.me/itsectionbrilliant)
- Habr: [Daniel Syrov](https://habr.com/ru/users/DanielSyrov/)
- GitHub: [Daniel1212649](https://github.com/Daniel1212649)

## Главный принцип

Не коллекционировать технологии, а понимать, как они работают, где полезны и
как ведут себя в реальных системах.
