# Login-password
This is a very simple login and password Script




session_start();
 
if(!session_is_registered(myusername)){
  header("location:main_login.php");
}
?>
 

<?
session_start();
session_destroy();
?>
