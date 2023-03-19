## Задание 2. Rebase

⦁	Создал и запушил файл task2-file 

⦁	Переключился на ветку main 

⦁	Изменил файл test2.txt, добавив текст(который съела кодировка) закоммитил и запушил

⦁	Переключился на эту ветку

⦁	Выполнил rebase от ветки main

⦁	Запушить новое состояние не получилось![image](https://user-images.githubusercontent.com/90779396/226182225-b4c80e0c-1d0a-43ba-b277-b7ecef0e7fed.png)

   
    Не удалось запушить ветку, так как после выполнения rebase в локальном репозитории изменилась история коммитов 
    и она отлична от истории коммитов в удаленном репозитории,
    т.е коммиту создания файла task2-file в локальном и удаленном репозитории предшествуют разные коммиты и из-за этого ошибка. 
    
``` 
Решение 1:
Воспользоваться force push, как указано на картинке, тогда запушится история коммитов с нашего локального репозитория,
а история на удаленном исчезнет и заменится на нашу.
Решение 2:
Не догадался до другого решения
