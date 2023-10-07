# Create-Ingress-EKS

1. Clone repository locally to your computer:
```js
git clone https://github.com/cloudtipss/Create-Ingress-EKS.git
```
2. Switch to the project directory:
```js
cd Create-Ingress-EKS
```
3. Create Kubernetes test Deployement and Service based on httpbin application: 
```js
kubectl apply -f ./test-app.yaml
```
4. Create Ingress for httpbin application: 
```js
kubectl apply -f ./ingress.yaml
```

You can find full guide in our article on [cloudtipss.com](https://cloudtipss.com/Create_Kubetnetes_Ingress)