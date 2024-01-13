### Домашнее задание 3.14.1 (HW-01) курса PHP-Pro (Skillfactory)

Автор: Александр Климок / [kydechuk01](https://github.com/kydechuk01/)

---

[<<< К оглавлению](./README.md#оглавление) 

### Команда git status

Команда, которую дает пользователь, чтобы проверить текущее состояния проиндексированных файлов проекта в рабочей директории. Обычно используется перед созданием нового *коммита*.

#### Варианты использования:
- `git status`

#### Результат
Выводит текущую ветку в репозитории проекта. Перечисляет файлы, которые были или еще не были проиндексированы командой `git add` перед созданием нового коммита.

Разным цветом выводятся файлы в состояниях:
- **untracked** - git видит файл, которого еще не было в предыдущем коммите, но не будет его добавлять в индекс
- **new** - отслеживает новый файл
- **modified** - отслеживает измененный файл
- **deleted** - показывает, какие файлы были удалены из проекта
- **renamed** - файл проекта был переименован
- **both modified** - файлы в сливаемых ветках содержат различия

#### Пример вывода команды:
```
PS K:\skillfactory\php-pro\HW-01> git status
On branch master
Your branch is up to date with 'origin/master'.    

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md    
        modified:   git-add.md   
        modified:   git-clone.md 
        modified:   git-commit.md
        modified:   git-init.md  
        modified:   git-remote.md
        modified:   git-status.md
```
> Более подробно про эту и другие команды можно изучить в книге ["Про Git"](https://git-scm.com/book/ru/v2/) в главе ["2.2 Основы Git - Запись изменений в репозиторий"](https://git-scm.com/book/ru/v2/%D0%9E%D1%81%D0%BD%D0%BE%D0%B2%D1%8B-Git-%D0%97%D0%B0%D0%BF%D0%B8%D1%81%D1%8C-%D0%B8%D0%B7%D0%BC%D0%B5%D0%BD%D0%B5%D0%BD%D0%B8%D0%B9-%D0%B2-%D1%80%D0%B5%D0%BF%D0%BE%D0%B7%D0%B8%D1%82%D0%BE%D1%80%D0%B8%D0%B9)

<br>

[< Назад](./README.md#оглавление) 