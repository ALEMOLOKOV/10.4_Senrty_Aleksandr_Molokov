# 10.4_Senrty_Aleksandr_Molokov

## Задание 1

Так как Self-Hosted Sentry довольно требовательная к ресурсам система, мы будем использовать Free Сloud account.

Free Cloud account имеет ограничения:

- 5 000 errors;
- 10 000 transactions;
- 1 GB attachments.

Для подключения Free Cloud account:

- зайдите на sentry.io;
- нажмите «Try for free»;
- используйте авторизацию через ваш GitHub-аккаунт;
- далее следуйте инструкциям.

В качестве решения задания пришлите скриншот меню Projects.

# Ответ

![Sentry login](https://user-images.githubusercontent.com/109212419/232139050-3070190a-46c0-49f8-8341-6246c399933b.jpg)


## Задание 2

1. Создайте python-проект и нажмите `Generate sample event` для генерации тестового события.

![1 1 create project](https://user-images.githubusercontent.com/109212419/232142206-4c63b012-adc1-4f9c-93af-ca0f32db8a39.jpg)

![1 1 create sample ivent](https://user-images.githubusercontent.com/109212419/232142228-03455a13-c8df-4601-8cb0-69265da7ce12.jpg)

2. Изучите информацию, представленную в событии.

![1 2 created event](https://user-images.githubusercontent.com/109212419/232142284-39b070d7-ae9f-4072-adbf-1c8f5b126249.jpg)

3. Перейдите в список событий проекта, выберите созданное вами и нажмите `Resolved`.

![1 3 list issues](https://user-images.githubusercontent.com/109212419/232142336-555f0f01-d001-4dd4-b820-47c91654c059.jpg)

4. В качестве решения задание предоставьте скриншот `Stack trace` из этого события и список событий проекта после нажатия `Resolved`.

![1 4 resolve issue](https://user-images.githubusercontent.com/109212419/232142608-8e9836cd-6b09-4ab1-82c6-7bbb6de75efc.jpg)


## Задание 3

1. Перейдите в создание правил алёртинга.

![3 1 allert lisr](https://user-images.githubusercontent.com/109212419/232337490-9c54bb96-671b-495c-8957-3c742b330a24.jpg)

2. Выберите проект и создайте дефолтное правило алёртинга без настройки полей.

![3 2 Test allert](https://user-images.githubusercontent.com/109212419/232337556-c16492da-1da8-4081-99b6-8c2758eeec50.jpg)

3. Снова сгенерируйте событие `Generate sample event`.
Если всё было выполнено правильно — через некоторое время вам на почту, привязанную к GitHub-аккаунту, придёт оповещение о произошедшем событии.

![3 3 Create new issue](https://user-images.githubusercontent.com/109212419/232337594-510b1915-81ab-4346-804a-4c1a047e3c09.jpg)

4. Если сообщение не пришло — проверьте настройки аккаунта Sentry (например, привязанную почту), что у вас не было 
`sample issue` до того, как вы его сгенерировали, и то, что правило алёртинга выставлено по дефолту (во всех полях all).
Также проверьте проект, в котором вы создаёте событие — возможно алёрт привязан к другому.
5. В качестве решения задания пришлите скриншот тела сообщения из оповещения на почте.

![3 5 Mail about issue](https://user-images.githubusercontent.com/109212419/232337602-06624057-34d3-4ddd-b962-269629c4fe7c.jpg)

6. Дополнительно поэкспериментируйте с правилами алёртинга. Выбирайте разные условия отправки и создавайте sample events. 

![3 6 add some allerts](https://user-images.githubusercontent.com/109212419/232337608-3dbd64cd-4da0-4b5a-9b2c-05a1af2407ad.jpg)

![3 6 mails](https://user-images.githubusercontent.com/109212419/232337616-09779cc4-0251-4309-9cca-61d08ba5e233.jpg)
