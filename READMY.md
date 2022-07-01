// патерны обработки роутов

'/hello' // helo
'/hel?lo' // hello, helo
'/hel+lo' // hello, hellllllo
'/hel*lo' // hello, helc,mcnvkhvbckjnlo
'/he(la)?lo' // helo, helalo

Функции промежуточной обработки (middleware) - это функции, 
имеющие доступ к объекту запроса ( req ), 
объекту ответа ( res ) и к следующей функции ...