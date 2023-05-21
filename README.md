<!DOCTYPE html>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<html>
<head>
  <title>Our Menu</title>

 <style>
    /* CSS Styling */
    body {
      font-family: Arial, sans-serif;
      background-color: white;
      margin: 0;
      padding: 20px;
    }
    
    h1 {
      text-align: center;
      font-size: 24.5px;
      font-family: Arial
    }
    
    .menu-container {
      text-align: left;
      margin-top:100px
    }

    .Test {
      position: absolute;
      top: 0;
      right: 0;
      width: 120px;
      height: 30px;
      border: 1px solid black;
      text-align: center;
      font-size: 18px ;
      font-weight: bold;
    }

    .Test.Chicken {
      background-color: khaki;
    }

    .Test.Beef {
      background-color: lightsalmon;
    }

    .Test.Sushi {
      background-color: lightpink;
    }

    .section {
      position: relative;
      float: left;
      height: 120px;
      width: 100% ;
      margin : 10px ;
      font-family: Arial;
      background-color: grey;
      border: 2px solid black;
      padding: 20px ;
      position: relative;
      font-size: 14px
    }
    
    @media (min-width: 992px) {
      .section {
        width: calc(33.33% - 65px);
      }
    }

    @media (min-width: 768px) and (max-width: 991px) {
      .section {
        width: calc(50% - 70px);
      }
      
      .section-ld {
        width: calc(100% - 75px);
        clear: both;
      }
    }

    @media (max-width: 767px) {
      .section {
        width: calc(100% - 65px);
      }
    }
</style>


</head>
<body>
  <h1>Our Menu</h1>
  
  <div class="menu-container">
    <div class="section section-md">

<div class="Test Chicken">
Chicken
</div>

      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
      tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
      quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
      consequat.</p>
      
      </div>
    
    <div class="section section-md">
      <div class="Test Beef">
Beef
</div>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
      tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
      quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
      consequat.</p>
    </div>
    
    <div class="section section-ld">

      <div class="Test Sushi">
Sushi 
</div>
      <p>
      Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
      tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
      quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
      consequat.</p>
    </div>
  </div>
</body>
</html>
