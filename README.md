ZendSkeletonApplication
=======================

If already have your Zend Application & Just want to add "Album" Module, than Follow these basic steps :

1) Open your git bash.

2) Go to your directory.

3) Run Command : git clone https://github.com/priyankmodi/zf-local.git

4) Find Album.zip & Extract it into your Zend application's module folder.

5) Add module name 'Album' in config/application.config.php in modules array.

6) Find zf2.sql & import into your DB.

7) Check your site at http://site-url/piblic/album.



=======================

To Add whole new Zend Framework Follow these basic steps :

1) Open your git bash.

2) Go to your directory.

3) Run Command : git clone https://github.com/priyankmodi/zf-local.git

4) Create DB in mysql & Import zf2.sql(from root directory).

5) Set DB name in config/autoload/global.php, and to set DB credentials create a local.php file there.
   In local.php, set your credentials like this :
   
   <?php
  
   return array(
    	
    	'db' => array(
             
             'username' => 'root',
            
             'password' => '',
         
         ),
         
    );

6) Run your site at http://site-url/public
