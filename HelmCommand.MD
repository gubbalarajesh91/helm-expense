Install helm chart
helm install <preffered-name> . ---> current directory
cd helm
helm install nginx .
helm uninstall nginx
helm list
helm upgrade nginx .
helm status nginx
helm history nginx
helm rollback nginx 