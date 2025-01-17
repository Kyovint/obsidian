# Que es un Pod?
Un pod es la unidad mas pequeña en kubernetes
- Un pod representa un unico proceso en el cluster
- Un pod puede contener n contenedores
> Los contenedores de un pod pueden compartir los procesos entre si con el comando `shareProcessNamespace: true`

Los pods se crean por medio de manifiestos los cuales son archivos .yml que se declaran especificaciones del pod

```yaml
apiVersion: v1
kind: Pod
metadata:
  name: <POD_NAME>
spec:
  containers:
  - name: <CONTAINER_NAME>
    image: <IMAGE_NAME>
  - name: <CONTAINER_NAME>
    image: <IMAGE_NAME>
```

# Volumenes en Pods
Los volumenes en los pods permiten atar un espacio de memoria del nodo al pod.
```dsadsa
dsadsa
```
