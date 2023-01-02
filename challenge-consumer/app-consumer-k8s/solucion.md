# 1. Construccin de imagenes a partir de Dockerfiles:

 3985  docker build -t app-consumer-app:ruben-1.0.1 .
 3986  docker images
 3987  cd ..
 3988  ls
 3989  cd consumer
 3990  ls
 3991  docker build -t app-consumer-consumer:ruben-1.0.1 .
 3992  docker images
 3993  docker login
 3994  docker tag app-consumer-app:ruben-1.0.1 rdespitia70/app-consumer-app:ruben-1.0.1
 3995  docker tag app-consumer-consumer:ruben-1.0.1 rdespitia70/app-consumer-consumer:ruben-1.0.1
 3996  docker push rdespitia70/app-consumer-app:ruben-1.0.1
 3997  docker push rdespitia70/app-consumer-consumer:ruben-1.0.1

