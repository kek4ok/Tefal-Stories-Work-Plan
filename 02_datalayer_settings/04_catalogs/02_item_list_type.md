[Вернуться на главную](/README.md)
# **Типы списков товаров**

## **По страницам** 


<table>
	<tr>
        <th class="col1">№</th>
        <th class="col2">Страница</th>
        <th class="col3">Описание</th>
        <th class="col4">Значение DataLayer</th>
        <th class="col5">Пример</th>
    <!-- 1 Главная -->
    <tr>
        <td rowspan=2>1</td>
        <td rowspan=2>
            Главная 
        </td>
    </tr>
    <tr>
        <td>
            CMS ФИМ: сайт 
        </td>
        <td>
            <ol>
                <li>popularProductList</li>
                <li>seasonalOffers</li>
                <li> timelessСlassic</li>
            </ol>
        </td> 
        <td>
            <img src="../../images/02_datalayer_settings/02_banners/01_homeProductList.png" alt="01_homeProductList" width="400"/>
        </td>
    </tr>
    <!-- 2 Каталог товарных групп -->
    <tr>
        <td>2</td>
        <td>
            Каталог товарных групп 
        </td>
        <td>
            CMS ФИМ: виджет лучший товар  
        </td> 
        <td>
            theBestProductList
        </td> 
     </tr>
    <!-- 3 Карточка товара -->
    <tr>
        <td rowspan=3>3</td>
        <td rowspan=3>
            Карточка товара 
        </td>
        <td>
            CMS ФИМ: виджет сопутствующие товары
        </td> 
        <td>
            relatedProductsList
        </td> 
    </tr>
    <tr>
        <td>
            Mindbox: С этим товаром покупают
        </td> 
        <td>
            buyWithThisProduct
        </td> 
     </tr>
    <tr>
        <td>
            Mindbox: Рекомендуем вам
        </td>
        <td>
            recommendProductForYou
        </td> 
    </tr>
    <!-- 4 Страница сравнения товаров -->
    <tr>
        <td>4</td>
        <td>
            Страница сравнения товаров 
        </td>
        <td>
            Наименование вкладки на странице сравнения  
        </td> 
        <td>
            robots-pylesosy и т.д.
        </td> 
     </tr>
    <!-- 5 Страница результатов поиска -->
    <tr>
        <td>5</td>
        <td>
            Страница результатов поиска
        </td>
        <td>
            Поисковая выдача
        </td> 
        <td>
            searchResultsList
        </td> 
     </tr>
    <!-- 6 Страница избранное -->
    <tr>
        <td>6</td>
        <td>
            Страница избранное
        </td>
        <td>
            Товары на странице избранное
        </td>
        <td>
            wishList
        </td> 
     </tr>
</table>

## **По виджетам**



<table>
	<tr>
        <th class="col1">№</th>
        <th class="col2">Виджет</th>
        <th class="col3">Описание</th>
        <th class="col4">Значение DataLayer</th>
    </tr>
   <!-- 1 Виджет Добавление товара в корзину -->
    <tr>
        <td>1</td>
        <td>
            Виджет Добавление товара в корзину
        </td>
        <td>
            Вам могут понравиться
        </td> 
        <td>
            youMayLikeList
        </td> 
     </tr>
    <!-- 2 Виджет избранное -->
    <tr>
        <td>2</td>
        <td>
            Виджет избранное
        </td>
        <td>
            В хедере при кликие не иконку избранное
        </td> 
        <td>
            wishListWidget
        </td> 
     </tr>
    <!-- 3 Виджет корзина -->
    <tr>
        <td>3</td>
        <td>
            Виджет корзина
        </td>
        <td>
            В хедере при кликие не иконку корзина
        </td> 
        <td>
            cartWidget
        </td> 
     </tr>
    <!-- 4 Виджет сравнение -->
    <tr>
        <td>4</td>
        <td>
            Виджет сравнение
        </td>
        <td>
            В хедере при кликие не иконку сравнение
        </td> 
        <td>
            compareWidget
        </td> 
     </tr>
    <!-- 5 Виджет внутренний поиск -->
    <tr>
        <td>5</td>
        <td>
            Виджет внутренний поиск
        </td>
        <td>
            В поисковой строке при вводе
        </td> 
        <td>
            searchResultsListWidget
        </td> 
     </tr>
</table>
