### Домашнее задание 3.14.1 (HW-01) курса PHP-Pro (Skillfactory)

Автор: Александр Климок / [kydechuk01](https://github.com/kydechuk01/)

---

[<<< К оглавлению](./README.md#оглавление) 

### Команда git push

Данная команда отправляет состояние текущей ветки в  онлайн-репозиторий, с которым был ранее связан локальный репозиторий (через `git clone` или `git remote`).

#### Варианты использования:

* `git push origin [branch]` - в онлайн-репозиторий отправляется ветка branch
* `git push -u origin master` - всегда в будущем при использовании короткого варианта команды `git push` отправлять данные из ветки master
* `git push` - отправка ветки по-умолчанию (master)
* `git push origin HEAD` - отправка текущей ветки в онлайн-ветку с таким же именем.
* `git push --force` или `-f` принудительная отправка ветви, несмотря на то, что git отклонил предыдущее действие из-за рассинхронизации репозиториев.
  

<br>

[< Назад](./README.md#оглавление) 