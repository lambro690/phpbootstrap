This project enables you to call PHP functions to make importing and using Bootstrap easier. 
I came up with the idea when I was contantly writing HTML tags for Bootstrap by hand. 
The idea is to save you from writing the same code twice. 

This is still a work in progress, so please check back for the latest updates. 


-10/30/18-
* Initial Commit 
The only functionality that works currently is the Bootstrap import. 
You can do this by creating a folder in the root of your web directory called php-bootstrap. 
On the page you wish to have bootstrap, simply "require" the page with php. Ex.

<?php
require('/php-bootstrap/bootstrap-html.php');
?>
