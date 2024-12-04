---
description: >-
  К серверам на основе ОС Linux подключение производится при помощи протоколов
  SSH/sFTP. Давайте разберем, как это можно сделать!
---

# 📪 Как подключиться по SSH и SFTP

## Как подключиться?

Чтобы подключиться к серверу с ОС Linux, Вам потребуется SSH и sFTP-клиенты.

{% hint style="info" %}
Ссылки на самые популярные клиенты для **Windows**!
{% endhint %}

* [PuTTY](https://the.earth.li/~sgtatham/putty/latest/w32/putty.exe) — **SSH-клиент**.
* [Termius](https://termius.com/free-ssh-client-for-windows) — альтернативный **SSH-клиент.**
* [FileZilla](https://filezilla.ru/) — **FTP-клиент**.
* [WinSCP](https://winscp.net/eng/download.php) — альтернативный **FTP-клиент.**
* [Bitvise](https://bitvise.com/ssh-client-download) — SSH и SFTP клиент.
* [MobaXTerm](https://mobaxterm.mobatek.net/download-home-edition.html) — SSH и SFTP/FTP клиент.

В данном случае мы **рекомендуем** использовать именно **Bitvise** или **WinSCP** для подключения по SSH/SFTP, однако как наиболее подходящий вариант для новичков, ниже мы разберем подключение через FileZilla.\


## Инструкция

{% hint style="info" %}
Данные для подключения можно посмотреть в сообщении на эл. почте или выбрать услугу в личном кабинете и кликнуть на неё, открыв страницу услуги.
{% endhint %}

{% hint style="warning" %}
**Для подключения по SFTP и SSH используются идентичные данные.**
{% endhint %}

{% tabs %}
{% tab title="PuTTY " %}
### **Порядок действий для подключения к VDS/VPS Linux по SSH** <a href="#poryadok-deistvii-dlya-podklyucheniya-k-vds-vps-linux-po-ssh" id="poryadok-deistvii-dlya-podklyucheniya-k-vds-vps-linux-po-ssh"></a>

1. В поле **Host Name** — укажите IP-адрес Вашего сервер&#x430;**.**
2. Далее введите порт. По умолчанию это — 22
3. Нажмите на кнопку для подключения — **Open**.

<figure><img src="../.gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure>

Далее необходимо указать имя пользователя (по умолчанию это — **root**).

Затем вводим **пароль**.

{% hint style="warning" %}
Пароль в PuTTY вводится невидимыми символами!
{% endhint %}

Чтобы вставить текст в PuTTY, необходимо нажать **ПКМ** (правая кнопка мыши) для Window&#x73;**.**
{% endtab %}

{% tab title="FileZilla" %}
### Как подключиться по sFTP?

Вам необходимо ввести следующие данные, которые были предоставлены после активации сервера:

```
IP-адрес — «‎Хост» в FileZilla.

Имя пользователя

Пароль

Порт
```
{% endtab %}
{% endtabs %}
