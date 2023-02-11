<?php
  session_start();
  if (isset($_POST['username']) && isset($_POST['password'])) {
    if ($_POST['username'] == 'admin' && $_POST['password'] == 'password') {
      $_SESSION['logged_in'] = true;
      header('Location: home.php');
    } else {
      $_SESSION['logged_in'] = false;
      echo 'Incorrect username or password';
    }
  }
?>
