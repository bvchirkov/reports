Заходим в корневую папку проекта.
![1.png](/img/Subtree/1.png "1.png")
Переходим в папку main и создаем там файлы, наполняем их информацией.
![2.png](/img/Subtree/2.png "2.png")
![3.png](/img/Subtree/3.png "3.png")
Инициализируем git в папке main
![4.png](/img/Subtree/4.png "4.png")
Создаем коммиты для созданных файлов(Git add -A).
![5.png](/img/Subtree/5.png "5.png")
Переходим в папку sub и проделываем те же действия.
![6.png](/img/Subtree/6.png "6.png")
![7.png](/img/Subtree/7.png "7.png")
Снова переходим в папку main и добавляем модуль к проекту.
![8.png](/img/Subtree/8.png "8.png")
Выгружаем содержимое в отдельную ветку.
![9.png](/img/Subtree/9.png "9.png")
![10.png](/img/Subtree/10.png "10.png")
Возвращаемся в ветку master и извлекаем содержимое ветки module1_B в подпапку. Коммитим содержимое.
![11.png](/img/Subtree/11.png "11.png")
![12.png](/img/Subtree/12.png "12.png")
Переходим в папку sub, инициируем обновление проекта. Затем переходим в папку main, переходим в ветку module1_B и выполняем скачивание данных из удаленного репозитория.
![13.png](/img/Subtree/13.png "13.png")
![14.png](/img/Subtree/14.png "14.png")
Чтобы слить изменения в репозитории module1 в ветку master, нужно воспользоваться командой слияния со стратегией subtree и параметрами --squash и --no-commit.
![15.png](/img/Subtree/15.png "15.png")
