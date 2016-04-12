##Required PIP Packages

MySQL-python

##MySQL Setup
- Copy db.cnf.template and rename db.cnf
- Fill in the values for the different configurations
- Copy db.cnf to $OPENSHIFT_DATA_DIR
- Each time the application is deployed this file will be copied to $OPENSHIFT_REPO_DIR where the app is running from

##Static Files
Each time the application is deployed the static files will be collected

##Migrations
Each time the application is deployed the pending migrations will be applied
