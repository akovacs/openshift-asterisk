# Asterisk on OpenShift


## Usage


### Build task
```
oc new-app https://github.com/gbraad/openshift-asterisk.git --name=asterisk
```

### Image
```
oc new-app gbraad/openshift-asterisk:latest --name=asterisk
```


## Links

  * Origin:  
    [weepee-org/openshift-asterisk](https://github.com/weepee-org/openshift-asterisk)
  * Images:  
    [Docker Hub](https://hub.docker.com/r/gbraad/openshift-asterisk/), [GitLab Registry](https://gitlab.com/gbraad/openshift-asterisk/container_registry)
  * Source:  
    [GitHub](https://github.com/gbraad/openshift-asterisk), [GitLab](https://gitlab.com/gbraad/openshift-asterisk)
