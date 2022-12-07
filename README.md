<?php

$a = 'a';
$b = $a;

$b  = 2;

//echo $a $a = a
//echo $b $b = 2

$obj1 = new \stdClass();
$obj2 = $obj1;
$obj2->test = 'test';
echo $obj1->test; //test

