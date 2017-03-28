# Sample command

`sudo ansible-playbook -e client=ghana -e pmsDatabaseHost=popo -e pmsDatabaseName=pokl -e pmsDatabaseUsername=uhy -e pmsDatabasePassword=gtf -e sleDatabaseHost=popo -e sleDatabaseName=pokl -e sleDatabaseUsername=uhy -e sleDatabasePassword=gtf  -e dgeDatabaseName=popo -e dgeDatabaseUsername=pokl -e dgeDatabaseHost=uhy -e dgeDatabasePassword=gtf -e dgwDatabaseName=popo -e dgwDatabaseUsername=pokl -e dgwDatabaseHost=uhy -e dgwDatabasePassword=gtf -e rmsDatabaseName=popo -e rmsDatabaseUsername=pokl -e rmsDatabaseHost=uhy -e rmsDatabasePassword=gtf main.yml`

`ansible-playbook -i hosts.yml -e target=test application_provision.yml`

`ansible-playbook -i hosts.yml -e target=test -e client=ghana -e pmsDatabaseHost=popo -e pmsDatabaseName=pokl -e pmsDatabaseUsername=uhy -e pmsDatabasePassword=gtf -e sleDatabaseHost=popo -e sleDatabaseName=pokl -e sleDatabaseUsername=uhy -e sleDatabasePassword=gtf  -e dgeDatabaseName=popo -e dgeDatabaseUsername=pokl -e dgeDatabaseHost=uhy -e dgeDatabasePassword=gtf -e dgwDatabaseName=popo -e dgwDatabaseUsername=pokl -e dgwDatabaseHost=uhy -e dgwDatabasePassword=gtf -e rmsDatabaseName=popo -e rmsDatabaseUsername=pokl -e rmsDatabaseHost=uhy -e rmsDatabasePassword=gtf application_deployment.yml`

# ESXI 

To setup a vm in esxi machine

# Application provisoning

To setup applications on server - JRE, JBOSS4, JBOSS7, MYSQL

# Application Deployment

To set up applications on Jboss servers, db credentials, properties files etc


