number2word
===========

Author: Lukasz Kosmaczewski
twitter: lucosmo							 
email: lukasz.kosmaczewski@gmail.com

*******************DESCRIPTION**************************

Script converts numbers into words e.g.:
123 -> "one hundred twenty-three"			 	
Script uses long-scale naming system		
Max value to convert is 999 999 999 999 999 999

*******************HOW TO USE IT?************************

Create php file in the same directory

Add below code in your php file:

require_once("num2word.php");
$s=new Num2Word("999");
$s->go();


