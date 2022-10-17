# Devaten-OnPremise-Dashboard

### Run Devaten Dashboard 

Open Command Prompt in the cloned folder where docker-compose.yml, mysql and README.md exists.

Run command pull containers locally-
```
docker compose pull
```
Once its done execute the command-
```
docker compose up
```
it runs the docker images/containers exists in the docker compose file.

when you see the message ```Tomcat started on port(s): 8081``` that means dashboard runs successfully & you can access the Devaten Dashboard using URL- [localhost:8081](http://localhost:8081/)

Login with 
***ADMIN CREDENTIALS:***  
```Username: admin@system.com```
```Password: 123456```

Once you Log in, click on Billing tab and select the Package Verification option. You can get Verification Key by Signing Up to [app.devaten.com](https://app.devaten.com/). When you Sign Up to Devaten you receive Welcome Mail & Activation Key Mail. So you can verify your On-Premise Package with that Key ```OR```
You can contact Devaten for the Subscription Package.  

After activation of your package log out from Admin Account. Now your Dashboard setup is ready for User. To use this application, you need to sign up with your own E-Mail and Log in with your credentials, use the application.

Firstly add Agent, for that you need On-Premise Agent Running on your system. You can get On-Prem Agents from our [GitHub Repositories](https://github.com/devatengit)
[named: Onpremise-MYSQL, OnPremise MSSQL, OnPremise-MARIADB, OnPremise-MONGODB, OnPremise-ORACLE, OnPremise-POSTGRESQL]

To connect ```On-Premise Agent``` to ```On-Premise-Dashboard``` need to do change in ```On-Premise Agent Docker Compose```. You have to add your systems ```IP Address``` in ```environment:```

- spring.activemq.broker-url=tcp://```IP_ADDRESS```:61616

To know more about how to add Agent, Application, Configure Datasource, Alertings and Start/Stop Recordings you can refer our [Devaten Documents](https://app.devaten.com/#/docs/getting_started).

After that if you want to stop/remove Docker Containers press ```ctrl + c``` and then run command-
```
docker compose down
```
