AlimentosApp
============

Aplicación de ejemplo construida con Symfony2 para el curso de Symfony2. 


Instalación
-----------

    # git clone https://github.com/juanda/AlimentosApp.git
    # cd AlimentosApp
    # sudo chmod -R 777 app/cache app/logs
    # composer.phar update
    # php app/console assets:install web --symlink

Y crear una base de datos llamada ``alimentos``:

    CREATE TABLE `alimentos` (
    `id` int(11) NOT NULL AUTO_INCREMENT,
    `nombre` varchar(255) NOT NULL,
    `energia` decimal(10,0) NOT NULL,
    `proteina` decimal(10,0) NOT NULL,
    `hidratocarbono` decimal(10,0) NOT NULL,
    `fibra` decimal(10,0) NOT NULL,
    `grasatotal` decimal(10,0) NOT NULL,
    PRIMARY KEY (`id`)
    ) ENGINE=InnoDB  DEFAULT CHARSET=utf8;
