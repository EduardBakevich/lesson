# Самоучитель по Гит
---
1. Предварительные действия
    * создаем на компьютере папку, в которой будем работать с гит
    * открываем папку в ВизуалСтудиоКод
    * создаем документ с нужным расширением (.md, txt и тд)
---
2. Изменения и сохранения
    * Сделав нужные изменения в файле, обязательно сохраняем их: ctrl+S
    * Добавляем версию в отслеживаемые: git add + название файла с его расширением
    * Фиксируем новую версию: git commit -a + "метка, чтобы ориентироваться в коммитах в будущем"
---
3. Ветвление и слияние
    * Создать ветку: git branch + названиеВетви.
    * Посмотреть список имеющихся веток: git branch
    * удалить одну из ветвей git branch -d + названиеВетви
    * перейти на нужну ветвь: git checkout + название ветви
    * возвратиться на главную ветвь: git checkout master
--- 
4. Некоторые хитрости, лайфхаки
    * Чтобы каждый раз не вводить две команды add и commit -a, пользуйтесь commit -am
    * Чтобы сразу создать ветвь и перейти на нее, используйте git checkout -b + названиеВетви
    * Чтобы не сохранять каждый раз изменения в документе, установите автосохранение: вкладка файл/автосохран.
---

## Пользуйтесь на здоровье!
>Знаниями надо делиться, а не заниматься их накоплением

### продолжение следует...