## How to make the text type input to take only numbers
 ```
    oninput="this.value=this.value.replace(/(?![0-9])./gmi,'')"
 ```

 
 ## How to center a Div without using flex, position and grid

 ```
<!DOCTYPE html>
<html>
  <head>
    <title>Hello, World!</title>
      
    <style>
      .parent{
        width: 500px;
        height: 500px;
        background-color: red;
        align-content: center;
      }
      .child{
        width: 200px;
        height: 200px;
        background-color: black;
        margin: auto;
      }
    </style>
  </head>
  <body>
     <div class="parent">
       <div class="child">
       </div>
     </div>
  </body>
</html>

 ```