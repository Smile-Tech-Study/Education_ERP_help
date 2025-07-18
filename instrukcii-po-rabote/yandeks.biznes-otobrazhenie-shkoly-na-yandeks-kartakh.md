---
description: Все школы ООО Лига будут отображаться на Я.Картах
---

# Яндекс.Бизнес отображение школы на Яндекс картах

Для школ ООО Лига предусмотрена передача данных о школах на Яндекс.Карты.

Каждая школа типов: Юниор, Юниор Код, Спартак Юниор и Русский Балет, на странице которой будет нажата кнопка "Показать школу", попадает в ФИД-файл — это файл, который автоматически формируется в Education ERP. ФИД каждой из указанных сетей школ собирает данные, запрашиваемые Яндекс.Картами, затем в автоматическом формате передаёт эти данные в Я.Бизнес. Данные из Я.Бизнес отображаются на Я.Картах.

![](<../.gitbook/assets/image (121).png>)

### **Какие данные передаются?**

Из Education ERP передаются следующие данные:

1. **Общий телефон сети школ** для каждой школы — он попадает в контакты в карточку школы на Я.Карте.
2. **Номер телефона со страницы школы**. В Education ERP всегда должен быть актуальный номер.
3. **Соц. сети, указанные в блоке "Контакты"** на странице школы.
4. **E-mail, указанныq в блоке "Контакты"** на странице школы.
5. **Адрес и метка на карте со страницы школы**. Здесь важно отметить, что адрес на странице школы и метка должны совпадать (для проверки можно вбить адрес школы на Я.Карте и проверить, что точка на Я.Карте соответствует той точке, которая поставлена при создании/редактировании школы в Education ERP). Иначе Яндекс не будет публиковать/обновлять информацию.
6. **Индекс школы**
7.  **Режим работы**:

    7.1 Если режим работы заполнен на странице школы, то передаётся именно этот график.

    7.2 Если режим работы не заполнен на странице школы, но есть группы, отмеченные как "Публичные группы", то в режим работы передаётся расписание их занятий.

    7.3 Если не заполнены пункты 6.1/6.2, передаётся режим по пятидневной рабочей неделе с 9:00 до 18:00.
8. **Логотип сети школ**
9. **Название сети школ**
10. **Сайт в соответствии с типом школы**: https://www.fsjunior.com/, http://juniorcode.ru/, https://www.fsspartak.com/, https://schoolballet.com и ссылки на соцсети со страницы школы (если заполнены).

### **Сроки передачи данных**

* Данные из Education ERP отправляются ежедневно (данные со страницы школы, где нажата кнопка "Показать школу", в ежедневном формате обновляются в ФИД-файле).
* Если были какие-либо изменения в любом филиале сети школ, то данные проходят проверку специалистами Яндекса на наличие ошибок (например, несовпадение точки на карте и адреса). Такая проверка занимает от нескольких часов до трёх дней.
* Если найдены ошибки, то для дальнейшей работы их необходимо исправить, об этом сообщает техподдержка Я.Бизнес в техподдержку Education ERP. Далее ошибка исправляется: если это опечатка, то исправление происходит сразу после получения замечания, если требуется уточнение, то время зависит от ответа франчайзи. После исправления ошибки ФИД повторно проходит проверку.
* Если ошибок нет, то изменения на Я.Картах после проверки появятся в срок от нескольких часов до 2-х недель.

### **Как получить доступ к карточке школы в Я.Бизнес?**

1. **Заполните номер телефона**:
   * В Education ERP на странице школы в блоке "Контакты" укажите номер телефона, на который можно получить код от Я.Бизнес для подтверждения владения организацией.
2. **Дождитесь отображения номера**:
   * Убедитесь, что указанный номер телефона отображается в карточке организации на Яндекс.Картах. [Подробнее о сроках](yandeks.biznes-otobrazhenie-shkoly-na-yandeks-kartakh.md#sroki-peredachi-dannykh)
3. **Получите доступ в кабинет Я.Бизнеса**:
   * Ознакомьтесь с публичной инструкцией Я.Бизнес по ссылке: [Яндекс Бизнес - Подтверждение прав на компанию](https://yandex.ru/support/business-priority/manage/verify.html#verify).
4. **Обратите внимание на данные в ФИД-файле**:
   * Все данные, передаваемые в ФИД-файле, являются первоочередными. Если после подтверждения владения в Личном кабинете Я.Бизнес данные в карточке школы будут отличаться, то за главные данные будут приняты данные из ФИД-файла, и внесенные изменения перезатрутся.
5. **Следите за актуальностью данных**:
   * Для того чтобы данные в карточке были актуальными, необходимо регулярно проверять информацию на странице школы в Education ERP.

### Как оформить переезд филиала?

:::info

Перед оформлением перезда необходимо сохранить фото, загруженные в карточке школы в ЛК Я.Бизнес, если эти фото ранее не сохраненны.

:::

1. Необходимо изменить адрес в Education ERP на новый. Изменение адреса в школе проходит проверку администратором сети школы. В случае одобрения изменённые данные отобразятся на странице школы.
2. Необходимо оформить  переезд школы в карточке организации в ЛК Я.Бизнес .

:::danger

Перед оформлением переезда необходимо убедиться, что галочка "Перенести фото и отзывы" отмечена. Если по какой-то причине галочка не будет отмечена, то восстановить отзывы и фото не получится (такой ответ был предоставлен технической поддержкой Я.Бизнеса).

:::

### Куда направлять вопросы по Я.Бизнес/Я.Картам?

Любые вопросы можно направлять в техподдержку Education ERP [https://education-erp.com/ru/Form](https://education-erp.com/ru/Form).  Если необходимо будет лично обратиться в техподдержку Я.Бизнеса, данная информация поступит в ответе. 
