[Вернуться на главную](/README.md)
# **Клик по истории**

Страницы, на которых работает код, триггеры находятся в таблице [тут](/02_datalayer_settings/01_events/01_ecommerce.md)

## **Код для dataLayer:**

### **Клик по истории из закрытого режима. В результате открывается предпросмотр:**
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
          'creative': 'productOfWeek',   	                                                    # название типа истории
          'position': '1'
         }]
      }
    },
    'event': 'event',
    'eventCategory': 'eecommerce',
    'eventAction': 'click',
    'eventLabel':'story',
    'eventNonInteraction': '0'
  });
</script>
```


### **Клик по истории из состояния предпросмотра. История уже открыта в предпросмотре:**
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
          'creative': 'productOfWeek',   	                                                    # название типа истории
          'position': '1'
         }]
      }
    },
    'event': 'event',
    'eventCategory': 'eecommerce',
    'eventAction': 'click',
    'eventLabel':'story',
    'eventNonInteraction': '0'
  });
</script>
```