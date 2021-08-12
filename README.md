# Deprecated

Sorry, this project is deprecated and no longer mantained 😔

Actually in the current versions of the framework a native driver is included, so this one is no more needed 

If you still use Codeigniter 2.x and this one works for you great 👍



# Firebird for Codeigniter 2.x

This is a Firebird driver for Codeigniter 2.x

Tested on Firebird 2.x and Codeingniter 2.x

# Utilization mode / Modo de utilización

## Example / Ejemplo

Put the files in the "system/database/drivers/firebird" folder and in the "application/config/database.php" you can use a configuration like this:
```php
    $db['default']['hostname'] = "localhost";
    $db['default']['username'] = "SYSDBA";
    $db['default']['password'] = "masterkey";
    $db['default']['database'] = "databasealias"; //or "c:\mydatabase.fdb"
    $db['default']['dbdriver'] = "firebird";
```

you can provide feedback in the forum here:

http://forum.codeigniter.com/

Good Luck

Carlos GT
