---
title: Заметки AlexBor
description: 
published: true
date: 2024-10-31T13:55:26.373Z
tags: 
editor: markdown
dateCreated: 2024-10-16T07:56:59.948Z
---

# Здравствуй, добрый рукожоп с ручками иначе, передам тебе «привет», чтоб пылало ярче!

> Если тебе что-то не нравится в инструкции - помни, что её могло бы вообще не быть! Так что не ной, а возьми и обнови...  {.is-success}

► ▼ → ○
<span style="color: red;"> ● </span>
<span style="color: yellow;"> ▲ </span>
<span style="color: green;"> ■ </span>
☐ ☑ ☒ ✎

> **Для тех, кому надо СРОЧНО сделать:**  
> https://rutube.ru/video/536fc124105095b385987b0012d39849/?r=plwd{.is-info}
> https://youtu.be/eYBwY6zKSNk{.is-info}

### Легендарные фразы
-   Сервер Лёх (лёг)
-   Бест практикс (Best practices) -- Какой проститесь? ***или*** Что проститесь?
-   Вас ребут, а Вы крепчаете
-   Кто там кёрнул? (Kernel - Ядро ОС)
-   Мой гуй (GUI) - мои правила
-   Первый раз вижу //**или**// Первый раз слышу
-   Предлагаю ничего не делать
-   Семь бед - один ресет
-   У нас в сети появился петлюх
-   Ууу... Ларина сегодня траблааа... ***или*** Ууу... Ларина трабла с утрааа... (Moby – Natural Blues [https://ruo.morsmusic.org/track/12050](https://ruo.morsmusic.org/track/12050))

<br><br>

Путь к **SAP ICON** - `\usr\sap\ER1\DVEBMGS00\data\icmandir\its\lsgui\themes\sap_corbu\images\icons\ltr`

- [Каталог Центра обновления Майкрософт *http://www.catalog.update.microsoft.com/Home.aspx*](http://www.catalog.update.microsoft.com/Home.aspx)
- [Download VMware Tools
*https://packages.vmware.com/tools/releases/latest/*](https://packages.vmware.com/tools/releases/latest/)
{.links-list}

<br><br>

### Как поменять мандант в SAP по умолчанию?

Параметр **login/system\_client** (Транзакция RZ10, но лучше через файл профиля "\\usr\\sap\\SID\\SYS\\profile\\DEFAULT.PFL")

<br><br>

### Как создать вариант для транзакции SU01?

Создаём в транзакции **SHD0**

<br><br>

### Какие транзакции запускал пользователь?

Смотрим в транзакции **SM20** / **SM20N**

<br><br>

### Массовая блокировка пользователей

Массово блокировать пользователей можно в транзакции **EWZ5** или **SU10**, необходимо только поставить галочку на своей учётке как суперадмина

Блокировать можно всех, кроме согласованных и системных

<br><br>

### Как изменить параметры запроса (❗ЭТО МОЖЕТ БЫТЬ ОПАСНО❗)?

> **Меняйте параметры запроса на свой страх и риск‼️** {.is-danger}

Параметры: Краткое описание, Владелец, Тип запроса, Статус, Вышестоящий запрос

_**Я ПРЕДУПРЕДИЛ!**_ -> Транзакция **SA38** / **SE38** -> Программа **RDDIT076**

<br><br>

### Как снять защиту с варианта?
Транзакция **SA38** / **SE38** -> Программа **RSVARENT**

<br><br>

### Запись изменений в таблице ABAP
Для просмотра зарегистрированных изменений, использовать транзакцию **SCU3**
Для получения списка таблиц, изменения данных в которых регистрируется, использовать отчёт **RSTBHIST**
Подробные сведения доступны в SAP Notes 1916 и 112388
Вообще смотрим в транзакции **SE11** -> Технические параметры настройки

<br><br>

### Как переслать файл большого размера (до 50 Гб)?
**DropMeFiles** – бесплатный сервис мгновенного обмена файлами:
[https://dropmefiles.com/](https://dropmefiles.com/)

Плюсы сервиса:
- Бесплатный
- Без регистрации
- Можно переслать файлы до 50 Гигабайт

Минусы сервиса:
- Ограничение на срок хранения файлов – 14 дней

Сервис создан, чтобы **обмениваться файлами**, а НЕ для их хранения, поэтому за 14 дней можно отправить и получить файлы большого размера.

<br><br>

### Как найти что-то в Google?
[https://ru.lmgtfy.com/](https://ru.lmgtfy.com/)
[https://google.gik-team.com/](https://google.gik-team.com/)

<br><br>

**Arch Linux**

-   Yaourt: a Pacman frontend
```plaintext
git clone https://aur.archlinux.org/package-query.git
cd package-query
makepkg -si
cd ..
git clone https://aur.archlinux.org/yaourt.git
cd yaourt
makepkg -si
cd .. 
```

- RealVNC Enterprise Key (realvnc-vnc-server)  
232NH-NH733-T85TH-KT2P2-7ZPUA  
HRBRH-3BN52-Z8ECH-CJ7B7-MNX3A

- VMware workstation 14 Serial Keys Linux:  
YV54A-2ZW5P-M887Y-UWXNE-QPUXD  
VY3R2-0NW0L-H845Q-TDMXT-XQAT0  
VC7JR-A0Z97-08EGZ-M4YNV-XVHD0  
FC1TU-4RGEQ-084EP-2XQQX-ZGHWA  
CU1WA-8HGEN-M815Z-HQP5E-QKADF  
AY7D0-FTG44-H846Y-2XPGV-P32T8

- VMware workstation 15 Pro Serial Keys Linux:  
YZ718-4REEQ-08DHQ-JNYQC-ZQRD0

- 15.5.0 Build 14665864 Serial Keys Linux:  
FC19K-6JX81-084TP-A7ZE9-Y6KV0  
ZG79K-80W15-081MP-Z5XNT-PGRU2  
AY542-89Y8H-48E4Y-5DZEC-YKAF2  
CV780-22ED2-M89XQ-R7NXT-PY8Y4  
GV59K-6RZ4J-08DHP-A6PQC-NY894  
VF31K-4DY92-48DYY-U6ZXE-ZQ2C6  
CY3RH-FXXD6-M8EZP-TXMQ9-P3AD0  
UC312-ALD4H-M84EP-ENNQC-Y7KF8  
YZ11K-DVZDJ-080FQ-YPXQT-MCUF6  
AZ11K-00D52-489AQ-CPYNT-Y7280  
ZU14H-28E12-H81VQ-DEN7X-YY8G6  
GU7DR-08W8P-4899P-17Q5E-Z72UA

- 7.1 Serial Keys Linux:  
FU3D8-28X0N-H8DJQ-4GZZX-MY2T8  
ZY7M2-8ZX81-0813Y-AWPG9-PP0G6  
CC3W8-DTX9M-4853Y-HPQGX-NU8X6  
YU15U-6TWDQ-H88RZ-GGNXC-QFATA  
AF1T0-FMZEL-H88FQ-N5NXG-PZUX0  
GC3MU-28W06-M80WQ-R4ZXV-YFK98  
UA5J0-0HW13-48EMY-VXQNZ-NFUD2  
VF7WU-2GF14-488CP-R4Z7Z-NL2YF

<br><br>

**Debian Linux**
-   Переименовывание группы томов (Volume Group LVM) в Debian

Небольшая заметка, объясняющая, как переименовать группу томов LVM в Debian.
-   Перезагружаем компьютер и выбираем режим восстановления (не обязательно, но рекомендуется)
-   Переименовываем Volume Group: **\# vgrename Текущее\_имя\_LVM Новое\_имя\_LVM**
-   Редактируем файл: **/etc/fstab** и меняем все записи с новым именем VG LVM
-   Редактируем файл: **/etc/initramfs-tools/conf.d/resume** и меняем старое наименование VG LVM на новое
-   Пересобираем initramfs: **\# update-initramfs -u -k all**
-   Перезагружаемся

<br><br>

| Компания 											| У кого спрашивать документы | Примечание 												|
| --- 													| --- 						| --- 																					|
| <center>ГС Сервис ([info@gs-s.ru](mailto:info@gs-s.ru))</center> |||
| АРКА 													| Куликова 				|     																					|
| Доменик 											|     						|     																					|
| Импориа 											|     						|     																					|
| Трамонтана 										| Блинова, Козлов	|																								|
| <center>ДОКЛИНК (СИСЛИНК)<br>(Сайт: [https://edi-lk.doclink.ru/](https://edi-lk.doclink.ru/)<br>Почта: [edi@doclink.ru](mailto:edi@doclink.ru)) Личный кабинет -> Файлы</center> |||
| АРКА (МВидео) 								| Бутурлакина 		| Логин: arkacompany<br>Пароль: ms1tKUDyej2XXBl |
| Трамонтана (Все инструменты) 	| Шарапов 				| Логин: tramontana<br>Пароль: 1G5yDjNJT8dmUnu	|