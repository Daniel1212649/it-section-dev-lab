# Как проходить практику

Репозиторий хранит условия заданий. Ваши решения и история обучения остаются в
вашем Fork.

## 1. Создайте и клонируйте Fork

На странице репозитория нажмите `Fork`, затем выполните:

```bash
git clone https://github.com/<ваш-username>/it-section-dev-lab.git
cd it-section-dev-lab
```

## 2. Выберите задание

Откройте директорию [tasks](tasks/README.md) и прочитайте условие выбранной
темы целиком.

## 3. Создайте отдельную ветку

```bash
git switch -c practice/01-linux
```

Примеры имён:

```text
practice/01-linux
practice/02-git
practice/03-api
```

Не выполняйте задания напрямую в `main`.

## 4. Подготовьте директорию решения

```bash
mkdir -p solutions/01-linux
```

Сохраняйте там команды, код, результаты и файл `README.md` с выводами. Не
изменяйте исходное условие в `tasks/` ради выполнения личного задания.

## 5. Делайте понятные коммиты

```text
docs: add Linux command notes
feat: add API contract example
test: add storage tests
fix: correct URL validation
```

Один коммит должен описывать одно логическое изменение.

## 6. Отправьте ветку в свой Fork

```bash
git push -u origin practice/01-linux
```

Pull Request в основной репозиторий для личного решения открывать не нужно.

## 7. Поделитесь результатом

Опубликуйте ссылку на ветку в Telegram или GitHub Discussions:

```text
Задание:
Ссылка на решение:
Что получилось:
Что было сложно:
Что понял после практики:
```

## Как получать новые задания

Через GitHub можно нажать `Sync fork`. Для синхронизации из терминала один раз
добавьте основной репозиторий как `upstream`:

```bash
git remote add upstream https://github.com/Daniel1212649/it-section-dev-lab.git
```

Затем периодически обновляйте свой `main`:

```bash
git fetch upstream
git switch main
git merge --ff-only upstream/main
git push origin main
```

Если `merge --ff-only` завершился ошибкой, не используйте `force push`. Сначала
проверьте `git status` и сравните историю своего Fork с `upstream/main`.
