
# SkillFactory (проектная работа 2)

**Адрес репозитория:** [sf_project2](https://github.com/cheremisam/sf_project2)

**Изменения вносим по GitHub Flow:** Под каждую задачу создается отдельная ветка, вливаем в Main через Pull Request

**Правила именования веток:**
 - feature/trello-123 - ветка для разработки нового функционала;
 - fix/trello-123 - ветка для исправление ошибок.

**Пример настроек Git:** [git_config.txt](https://github.com/cheremisam/sf_project2/blob/main/git_config.txt)

**Пример по работе над новой задачей:**
 1. Переключаемся в ветку main: git switch main
 2. Получаем последниеизменения из ветки main: git pull origin main 
 3. Создаем новую ветку и переключаемся на нее: git switch -c feature/trello-123
 4. Code...
 5. Добавляем свои измененения в индекс: git add . 
 6. Делаем фиксацию: git commit -m "feature/trello-123 Краткий комментарий о внесенных изменениях"
 7. Отправляем изменения в удаленный репозиторий: git push origin Название_вашей_ветки
 8. Заходим врепозиторий gitHub и создаем запрос на слиеяние (Pull Request)