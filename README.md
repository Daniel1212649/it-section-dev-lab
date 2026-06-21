# Короткая шпаргалка

| Термин | Описание |
|--------|----------|
| конфликт | Git не смог сам объединить изменения |
| rebase | переносит коммиты поверх новой базы |
| cherry-pick | переносит один выбранный коммит |
| revert | отменяет коммит новым коммитом |
| stash | временно прячет изменения |

## Основные команды:
git status
git rebase main
git rebase --continue
git rebase --abort
git cherry-pick a1b2c3d
git cherry-pick --abort
git revert a1b2c3d
git revert --abort
git stash
git stash list
git stash pop

---
# Задание: пройти один Git-сценарий

1. В main добавь строку в README.md и сделай коммит.
2. Создай ветку feature/conflict.
3. Измени ту же строку и сделай коммит.
4. Вернись в main, измени эту строку иначе и сделай коммит.
5. Выполни git merge feature/conflict.
6. Изучи конфликт через git status.
7. Исправь файл, выполни git add README.md и заверши merge.
8. Создай еще одно изменение и спрячь его через git stash.
9. Верни его через git stash pop.
10. Создай тестовый коммит и отмени его через git revert.

После каждого шага проверяй состояние:
git status
git log --oneline --graph --decorate

# Задание 1 мы выполнили во время linux-practice :-)
