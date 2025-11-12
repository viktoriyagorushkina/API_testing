# API_testing


1. Я создала <a href="https://docs.google.com/spreadsheets/d/13F3SqQkT8GsVRRE4qFwi5nX10LyYTxcF/edit?usp=drive_link&ouid=109099841188130348235&rtpof=true&sd=true">коллекцию</a> в POSTMAN: 

    Задание:
 <ul>
<li>  Перейдите по  <a href="https://docs.google.com/spreadsheets/d/13F3SqQkT8GsVRRE4qFwi5nX10LyYTxcF/edit?usp=drive_link&ouid=109099841188130348235&rtpof=true&sd=true">ссылке</a> и изучите документацию в Swagger.</li>
<li> Создай коллекцию "DemoShopping".</li>
<li> Создай папку "Products" и "Cart"и оформь все методы, которые относятся к этим категориям в Swagger.</li>
<li> Для всех методов Products напиши автотесты, которые могут проверять: статус-код после отправки запроса (обязательный тест), проверки для тела (тип данных в значениях, изменение ключа и значения для POST и т.д.), время ответа и т.д.</li>
<li> Создай переменные окружения QA, которые будут часто переиспользоваться, например, базовый URL, token и ID. Подумайте, что еще можно добавить в них.  </li> 
</ul>
 <ul>  
2. Используя следующий <a href="http://webservices.oorsprong.org/websamples.countryinfo/CountryInfoService.wso?WSDL">WSDL</a>, я создала в Postman рабочую <a href="https://www.postman.com/olyaskh/workspace/my-workspace/collection/26094887-82437438-8394-4d13-9860-8d57d336d8be?action=share&creator=26094887">коллекцию</a> , с помощью которой можно получать информацию о целевой стране: 
 
 <ul> 
    Задание:
  <ul>   
 Cоздать коллекцию в Postman для тестирования данного сервиса, который позволяет получать информацию о целевой стране.
  <a href="https://docs.google.com/spreadsheets/d/13F3SqQkT8GsVRRE4qFwi5nX10LyYTxcF/edit?usp=drive_link&ouid=109099841188130348235&rtpof=true&sd=true">Список</a> ISO-кодов стран для тестирования методов.
  В коллекцию должны попасть следующие методы:
 <li> ListOfContinentsByName</li>
 <li> CountryName</li>
 <li> FullCountryInfo</li>
 <li> LanguageName</li>
В качестве страны, которую необходимо ввести для отправки запроса, используйте свою родную страну.</ul>
</ul>
