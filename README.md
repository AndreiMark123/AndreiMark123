<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Internal Links</title>
 
 <style>
   .top{
     border: 5px solid;
     border-color: greenyellow;
     background-color: hotpink;
     text-align: center;
     padding: 30px;
     margin-bottom: 500px;
     color: darkblue;
   }
   
   .top .top-content a{
     text-decoration:none;
     font-size: 20px;
     font-weight: bold;
     color: darkblue;
   }
   
 .middle{
     border: 5px solid;
     border-color: blueviolet;
     background-color: skyblue;
     text-align: center;
     padding: 30px;
     margin-bottom: 500px;
     color: brown;
   }
   
   .middle .middle-content a{
     text-decoration:none;
     font-size: 20px;
     font-weight: bold;
     color: brown;
   }
   .bottom{
     border: 5px solid;
     border-color: orangered;
     background-color: lightgray;
     text-align: center;
     padding: 30px;
     margin-bottom: 500px;
     color: black;
   }
   
   .bottom .bottom-content a{
     text-decoration:none;
     font-size: 20px;
     font-weight: bold;
     color: black;
   }
   
   
 </style>
 
  </head>
  <body>
    
    	<div class="navigation">
    	  <a href="internal_links.html"> Click to Go to Internal Page</a> &nbsp; |
    	  <a href="external_links.html"> Click to Go to External Page</a> &nbsp;
    	</div>
    
    	<div class="content">
    	  <h1> This is Internal Page</h1>
    	</div>
    
    <div class="top" id="mytop">
    <div class="top-content">
    <h1> This is a Top content!</h1>
    <a href ="#mytop"> Click To Go Top </a> &nbsp; | &nbsp;
    <a href ="#mymiddle"> Click To Go Middle </a>&nbsp; | &nbsp;
    <a href ="#mybottom"> Click To Go Bottom </a>
    </div>
    </div>
      
 <div class="middle" id="mymiddle">
       <div class="middle-content">
         <h1> This is a Middle content!</h1>
         <a href="#mytop"> Click To Go Top </a> &nbsp; | &nbsp;
         <a href="#mymiddle"> Click To Go Middle </a>&nbsp; | &nbsp;
         <a href="#mybottom"> Click To Go Bottom </a>
       </div>
 </div>
       <div class="bottom" id="mybottom">
       <div class="bottom-content">
         <h1> This is a Bottom content!</h1>
         <a href="#mytop"> Click To Go Top </a> &nbsp; | &nbsp;
         <a href="#mymiddle"> Click To Go Middle </a>&nbsp; | &nbsp;
         <a href="#mybottom"> Click To Go Bottom </a>
       </div>
       </body>
    
  </body>
