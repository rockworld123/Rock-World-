# Rock-World-
<!DOCTYPE html>
<html>
<head>
   <title> Try It Yourself </title>
   <style type="text/css">
      .dd {
         position: reletive;
         display: inline-block;
      }
      .dd-btn {
         padding: 15px;
         text-align: left;
         background: #173459;
         border: none;
         width: 45px;
         color: red;
      }
      .dd-content {
         position: absolute;
         display: none;
         width: 100%;
         box-shadow: 0 18px 36px rgba(0,0,0,0.30), 0 14px 11px rgba(0,0,0,0.22);
      }
      .dd:hover > .dd-content {
         display: block;
      }
      .dd-content > a {
         display: block;
         padding: 15px;
         text-decoration: none;
         color: black;
      }
      .dd-content > a:hover {
         color: white;
         background: #903C56;
      }
   </style>
</head>
<body>   
   <div class="dd">
      <button class="dd-btn"> Menu </button>
      <div class="dd-content">
         <a href="#"> Home </a>
         <a href="#"> About </a>
         <a href="#"> Sign up/Login</a>
      </div>
   </div>
</body>
</html>
