# Oracle Update CronJob

This deploys a Kubernetes CronJob that updates a column in an Oracle DB every 20 minutes.

- Update DB credentials in `secret.yaml`
- Apply with ArgoCD using `argocd-app.yaml`
