Закрыл историю при просмотре

[Вернуться на главную](/README.md)
# **Закрыл предпросмотр истории**

Страницы, на которых работает код, триггеры находятся в таблице [тут](/02_datalayer_settings/01_events/02_interactions.md)

## **Код для dataLayer:**

### **Код для закрытия через крестик в верхнем правом углу:**

```javascript
<script>
window.dataLayer = window.dataLayer || [];
dataLayer.push({    
 'pageType': 'homeStory',	                     	                                            # тип страницы
 'event': 'event',
 'eventCategory': 'interactions',
 'eventAction': 'close',
 'eventLabel': 'story_<id истории>', #id истории - уникальный код истории из бекэнда
 'eventNonInteraction': 0
});
</script>
```

### **Код для закрытия в любом другом месте:**
```javascript
<script>
window.dataLayer = window.dataLayer || [];
dataLayer.push({    
 'pageType': 'homeStory',	                     	                                            # тип страницы
 'event': 'event',
 'eventCategory': 'interactions',
 'eventAction': 'closeClickAway',
'eventLabel': 'story_<id истории>', #id истории - уникальный код истории из бекэнда
 'eventNonInteraction': 0
});
</script>
```
