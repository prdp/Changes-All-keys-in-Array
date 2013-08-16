Changes-All-keys-in-Array
=========================

array_map('strtolower', $yourArray);    http://php.net/manual/en/function.array-map.php                         

Returns an array with all keys from input lowercased or uppercased

array_change_key_case ( array $input [, int $case = CASE_LOWER ] )  :-

<?php
$input_array = array("FirSt" => 1, "SecOnd" => 4);
print_r(array_change_key_case($input_array, CASE_UPPER));
?>
