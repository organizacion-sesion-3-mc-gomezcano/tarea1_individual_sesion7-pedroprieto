# sesion7-tarea-individual
Crea una topología con 3 subredes (usando VLAN) con 4 switches. A cada switch se conectan 4 PCs. Se quiere segmentar el tráfico (reducir el dominio de broadcast) y que los equipos, aunque estén en switches diferentes, pertenezcan a la misma subred IP. El direccionamiento IP que usa es 192.168.x.0/24 donde x es 10, 20 o 30 según cada VLAN. Los switches se conectan entre sí utilizando los puertos Gigabit. Se van a utilizar las siguientes VLAN, configuradas por puerto (fastethernet):
- VLAN 10: Los dos primeros puertos de los switches 1, 2 y 3. Y el tercer puerto del switch 4.
- VLAN 20: Los dos siguientes puertos de los switches 1,2 y 3. Y el cuarto puerto del switch 4.
- VLAN 30: Los dos primeros puertos del switch 4.
