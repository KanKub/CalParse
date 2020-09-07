# CalParse v1.1
for LaTeX

Example
------------------------------
plain text output  
\cm{{Dz}/{Dx} = {2x}/{(x^2+y^2)} - {2x^3}/{(x^2+y^2)^2}} 

math mode output  
$\cp{{Dz}/{Dx} = 5/6}$
String replacement table
-------------------------------
 D  -> partial  
*(  -> \left(  
*)  -> \left)  
*[  -> \left[  
*]  -> \left]  
.   -> \cdot
{abc}/{def}   -> \frac{abc}{def}  
a/b           -> \frac{a}{b}  
{abc}*/{def}  -> \dfrac{abc}{def}  
a*/b          -> \dfrac{a}{b}  

