## Odoo-Installation-with-Docker

### Steps
1. Clone: `git clone https://github.com/Arafath1019/Odoo-Installation-with-Docker.git`
2. Run: `docker-compose up`
3. Browse: http://localhost:8069

### Important links
* [How to install Odoo 16 in Docker?](https://www.cybrosys.com/blog/how-to-install-odoo-16-in-docker)

### Reference odoo.conf setup
```
[options]
; This is the password that allows database operations:
admin_passwd = admin1234
db_host = db
db_port = 5432
db_user = odoo
db_password = odoo
addons_path = /var/lib/odoo/.local/share/Odoo/addons/13.0,/usr/lib/python3/dist-packages/odoo/addons,/mnt/extra-addons
; If you are using custom modules
```