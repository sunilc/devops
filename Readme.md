# Pull and Run image adding a jar file
    - Create a docker file to add hellodtmb-0.0.1-SNAPSHOT.jar to /deployments folder
    - Image Location 
        https://catalog.redhat.com/software/containers/ubi8/openjdk-17-runtime/618bdc5f843af1624c4e4ba8?container-tabs=gti
        registry.access.redhat.com/ubi8/openjdk-17-runtime:1.14-8
    - jar Location https://github.com/sunilc/devops

# Download and Install OC Command
Location :https://mirror.openshift.com/pub/openshift-v4/clients/oc/latest/linux/oc.tar.gz

- Log in to Openshift and list projects and pod's
```
    oc login --token=************ --server=https://api.sandbox-m2.ll9k.p1.openshiftapps.com:6443
```
- display logs from pod