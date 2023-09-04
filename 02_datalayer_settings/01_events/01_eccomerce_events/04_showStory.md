[Вернуться на главную](/README.md)
# **Показ истории**

Страницы, на которых работает код, триггеры находятся в таблице [тут](/02_datalayer_settings/01_events/01_ecommerce.md)

## **Код для dataLayer:**
```javascript
<script>
window.dataLayer = window.dataLayer || [];
dataLayer.push({    
  'pageType': 'home',	                     	                                            # тип страницы (полный список в README.md)
  'ecommerce': {       
    'promoView': {                                                                      
      'promotions': [
        {
        'id': '1234', 	                                                                    # id истории
        'name': 'Продукт недели',   	                                            # название истории
        'imgDesk': 'https://www.frisbuy.ru/sld07/post-media/60175/274285421.jpeg', # ссылка на изображение
        'imgTouch': 'https://www.frisbuy.ru/sld07/post-media/60175/274285421.jpeg',
        'creative': 'productOfWeek',   	                                                    # название типа истории
        'position': 1                                                                       # порядковый номер истории
        },
        <<...>>
        ]
      }
  }
 'event': 'event',
 'eventCategory': 'eecommerce',
 'eventAction': 'show',
 'eventLabel':'story',
 'eventNonInteraction': '1'
});
</script>
```


