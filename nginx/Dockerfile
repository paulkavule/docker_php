FROM nginx

#COPY your.cert.pem /etc/nginx/your.cert.pem
#COPY your.cert.key /etc/nginx/your.cert.key

RUN rm /etc/nginx/conf.d/default.conf
COPY nginx.conf /etc/nginx/conf.d