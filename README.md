# **Техническое задание на внедрение Google Tag Manager и Google Analytics 360 для историй на сейте Tefal**
## **Содержание:** 

### **Общая информация (для веб-аналитика и разработчика)**

- [Цель документа](#цель-документа)
- [Порядок действий](#порядок-действий)
- [Чек-лист проверки событий](#чек-лист-проверки-событий)
- [Макеты нового дизайна сайта](#макеты-нового-дизайна-сайта)

### **Общие настройки dataLayer (для разработчика)**

- [Карты событий](#карты-событий)
- [Custom Dimensions 2](#custom-dimensions-2)
- [Справочники](#справочники)
  
### **Справочная информация для разработчиков от Google (для разработчика)**

- [Электронная торговля GA360 документация для разработчиков от Google](https://developers.google.com/analytics/devguides/collection/ua/gtm/enhanced-ecommerce)
- [Менеджер тегов: расширенная электронная торговля для разработчиков от Google](https://developers.google.com/analytics/devguides/collection/gtagjs/enhanced-ecommerce#action-data)

### **Общие настройки Google Analytics и Яндекс.Метрики (для веб-аналитика)**

- Настройки Google Analytics
- Настройки Яндекс Метрики



***
## **Общая информация (для веб-аналитика и разработчика)**
### **Цель документа**
Документ описывает инструкцию для разработчиков по внедрению Google Tag Manager. Данный инструмент позволяет упростить добавление и настройку JS-кодов внешних систем и проводить ее в будущем централизованно через веб-интерфейс.

### **Порядок действий**
1. Добавить код Google Tag Manager на все страницы проекта
2. Наполнить JS-переменную dataLayer для каждого типа страниц и событий на основе  [карты событий](#карты-событий)
3. Настроить Google Analytics на основе dataLayer через Google Tag Manager
4. Перенести существующие коды и проверить их работу

### **Чек-лист проверки событий**
[Чек-лист](https://docs.google.com/spreadsheets/d/1BqcdZCeuPjZTE0PALzi64Hl1YA1AKelsG5PGsbYC7Cw/edit?usp=sharing) проверки событий:


## **Общие настройки dataLayer (для разработчика)**
### **Карты событий**
- [Карта событий электронная торговля](/02_datalayer_settings/01_events/01_ecommerce.md) 
- [Карта событий интерактивных](/02_datalayer_settings/01_events/02_interactions.md)


### **Справочники** 
- [Типы страниц](/02_datalayer_settings/04_catalogs/01_page_type.md)
- [Типы списков товаров](/02_datalayer_settings/04_catalogs/02_item_list_type.md)
- [Типы сервисов/виджетов на сайте](/02_datalayer_settings/04_catalogs/05_placement.md)
***