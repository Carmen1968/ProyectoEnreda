

Para el desarrollo de esta prueba he utilizado Codelgniter. 

1) En primer lugar hay que importar la base de datos enreda_db.sql a MySQL. En esta base de datos está la tabla de login user_login. 
2) Esta será la configuración de la base de datos:

$db['default'] = array(
	'dsn'	=> '',
	'hostname' => 'localhost',
	'username' => 'root',
	'password' => '',
	'database' => 'enreda_bd', 
	'dbdriver' => 'mysqli',
	'dbprefix' => '',
	'pconnect' => TRUE,
	'db_debug' => TRUE,
	'cache_on' => FALSE,
	'cachedir' => '',
	'char_set' => 'utf8',
	'dbcollat' => 'utf8_general_ci',
	'swap_pre' => '',
	'encrypt' => FALSE,
	'compress' => FALSE,
	'stricton' => FALSE,
	'failover' => array(),
	'save_queries' => TRUE
);
3) El controlador por defecto será: $route['default_controller'] = 'user_authentication'; 
4) La url de base será: $config['base_url'] = 'http://localhost/ProyectoEnreda/'; 
4) Una vez realizadas las configuraciones anteriores ya se podrá ejecutar. 


Notas: No he podido terminar por falta de tiempo (trabajo mañana y tarde), además solo tengo experiencia en back-end y era la primera vez que usaba un framework. 