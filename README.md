# Sample Continuous Deployment Application written on Go

This application demonstrates the lightweight result of Go and consumes a PostgreSQL StatefulSet.

It includes NetworkPolicies and IngressController which defines the baseuri path on /app-golang.

This is the CD part of the application, Jenkins will build any version and will push here the change on the Deployment. 

After that, ArgoCD will deploy the objects on the manifest.

![ArgoCD view](/images/Golang-app.png)


