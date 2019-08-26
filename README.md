# Blog-coded-full
Version1 Full
Version1 All 12 sections.
create .htaccess text file in the folder containing index.php and paste the following contents:
RewriteEngine on
RewriteCond %{REQUEST_URI} ^/(data|lib|templates|vendor)/
RewriteRule ^ - [L,R=404]

