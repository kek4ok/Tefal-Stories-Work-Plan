[Вернуться на главную](/README.md)
# **Клик по ссылке**

Страницы, на которых работает код, триггеры находятся в таблице [тут](/02_datalayer_settings/01_events/01_ecommerce.md)

## **Код для dataLayer:**

### **Клик по ссылке снизу истории. В результате открывается товар\страница кампании:**
```javascript
<script>
window.dataLayer = window.dataLayer || [];
dataLayer.push({
    'pageType': 'home',                   # тип страницы (полный список в README.md)
    'ecommerce': {
      'promoClick': {
        'promotions': [
         {
          'id': '2',                         // Name or ID is required.
          'name': 'Продукт недели',   
          'creative': 'productOfWeek',   	                                                    # название типа ссылки
          'position': '1'
         }]
      }
    },
    'event': 'event',
    'eventCategory': 'eecommerce',
    'eventAction': 'click',
    'eventLabel':'url',
    'eventNonInteraction': '0'
  });
</script>
```
