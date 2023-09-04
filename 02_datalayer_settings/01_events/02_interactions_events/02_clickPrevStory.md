[Вернуться на главную](/README.md)
# **Клик по кнопке предыдущая история**

Страницы, на которых работает код, триггеры находятся в таблице [тут](/02_datalayer_settings/01_events/02_interactions.md)

## **Код для dataLayer:**


```javascript
<script>
window.dataLayer = window.dataLayer || [];
dataLayer.push({
    'pageType': 'home',	                     	                                            # тип страницы
    'event': 'event',
    'eventCategory': 'interactions',
    'eventAction': 'click',
    'eventLabel': 'prevStories',
    'eventNonInteraction': 0
});
</script>
```

