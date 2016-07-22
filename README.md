# Nexus for OpenShift Enterprise 3

This is instant jenkins application for OpenShift Enterprise 3.

```
oc new-project jenkins --display-name="Jenkins" --description="Jenkins"
oc new-app -f https://raw.githubusercontent.com/eformat/openshift-jenkins/master/jenkinstemplate.json
```
