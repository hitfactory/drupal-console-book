# user:password:reset
Reinicialitzar una contrasenya per un usuari determinat.

**Usage:**
```
drupal user:password:reset [arguments]
upr
upsr
```

## Available arguments
Argument | Details
---------|-------------
user | User name/id
password | Contrasenya en text sense format

## Examples
* Update password specifying the user id and the new password
```
drupal user:password:reset  2 p455w0rd
```
* Update password specifying the user jmolivas and the new password
```
drupal user:password:reset jmolivas p455w0rd
```
