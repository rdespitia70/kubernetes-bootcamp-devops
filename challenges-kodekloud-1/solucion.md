# 1. Se decidión lanzar el .yaml en un solo archivo llamado all_lab.yaml el cual contiene:
- Configuración del pod
- Rol
- Role binding
- Service
- Persistent Volume Claim

# 2. Para el user martin:
Ejecutamos los siguientes comandos:

kubectl config set-credentials martin --client-certificate ./martin.crt --client-key ./martin.key
kubectl config set-context developer --cluster kubernetes --user martin
kubectl config use-context developer

Nota: se debe ejecutar primero el yaml y de ultimas los comandos relacionados a martin

# 3. Evidencias:

Ejercicio finalizado con exito:
![](assets/kub-1-2.png)
Evidencias varias 1:
![](assets/kub-1-3.png)
Evidencias varias 2:
![](assets/kub-1-4.png)
Evidencias varias 3:
![](assets/kub-1-5.png)
