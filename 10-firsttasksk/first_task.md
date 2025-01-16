# Первое самостоятельное задание с пары

1) Установить пакеты samba bind bind-utils и любой питоновский модуль
![alt text](image.png)
и установила python3
![alt text](image-1.png)

2) Вывести:
    2.1) Версию
    ![alt text](image-2.png)

    2.2) Файлы пренадлежащие пакету
    cамба:
    ![alt text](image-3.png)
    у нее очень много файлов, поэтому все не стану загружать

    bind:
    ![alt text](image-4.png)
    аналогично, что и с самбой

    bind-utils и python3:
    ![alt text](image-5.png)

    2.3) Зависимости
    самба:
    ![alt text](image-6.png)

    bind:
    ![alt text](image-7.png)
    все не стала показывать

    bind-utils и python3:
    ![alt text](image-8.png)

3) Проверить службы установленных пакетов, еси не запущенны запустить, добавить в автозагрузку
    ![alt text](image-9.png)
    ![alt text](image-10.png)


    3.1) можно ли включить и добавить в автозагрузку одной командой?
    systemctl enable --now [пакет]

4) Найти и вывести конфигурационные файлы пакетов у которых они есть
![alt text](image-11.png)
сделала все