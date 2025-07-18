---
description: Добавлена возможность использовать свои  названия статусов вместо стандартных
---

# Уникальные статусы для клиентов

Ранее в Education ERP были только 9 стандартных статусов. [Подробнее](unikalnye-statusy-dlya-klientov.md#standartnye-statusy-v-education-erp)

К нам часто приходили запросы от франчайзи, что для их школ набор стандартных статусов не отражает суть той работы, которая  в данный момент проводится с клиентом.

Было решено добавить возможность создания новых уникальных статусов, которые четко покажут процесс работы с клиентами в каждой школе.

### Добавление нового статуса

На странице Клиенты - Все клиенты нажмите кнопку "Настройки статусов".

![](<../.gitbook/assets/image (22).png>)

Далее в блоке с базовым статусом, для которого хотите указать уникальное название, нажмите кнопку "Добавить новый".

![](<../.gitbook/assets/image (27).png>)

Введите название статуса и сохраните.

:::info

Называйте статусы корректно и понятно.

:::

![](<../.gitbook/assets/image (23).png>)

:::info

Если в системы уже был аналогичный статус, то при добавлении будет предложено использовать его.

:::

### Переключение стандартного статуса на уникальный

Включите свой созданный статус и все клиенты, кто раньше был в статусе Новый теперь будут в статусе "Новичок".

![](<../.gitbook/assets/image (11).png>)

:::danger

Для автоматического перехода можно выбрать только 1 статус.

:::

### Несколько статусов в блоке одного базового

Вы можете добавить нескольких статусов а блоке одного базового. В автоматическом режиме будет работать только 1 из них, но в ручном режиме вы можете переключится на любой из списка.

:::info

Почему один из статусов должен быть обязательно выбран для автоматического перехода?

Например, при покупке абонемента клиент в статусе Новичок, должен автоматически попасть в новый статус из блока "Базовый статус: Купил абонемент",  чтобы получить уведомление-приглашение в личный кабинет.

:::

![](<../.gitbook/assets/Статусы (1).gif> "Ручной перевод в новый статус из блока "Купил абонемент"")

### Удаление статуса

![](<../.gitbook/assets/image (29).png>)

Обязательные условия, при котором кнопка "Удалить" доступна для статуса:

* не используется для автоматического перехода;
* не выставлен ни у одного из клиентов;
* есть хотя бы один другой статус в этой категории базового статуса.

### Базовые (стандартные) статусы в Education ERP

<details>

<summary>Новый</summary>

Новые клиенты школы, кто не купили ни одного абонемента и не посетили пробное занятие.

</details>

<details>

<summary>В работе</summary>

Клиенты из 'Новые', кто пока не принял решение, не записались на пробное занятие и не отказались.

</details>

<details>

<summary>Записался на пробное занятие</summary>

В этот список попадают те клиенты из 'Новые', у которых проставлена дата записи на пробное занятие.

</details>

<details>

<summary>Посетил пробное занятие</summary>

В этот список попадают клиенты, которые не купили ни одного абонемента, но посетили пробное занятие. Посещение пробного занятия можно отметить на странице клиента в поле "Посетил пробное занятие" .

</details>

<details>

<summary>Подбор группы</summary>

Клиенты, чьи ученики находятся в процессе подбора группы

</details>

<details>

<summary>Купил абонемент</summary>

В этот список попадают клиенты, которые купили хотя бы один абонемент. Абонемент можно добавить на странице ученика. Ученик - ребенок клиента.

</details>

<details>

<summary>Резерв</summary>

В этот список попадают заинтересованные клиенты. Например, не согласился прийти на пробное занятие сразу, но готов посетить пробное занятие позже или если не хватает мест в группе.

</details>

<details>

<summary><strong>Отказался</strong></summary>

В этот список попадают клиенты, которые отказались посещать занятия.

</details>

<details>

<summary>Удален</summary>

Удалёнными помечаются пользователи, которые обратились как клиенты, но клиентами по сути не являются. Например, предложения от другого бизнеса или звонки детей.

</details>

\


