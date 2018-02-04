# EulerProject1
<!DOCTYPE html>
<html>
    <head > <h3 align="center">Euler Question 1 </h3></head>
    <body>
     <p align="center"> The sum of the variables below 1000 which are either multiples of 3 or 5:</p>
     <b>
        <p align="center" id="add"></p>  
      </b> 

    <script>
       var multiples_sum = 0;   //multiples_sum is initialized to zero

       for (var a = 0; a < 1000; a++) //condition for considering the varibles below 1000, 'a' be the variable
       {  
              if (a % 3 == 0 || a % 5 == 0)  //if condition to check the multiples of 3 or 5
              multiples_sum += a;      //sum is incremented if the 'if' condition satifies
       }

       document.getElementById("add").innerHTML = multiples_sum;
    </script>
    
    </body>
  
</html>
