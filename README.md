# CalParse v1.1
for LaTeX  
Shorter math commands for calculus  
  
Open calparse.tex above and copy it!  

Example
------------------------------
math mode output `\calm{{Dz}/{Dx} = {2x}/{(x^2+y^2)} - {2x^3}/{(x^2+y^2)^2}}`  
![Math](/images/tex1.png)  

plain text output `$\calp{{Dz}/{Dx} = 5/6}$`  
![Text](/images/tex2.png)  
  
String replacement table  
-------------------------------
```
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
```
  
Known bugs
-------------------------------
- incompatible with \sin \cos \tan \arctan etc. in falign and others
