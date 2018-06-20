FROM amd64/busybox

MAINTAINER admin@kubekit99.cloud

ADD kubekit/index.html /www/index.html
EXPOSE 80
CMD httpd -p 80 -h /www; tail -f /dev/null
