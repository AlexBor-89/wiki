---
title: Увеличение размера диска в Linux (не LVM)
description: 
published: true
date: 2024-11-01T14:47:11.848Z
tags: sap, linux
editor: markdown
dateCreated: 2024-10-31T07:31:05.815Z
---

Информация о месте на диске
```
df -h
```

> Все данные на разделе останутся, но снапшот не помешает!
```bash
sudo umount -l /dev/sdb1 или umount -f /dev/sdb1
```
а лучше
```bash
sudo mcedit /etc/fstab
```
и закомментировать `/dev/sdb1` -> Save <kbd>F2</kbd>
```bash
sudo reboot
```

> fdisk (до версии `linux-utils 2.30.2`) не поддерживает разделы более 2 ТБ
{.is-warning}

```bash
sudo tune2fs -O ^has_journal /dev/sdb1 (Отключите ведение журнала)
  
sudo fdisk /dev/sdb
d
n
p
1
[Enter]
[Enter]
w
  
sudo e2fsck -f /dev/sdb1 (Принудительная проверка файловой системы, даже если по журналу она чистая)
sudo resize2fs /dev/sdb1 (Программа resize2fs перезапишет метаданные файловой системы)
```

```bash
sudo mcedit /etc/fstab
```
и раскомментировать `/dev/sdb1` -> Save <kbd>F2</kbd>
```bash
sudo reboot
```