---
tags: html form input 
aliases: форма html, html form
---
Простая форма

```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8" />
<title>First form</title>
</head>
<body>
<h2>Let’s search something</h2>
<form>
<input type="text" />
<input type="submit" value="Search" />
</form>
</body>
</html>
```

Форма с "фокусом"

```html

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8" />
<title>Send message to us</title>
</head>
<body>
<h3>We need your opinion!</h3>
<form action="/search" method="POST">
<div>
<label for="uname">Name:</label>
<input type="text" id="uname" name="userName" />
</div>
<div>
<label for="email">Email:</label>
<input type="text" id="email" name="userEmail" />
</div>
<div>
<label for="message">Message:</label>
<textarea id="message" name="userMessage">
</textarea>
</div>
<div>
<input type="submit" value="Send my message" />
</div>
</form>
</body>
</html>
```


___
Связано: [[HTML]]

Источники:
___
