# php-array_combine
PHP function array_combine
<?php
//array combine= 2 array same element
$arr1= array('dhaka','capital','bangladesh');
$arr2= array(1,2,3);
$arr3= array_combine($arr1,$arr2);
echo "<pre>";
print_r($arr3);
echo "<pre>";
echo "<br><br>";
$arr1= array("c","c++");
$arr2= array(1,2);
$arr3= array_combine($arr1,$arr2);
echo "<pre>";
print_r($arr3);
echo "</pre>";
?>
