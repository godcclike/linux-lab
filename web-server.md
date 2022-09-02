# Starting a webserver on Linux

| Syntax | Description |
| ----------- | ----------- |
| `python3 -m http.server` | setup webserver using python defaults to 8000 |
| `php -S 127.0.0.1:<portnumber>` | setup webserver using php |
| `npx http-server -p <portnumber>` | setup webserver using npm(nodejs) |
| `sudo nano /etc/apache2/ports.conf` | change default listen port to other usable ports |
| `systemctl start apache2` | start apache webserver |
| `curl -o <filename> localhost:<portnumber>` | to download webpage as a file |
| `curl -I localhost:<portnumber>` | to see request header |
| `curl -v localhost:<portnumber>` | to see request and response header |