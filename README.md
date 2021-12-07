number2word
===========

Author: Lukasz Kosmaczewski<br>
twitter: lucosmo<br>							 
email: lukasz.kosmaczewski@gmail.com<br><br><br>

<b><i>DESCRIPTION</i></b>

Script converts numbers into words e.g.:
123 -> "one hundred twenty-three"			 	
Script uses long-scale naming system		
Max value to convert is 999 999 999 999 999 999

<b><i>HOW TO USE IT?</b></i>
<br>
Create php file in the same directory
<br><br>
Add below code in your php file:
<br><br>
require_once("num2word.php");<br>
$s=new Num2Word("999");<br>
$s->go();<br>


