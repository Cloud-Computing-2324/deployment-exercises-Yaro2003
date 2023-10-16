#Uptime
Opdracht 2 op Toledo. Als je gebruik maakt van Helm, zet je values-file in deze map, en je commando hieronder. Maak je gebruik van klassieke deployments, zet dan je bestanden in deze map.

commando's:
 helm repo add kuma https://louislam.net/uptime-kuma-helm/charts/

 helm repo update
 
 helm search repo kuma/uptime-kuma
 
 helm install my-kuma uptime-kuma/uptime-kuma --values values.yaml