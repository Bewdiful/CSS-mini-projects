The CSS BOX Model margin, padding and border
before we start install chrome extension Pesticide:
A CSS debugging tool that inserts outlines onto all elements to help with debugging layout issues
https://chromewebstore.google.com/detail/pesticide/bakpbgckdnepkmkeaiomhmfcnejndkbi?pli=1

https://sabe.io/classes/css/css-box-model-padding-border-margin
The CSS box model is a very important concept to grasp. The box model is a way to describe the layout of an element and its content. The most important CSS properties we will go over are padding, border, and margin.

Here is a nice diagram of the CSS box model:

![image](https://github.com/user-attachments/assets/a5cae5a0-c18d-471c-ab9a-6e816ae65ea7)

![image](https://github.com/user-attachments/assets/ed4ca3ac-4ef8-46ed-991f-9624d561de49)



press inspect on the box model
![image](https://github.com/user-attachments/assets/6569e611-6254-4aee-8ddd-fe4b3a1a82e3)
![image](https://github.com/user-attachments/assets/e6bc61c8-08dd-4cf9-b607-086254fd8c77)

goal:
![image](https://github.com/user-attachments/assets/6fc1c559-ac87-4664-a946-1ad0d59a08e3)

todo:
![image](https://github.com/user-attachments/assets/3c60ab82-a7fe-403d-adbf-91a3115385c3)

after:

<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <title>CSS Box Model</title>
  <style>
    div {
      height: 200px;
      width: 200px;
    }

    p {
      margin: 0;
    }

    #first {
      background-color: cadetblue;
      padding: 20px;
      border: 10px solid black;
    }

    #second {
      background-color: gold;
      border: solid black;
      border-width: 20px 10px;
      margin-left: 260px;
    }

    #third {
      background-color: indianred;
      border: 10px solid black;
      margin-left: 40px;
    }
  </style>
</head>

<body>
  <div id="first">
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam at sapien porttitor urna elementum lacinia. In
      id magna pulvinar, ultricies lorem id, vehicula elit. Aliquam eu luctus nisl, vitae pellentesque magna. Phasellus
      dolor metus, laoreet ac convallis sit amet, efficitur sed dolor. </p>
  </div>
  <div id="second">

  </div>
  <div id="third">

  </div>
</body>

</html>
</body>

</html>

  <!-- TODOs:
1. Create 3 Boxes using the div element.
i will use id to set the css using #top box
2. Set their sizes to 200px heigh by 200px wide.
3. Set different background colors for each of the boxes (I used cadetblue, gold and indianred).
4. Add a paragraph <p> element into the first div and add the following words:
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam at sapien porttitor urna elementum lacinia. In
    id magna pulvinar, ultricies lorem id, vehicula elit. Aliquam eu luctus nisl, vitae pellentesque magna. Phasellus
    dolor metus, laoreet ac convallis sit amet, efficitur sed dolor.
5. Set the 1st div to have 20px padding all around with a black 10px border.
6. Fix the style of the <p> element to remove all margins.
Hint: Use the CSS inspector in Chrome.
7. Set the 2nd div to have a 20px border on top and bottom and 10px border left and right. (See goal image)
8. Set the 3rd div to have a 10px border 
9. Set the margins for the divs so that each box corner touches the other. (See the goal image)
-->
