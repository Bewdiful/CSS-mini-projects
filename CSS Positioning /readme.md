https://developer.mozilla.org/en-US/docs/Web/CSS/position

https://codepen.io/pen

![image](https://github.com/user-attachments/assets/ec653cff-1d20-473b-bae6-94ba75ef6891)


goal:

![image](https://github.com/user-attachments/assets/6706b82a-b1a9-43dc-acc2-a14e2e3e3db9)

![image](https://github.com/user-attachments/assets/06b46074-3acd-48da-a2dc-76d82c4870d4)

before:
![image](https://github.com/user-attachments/assets/11bd5dbd-2202-421b-9b82-da85aa208a84)

after:


using:
https://appbrewery.github.io/css-positioning/

and the extension

<!DOCTYPE html>
<html>

<head>
  <title>CSS Positioning Exercise</title>
  <style>
    .red-circle {
      width: 200px;
      height: 200px;
      background-color: red;
      border-radius: 50%;
      position: absolute;
      top: 150px;
      left: 250px;
    }
    
    .blue-box {
      background-color: blue;
      width: 500px;
      height: 300px;
      position: relative;
      top: 200px;
      left: 200px;
    }

  </style>
</head>

<body>
  <div class="blue-box">
    <div class="red-circle"></div>
  </div>
</body>

</html>
