# laba_3
  # задание 1: 
[ссылка](https://hub.docker.com/repository/docker/amm45/custom-nginx/general) на репозиторий

  # задание 2: 
* Для запуска контейнера с заданными характеристиками использовал команду ![1](https://github.com/user-attachments/assets/260172c9-c71f-4c1e-b360-77084345596b)

* Не удаляя, переименуйте контейнер ![image](https://github.com/user-attachments/assets/e770fecc-ee0a-489b-b513-f88d37f6ebc2)

* Выполнени команд ![image](https://github.com/user-attachments/assets/88e626b7-2525-40f8-a622-151d513156aa)

* Убедитесь с помощью curl или веб браузера, что индекс-страница доступна ![image](https://github.com/user-attachments/assets/7c7fcc08-93aa-47d7-bcb6-91524e8f1175)

  # задание 3
* Воспользуйтесь docker help или google, чтобы узнать как подключиться к стандартному потоку ввода/вывода/ошибок контейнера "custom-nginx-t2". Подключитесь к контейнеру и нажмите комбинацию Ctrl-C. ![image](https://github.com/user-attachments/assets/779e4087-9ca6-4271-b656-2f5d4c2e9222)

* Перезапустите контейнер (не сложно :) )![image](https://github.com/user-attachments/assets/169d8fea-46d2-49f9-807e-54c7f297864b)

* Зайдите в интерактивный терминал контейнера "custom-nginx-t2" с оболочкой bash. ![image](https://github.com/user-attachments/assets/41cfdafa-17ae-4f7d-9433-d8dece21bd75)

* Установите любимый текстовый редактор (vim, nano итд) с помощью apt-get ![image](https://github.com/user-attachments/assets/f7d82c0b-4eef-47de-b603-794db6e2f2a8)

* Отредактируйте файл "/etc/nginx/conf.d/default.conf", заменив порт "listen 80" на "listen 81" ![image](https://github.com/user-attachments/assets/1a84a121-3151-42bf-9a01-fdfc3bd6aac8)

* Удалите запущенный контейнер "custom-nginx-t2", не останавливая его. ![image](https://github.com/user-attachments/assets/0cfd8384-6513-441b-ab06-2a67fafbe9ab)

  # задание 4:
* Запустите первый контейнер из образа ***centos*** c любым тегом в фоновом режиме, подключив папку  текущий рабочий каталог ![image](https://github.com/user-attachments/assets/86486b40-d7d7-477f-8ae6-60b8a7690495)

* Запустите второй контейнер из образа ***debian*** в фоновом режиме, подключив текущий рабочий каталог ![image](https://github.com/user-attachments/assets/c49ec986-fdb6-4fe3-abcd-765f3c763881)

* Подключитесь к первому контейнеру и создайте текстовый файл любого содержания Добавьте ещё один файл в текущий каталог на хостовой машине ![image](https://github.com/user-attachments/assets/ee8ff9a3-7a93-4049-85f7-77415601145c)

 # задание 5:
* Создайте отдельную директорию(например /tmp/ZGU/docker/task) и 2 файла внутри него. ![image](https://github.com/user-attachments/assets/94e44525-71d0-47e8-afde-5fafdb824e47)

  
* Отредактируйте файл compose.yaml так, чтобы были запущенны оба файла.(было добавлено include:  - docker-compose.yaml) ![image](https://github.com/user-attachments/assets/da278070-5fd5-472e-a91f-69b33246f8d2)









