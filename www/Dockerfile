FROM nginx:alpine
COPY certs /certs
COPY nginx.conf /etc/nginx/conf.d/default.conf
# remove COPY ./nginx.conf /etc/nginx/nginx.conf 
#  this line does not work 
# COPY nginx.conf . work fine 
# error : not allowed to add file to this path 