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

Once you Log in click on Billing tab and select the Package Verification option. You can get Verification Key by Signing Up to [app.devaten.com](https://app.devaten.com/). When you Sign Up to Devaten you receive Welcome Mail & Activation Key mail. So you can verify your On-Premise Package with that Key ```OR```
You can contact Devaten for the Subscription Package.  

After activation of your package log out from Admin Account. Now your Dashboard setup is ready for User. To use this application, you need to sign up with your own E-Mail and Log in with your credentials, use the application.
