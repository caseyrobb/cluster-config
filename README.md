# GitOps cluster-config

This repo contains cluster configurations that I use in my OpenShift clusters.  It is loosely based off of Gerald Nunn's [Standards](https://github.com/gnunn-gitops/standards).

# Application tiles
![alt text](https://raw.githubusercontent.com/caseyrobb/cluster-config/master/argotiles.png)

## App of Apps
![alt text](https://raw.githubusercontent.com/caseyrobb/cluster-config/master/appofapps.png)

# Install app-of-apps

```
oc apply -k bootstrap/overlays/<cluster-name>
```
