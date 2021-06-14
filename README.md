# Dead Simple Login System
This system users PHP, jQuery, Bootstrap, SQL

## Instructions
You will need to create a DB config file in and as <br>
`db/meekrodb/meekrodb-2.3.1/db.conf.php` <br>
With the following<br>
```phpt
<?php
DB::$dbName = '';
DB::$user = '';
DB::$password = '';
DB::$host = '';
DB::$port = 3306; //hhvm complains if this is null
DB::$socket = null;
DB::$encoding = 'latin1';
?>
```
And run the SQL file in `sql/form.sql`

## Start 14/02/2020
This is part replica of progress made in the Forum2.0 just so i can come back to if need be
