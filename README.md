# klasemen-premier

<p>Penggunaan API untuk Cek Klasemen PREMIER LEAGUE</p>




<?php
require_once('cURLclass.php');

$get 	= 	new cURL('http://bayyu.me/api/klasemen-premier/');
$data 	= 	$get->getData();




<a href="http://bayyu.me/demo/cek-klasemen/" target="_blank"><h2>DEMO</h2></a>
