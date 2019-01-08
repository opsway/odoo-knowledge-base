# Odoo Knowledge Base

## Functional 
Inventory Terminology: https://www.odoo.com/documentation/user/12.0/inventory/overview/concepts/terminologies.html 

### Routes
Creating automatic route for stock movement https://www.youtube.com/watch?v=T-tzrcJL0sg

Warehouse management with examples and ideas about routes/push/pull rules: https://www.odoo.com/slides/slide/introduction-to-odoo-warehouse-management-44

### Importing data

How to import simple data, Many2One, One2Many, Many2Many records https://fr.slideshare.net/Audaxis/opendays-import-csv-2013v5

Example how to import multiline documents: https://github.com/lumirang/odoo-knowledge-base/wiki/Importing-data

Example how to import product with multiple attributes and values: https://www.youtube.com/watch?v=tafkwl5dO_k


### Issues
Website and mulitcompany issue:
https://www.odoo.com/forum/help-1/question/fiscal-localization-multi-company-issue-with-webiste-odoo12-141961

## Warehouse

Warehouse management https://www.youtube.com/watch?v=Zj8_8Uh3EAo
Stock accounting https://www.youtube.com/watch?v=m9jUeUi2OcI&t=3152s
Putaway strategy https://www.youtube.com/watch?v=UkYZSKR7AzU

## Manufacturing

https://www.youtube.com/watch?v=PjZJVKT_AF4 - Odoo v12 manufacturing


## Project Management

Implementation stratery https://www.odoo.com/openerp_portal/static/src/pdf/odoo_implementation.pdf


# Development

## Backend
### Database
* Migaration: https://doc.therp.nl/openupgrade/
### Connector
Odoo connector: http://odoo-connector.com/

### Security:
Generic security structure overview and tips to avoid vulnerability:
https://www.youtube.com/watch?v=27K-LmTPnZQ

### Jobs
Main module to use for jobs: https://apps.odoo.com/apps/modules/11.0/queue_job/

### Testing
Pytest for odoo: https://github.com/camptocamp/pytest-odoo

### Extra model, tab in the backend menu
 * Create extra model: https://www.odoo.com/documentation/12.0/howtos/backend.html
 * Add new button to existing menu:
   * https://stackoverflow.com/questions/30050145/how-to-add-new-menu-item-to-an-existing-odoo-module
   * https://stackoverflow.com/questions/52439859/odoo-10-extending-existing-module-to-show-new-menu-item?rq=1
   * https://www.odoo.com/forum/help-1/question/how-to-add-a-new-action-menu-item-16786

## Frontend
### Odoo Javascript framework
- Create JS module: https://github.com/lumirang/odoo-assets-managment
* Angular: https://github.com/akretion/angular-odoo
* React: https://www.npmjs.com/package/react-native-odoo

## Performance
* Optimizing PostgreSQL for Odoo: https://www.odoo-consultants.com/2016/01/23/improve-your-odoo-postgresql-performance/
* BigData in Odoo: https://www.odoo-consultants.com/2017/09/23/big-data-odoo-optimization/
* Common performance-related mistakes in Odoo custom apps https://www.slideshare.net/openobject/performance2014-35689113

## DevOps
### How to Deploy Odoo with Docker:
  One can use https://github.com/lumirang/odoo-docker-extend repo in two ways, eather make a fork and add your addons, or add your existing repo as submodule. For more details see repository readme.
  
## Quality
Common tools to use for code quality:
* https://github.com/OCA/maintainer-quality-tools
* https://github.com/OCA/pylint-odoo
Usefull to watch about automating code quality:
https://www.youtube.com/watch?v=G1lDk_WKXvY

