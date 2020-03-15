# Some symfony commands

With symfony app check if your computer has the needed requirements
> symfony check:requirements

Install symfony for a traditionanl web application with symfony app
> symfony new your_project_name --full

* Alt With Composer
* > composer create-project symfony/website-skeleton my_project_name

Install Symfony for microserver, console application or API
> symfony new your_project_name

* Alt With Composer
* > composer create-project symfony/skeleton your_project_name
 

Create database
> php bin/console d:d:c

Create entity with make
> php bin/console m:e EntityName

Create migration files
> php bin/console make:migration

Send migration to database
> php bin/console doctrine:migrations:migrate

> php bin/console migrate

Add fixtures to database
> php bin/console d:f:l --no-interaction

Rollback a migration
> php bin/console doctrine:migrations:execute --down id_migration

Clear cache
> php bin/console c:c

Launch server with symfony app
> symfony server:start

Launch server with php
> php -S localhost:3000 -t public

Launch cron file from Command 
> php bin/console name_defined_in_the_wanted_class
