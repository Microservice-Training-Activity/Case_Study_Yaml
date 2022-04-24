### __Dockerize the application docker hub__
> * docker build -t ponmalar/product .  
> * docker push ponmalar/product
> * docker run -p 8000:8080 -d ponmalar/product

### __Invoke the application from kubernate__
> * C:\Users\vmware19\Downloads\K8S>kubectl apply -f product.yaml
> * C:\Users\vmware19\Downloads\K8S>kubectl apply -f productingress.yaml 
> * C:\Users\vmware19\Downloads\K8S>kubectl apply -f productratelimit.yaml

### __Result from Terminal__
![product Result](./image.jpg)
 

 

 

 
 
 

 


 


 
 
