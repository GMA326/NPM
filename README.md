# NPM
docker compose for Nginx Proxy Manager
I used a pre-worked code from the web for running and double checked with portainer if it works properly
login admin@example.com  
pw changeme
after first login you will be asked to change domain and pw

1. use your server ip with 81
2. use your credentials to log into nginx proxy manager
3. change the credentials as asked
4. klick on Hosts then Proxy Hosts and then add Proxy Host
5. Details = Domainname Scheme = http forward Hostname/IP = IP of the server or the name of the host and the right Port
6. Click Cache Assets and Block Common Exploits Save
7. SSL Certificates -> Add SSL Certificate -> let's Encrypt -> write registered domain name and your email and agree to the let's Encrypt termins of Service
8. Go back to Hosts and click the 3 little points overhead on the right side to edit go then to ssl use drag and drop for the lets encrypt certificate and drop Force SSL save
9. Proxy host should be access public and status online
10. have fun
