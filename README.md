# Su- 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<h1> Tarte citron meringué</h1>
<body>
    
 <img src="img/pic.jpeg" id="tarte" width="200" height="250">

 <input type="button" onclick="changeImage()" value=" Changer l'image" />


 <script>
var x=0 ;
     function changeImage() 
     {
        
         if (x==0)
         { 
             document.getElementById('tarte').src="img/pic2.jpeg";
             x++
            
         }
         else 

         {
           document.getElementById('tarte').src="img/pic.jpeg";
           x=0
         }

         }
 </script>




<ul> 
<li> Ingrédients</li>
<br> 
<br>
<li> Recette </li>
</ul>


 
 
</body>
</html>
