<p align = "center">МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ<br>
РОССИЙСКОЙ ФЕДЕРАЦИИ<br>
ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ<br>
ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ<br>
«САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»</p>
<br><br><br><br><br><br>
<p align = "center">Институт естественных наук и техносферной безопасности<br>Кафедра информатики<br>Коньков Никита Алексеевич</p>
<br><br><br>
<p align = "center">Лабораторная работа №9<br><b>«Разработка серверных скриптов»</b><br>01.03.02 Прикладная математика и информатика</p>
<br><br><br><br><br><br><br><br><br><br><br><br>
<p align = "right">Научный руководитель<br>
Соболев Евгений Игоревич</p>
<br><br><br>
<p align = "center">г. Южно-Сахалинск<br>2022 г.</p>
<br><br><br><br><br><br><br><br><br><br><br><br>

<h1 align = "center">Введение</h1>

<p> <b>HTML</b> (или же HyperText Markup Language) - стандартизированный язык разметки документов для просмотра веб-страниц в браузере. Веб-браузеры получают HTML документ от сервера по протоколам HTTP/HTTPS или открывают с локального диска, далее интерпретируют код в интерфейс, который будет отображаться на экране монитора. </p>

<p><b>PHP</b> (произносится пи-эйч-пи́) — скриптовый язык программирования, созданный для генерации HTML-страниц на веб-сервере и работы с базами данных. На сегодняшний момент поддерживается подавляющим большинством представителей хостингов. Входит в «LAMP» — «стандартный» набор для создания веб-сайтов.</p>

<h1 align = "center">Цели и задачи</h1>

<p>1.	По заходу на страницу выведите сколько дней осталось до нового года.</p>

<p>2.	Дан инпут и кнопка. В этот инпут вводится год. По нажатию на кнопку выведите на экран, високосный он или нет.</p>

<p>3.	Дан инпут и кнопка. В этот инпут вводится дата в формате '01.12.1990'. По нажатию на кнопку выведите на экран день недели, соответствующий этой дате, например, 'воскресенье'.</p>

<p>4.	По заходу на страницу выведите текущую дату в формате '12 мая 2015 года, воскресенье'.</p>

<p>5.	Дан инпут и кнопка. В этот инпут вводится дата рождения в формате '01.12.1990'. По нажатию на кнопку выведите на экран сколько дней осталось до дня рождения пользователя.</p>

<p>6.	По заходу на страницу выведите сколько дней осталось до ближайшей масленницы (последнее воскресенье весны).</p>

<p>7.	Дан инпут и кнопка. В этот инпут вводится дата рождения в формате '31.12'. По нажатию на кнопку выведите знак зодиака пользователя.</p>

<p>8.	Дан массив праздников. По заходу на страницу, если сегодня праздник, то поздравьте пользователя с этим праздником.</p>

<p>9.	Сделайте скрипт-гороскоп. Внутри него хранится массив гороскопов на несколько дней вперед для каждого знака зодиака. По заходу на страницу спросите у пользователя дату рождения, определите его знак зодиака и выведите предсказание для этого знака зодиака на текущий день.</p>

<p>10. Дан текстареа и кнопка. В текстареа вводится текст. По нажатию на кнопку выведите количество слов в тексте, количество символов в тексте, количество символов за вычетом пробелов.</p>

<p>11. Дан текстареа и кнопка. В текстареа вводится текст. По нажатию на кнопку нужно посчитать процентное содержание каждого символа в тексте.</p>

<p>12. Дан массив слов, инпут и кнопка. В инпут вводится набор букв. По нажатию на кнопку выведите на экран те слова, которые содержат в себе все введенные буквы.</p>

<p>13. Дан текстареа и кнопка. В текстареа через пробел вводятся слова. По нажатию на кнопку выведите слова в таком виде: сначала заголовок 'слова на букву а' и под ним все слова, которые начинаются на 'а', потом заголовок 'слова на букву б' и все слова на 'б' и так далее. Буквы должны идти в алфавитном порядке. Брать следует только те буквы, на которые начинаются наши слова. То есть: если нет слов, к примеру, на букву 'в' - такого заголовка тоже не будет.</p>

<p>14. Дан инпут и кнопка. В этот инпут вводится строка на русском языке. По нажатию на кнопку выведите на экран транслит этой строки.</p>

<p>15. Дан инпут, 2 радиокнопочки и кнопка. В инпут вводится строка, а с помощью радиокнопочек выбирается - нужно преобразовать эту строку в транслит или из транслита обратно.</p>

<p>16. Дан массив с вопросами и правильными ответами. Реализуйте тест: выведите на экран все вопросы, под каждым инпут. Пользователь читает вопрос, пишет свой ответ в инпут. Когда вопросы заканчиваются - он жмет на кнопку, страница обновляется и вместо инпутов под вопросами появляется сообщение вида: 'ваш ответ: ... верно!' или 'ваш ответ: ... неверно! Правильный ответ: ...'. Правильно отвеченные вопросы должны гореть зеленым цветом, а неправильно - красным.</p>

<p>17. Модифицируем предыдущую задачу: пусть теперь тест показывает варианты ответов и радиокнопочки. Пользователь должен выбрать один и вариантов.</p>

<p>18. Модифицируем предыдущую задачу: пусть теперь на один вопрос может быть несколько правильных ответов. Пользователь должен отметить один или несколько чекбоксов.</p>

<p>19. Напишите скрипт, который будет считать факториал числа. Само число вводится в инпут и после нажатия на кнопку пользователь должен увидеть результат.</p>

<p>20. Напишите скрипт, который будет находить корни квадратного уравнения. Для этого сделайте 3 инпута, в которые будут вводиться коэффициенты уравнения.</p>

<p>21. Даны 3 инпута. В них вводятся числа. Проверьте, что эти числа являются тройкой Пифагора: квадрат самого большого числа должен быть равен сумме квадратов двух остальных.</p>

<p>22. Дан инпут и кнопка. В инпут вводится число. По нажатию на кнопку выведите список делителей этого числа.</p>

<p>23. Дан инпут и кнопка. В инпут вводится число. По нажатию на кнопку разложите число на простые множители.</p>

<p>24. Даны 2 инпута и кнопка. В инпуты вводятся числа. По нажатию на кнопку выведите список общих делителей этих двух чисел.</p>

<p>25. Даны 2 инпута и кнопка. В инпуты вводятся числа. По нажатию на кнопку выведите наибольший общий делитель этих двух чисел.</p>

<p>26. Даны 2 инпута и кнопка. В инпуты вводятся числа. По нажатию на кнопку выведите наименьшее число, которое делится и на одно, и на второе из введенных чисел.</p>

<p>27. Даны 3 селекта и кнопка. Первый селект - это дни от 1 до 31, второй селект - это месяцы от января до декабря, а третий - это годы от 1990 до 2025. С помощью этих селектов можно выбрать дату. По нажатию на кнопку выведите на экран день недели, соответствующий этой дате, например, ‘воскресенье'.</p>

<h1 align = "center">Решение</h1>  

```php
<!DOCTYPE html>
<html lang="ru">
<head>
	<meta charset="ISO-8859-1">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Document</title>
</head>
<body>
<?php
function RusToLat($a)
{
	$ru = [
		"А", "Б", "В", "Г", "Д", "Е", "Ё", "Ж", "З", "И", "Й", "К", "Л", "М", "Н", "О", "П", "Р", "С", "Т", "У", "Ф", "Х", "Ц", "Ч", "Ш", "Щ", "Ъ", "Ы", "Ь", "Э", "Ю", "Я",
		"а", "б", "в", "г", "д", "е", "ё", "ж", "з", "и", "й", "к", "л", "м", "н", "о", "п", "р", "с", "т", "у", "ф", "х", "ц", "ч", "ш", "щ", "ъ", "ы", "ь", "э", "ю", "я"
	];
	$lat = [
		"A", "B", "V", "G", "D", "E", "Yo", "Zh", "Z", "I", "J", "K", "L", "M", "N", "O", "P", "R", "S", "T", "U", "F", "H", "C", "Ch", "Sh", "Shh", "``", "Y", "`", "E", "Yu", "Ya",
		"a", "b", "v", "g", "d", "e", "yo", "zh", "z", "i", "j", "k", "l", "m", "n", "o", "p", "r", "s", "t", "u", "f", "h", "c", "ch", "sh", "shh", "``", "y", "`", "e", "yu", "ya"
	];
	return str_replace($ru, $lat, $a);
}

function LatToRus($a)
{
	$ru = [
		"А", "Б", "В", "Г", "Д", "Е", "Ё", "Ж", "З", "И", "Й", "К", "Л", "М", "Н", "О", "П", "Р", "С", "Т", "У", "Ф", "Х", "Ц", "Ч", "Ш", "Щ", "Ъ", "Ы", "Ь", "Э", "Ю", "Я",
		"а", "б", "в", "г", "д", "е", "ё", "ж", "з", "и", "й", "к", "л", "м", "н", "о", "п", "р", "с", "т", "у", "ф", "х", "ц", "ч", "ш", "щ", "ъ", "ы", "ь", "э", "ю", "я"
	];
	$lat = [
		"A", "B", "V", "G", "D", "E", "Yo", "Zh", "Z", "I", "J", "K", "L", "M", "N", "O", "P", "R", "S", "T", "U", "F", "H", "C", "Ch", "Sh", "Shh", "``", "Y", "`", "E", "Yu", "Ya",
		"a", "b", "v", "g", "d", "e", "yo", "zh", "z", "i", "j", "k", "l", "m", "n", "o", "p", "r", "s", "t", "u", "f", "h", "c", "ch", "sh", "shh", "``", "y", "`", "e", "yu", "ya"
	];
	return str_replace($lat, $ru, $a);
}
?>
<?php
	echo "Задание 1 <br>";

	$rightNow = time();
	$notNow = mktime(0, 0, 0, 01, 01, 2023);
	$goal = $notNow - $rightNow;
	echo "До нового года осталось " . floor($goal/3600/24) . " дней<br>";

	echo "<br> Задание 2 <br>";
?>
<br>
<form action="" method="get" >
Год: <input type="text" name="year"> <br>
<input type="submit">
</form>
<?php
	if (!empty($_GET["year"])) 
	{
		$year = $_GET["year"];
		if($year % 4 == 0){
			if($year % 100 == 0){
				if($year % 400 == 0){
					echo "Год високосный<br>";
				}
				else{
					echo "Год не високосный<br>";
				}
			}
			else{
				echo "Год високосный<br>";
			}
		}
		else{
			echo "Год не високосный<br>";
		}
	}
	else
	{
		echo "Вы оставили поле записи пустым<br>";
	}
	echo "<br>Задание 3 <br>";
?>
<br>
<form action="" method="get" >
Дата: <input type="text" name="date"> <br>
<input type="submit">
</form>
<?php
	if (!empty($_GET["date"])) 
	{
		$date = date_create($_GET["date"]);
		echo "День недели заданной даты " . date_format($date, "l") . "<br>";
	}
	else
	{
		echo "Вы оставили поле записи пустым<br>";
	}
	echo "<br>Задание 4 <br>";
?>
<br>
<?php
	
	echo date("d F Y, l",time());
	echo "<br>Задание 5 <br>";

?>
<br>
<form action="" method="get" >
Дата: <input type="text" name="bd"> <br>
<input type="submit">
</form>
<?php
	if (!empty($_GET["bd"])) 
	{
		$date = explode('.', $_GET['bd']);
		$rightNow = time();
		$rightNowYear = date("Y", time());
		$birthDate = mktime(0, 0, 0, $date[1], $date[0], $rightNowYear);
		$currDay = date("d.m.Y", time());
		$BirthDay = $date[0] . '.' . $date[1] . '.' . $rightNowYear;
		if($currDay == $BirthDay){
			echo "День рожднения сегодня!";
		}
		else if($birthDate < $rightNow){
			$birthDate = mktime(0, 0, 0, $date[1], $date[0], $rightNowYear + 1);
			$goal = floor(($birthDate - $rightNow)/3600/24);
			echo  "День рождения через " . $goal . " дней";
		}
		else{
			$goal = floor(($birthDate - $rightNow)/3600/24);
			echo "День рождения через " . $goal . " дней";
		}
	}
	else
	{
		echo "Вы оставили поле записи пустым<br>";
	}
	echo "<br>Задание 6 <br>";
?>
<br>
<?php

$rightNow = time();
$goal = 0;
for ($i = 28; $i >= 1; $i--) {
    if (date('w', mktime(0, 0, 0, 2, $i)) == 0) {
        $goal = mktime(23, 59, 59, 2, $i) + 1;
        break;
    }
}

if ($goal > $rightNow) {
    echo "До масленницы осталось " . floor(($goal - $rightNow)/3600/24) . " дней<br>";
} else {
    echo "До масленницы осталось " . floor(($goal - $rightNow + 3600*24*365)/3600/24) . " дней<br>";
}

echo "<br>Задание 7 <br>";

?>
<br>
<form action="" method="get" >
Дата Рождения (формат 31.12): <input type="text" name="zodiak"> <br>
<input type="submit">
</form>
<?php

if (!empty($_GET["zodiak"])) {
	$date = explode('.', $_GET['zodiak']);
	$bD = $date[1] . $date[0];
	if(($bD >= '2103') && ($bD <= '2004')){
		echo "Овен<br>";
	} else if(($bD >= '0421') && ($bD <= '0520')){
		echo "Телец<br>";
	} else if(($bD >= '0521') && ($bD <= '0620')){
		echo "Близнецы<br>";
	} else if(($bD >= '0621') && ($bD <= '0722')){
		echo "Рак<br>";
	} else if(($bD >= '0723') && ($bD <= '0822')){
		echo "Лев<br>";
	} else if(($bD >= '0823') && ($bD <= '0922')){
		echo "Дева<br>";
	} else if(($bD >= '0923') && ($bD <= '1022')){
		echo "Весы<br>";
	} else if(($bD >= '1023') && ($bD <= '1121')){
		echo "Скорпион<br>";
	} else if(($bD >= '1122') && ($bD <= '1221')){
		echo "Стрелец<br>";
	} else if((($bD >= '1222') && ($bD <= '1231')) || (($bD >= '0101') && ($bD <= '0119'))){
		echo "Козерог<br>";
	} else if(($bD >= '0120') && ($bD <= '0218')){
		echo "Водолей<br>";
	} else if(($bD >= '0219') && ($bD <= '0320')){
		echo "Рыбы<br>";
	} else{
		echo "Дата задана неверно<br>";
	}
	
}
else{
	echo "Вы не ввели дату рождения<br>";
}

echo "<br>Задание 8 <br>";

?>
<br>
<?php

$holidaysArray = [
	'18.11' => 'День маринованного огурчика',
    '19.11' => 'День глазированного сырка'
];

$date = date('d.m', time());

if (array_key_exists($date, $holidaysArray)) {
    echo $holidaysArray[$date] . "<br>";
} else{
	echo "Сегодня праздников нет<br>";
}

echo "<br>Задание 9 <br>";

?>
<br>
<form action="" method="get" >
Дата Рождения (формат 31.12): <input type="text" name="zodiakAndGor"> <br>
<input type="submit">
</form>
<?php
$arrayGor = [
    'Овен' => ['03.12' => 'Всё будет хорошо', '04.12' => 'Всё будет плохо'],
    'Телец' => ['03.12' => 'Всё будет хорошо', '04.12' => 'Всё будет плохо'],
    'Близнецы' => ['03.12' => 'Всё будет хорошо', '04.12' => 'Всё будет хорошо'],
    'Рак' => ['03.12' => 'Всё будет плохо', '04.12' => 'Всё будет хорошо'],
    'Лев' => ['03.12' => 'Всё будет плохо', '04.12' => 'Всё будет плохо'],
    'Дева' => ['03.12' => 'Всё будет хорошо', '04.12' => 'Всё будет плохо'],
    'Весы' => ['03.12' => 'Всё будет плохо', '04.12' => 'Всё будет плохо'],
    'Скорпион' => ['03.12' => 'Всё будет плохо', '04.12' => 'Всё будет плохо'],
    'Стрелец' => ['03.12' => 'Всё будет плохо', '04.12' => 'Всё будет хорошо'],
    'Козерог' => ['03.12' => 'Всё будет плохо', '04.12' => 'Всё будет плохо'],
    'Водолей' => ['03.12' => 'Всё будет плохо', '04.12' => 'Всё будет хорошо'],
    'Рыбы' => ['03.12' => 'Всё будет хорошо', '04.12' => 'Всё будет плохо']
];

if (!empty($_GET["zodiakAndGor"])) {
	$date = explode('.', $_GET['zodiakAndGor']);
	$bD = $date[1] . $date[0];
	if(($bD >= '2103') && ($bD <= '2004')){
		$zn = "Овен";
	} else if(($bD >= '0421') && ($bD <= '0520')){
		$zn = "Телец<br>";
	} else if(($bD >= '0521') && ($bD <= '0620')){
		$zn = "Близнецы";
	} else if(($bD >= '0621') && ($bD <= '0722')){
		$zn = "Рак";
	} else if(($bD >= '0723') && ($bD <= '0822')){
		$zn = "Лев";
	} else if(($bD >= '0823') && ($bD <= '0922')){
		$zn = "Дева";
	} else if(($bD >= '0923') && ($bD <= '1022')){
		$zn = "Весы";
	} else if(($bD >= '1023') && ($bD <= '1121')){
		$zn = "Скорпион";
	} else if(($bD >= '1122') && ($bD <= '1221')){
		$zn = "Стрелец";
	} else if((($bD >= '1222') && ($bD <= '1231')) || (($bD >= '0101') && ($bD <= '0119'))){
		$zn = "Козерог";
	} else if(($bD >= '0120') && ($bD <= '0218')){
		$zn = "Водолей";
	} else if(($bD >= '0219') && ($bD <= '0320')){
		$zn = "Рыбы";
	} else{
		echo "Дата задана неверно<br>";
		return;
	}

	$rightNow = date('d.m', time());
	$rightNow = date_create($rightNow);
    date_modify($rightNow, "+ 1 day");
    $nextDay = date_format($rightNow, "d.m");
    echo $arrayGor[$zn][$nextDay];
	
}
else{
	echo "Вы не ввели дату рождения<br>";
}

echo "<br>Задание 10 <br>";

?>
<br>
<form action="" method="get">
    <input type="text" name="string">
    <input type="submit">
</form>
<?php

if (!empty($_GET["string"])){
	$string = $_GET["string"];
	$wordsCount = count(explode(" ", $string));
	$spacesCount = strlen($string) - $wordsCount + 1;
	echo "Количество слов в тексте = " . $wordsCount . ", Количество символов в тексте = " . strlen($string) . ", Количество символов за вычетом пробелов = " . $spacesCount . "<br>";
}
else{
	echo "Строка пуста<br>";
}

echo "<br>Задание 11 <br>";

?>
<br>
<form action="" method="get">
    <input type="text" name="percent">
    <input type="submit">
</form>
<?php

if (!empty($_GET["percent"])){
	$string = $_GET["percent"];
	$length = strlen($string);
	$count = array_count_values(str_split($string));
	foreach($count as $key => $item){
		$res = 100 / $length * $item;
		echo "символ " . $key . ", Процентное содержание = " . round($res, 2) . "%<br>";
	}
}
else{
	echo "Строка пуста<br>";
}

echo "<br>Задание 12 <br>";

?>
<br>
<form action="" method="get" >
Строка: <input type="text" name="equal"> <br>
<input type="submit">
</form>
<?php

$words = ['hello', 'world', 'javascript', 'example', 'aha', 'ohayo', 'little', 'cake', 'joke'];

if (!empty($_GET["equal"])){
	$chars = str_split($_GET['equal']);
    $wordsNew = [];
    $count = count($chars);
    foreach ($words as $word) {
        $good = true;
        for ($i = 0; $i < $count; $i++) {
            if (!strpbrk($word, $chars[$i])) {
                $good = false;
            }
        }
        if ($good) {
            $wordsNew[] = $word;
        }
    }
    foreach ($wordsNew as $word) {
        echo $word . " ";
    }
	echo "<br>";
}
else{
	echo "Строка пуста<br>";
}

echo "<br>Задание 13 <br>";

?>
<br>
<form action="" method="get">
    <input type="text" name="abc">
    <input type="submit">
</form>
<?php

$abc = ['а', 'б', 'в', 'г', 'д', 'е', 'ё', 'ж', 'з', 'и', 'й', 'к', 'л', 'м', 'н', 'о', 'п', 'р', 'с', 'т', 'у', 'ф', 'х', 'ц', 'ч', 'ш', 'щ', 'ы', 'э', 'ю', 'я'];

if (!empty($_GET["abc"])){
	$words = explode(' ', $_GET['abc']);
    $res = [];
    foreach ($abc as $x) {
        foreach ($words as $word) {
            $word = strtolower($word);
            if (substr($word, 0, 1) == $x) {
                $res[$x][] = $word;
            }
        }
    }
    foreach ($res as $key => $item) {
        echo 'Слова на букву '.$key.'<br>';
        foreach ($item as $x) {
            echo $x . '<br>';
        }
    }
}
else{
	echo "Строка пуста<br>";
}

echo "<br>Задание 14 <br>";

?>
<br>
<form action="" method="get">
    <input type="text" name="trans">
    <input type="submit">
</form>
<?php
if (!empty($_GET["trans"])){
	echo RusToLat($_GET["trans"]) . "<br>";
}
else{
	echo "Строка пуста<br>";
}

echo "<br>Задание 15 <br>";

?>
<br>
<form action="" method="get">
    <input type="text" name="TransMeth">
    <input type="submit"><br>
    <input type="radio" name="radio" value="Into" checked><label>RUS - LAT</label><br>
    <input type="radio" name="radio" value="From"><label>LAT - RUS</label><br>
  </form>
<?php

if (!empty($_GET["TransMeth"])){
	if($_GET["radio"] == "Into"){
		echo RusToLat($_GET["TransMeth"]) . "<br>";
	} else {
		echo LatToRus($_GET["TransMeth"]) . "<br>";
	}
}
else{
	echo "Строка пуста<br>";
}

echo "<br>Задание 16 <br>";

?>
<br>

<style>
    .yes {
      background-color: green;
    }

    .no {
      background-color: red;
    }

	p {
		width: 450px;
	}
</style>

<form action="" method="get">
    <?php
    $questions = [
      "Сколько дней в году? (не високосный)" => "365",
      "Самый большой орган человека?" => "кожа",
      "Сколько человек у нас в группе?" => "12",
    ];

    $i = 1;

    foreach ($questions as $Q => $answer) {
      echo $Q . "<br>";
      if (!empty($_GET["question$i"])) {
        if ($_GET["question$i"] === $answer){
			echo "<p class = 'yes'>Ответ: " . $_GET["question$i"] . " - ";
			echo "<span>Правильный ответ!";
		} else {
			echo "<p class = 'no'>Ответ: " . $_GET["question$i"] . " - ";
			echo "<span>неверно!";
		}
        echo "</span></p>";
      } else {
        echo '<input type="text" name="question' . $i . '"><br>';
	  }
      $i++;
    }
    ?>
    <input type="submit">
  </form>

<?php

echo "<br>Задание 17 <br>";

?>
<br>

<form action="" method="get">
    <?php
    $questions = [
      "Сколько дней в году? (не високосный)" => "365",
      "Самый большой орган человека?" => "кожа",
      "Сколько человек у нас в группе?" => "12",
    ];

	$wrong = [
		1 => "364",
		2 => "толстая кишка",
		3 => "13",
	];

    $i = 1;
	$ans = "";

    foreach ($questions as $Q => $answer) {
		echo $Q . "<br>";
		$ans = $Q;
    	if (!empty($_GET["rad$i"])) {
        	if ($_GET["rad$i"] === $answer){
				echo "<p class = 'yes'>Ответ: " . $_GET["rad$i"] . " - ";
				echo "<span>Правильный ответ!";
			} else {
				echo "<p class = 'no'>Ответ: " . $_GET["rad$i"] . " - ";
				echo "<span>неверно!";
			}
        	echo "</span></p>";
      	} else {
			echo "<input type='radio' name='rad" . $i . "' value='" . $wrong[$i] . "'>" . "<label>" . $wrong[$i] . "<label>";
			echo "<input type='radio' name='rad" . $i . "' value='" . $questions[$Q] . "'>" . "<label>" . $questions[$Q] . "<label>";

			echo "<br>";
		
	  	}
      $i++;
    }
    ?>
    <input type="submit">
  </form>

<?php

echo "<br>";
echo "<br>Задание 18 <br>";

?>
<br>

<form action="" method="get">
    <?php
    $questions = [
      "Сколько дней в году? (не високосный)" => ["365", "Не знаю"],
      "Самый большой орган человека?" => ["Кожа", "Не знаю"],
      "Сколько человек у нас в группе?" => ["12", "Не знаю"],
    ];

	$overAll = [
		["365", "364", "Не знаю"],
		["Кожа", "Толстая кишка", "Не знаю"],
		["12", "13", "Не знаю"],
	];

    $i = 0;
	$ans = "";

    foreach ($questions as $Q => $answer) {
		echo $Q . "<br>";
		$ans = $Q;
    	if (!empty($_GET["submit"])) {
			echo "Ваш ответ: ";
			$answers = [];
			for ($j = 0; $j < count($overAll[$i]); $j++) {
				if (!empty($_GET["check$i$j"])) {
				array_push($answers, $_GET["check$i$j"]);
				}
			}
			echo implode(", ", $answers) . " - ";
			if (!array_diff($answers, $answer) && !array_diff($answer, $answers)){
				echo "<span class = 'yes'>Правильный ответ";
			} else {
				echo "<span class = 'no'>Неверно";
			}
			echo "</span></p>";
		} else {
			for($j = 0; $j < count($overAll[$i]); $j++){
				echo "<input type='checkbox' name='check" . $i . $j . "' value='" . $overAll[$i][$j] . "'>" . "<label>" . $overAll[$i][$j] . "<label>";
			}

			echo "<br>";
		
	  	}
      $i++;
    }
    ?>
    <input type="submit" name="submit">
	<input type="submit" value="Очистить">
	<i>
  </form>
  

<?php

echo "<br>";
echo "<br>Задание 19 <br>";

?>
<br>
<form action="" method="get">
    <input type="text" name="factor">
    <input type="submit">
  </form>
<?php

if (!empty($_GET["factor"])){
	$num = $_GET["factor"];
	$res = 1;
	for($i = 1; $i <= $num; $i++){
		$res *= $i;
	}
	echo "Факториал " . $num . " = " . $res . "<br>";
}

echo "<br>Задание 20 <br>";

?>
<br>
<form action="" method="get">
    <label>a = </label>
    <input type="text" name="coef1">
    <label>b = </label>
    <input type="text" name="coef2">
    <label>c = </label>
    <input type="text" name="coef3">
    <br>
    <input type="submit">
  </form>
<?php

if(!empty($_GET["coef1"]) && !empty($_GET["coef2"]) && !empty($_GET["coef3"])){
	$a = $_GET["coef1"];
	$b = $_GET["coef2"];
	$c = $_GET["coef3"];
	$disc = $b * $b - (4 * $a * $c);
	$discSqrt = sqrt(abs($disc));

	if($disc == 0){
		$x = -$b / (2 * $a);
		echo "x = " . $x . "<br>";
	} else if($disc > 0){
		$x1 = (-$b + $discSqrt) / (2 * $a);
		$x2 = (-$b - $discSqrt) / (2 * $a);
		echo "x1 = " . $x1 . "<br>";
		echo "x2 = " . $x2 . "<br>";
	} else {
		echo "x1 = (" . -$b . " + " . $discSqrt . "i) / " . 2 * $a . "<br>";
		echo "x2 = (" . -$b . " - " . $discSqrt . "i) / " . 2 * $a . "<br>";
	}

} else {
	echo "Вы ввели не все коэффициенты уравнения";
}

echo "<br>Задание 21 <br>";

?>
<br>
<form action="" method="get">
    <label>a = </label>
    <input type="text" name="pif1">
    <label>b = </label>
    <input type="text" name="pif2">
    <label>c = </label>
    <input type="text" name="pif3">
    <br>
    <input type="submit">
</form>
<?php

if(!empty($_GET["pif1"]) && !empty($_GET["pif2"]) && !empty($_GET["pif3"])){
	$a = $_GET["pif1"];
	$b = $_GET["pif2"];
	$c = $_GET["pif3"];
	$max = 0;
	$sum = 0;

	if($a < $b){
		$max = $b;
		$sum += $a * $a;
	} else {
		$max = $a;
		$sum += $b * $b;
	}

	if($max < $c){
		$sum += $max * $max;
		$max = $c;
	} else {
		$sum += $c * $c;
	}

	$max *= $max;

	if($max > $sum){
		echo "Числа являются тройкой Пифагора<br>";
	} else {
		echo "Числа не являются тройкой Пифагора<br>";
	}

} else {
	echo "Вы ввели не все числа<br>";
}

echo "<br>Задание 22 <br>";

?>
<br>
<form action="" method="get">
    <input type="text" name="div22">
    <input type="submit">
</form>
<?php

if(!empty($_GET["div22"])){
	$num = $_GET["div22"];
	$correct = [];
	for($i = 1; $i <= $num; $i++){
		if($num % $i == 0){
			array_push($correct, $i);
		}
	}

	echo implode(" ", $correct) . "<br>";
	
	echo "<br>";

} else {
	echo "Вы не ввели число<br>";
}

echo "<br>Задание 23 <br>";

?>
<br>
<form action="" method="get">
    <input type="text" name="razl">
    <input type="submit">
</form>
<?php

if(!empty($_GET["razl"])){

	$num = $_GET["razl"];
	$correct = [];
    $i = 1;

    while ($num != 1) {
      $i++;
      if ($num % $i == 0) {
        array_push($correct, $i);
		$num /= $i;
        $i = 1;
      }
    }

    echo implode(" ", $correct) . "<br>";
	
	echo "<br>";

} else {
	echo "Вы не ввели число<br>";
}

echo "<br>Задание 24 <br>";

?>
<br>
<form action="" method="get">
    <input type="text" name="zad241">
	<input type="text" name="zad242">
    <input type="submit">
</form>
<?php

if(!empty($_GET["zad241"]) && !empty($_GET["zad242"])){

	$num1 = $_GET["zad241"];
	$num2 = $_GET["zad242"];
	$correct = [];
	if($num1 > $num2){
		$min = $num2;
	} else {
		$min = $num1;
	}

	for($i = 1; $i <= $min; $i++){
		if($num1 % $i == 0 && $num2 % $i == 0){
			array_push($correct, $i);
		}
	}

    echo implode(" ", $correct) . "<br>";

	echo "<br>";

} else {
	echo "Вы не ввели все числа<br>";
}

echo "<br>Задание 25 <br>";

?>
<br>
<form action="" method="get">
    <input type="text" name="zad251">
	<input type="text" name="zad252">
    <input type="submit">
</form>
<?php

if(!empty($_GET["zad251"]) && !empty($_GET["zad252"])){

	$num1 = $_GET["zad251"];
	$num2 = $_GET["zad252"];
	$correct = [];
	if($num1 > $num2){
		$min = $num2;
	} else {
		$min = $num1;
	}

	for($i = 1; $i <= $min; $i++){
		if($num1 % $i == 0 && $num2 % $i == 0){
			array_push($correct, $i);
		}
	}

    echo $correct[count($correct) - 1] . "<br>";

	echo "<br>";

} else {
	echo "Вы не ввели все числа<br>";
}

echo "<br>Задание 26 <br>";

?>
<br>
<form action="" method="get">
    <input type="text" name="zad261">
	<input type="text" name="zad262">
    <input type="submit">
</form>
<?php

if(!empty($_GET["zad261"]) && !empty($_GET["zad262"])){

	$num1 = $_GET["zad261"];
	$num2 = $_GET["zad262"];
	$i = 1;

	while(true){
		if($i % $num1 == 0 && $i % $num2 == 0){
			$res = $i;
			break;
		}
		$i++;
	}

    echo $res . "<br>";

	echo "<br>";

} else {
	echo "Вы не ввели все числа<br>";
}

echo "<br>Задание 27 <br>";

?>
<br>
<form action="" method="get">
    <input type="text" name="zad271"><label>День(1-31)</label>
	<input type="text" name="zad272"><label>Месяц(1-12)</label>
	<input type="text" name="zad273"><label>Год(1990-2025)</label>
    <input type="submit">
</form>
<?php

if(!empty($_GET["zad271"]) && !empty($_GET["zad272"]) && !empty($_GET["zad273"])){

	$d = $_GET["zad271"];
	$m = $_GET["zad272"];
	$y = $_GET["zad273"];

	$massOfDays = ["Понедельник", "Вторник", "Среда", "Четверг", "Пятница", "Суббота", "Воскресенье"];

	echo $massOfDays[date("N", strtotime("$d.$m.$y")) - 1];
	echo "<br>";

} else {
	echo "Вы не ввели все числа<br>";
}

?>
</body>
</html>
```

<h1 align = "center">Вывод</h1>
<p>Опираясь на материал с сайта w3school, помощь различных руководств, Я выполнил лабораторную работу и научился некоторым функциям в mySQL (на php).</p>