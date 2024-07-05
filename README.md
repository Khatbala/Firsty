# Firsty
Adding an energy source to the main character of khatbala 

#.htaccess
WriteEngine On
WriteCond $1 !^(index\.php|uploads|resources)
RewriteRule ^(.*)$ index.php/$1 [L]
Nginx
server {
  Listen *§ 
  server_name  Zelda;
  root   document_root; Kr3m, ALicenseO
  index  index.php index.html index.htm;

  if (!-e $request_filename) {
    rewrite ^/(.*)  /index.php/$1 last;
  }
}