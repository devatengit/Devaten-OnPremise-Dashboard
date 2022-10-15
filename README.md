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

when you see the message ```Tomcat started on port(s): 8081``` that means dashboard runs successfully & can access the Devaten using URL-
```
localhost:8081
```
