# Starting a webserver on Linux

| Syntax | Description |
| ----------- | ----------- |
| `python3 -m http.server` | setup webserver using python defaults to 8000 |
| `php -S 127.0.0.1:8085` | setup webserver using php |
| `npx http-server -p 8086` | setup webserver using npm(nodejs) |
| `sudo nano /etc/apache2/ports.conf` | change default listen port to other usable ports |
| `systemctl start apache2` | start apache webserver |