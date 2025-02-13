<?php

function dividir(int $value){
    return($value / 2);
};


try{
print( dividir(6));
} catch(Throwable $e){
    echo"Error";

}

?>
