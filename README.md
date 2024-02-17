# Домашнее задание к занятию  «Защита хоста» - Юрий Белобородов


### Задание 1

1. Установите **eCryptfs**.
2. Добавьте пользователя cryptouser.
3. Зашифруйте домашний каталог пользователя с помощью eCryptfs.

*В качестве ответа  пришлите снимки экрана домашнего каталога пользователя с исходными и зашифрованными данными.*

Ответ:

Был создан пользователь cryptouser и зашифрован его домашний каталог

```
ecryptfs-migrate-home -u cryptouser
```

Каталог пользователя: 

![1-1_home_dir.png](https://github.com/Zikin18/SYS-25_13.02/blob/master/1-1_home_dir.png)

Содержимое зашифрованного каталога для другого пользователя

![1-2_encrypted.png](https://github.com/Zikin18/SYS-25_13.02/blob/master/1-2_encrypted.png)


### Задание 2

1. Установите поддержку **LUKS**.
2. Создайте небольшой раздел, например, 100 Мб.
3. Зашифруйте созданный раздел с помощью LUKS.

*В качестве ответа пришлите снимки экрана с поэтапным выполнением задания.*

Ответ:

Диск:

![2-1_create_disk.png](https://github.com/Zikin18/SYS-25_13.02/blob/master/2-1_create_disk.png)

Форматирование и создание зашифрованного каталога:

![2-2_format_lux.png](https://github.com/Zikin18/SYS-25_13.02/blob/master/2-2_format_lux.png)

![2-3_format_lux.png](https://github.com/Zikin18/SYS-25_13.02/blob/master/2-3_format_lux.png)

Мотирование, просмотр содержимого и отключение:

![2-4_mount_and_close.png](https://github.com/Zikin18/SYS-25_13.02/blob/master/2-4_mount_and_close.png)
