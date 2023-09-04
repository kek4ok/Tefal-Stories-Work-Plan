[Вернуться на главную](/README.md)


# **Custom Dimensions 2**

<style>
   table {
    table-layout: fixed; /* Фиксированная ширина ячеек */
    width: 100%; /* Ширина таблицы */
   }
   .col1 { width: 10px; }
   .col2 { width: 20px; }
   .col3 { width: 20px; }
   .col4 { width: 90px; }
   .col5 { width: 20px; }
   .col6 { width: 20px; }
  </style>

<table>
	<tr>
	    <th class="col1">№</th>
	    <th class="col2">event parameters </th>
        <th class="col3"> Использовать (да/нет)</th> 
	    <th class="col4">Описание</th> 
        <th class="col5">Тип </th> 
        <th class="col6">Значения </th> 
	</tr >
  	<tr>
	    <td>1</td>
	    <td>page_type</td>
        <td>да</td>
        <td>Тип посещаемой страницы. Передается на всех событиях</td>
        <td>Custom</td>
        <td><a href="../02_datalayer_settings/04_catalogs/01_page_type.md" target="_blank">Типы страниц</a></td>
    </tr>
  	<tr>
	    <td>2</td>
	    <td>item_list_name</td>
        <td>да</td>
        <td>Position of the product added to cart : 
            <li> the component name : ex product finder</li>
            <li> the product list name : ex "you would also like…" or cross sell or up sell </li>
            <li> the zone if we don't have the two others values listed before ex cart, recipe …</li>
            </td>
        <td>Pre-defined</td>
        <td><a href="../02_datalayer_settings/04_catalogs/02_item_list_type.md" target="_blank">Типы списков товаров</a></td>
    </tr>
    <tr>
	    <td>3</td>
	    <td>promotion_id</td>
        <td>да</td>
        <td>Promotion ID</td>
        <td>Pre-defined</td>
        <td><a href="../02_datalayer_settings/04_catalogs/02_item_list_type.md" target="_blank">Типы баннеров</a></td>
    </tr>
    <tr>
	    <td>3</td>
	    <td>promotion_name</td>
        <td>да</td>
        <td>Name of promotion</td>
        <td>Pre-defined</td>
        <td><a href="../02_datalayer_settings/04_catalogs/03_.md" target="_blank">Типы баннеров</a></td>
    </tr>
</table>