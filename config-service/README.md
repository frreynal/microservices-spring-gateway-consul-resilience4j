### Pour voir les propriétés

Se connecter à http://localhost:8888/<nom-application>/<profile> avec profile = dev, prod, default

Ex : http://localhost:8888/customer-service/dev


#### Refresh

Pour que les modifs du config server soient prises en compte dans les micro-services,
il faut faire un POST sur actuator/refresh du micro-service ex :

````
POST http://localhost:8081/actuator/refresh

````