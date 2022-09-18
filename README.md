# cookiew
Виджет для уведомления пользователя о том, что сайт использует куки.
# Установка
1. Скачайте последний релиз
2. Распакуйте его в корень сайта
# Пример использования
```html
<!DOCTYPE html>
<html>
<head>
	<title>Тест</title>
	<link rel="stylesheet" type="text/css" href="cookiew.css">
	<script type="text/javascript" src="cookiew.js"></script>
</head>
<body>
Тут содержимое вашего сайта..
<div id="cookiew" class="cookiew"> <!--  Блок с виджетом, должен иметь класс cookiew-->
</div>
	<script type="text/javascript">
		renderCW("cookiew"); // Если вам нужно проверять, было ли выведено уведомление ранее
    // RenderCW('cookiew') // Вывести уведомление без проверок
    // closeCookieW(); // Закрыть последнее открытое уведомление
	</script>
</body>
</html>
```

