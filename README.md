# Basket fraud

Este conjunto de datos contiene una lista de compras financiadas, en la que hay información sobre el contenido de las cestas.
Para cada línea del conjunto de datos hay 147 columnas, de las cuales 144 están agrupadas en 6 categorías:
- item,
- cash_price,
- make,
- model,
- goods_code,
- Nbr_of_prod_purchas.

Para cada una de estas categorías hay 24 instancias que se completarán con información relevante cuando un artículo exista en la cesta o serán nulas cuando no exista. Por ejemplo, si una aplicación tiene 3 artículos en la cesta, habrá información en las columnas _item1 a item3 , cash_price1 a cash_price3 , make1 a make3 , model1 a model3 , good_code1 a good_code3 y Nbr_of_prod_purchas1 a Nbr_of_prod_purchas3_; pero las columnas restantes de estas categorías serán nulas (por ejemplo: _elemento4 a elemento24_).
La variable **Nb_of_items** corresponde al número único de artículos en la cesta, y a la suma de todos ellos en los casos en que una de las instancias de **Nbr_of_prod_purchas** sea mayor que 1.
Finalmente, la variable **fraude_flag** indica si esa aplicación es fraudulenta o no.
