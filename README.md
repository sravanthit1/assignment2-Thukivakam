# assignment2-Thukivakam
# Sravanthi Thukivakam
#### Hockey
The first organized indoor hockey game was played **March 3**, 1875 at Montreal’s Victoria Skating Rink, between two teams of nine players each, many of whom were **McGill University** students.
---------------------------------------------------------------------------------------------------------
#### National Hockey League
My favourite team that plays hockey is New Jersey Devils.
1. Nathan Bastian
2. Jesper Boqvist
3. Jesper Bratt

Teams that would be good to watch play.
- Dallas stars
- Arizona Coyotes
- Los Angeles Kings

[Link_to_AboutMe](https://github.com/sravanthit1/assignment2-Thukivakam/blob/main/AboutMe.md)
---------------------------------------------------------------------------------------------------------
### Tables
| Country | Reason | Days Spent |
| --- | --- | ---: |
| India | Different food <br> Culture | 20 days |
| Singapore | architectural wonders | 5 days |
| Paris | Eiffel Tower | 10 days |
| Maldives | spellbinding sceneries | 6 days |
| Dubai | Arabic architecture | 7 days |
---------------------------------------------------------------------------------------------------------
### Pithy quotes
>Fluent in Telugu, Tamil and Hindi. Still strugling in writing and reading Telugu-*Sravanthi Thukivakam* <br>
>Wanted to become Interior Designer, but ended up in IT - *Asritha Oruganti*
--
---------------------------------------------------------------------------------------------------------
### Code Fencing
>Custom Error Pages
[Link to stack overflow](https://stackoverflow.com/questions/25869504/htaccess-show-404-403-500-error-pages-via-php)
```
<?php

$status=$_SERVER['REDIRECT_STATUS'];
$codes=array(
      400 => array('400 Bad Request', 'The request cannot be fulfilled due to bad syntax.'),
      401 => array('401 Login Error', 'It appears that the password and/or user-name you entered was incorrect.'),
      403 => array('403 Forbidden', 'Sorry, employees and staff only.'),
      404 => array('404 Missing', 'We\'re sorry, but the page you\'re looking for is missing, hiding, or maybe it moved somewhere else and forgot to tell you.'),
      405 => array('405 Method Not Allowed', 'The method specified in the Request-Line is not allowed for the specified resource.'),
      408 => array('408 Request Timeout', 'Your browser failed to send a request in the time allowed by the server.'),
      414 => array('414 URL To Long', 'The URL you entered is longer than the maximum length.'),
      500 => array('500 Internal Server Error', 'The request was unsuccessful due to an unexpected condition encountered by the server.'),
      502 => array('502 Bad Gateway', 'The server received an invalid response from the upstream server while trying to fulfill the request.'),
      504 => array('504 Gateway Timeout', 'The upstream server failed to send a request in the time allowed by the server.'),
);

$errortitle=$codes[$status][0];
$message=$codes[$status][1];

if($errortitle==false){
       $errortitle="Unknown Error";
       $message="An unknown error has occurred.";
}

?>
<!doctype html>
<html>
<head>
<title><?php echo("$errortitle");?></title>
<meta charset="utf-8">
</head>
<body>

<!-- Insert headers here. -->

<?php
echo('<h1>'.$errortitle.'</h1>');
echo('<p>'.$message.'</p>');
?>

<!-- Insert footers here. -->

</body>
</html>
```
[css-tricks Link](https://css-tricks.com/snippets/htaccess/custom-error-pages/)