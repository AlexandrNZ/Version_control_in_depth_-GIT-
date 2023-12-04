# Урок 1. Работа с удалёнными репозиториями
**1.** Выберите какой-нибудь проект на изучаемом вами языке программирования, с которым вы будете тренироваться работать в Git, и инициализируйте в папке этого проекта локальный репозиторий.  
**2.** Создайте непустой удалённый репозиторий (например, с файлом README.md) с именем, соответствующим имени этого проекта.  
**3.** Подключите свой проект к этому удалённому репозиторию и отправьте в него код этого проекта. Самостоятельно разрешите конфликты и проблемы, если они возникнут при выполнении данного задания.  

# Урок 2. Работа с изменениями
Данное домашнее задание является продолжением домашнего задания, которое вы выполняли на предыдущем семинаре в репозитории с собственным проектом.

**1.** Просмотрите историю коммитов в своём проекте и выберите три случайных коммита. Просмотрите изменения, которые были в них сделаны.

**2.** Верните эти изменения командой git revert последовательно, чтобы в итоге получилось тоже три коммита.

**3.** Попробуйте отменить эти три коммита:  
* последний — командами git reset --soft и git restore;
* предпоследний — командой git reset --mixed и git restore;  
* первый — командой git reset --hard.

# Урок 3. Практики и инструменты для работы с Git
Данное домашнее задание является продолжением домашнего задания, которое вы выполняли на предыдущем семинаре в репозитории с собственным проектом.

В этом задании предлагаем каждому из вас побыть в роли тимлида.

**1.** Пригласите в свой проект кого-то из коллег по обучению, дайте им доступ к своему репозиторию (кроме ветки master).

**2.** Поставьте ему в GitHub задачу по своему проекту, попросите её выполнить в отдельной ветке, а после выполнения — создать pull request и перевести задачу обратно на вас.

**3.** Проверьте выполнение задачи, примите pull request и удалите ветку, в которой решалась данная задача.
