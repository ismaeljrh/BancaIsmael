# BancaIsmael
Proyecto de banca en web y API

para correr el proyecto debe tener instalado Mysql

cree una base de datos llamada bancaismael tipo InnoBD cotejamiento utf8mb4_general_ci, ejecute el archivo ubicado en la carpeta bdd bancaismael.sql que creara las tablas necesarias para el proyecto 
el archivo esta con las varibales por defecto( $dbUsername = 'root';  $dbUserPassword = '';) cambie estos valores para que coincidad con el usuario de su MYSQL y en el caso que su servidor de Mysql no sea local cambiar la varible ( $dbHost = 'localhost' ) indicando la ruta de su server 

el proyeto esta en PHP puro en version 8 solo es necesario que su server tenga activo el mod_rewrite

el proyecto esta pensado para implementarse en localhost pero puede cambiarse la ruta del servidor en la carpeta datos archivo configuracion.php $URLServidor 

