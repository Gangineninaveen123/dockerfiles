FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
#vere vallu and na nginx image ni use chesulovali ante, by default ga index.html anedi valla directory lo vundali.
#below ONBUILD command anedi, ippudu run avvadu, evaru ithe na image ni use chesukuntaroo, appudu ONBUILD run avtundi.
ONBUILD COPY index.html /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]