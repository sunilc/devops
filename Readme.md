# Pull and Run image adding a jar file

### PREP
    - Launch Lab "Red Hat Enterprise Linux Open Lab" from https://lab.redhat.com
        - Install docker
    - Login to https://github.com/ , click on Codespaces and  use the blank template.
 
 ### ACTIVITY
    - Create a docker file to add hellodtmb-0.0.1-SNAPSHOT.jar to /deployments folder
       - base Image Location "registry.access.redhat.com/ubi8/openjdk-17-runtime:1.14-8"
            - Reference help for Dockerfile https://docs.docker.com/engine/reference/builder/
            - base Image Docker file for Reference (https://catalog.redhat.com/software/containers/ubi8/openjdk-17-runtime/618bdc5f843af1624c4e4ba8?container-tabs=dockerfile)
       - jar Location https://filebin.net/ofqooy94m97i5zdt/hellodtmb-0.0.1-SNAPSHOT.jar
       - build and tag image as hello-world
    - list and run image hello-world

# Download and Install OC Command
    Location : https://mirror.openshift.com/pub/openshift-v4/clients/oc/latest/linux/oc.tar.gz

    - Log in to Openshift from command line using oc command 
```
    oc login --token=************ --server=https://api.sandbox-m2.ll9k.p1.openshiftapps.com:6443

```
    - list project(s) 
    - list pods
    - display logs from pod
