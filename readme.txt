mkdir -p /web/uploads
apt-get install php5-fpm
curl https://getcaddy.com | bash
caddy -quic 

echo "# test" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/dincerkurnaz/test.git
git push -u origin master
