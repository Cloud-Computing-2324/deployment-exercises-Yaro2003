#Redmine

Opdracht 3 op Toledo. Als je gebruik maakt van Helm, zet je values-file in deze map, en je commando hieronder. Maak je gebruik van klassieke deployments, zet dan je bestanden in deze map.

commando's:
 helm repo add redmine https://charts.bitnami.com/bitnami

 helm repo update

 helm search repo redmine

 helm install my-redmine redmine/redmine --values values.yaml