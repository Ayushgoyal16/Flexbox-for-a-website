<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flexbox</title>
    <link rel="stylesheet" href="C:\Users\goyal\Desktop\HTML\qwerty23.css"/>
</head>
<body>
    <h1>Flexbox Playground</h1>
    <div id="ayush">
        <div id="ayush1">Violet</div>
        <div id="ayush2">Indigo</div>
        <div id="ayush3">Blue</div>
        <div id="ayush4">Green</div>
        <div id="ayush5">Yellow</div>
        <div id="ayush6">Orange</div>
        <div id="ayush7">Red</div>

    </div>
    
</body>
</html>


/*Css Properties used in Html*/
#ayush
{
    height:400px;
    width:800px;
   margin:20px auto;
   border:2px solid black;
   background-color: azure;
   display:flex;
   /*flex-direction:row-reverse*/
   /*flex-direction:column-reverse;*/
   /*flex-direction:column;*/
   /*justify-content: flex-start;*/
   /*justify-content:flex-end;c
   /*justify-content:center;*/
   /*justify-content:space-around;*/
   /*justify-content:space-between;*/
   flex-direction:row;
   /*flex-wrap:wrap-reverse;*/
   /*flex-wrap: wrap;*/
   /*justify-content: space-evenly;*/
   /*flex-wrap: wrap;*/
   /*align-items:flex-start;*/
   align-items:flex-start;
   align-content: flex-start;
   /*align-content: flex-end;*/
   /*align-content:center;*/
   /*align-content:space-between;*/
   /*align-content: space-around;*/
   /*align-content: baseline;*/

   flex-basis: 100px;
   flex-grow: 1;

   
}
#ayush1
{
background-color:violet;
align-self: flex-start;
/*align-self: flex-end;*/
flex-basis: 100px;

}
#ayush2
{
background-color:indigo;
/*align-self:center;*/
flex:2 100px;
}
#ayush3
{
background-color:blue;
align-self:baseline;

   flex-grow:2;
}
#ayush4
{
background-color:green;
/*flex-basis: 600px;*/
flex-shrink: 3;
}
#ayush5
{
background-color: yellow;
flex-basis: 100px;
   flex-grow:2;

}
#ayush6 {
  height: 200px;
  font-size: 200px;
  background-color: orange;
}
#ayush7
{
background-color: red;
flex:3 2 300px;
}

h1{
    text-align: center;
}

#ayush div{
  height:100px;
  width:80px;
  text-align: center;
  color: white;
  font-size: 1.7em;
}















