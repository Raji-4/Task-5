# Task-5
<?php
// connect to MySQL
$host = "127.0.0.1";
$user = "root";
$password = "123456";
$database = "moverecord";

$connect =  mysqli_connect($host, $user, $password, $database);
if (mysqli_connect_errno()) {
    die("cannot connect to database field:" . mysqli_connect_error());
} else {
    echo 'Database is connected';
}
?>
