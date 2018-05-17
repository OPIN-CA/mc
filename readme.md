Helper module for YAML Content module - part of Whirlwind profile.

## Intro ##

The module must not be enabled. It only acts as a yaml file repository to be imported by YAML Content module.

## Installation ##
Enable [**YAML Content**](https://www.drupal.org/project/yaml_content) module  using Drush

```yml
 drush en yaml_content
 ``` 
or using Drupal Console
```yml 
drupal moi yaml_content
``` 


## Using ##
References detail how to create YAML files with different content types and entities.

Use **content/demo.content.yml** as a example file to create dummy content. 

Run

```yml
drush ycim mc
```
to import content into the site once yaml files are created. 


## References ##

- Field Templates[https://www.drupal.org/docs/8/modules/yaml-content/field-templates-v8x-1x]

- Examples and Snippets[https://www.drupal.org/docs/8/modules/yaml-content/examples-and-snippets-v8x-1x]
- Creating a YAML Content Event Subscriber [https://www.drupal.org/docs/8/modules/yaml-content/creating-a-yaml-content-event-subscriber]
- Introducing the YAML Content Module[https://www.mediacurrent.com/blog/introducing-yaml-content-module/]
- Creating Content with YAML Content Module [https://www.mediacurrent.com/blog/creating-content-yaml-content-module/]

## Changelog ##

### v1.0 ###
- Initial release

