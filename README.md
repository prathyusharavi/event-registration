# Event Registration Web Application

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:

Create a new frame

### Step 2:
Select any one preset size of your choice.

### Step 3:

Select the shapes you need.



### Step 4:
import images as needed


### Step 5:
Create pages based on your need and link them

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN:
Figma

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Dream of Artificial World 2023 Registration</title>
</head>
<body>
<div id="page1">
<form action="page2.html" method="post">
<label for="userID">User ID:</label>
<input type="text" id="userID" name="userID" required>
<br><br>
<label for="password">Password:</label>
<input type="password" id="password" name="password"
required><br><br>
<input type="submit" value="Login">
</form>
</div>
<div id="page2" style="display: none;">
<form action="page3.html" method="post">
<label for="phoneNumber">Phone Number:</label>
<input type="tel" id="phoneNumber" name="phoneNumber"
required><br><br>
<label for="email">Email:</label>
<input type="email" id="email" name="email" required>
<br><br>
<label for="department">Department:</label>
<select id="department" name="department">
<option value="IT">IT</option>
<option value="Marketing">Marketing</option>
<option value="Engineering">Engineering</option>
</select><br><br>
<input type="submit" value="Next">
</form>
</div>
<div id="page3" style="display: none;">
<form action="submission.php" method="post">
<p>Please select the workshops you're interested in:</p>
<input type="checkbox" id="workshop1" name="workshop1"
value="Workshop 1">
<label for="workshop1">Workshop 1</label><br>
<input type="checkbox" id="workshop2" name="workshop2"
value="Workshop 2">
<label for="workshop2">Workshop 2</label><br>
<br>
<input type="submit" value="Submit">
</form>
</div>
<script>
document.querySelector('#page1
form').addEventListener('submit', function (e) {
e.preventDefault();
document.getElementById('page1').style.display = 'none';
document.getElementById('page2').style.display = 'block';
});
document.querySelector('#page2
form').addEventListener('submit', function (e) {
e.preventDefault();
document.getElementById('page2').style.display = 'none';
document.getElementById('page3').style.display = 'block';
});
</script>
</body>
</html>
```


## OUTPUT:
```
HOMEPAGE:
![image](https://github.com/prathyusharavi/event-registration/assets/147474424/adcad8e1-6cac-4c65-aa21-d329fa710e1c)
LOGIN PAGE:
![image](https://github.com/prathyusharavi/event-registration/assets/147474424/f1f7c1d6-bd78-4a08-a6b5-d5e8a874881f)
SEC PAGE:
![image](https://github.com/prathyusharavi/event-registration/assets/147474424/af899214-4e66-4868-94f9-b3d12079e6c4)
```


## Result: 
Thus the program executed.

