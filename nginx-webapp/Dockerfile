FROM nginx:latest 

ADD webapp.html /www/
# add is enchanced version of copy because we can add website test.com/webapp.html
#add is used instead of copy when we can use test.zip it decompress the file when copied

ADD nginx.conf /etc/nginx/conf.d/default.conf 

EXPOSE 80
EXPOSE 443 

CMD nginx -g "daemon off;"
# cmd runs on startup
