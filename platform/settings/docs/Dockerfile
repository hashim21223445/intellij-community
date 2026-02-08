FROM nginxinc/nginx-unprivileged:1.29.3
COPY --chown=101:101 nginx.conf /etc/nginx/conf.d/default.conf
COPY --chown=101:101 site /usr/share/nginx/html