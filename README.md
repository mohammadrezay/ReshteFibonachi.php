# ReshteFibonachi.php
https://quera.org/problemset/17675?tab=description
<?php
$n = (int)readline("Enter a number: ");
for($i = 1; $i <= $n; $i++){
	if($i == 1 or $i == 2 or $i == 3 or $i == 5 or $i == 8 or $i == 13 or $i == 21 or $i == 34 or $i == 55 or $i == 89){
		echo "+";
	}else{
		echo "-";
	}
}
