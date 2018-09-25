# smartdocs_tpl

This is an Apigee SmartDocs sample template for use on Apigee Drupal developer portal.

This is *not* a Drupal module. Two places to use:
1. in SmartDocs config advanced settings "upload customized method template." It can be found at: /admin/config/smartdocs
2. to use for a specific model in the settings you need to copy the code from the file and then paste it into the field "Method Template" being sure to replace the code currently there: Go to /admin/content/smartdocs/models, find the model you want to customize, click on the dropdown on the right and choose "settings."

The initial commit is from Anil's Sagar's [article on the Apigee Community site called *Apigee Developer Portal - Custom - SmartDocs Template - Request Body Parameters - SDCT002*](https://community.apigee.com/articles/48875/apigee-developer-portal-custom-smartdocs-template-1.html)

For reference the version of the template file that ships with apigee installation profile at /profiles/apigee/modules/custom/devconnect/smartdocs/templates/smartdocs.hbr has also been included and called "model_tpl_original.hbr".

The purpose here is 
1. to improve the template and work out any issues
2. share forks (hopefully well documented) to share ideas about best presentation for SmartDocs.

Note that the template uses the handlebars js templating system. More info about handlebars js can be found at https://handlebarsjs.com/.