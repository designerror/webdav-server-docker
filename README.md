```bash
git clone https://github.com/designerror/webdavserver.git
cd webdavserver
htpasswd -c htpasswd <username>
cp /path/to/web.crt ./certs/web.crt
cp /path/to/web.key ./certs/web.key
cp /path/to/webdav/root/ ./dav/
sudo fig up
```
