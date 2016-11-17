# Примеры миграций баз данных для 1С-Битркс

##Главный модуль
- [Добавить пользовательское свойство (или Highload Block поле)](migrations/cms/main/AddUserField.php)
- [Добавить группу пользователей](migrations/cms/main/AddUserGroup.php)
- [Добавить группы пользователей (Д7)](migrations/cms/main/AddUserGroups.php)
- [Добавить агента](migrations/cms/main/AddAgent.php)
- [Добавить записи в b_option](migrations/cms/main/SetOption.php)
- [Добавить правило подключения шаблона сайта](migrations/cms/main/AddSiteTemplateRule.php)
- [Добавить тип почтового события и шаблон](migrations/cms/main/AddMailEventTypeAndTemplate.php)

##Информационные блоки

- [Добавить свойство инфоблока](migrations/cms/iblock/AddIblockProperty.php)
- [Добавить свойство инфоблока типа Список](migrations/cms/iblock/AddEnumIblockProperty.php)
- [Обновить свойство инфоблока](migrations/cms/iblock/UpdateIblockProperty.php)
- [Обновить свойство инфоблока типа Список](migrations/cms/iblock/AddEnumIblockPropertyValues.php)
- [Удалить свойство инфоблока](migrations/cms/iblock/DeleteIBlockProperty.php)
- [Добавить новый раздел](migrations/cms/iblock/AddNewIblockSection.php)
- [Добавить инфоблок](migrations/cms/iblock/AddIBlock.php)

##Интернет-магазин

- [Добавить свойство заказа](migrations/cms/sale/AddOrderProperty.php)
- [Обнулить внутренний счет](migrations/cms/sale/ClearSaleUserAccounts.php)

##Каталог

- [Добавить тип цен](migrations/cms/catalog/AddNewCatalogGroup.php)

##Веб-формы

- [Добавить веб-форму](migrations/cms/forms/AddNewWebForm.php)

##Другое

- [Произвольный SQL-запрос](migrations/cms/main/RawSql.php)

---

##Кор. портал

- [Новая стадия сделки](migrations/intranet/crm/AddNewDealStages.php)
