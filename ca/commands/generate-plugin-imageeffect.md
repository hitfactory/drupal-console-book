# generate:plugin:imageeffect
Generar un connector d'efecte d'imatge.

**Usage:**
```
drupal generate:plugin:imageeffect [options]
gpie
```

## Available options
Option | Details
-------|-------------
--module | Nom del mòdul.
--class | Nom de la classe del connector
--label | Etiqueta del connector
--plugin-id | Identificador del connector
--description | Descripció del connector

## Examples
* Generate a image effect plugin specifying the module name, the class, its label, the plugin id and a description
```
drupal generate:plugin:imageeffect  \
  --module="modulename"  \
  --class="DefaultImageEffect"  \
  --label="Default image effect"  \
  --plugin-id="default_image_effect"  \
  --description="My Image Effect"
```
