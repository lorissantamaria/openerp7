Docker container for OpenERP 7

To run the container ...

docker run -d -p 8069:8069 -v /var/lib/openerp:/var/lib/openerp lorissantamaria/openerp7

To run OpenERP just point your browser at http://your.docker.host:8069

Master password is Chang3M3 which you should later change in 
/var/lib/openerp/conf/openerp-server.conf

Server logs will be located at /var/lib/openerp/logs/openerp-server.log
