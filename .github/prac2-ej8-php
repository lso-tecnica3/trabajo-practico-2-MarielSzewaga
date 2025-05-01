<?php

$meses = ["Ene", "Feb", "Mar", "Abr", "May", "Jun", "Jul", "Ago", "Sep", "Oct", "Nov", "Dic"];
$altas = [30.4, 29, 26.8, 23.4, 19.3, 16.6, 16, 17.7, 19.6, 23.1, 26.1, 28.5];
$bajas = [20.2, 19.5, 18, 15, 10.5, 8.3, 7.7, 7.8, 10.6, 13.5, 16, 18.2];


$promedioAltas = array_sum($altas) / count($altas);
$promedioBajas = array_sum($bajas) / count($bajas);


$maxTemp = max($altas);
$minTemp = min($bajas);
$mesMax = $meses[array_search($maxTemp, $altas)];
$mesMin = $meses[array_search($minTemp, $bajas)];


print "Promedio de temperaturas altas: " . number_format($promedioAltas, 2) . "°C<br>";
print "Promedio de temperaturas bajas: " . number_format($promedioBajas, 2) . "°C<br>";
print "Temperatura más alta: " . $maxTemp . "°C en " . $mesMax . "<br>";
print "Temperatura más baja: " . $minTemp . "°C en " . $mesMin . "<br>";
?>
