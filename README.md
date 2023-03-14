# bootcamp_devops-k8s_mini-projet-
Mini projet Kubernetes: Dépoyer Wordpress à l'aide de manifests

## Notes:
Example of secret file with imperative command:

> kubectl create secret generic wordpress-secret --from-literal=WORDPRESS_DB_PASSWORD=jules --dry-run='client' -o yaml

The command above print the declarative code and don't really apply the command due to the option *--dry-run='client'*

