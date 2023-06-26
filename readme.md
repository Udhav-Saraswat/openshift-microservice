## Running Java Microservices on OpenShift using Source-2-Image  

$ oc login -u system:admin
$ oc policy add-role-to-user cluster-reader system:serviceaccount:myproject:default

$ kubectl create clusterrolebinding admin --clusterrole=cluster-admin --serviceaccount=default:default
