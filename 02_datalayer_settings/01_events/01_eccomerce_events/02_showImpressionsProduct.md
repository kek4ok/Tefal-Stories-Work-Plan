[Вернуться на главную](/README.md)
# **Показ товаров**

**Важно:** передавать объекты и их значения только в момент видимости элементов на экране пользователя.

Страницы, на которых работает код, триггеры находятся в таблице [тут](/02_datalayer_settings/01_events/01_ecommerce.md)

## **Код для dataLayer:**

```javascript
<script>
window.dataLayer = window.dataLayer || [];
dataLayer.push({
	'pageType': 'home',	                     	                                            # тип страницы (полный список в README.md)
	'catalogId': '1234',    	   									   							# Id каталога товаров
	'catalogName': 'Контейнеры для хранения продуктов', 										# название каталога товаров
	'catalogLevel': '2',
	  'ecommerce': {       
	     'currencyCode': "RUB",                                                                 # необязательный параметр
	     'impressions': [             	  	  	                                                # массив с загруженными товарами
	       {
		'name': 'Ланч-бокс EMSA CLIP & GO со вставками, 1,2 л, зелёный 518098',	            # название товара
		'id': 'СП-00034095',    	         	                                            # Id товара
		'price': '1890.00',       	                                                        # цена товара
		'metric1': '2690.00',                                                               # цена товара до скидки
		'brand': 'EMSA',   	                                                                # производитель товара
		'category': 'Контейнеры для хранения продуктов',                                	# вкладка
		'variant': 'зелёный',          		                                                # вариант товара        
		'list': 'bestsellerList',    		                                                            # название товарного блока                   
		'position': '1'         	                                                            # порядковый номер товара в блоке    	
	      },
		{
		'name': 'Контейнер EMSA CLIP&CLOSE пластиковый прямоугольный, 1.2 л 508542',
		'id': 'СП-00034113',    	         	    
		'price': '489.00',       	      
		'metric1': '699.00',       	     
		'brand': 'EMSA',   	     
		'category': 'Контейнеры для хранения продуктов',     	
		'variant': 'белый',          	  	  	        	  
		'list': 'newProductList',    		  	                      
		'position': '2'         	               	  
	      }]
	      <<...>>
	  },
	 'event': 'event',
	 'eventCategory': 'eecommerce',
	 'eventAction': 'show',
	 'eventLabel':'impressionsProduct',
	 'eventNonInteraction': '1'
	});
	</script>
	```