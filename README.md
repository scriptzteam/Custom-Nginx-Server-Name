# Custom-Nginx-Server-Name
Customize Your Nginx Server Name

```
apt install nginx nginx-extras

Edit your nginx.conf to set a custom string as "Server"

more_set_headers 'Server: some-string-here';

save and restart
service nhinx restart
```
Done!
