---
icon: globe-pointer
---

# Подключение роутера как основной

{% hint style="info" %}
Перед тем как приступить к настройке запросите пароль доступа к web интерфейсу роутера через техподдержку.
{% endhint %}

{% hint style="info" %}
<mark style="color:red;">ВНИМАНИЕ! После получения пароля от техподдержки мы полностью снимаем с себя ответственность за работоспособность роутера. Если вы сомневаетесь, то наши специалисты в силах внести настройки самостоятельно.</mark>
{% endhint %}

{% hint style="info" %}
**В данном примере указан тип подключения PPPoE. Вам необходимо уточнить у вашего провайдера используемый тип подключения и по аналогии создать нужный.**
{% endhint %}

{% content-ref url="kak-s-nami-svyazatsya.md" %}
[kak-s-nami-svyazatsya.md](kak-s-nami-svyazatsya.md)
{% endcontent-ref %}

Откройте браузер и перейдите по адресу:

> 192.168.99.1

Авторизуйтесь с помощью логина и пароля&#x20;

<figure><img src=".gitbook/assets/Снимок экрана 2025-04-20 в 23.21.57.png" alt=""><figcaption></figcaption></figure>

Нажмите на вкладку Network

<figure><img src=".gitbook/assets/Снимок экрана 2025-04-20 в 23.23.10.png" alt=""><figcaption></figcaption></figure>

Далее перейдите в Interfaces и нажмите Add new interface...

<figure><img src=".gitbook/assets/Снимок экрана 2025-05-12 в 15.49.43.png" alt=""><figcaption></figcaption></figure>

Укажите имя подлючения. В поле Protocol укажите типа подключения вашего провайдера. В поле Device выберите Switch port: "wan"

<figure><img src=".gitbook/assets/Снимок экрана 2025-05-12 в 15.50.33.png" alt=""><figcaption></figcaption></figure>

В списке сетевых интерфейсов выберите только что созданный и нажмите кнопку Edit

<figure><img src=".gitbook/assets/Снимок экрана 2025-05-12 в 16.09.31.png" alt=""><figcaption></figcaption></figure>

Ввведите учетные данные полученные от провайдера

<figure><img src=".gitbook/assets/Снимок экрана 2025-05-12 в 16.09.59.png" alt=""><figcaption></figcaption></figure>

Затем перейдите во вкладку Firewall Settings и выберите интерфейс wan

<figure><img src=".gitbook/assets/Снимок экрана 2025-05-12 в 16.10.07.png" alt=""><figcaption></figcaption></figure>

Затем нажмите Save

Далее нажмите Save & Apply для применения настроек

{% hint style="info" %}
Если у вас возникли сложности с настройкой, вы всегда можете обратиться в нашу техподдержку. Наши специалисты настроят подключение удаленно.
{% endhint %}

{% hint style="info" %}
<mark style="color:red;">Не сбрасывайте роутер в заводские настройки! Не нажимайте кнопку RESET. В этом случае роутер перестанет выполнять свои заявленные функции!</mark>
{% endhint %}

{% content-ref url="kak-s-nami-svyazatsya.md" %}
[kak-s-nami-svyazatsya.md](kak-s-nami-svyazatsya.md)
{% endcontent-ref %}
