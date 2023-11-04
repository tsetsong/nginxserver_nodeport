Deployment steps :
    1. helm install -n ingressnginxserver ingress-nginx --namespace ingress-nginx --create-namespace -f values.yaml .
    2. openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout ingress-nginx-1.key -out ingress-nginx-1.crt -subj "/CN=vm-ubuntu-2204-1/O=ingress-nginx"
    3. kubectl create secret tls vm2204-1x-tls --key ingress-nginx-1.key --cert ingress-nginx-1.crt --namespace=ingress-nginx
    