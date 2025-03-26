before:
![image](https://github.com/user-attachments/assets/d8b59ad9-c03f-427d-abc1-6cae7dc9f7a5)
**![image](https://github.com/user-attachments/assets/a1f91418-bc6f-4dcd-acbf-ef2cfe88b048)
**
index.html
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <title>Combining CSS Selectors</title>
  <link rel="stylesheet" href="./style.css">
</head>

<!-- Don't change any of the HTML code! -->

<body>
  <h1>To Do List</h1>
  <h2>Monday</h2>
  <div class="box">
    <p class="done">Do these things today!</p>
    <ul class="list">
      <li>Wash Clothes</li>
      <li class="done">Read</li>
      <li class="done">Maths Questions</li>
    </ul>
  </div>

  <ul>
    <p class="done">Other items</p>
  </ul>
  <p>The best preparation for tomorrow is doing your best today.</p>

</body>

</html>
AFTER:
style.css 
![image](https://github.com/user-attachments/assets/518ec727-b380-4c31-a0a8-fa2a7e4f74c6)

/* Write your code here: */
/* Group */
h1,
h2 {
  color: blueviolet;
}

/* Child */
.box > p {
  color: firebrick;
}

/* Descendent */
.box li {
  color: blue;
}

/* Chained */
li.done {
  color: green;
}

/* Multiple Combiners */
ul p.done {
  font-size: 0.5rem;
}

