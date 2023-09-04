[Вернуться на главную](/README.md)
# **Клик по карточке товара**

**Важно:** передавать объекты и их значения только после клика пользователя на миниатюру товара.

Страницы, на которых работает код, триггеры находятся в таблице [тут](/02_datalayer_settings/01_events/01_ecommerce.md)

## **Код для dataLayer:**


```javascript
<script>
window.dataLayer = window.dataLayer || [];
dataLayer.push({
	'pageType': 'home',	                     	                                            # тип страницы (полный список в README.md)
	'catalogId': '1234',    	   									   							# Id каталога товаров
	'catalogName': 'Контейнеры для хранения продуктов', 										# название каталога товаров
	'catalogLevel': '2',																		# уровень каталога товаров
	'ecommerce': {
        'currencyCode': 'RUB',
        'click': {'actionField': {'list': 'productPage'},										# название товарного блока
			'products': [{																		# массив с товарами
			'name': 'Контейнер EMSA CLIP&CLOSE пластиковый прямоугольный, 1.2 л 508542', 		# название товара
			'id': 'СП-00034095',																# Id товара
			'price': '489.00',																	# цена товара
			'metric1': '699.00'																	# цена товара до скидки
			'brand': 'Kenwood',																	# производитель товара
			'category': 'Контейнеры для хранения продуктов',									# категория товара
			'variant': 'белый',																	# вариант товара
		}]
 	}
},
'event': 'event',
'eventCategory': 'eecommerce',
'eventAction': 'click',
'eventLabel':'productDetail',
'eventNonInteraction': '0'
});
</script>
```
