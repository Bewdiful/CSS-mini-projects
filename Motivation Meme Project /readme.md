
![image](https://github.com/user-attachments/assets/dbf79c9b-5b8f-4e84-87f6-ccde4d263b5f)

![image](https://github.com/user-attachments/assets/6355541f-e5d1-4c23-a9b7-90c881a79fd8)


style.css
body {
    background-color: black;
  }
  h1 {
    text-transform: uppercase;
    font-size: 3rem;
  }
  
  .poster {
    width: 50%;
    margin-left: 25%;
    margin-top: 100px;
    color: white;
    font-family: "Libre Baskerville", serif;
    text-align: center;
  }
  
  .motivation-img {
    border: 5px solid white;
    width: 100%;
  }

  index.html 
  <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <link rel="stylesheet" href="style.css">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Libre+Baskerville&display=swap" rel="stylesheet">
</head>

<body>

  <div class="poster">
    <img class="motivation-img" src="./assets/images/daenerys.jpeg" src="daenerys with egg" />
    <h1>That Special Moment</h1>
    <p>When you find the perfect avocado at the supermarket</p>
  </div>
<div class="poster">
  <img class="motivation-img" src="./assets/images/image.png" src="kid" />
  <h1>HAS BEEN A MEME FOR 10 YEARS</h1>
  <p>Still popular</p>
</div>

</html>
<!-- 
  TODO: Create a motivational post website.
Style it how ever you like. 
Look at the goal image for inspiration.
But it must have the following features:
1. The main h1 text should be using the Regular Libre Baskerville Font from Google Fonts:
  https://fonts.google.com/specimen/Libre+Baskerville
2. The text should be white and background black.
3. Add your own image into the images folder inside assets. It should have a 5px white border.
4. The text should be center aligned.
5. Create a div to contain the h1, p and img elements. Adjust the margins so that the image and text are centered on the page. 
  Hint: You horizontally center a div by giving it a width of 50% and a margin-left of 25%.
  Hint: Set the image to have a width of 100% so it fills the div. 
6. Read about the text-transform property on MDN docs to make the h1 uppercase with CSS.
  https://developer.mozilla.org/en-US/docs/Web/CSS/text-transform 
-->
