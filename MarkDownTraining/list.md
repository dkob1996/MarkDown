# Основные команды GIT
* Вывести версию git:
```
git --version
```
---
* Все введенные когда-либо в терминал команды:
```
history
```
---
## Команды для начала работы.
* Инициализация локального репозитория:
```
git init
```
---
* Создание новой директории/папки:
```
mkdir 'название_папки'
```
---
* Создание нового файла:
```
touch 'название_файла.расширение_файла'
```
---
* Получить информацию от git о его текущем состоянии:
```
git status
```
---
* Создание коммита с свои комментарием (<a href="https://gbcdn.mrgcdn.ru/uploads/asset/4686515/attachment/f7ff2a83f718ce75edc85fd3cc3a2285.docx">ссылка на doc файл с правилами комментариев</a>):
```
git commit -m "комментарий"
```
---
* Вывод на экран истории всех коммитов с их хэш-кодами:
```
git log
```
---
* Более сжатая версия вывода всех коммитов с их хэш-кодами:
```
git reflog
```
---
* Вывод на экран истории всех коммитов по разным веткам:
```
git log --graph
```
---
## Команды для работы с файлом.
* Увидеть разницу между текущем файлом и закоммиченным файлом:
```
git diff
```
---
* Переход от одного коммита к другому / от одной ветки к другой:
```
git checkout 'первые_4_цифры_номера_хэш'   / git checkout 'название_ветки'
```
---
* Вернутся к актуальному состоянию и продолжить работать:
```
git checkout master
```
---
* Переход от одного коммита к другому:<br>
_схож с checkout_
```
git switch 'первые_4_цифры_номера_хэш'
```
* Просмотр всех веток для файла:
```
git branch
```
---
## Редактирование файла.
* Создание новой ветки:
```
git branch 'название_новой_ветки'
```
---
* Слияние двух веток:
```
git merge 'название_ветки_которую_надо_добавить_к_текущей'
```
---
* Удаление ветки:
```
git branch -d 'название_ветки_которую_надо_удалить'
```
---
* Жесткое удаление ветки (возможно с последствиями):
```
git branch -D 'название_ветки_которую_надо_удалить'
```
---
## Редактирование git-отпечатка в файле.
* Отмена последней фиксации:
```
git stash
```
---
* Исправить комментарий к последнему коммиту:
```
git commit --ammend -m "исправленный_комментарий"
```
---
* Сброс ветки до выбранного коммита:
```
git reset 'первые_4_цифры_номера_хэш'
```
---
## Дополнительные комманды
* Отображение файлов и папок:
```
ls -L
```
--- 
* Очистка терминала:
```
clear
```
--- 
* Переход в нужную папку:
```
cd 'название_папки_в_корне'
```
--- 
* Выход из всех папок:
```
cd
```
--- 
* Клонирование репозитория:
```
git clone
```
--- 