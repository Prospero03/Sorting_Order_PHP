<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <?php 
        $array = array(1,0,6,9,4,5,2);

        for ( $j = 0; $j<count($array)-1; $j++ ){
            for($i = 0; $i<count($array) - $j-1; $i++ ){
                if( $array[$i] > $array[$i+1]){
                    $tmp_var = $array[$i+1];
                    $array[$i +1] = $array[$i];
                    $array[$i] = $tmp_var;
                }
            }
        }
        var_dump($array);
    ?>
</body>
</html>
