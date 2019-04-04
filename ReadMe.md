# Service configuration 
# Pré-requis
* spring boot
* spring-cloud-config-server
* git repot for adding configuration files
# Configuration
on AgixisAppApplication add this annotations 
* @EnableConfigServer
On application.properties add this 
* server.port=port number
* spring.cloud.config.server.git.uri=file://${user.home}/cloud-conf
