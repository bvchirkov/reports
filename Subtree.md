Заходим в корневую папку проекта.
![1.png](/img/Subtree/1.jpg "1.jpg")
Переходим в папку main и создаем там файлы, наполняем их информацией.
![2.png](/img/Subtree/2.jpg "2.jpg")
![3.png](/img/Subtree/3.jpg "3.jpg")
Инициализируем git в папке main
![4.png](/img/Subtree/4.jpg "4.jpg")
Создаем коммиты для созданных файлов(Git add -A).
![5.png](/img/Subtree/5.jpg "5.jpg")
Переходим в папку sub и проделываем те же действия.
![6.png](/img/Subtree/6.jpg "6.jpg")
![7.png](/img/Subtree/7.jpg "7.jpg")
6 и 7
Снова переходим в папку main и добавляем модуль к проекту.
8
![8.png](/img/Subtree/8.jpg "8.jpg")
Выгружаем содержимое в отдельную ветку.
9 и 10
![9.png](/img/Subtree/9.jpg "9.jpg")
![10.png](/img/Subtree/10.jpg "10.jpg")
Возвращаемся в ветку master и извлекаем содержимое ветки module1_B в подпапку. Коммитим содержимое.
11 и 12
![11.png](/img/Subtree/11.jpg "11.jpg")
![12.png](/img/Subtree/12.jpg "12.jpg")
Переходим в папку sub, инициируем обновление проекта. Затем переходим в папку main, переходим в ветку module1_B и выполняем скачивание данных из удаленного репозитория.
13 и 14
![13.png](/img/Subtree/13.jpg "13.jpg")
![14.png](/img/Subtree/14.jpg "14.jpg")
Чтобы слить изменения в репозитории module1 в ветку master, нужно воспользоваться командой слияния со стратегией subtree и параметрами --squash и --no-commit.
15
![15.png](/img/Subtree/15.jpg "15.jpg")